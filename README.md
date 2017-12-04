Docker compose makefile
=======================

Template for docker-compose

USAGE
-----

- **make help** - show help (see above)
- **make start** - start all containers
- **make start c=hello** - start container hello
- **make stop** - stop all containers
- **make status** - show list of containers with statuses
- **make clean** - clean all data

CUSTOMIZATION
-------------
You can create _.make.env_ file in directory with Makefile

Available variables

* DOCKER_COMPOSE = {docker-compose} executable command
* DOCKER_COMPOSE_FILE = {custom docker-compose.yml file}

TO-DO
-----

- check dependencies
- checkout code
- update readme

LICENSE
-------

MIT

AUTHOR
------

Roman Kudlay (roman@kudlay.pro)