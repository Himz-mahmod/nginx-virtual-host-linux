# Nginx Virtual Host Setup on Ubuntu

This project demonstrates how to configure multiple virtual hosts using Nginx on Ubuntu Linux.

## Websites Created

- site1.local
- site2.local

Each website has its own root directory and configuration.

## Project Structure

/var/www/site1/index.html
/var/www/site2/index.html

Nginx configuration files:

/etc/nginx/sites-available/site1
/etc/nginx/sites-available/site2

Enabled using symbolic links in:

/etc/nginx/sites-enabled/

## Features

- Nginx installation
- Virtual host configuration
- Local DNS mapping using `/etc/hosts`
- Multiple websites running on one server

## Technologies Used

- Ubuntu Linux
- Nginx
- VirtualBox
- HTML

## Example Websites

Site 1:
"This is my first virtual host website."

Site 2:
"This is my second virtual host website."
