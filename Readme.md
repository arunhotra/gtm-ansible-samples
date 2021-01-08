
# GTM examples for ansible

## Pre-req's

Docker

## Steps

* ### clone the repo

* ### modify hosts file to point to the IP of your BIG-IP

* ### build and run the container

``` docker-compose run gtm```

* ### Once in the container, run the playbook using the following command.

``` ansible-playbook <playbook-name>.yml -i hosts ```

It will ask you for username, password. 


