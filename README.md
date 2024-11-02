# Vagrant-Virtualbox-local-multi-tier-app

This project provides a multi-tier setup for deploying the VProfile application on virtual machines using **Vagrant** and **Oracle VirtualBox**. It demonstrates a scalable architecture suitable for development and testing.

## Prerequisites

Before you begin, ensure the following tools are installed:
- **Oracle VM VirtualBox**
- **Vagrant** with plugins, including:
  - `vagrant-hostmanager` (Install using `vagrant plugin install vagrant-hostmanager`)
- **Git Bash** or an equivalent terminal editor

## Architecture Overview

The VProfile application is designed with a multi-tier structure, where each VM provides a dedicated service:
1. **Nginx** - Web server
2. **Tomcat** - Application server
3. **RabbitMQ** - Message broker
4. **Memcached** - Database caching
5. **MySQL** - SQL database

