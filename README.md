# Linux Server Configuration

## Server Details

+ IP: 54.173.126.72
+ SSH Port: 2200
+ URL of app: http://54.173.126.72/

## Installed Software

+ All packages updated with `apt-get`
+ Apache
+ mod_wsgi
+ PostgreSQL
+ Python + packages to satisfy requirements of the Catalog app

## Configuration Changes

+ SSH port changed from `22` to `2200`
+ Firewall configured to allow incoming connections only on ports `2200`, `80`, and `123`
+ A new user called `grader` has been created and given `sudo` access
+ An SSH keypair has been created for `grader`
+ The timezone has been set to `UTC`
+ A new user called `catalog` has been created for the Postgres database
