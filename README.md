# Linux Server Configuration
### A Udacity Project - Full Stack Web Developer
**Purpose:**
Put in practice the knowledge acquire during the course about how to configure a Linux Server and host an application.

**Project:**
Configure a Linux web server with the proper security measures installed. Such as create users with sudo powers, change ports, authenticate users using RSA keys. In addition, the server must host a web python application.

**Procedures:** The following steps where taken to complete this project.
1. Server
 * We use [Amazon LaightSail](https://lightsail.aws.amazon.com/) to create a new Linux Server instance.
2. Secure Server
 * Update installed package
 * Create new port 2200 for SSH connection
 * Configure firewall to only accept connection from port 2200 for SSH, port 80 HTTP, and NTP port 123.
 * Disable remote SSH for root user.
3. Users
 * Create new users
 * Give them `sudo` permission
 * Create SSH Key pair authentication using RSA keys.
4. Apache
 * Install and configure Apache to serve a Python mod_wsgi application.
5. Git
 * Install and configure Git to clone the project from personal machine to the server.
6. Other Apps Installed
 * Python with some libraries
 * PostgresSQL
7. IP Address
 * This is the public address `18.221.25.207`
8. URL
 * This is the url to access the application [18.221.25.207.xio.io](18.221.25.207.xio.io)
