# WordPress and MySQL Distributed Deployment

This project demonstrates setting up WordPress on an Ubuntu server with MySQL hosted on OpenSUSE, configured for remote access. The setup ensures seamless data exchange between the two systems while adhering to security best practices.

## Prerequisites

- Ubuntu server (for WordPress deployment)
- OpenSUSE server (for MySQL deployment)
- Basic knowledge of MySQL, WordPress, firewall, and remote access configurations

## Project Setup

### 1. MySQL Configuration on OpenSUSE

- Install MySQL on OpenSUSE.
- Configure MySQL to allow remote connections.
- Set up secure user permissions.
- Open necessary ports in the firewall to allow communication between WordPress and MySQL servers.

### 2. WordPress Installation on Ubuntu

- Install WordPress on an Ubuntu server.
- Configure WordPress to use the MySQL database on the OpenSUSE server.
- Update the `wp-config.php` file with the MySQL remote database credentials.

### 3. Testing & Validation

- Verify the setup by testing WordPress's ability to read and write data to the MySQL database.
- Ensure all firewall and network settings are properly configured for seamless communication.

## Security Best Practices

- Use strong passwords for MySQL user accounts.
- Restrict MySQL remote access to specific IP addresses.
- Regularly update both servers and maintain firewall settings.

## Documentation

The full documentation covering the installation, configuration, troubleshooting steps, and best practices is included in the project folder.

## Use Case

This distributed deployment setup enables scalable, resilient web applications, with WordPress running on Ubuntu and MySQL hosted remotely on OpenSUSE, ideal for production or staging environments.

