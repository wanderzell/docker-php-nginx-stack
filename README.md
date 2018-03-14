# Scalable PHP backend with NGINX frontend in a Docker stack

Proof of concept - the most basic vanilla NGINX and PHP deployment uses Docker stack for load balancing and scaling.

Main point of this project is to keep it as simple as possible, to demonstrate the concept - how this type of load balancing works. It can be used easily to bootstrap any Docker based PHP deployment by just providing:
 - php/php.ini
 - nginx/nginx.conf
 - src/ - application files
 - docker-compose.yml - any additional services as needed
