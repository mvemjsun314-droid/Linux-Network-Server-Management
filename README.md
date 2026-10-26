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

### 1. Server Administration — Webmin

![Webmin Dashboard](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 030140.png>)

### 2. DNS Configuration — BIND

![BIND DNS Dashboard](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 030809.png>)

### 3. Apache Web Server

![Apache Dashboard](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 095148.png>)

### 4. Main Website

![Main Website](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 102115.png>)

### 5. Research Department Website

![Research Website](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 102241.png>)

### 6. Sales Department Website

![Sales Website](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 102256.png>)

### 7. FTP File Transfer — FileZilla

![FileZilla FTP Connection](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 104833.png>)

### 8. Email Services — SquirrelMail

![SquirrelMail Login](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 105214.png>)

### 9. User Management — Sales

![Sales User Management](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 110846.png>)

### 10. User Management — Research

![Research User Management](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 111047.png>)

### 11. User Management — Accounts

![Accounts User Management](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 111239.png>)

### 12. Compose Email

![Compose Email](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 112604.png>)

### 13. Received Email

![Received Email](<docs/screenshots/01-server-administration/Screenshot 2026-07-07 112703.png>)

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

