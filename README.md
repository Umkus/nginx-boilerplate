#Nginx Boilerplate 

[![Join the chat at https://gitter.im/nginx-boilerplate/nginx-boilerplate](https://badges.gitter.im/nginx-boilerplate/nginx-boilerplate.svg)](https://gitter.im/nginx-boilerplate/nginx-boilerplate?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Chat](https://img.shields.io/gitter/room/gitterHQ/gitter.svg)](https://gitter.im/nginx-boilerplate )

Awesome Nginx configuration template and a set of handy must-have snippets.

## Features
 * Convenient include-based config structure
 * Optimized defaults
 * Connection and requests rate limiting settings
 * Backend response caching
 * Various predefined locations
 * Advanced logging
 
## Requirements
 * `Nginx` >= `1.7`
 * `/etc/hosts` might need changing for local development

## If something doesn't work
 * Make sure you have `cgi.fix_pathinfo` set to `1` or commented out in php.ini
 * Check the contents of the site's access/error logs
 * Make sure to have proper file/folder permissions
 * Create an issue on the project's github page
