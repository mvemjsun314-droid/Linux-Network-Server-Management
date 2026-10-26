# Linux-Based Network Server Configuration and Management System

## Project Overview

This project demonstrates the configuration and management of a simulated company network using VMware and Red Hat Linux.

A Linux virtual machine was configured as a server, while a Windows machine was used as a client to test network connectivity and services.

## Objectives

* Learn Linux server administration.
* Configure and manage network services.
* Understand DNS and domain name resolution.
* Host multiple websites using Apache virtual hosts.
* Configure DHCP for automatic IP address assignment.
* Explore FTP-based file transfer.
* Configure mail services for email communication.
* Manage Linux users, groups, and file permissions.

## Technologies Used

* VMware
* Red Hat Linux
* Webmin
* BIND DNS Server
* Apache HTTP Server
* DHCP
* Sendmail
* Dovecot
* SquirrelMail
* FTP / FileZilla
* Telnet
* Windows Command Prompt

## Features

### 1. Linux Server Configuration

Configured network settings and tested connectivity between the server and client.

### 2. DNS Configuration

Created DNS zones and configured records for a company domain and departmental subdomains.

### 3. Apache Virtual Hosting

Configured virtual hosts to serve separate web pages for different departments.

### 4. DHCP Configuration

Configured a subnet and IP address range to demonstrate automatic IP assignment.

### 5. Mail Server Configuration

Configured Sendmail and Dovecot and used SquirrelMail to demonstrate email communication between users.

### 6. FTP File Transfer

Used FileZilla to transfer files between the Windows client and Linux server.

### 7. Linux User and Group Management

Created users and groups and configured directory ownership and file permissions.

## Project Screenshots

The following screenshots demonstrate the configuration and testing of the services in the virtual lab environment.

### 1. Linux Server Administration

This screenshot demonstrates the Webmin dashboard used for Linux server administration.

![Webmin Dashboard](docs/screenshots/01-server-administration/webmin-dashboard.png)

### 2. DNS Configuration

This screenshot demonstrates the BIND DNS server administration interface.

![BIND DNS Dashboard](docs/screenshots/02-dns-configuration/bind-dns-dashboard.png)

### 3. Apache Web Server and Virtual Hosting

The following screenshots demonstrate the Apache web server dashboard and the websites configured for different departments.

![Apache Dashboard](docs/screenshots/03-apache-web-server/apache-dashboard.png)

**Main Website**

![Main Website](docs/screenshots/03-apache-web-server/main-website.png)

**Sales Department Website**

![Sales Website](docs/screenshots/03-apache-web-server/sales-website.png)

**Research Department Website**

![Research Website](docs/screenshots/03-apache-web-server/research-website.png)

### 4. FTP File Transfer

This screenshot demonstrates the FileZilla FTP connection to the Linux server.

![FileZilla FTP Connection](docs/screenshots/04-ftp-file-transfer/filezilla-ftp-connection.png)

### 5. Email Services

The following screenshots demonstrate the SquirrelMail interface and email-related activities.

**SquirrelMail Login**

![SquirrelMail Login](docs/screenshots/05-mail-server/squirrelmail-login.png)

**Compose Email**

![Compose Email](docs/screenshots/05-mail-server/compose-email.png)

**Received Email**

![Received Email](docs/screenshots/05-mail-server/received-email.png)

### 6. Linux User and Permission Management

The following screenshots demonstrate departmental user management and Linux access-control configuration.

**Sales Department**

![Sales User Management](docs/screenshots/06-user-management/sales-user-management.png)

**Research Department**

![Research User Management](docs/screenshots/06-user-management/research-user-management.png)

**Accounts Department**

![Accounts User Management](docs/screenshots/06-user-management/accounts-user-management.png)

## Testing

The project included testing of:

* Network connectivity using ping.
* DNS resolution.
* Apache website access.
* DHCP client configuration.
* FTP file transfer.
* Email sending and receiving.
* Linux users, groups, and permissions.

## Environment

The project was implemented in a virtualized lab environment using VMware, Red Hat Linux, and a Windows client.

## Security Considerations

This project was developed for learning purposes in a lab environment. Telnet transmits credentials without encryption, and permissions such as `777` can grant excessive access. SSH and least-privilege permissions are preferred for production environments.

