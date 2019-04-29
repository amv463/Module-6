# Dev Ops/Ansible Example

Creates a web server that connects with a database in order to provide
messages to the user.  

## Files

- yaml/retry files

	- provisionAppPlaybook.yaml --> provisions and runs the application
	- provisionAppPlaybook.retry --> tries to provision the application again in case it fails
	- stopAppPlaybook.yaml --> stops the containers
	- removeAppPlaybook.yaml --> stops all containers and removes all images

## Directories

### adrs

This directory contains adr files used to document decisions regarding the application.

### mongo

This directory contains all of the necessary files to build the MongoDB container.

### server

This directory contains all of the necessary files to build the web server container.

### webclient

This directory contains all of the necessary files to build the business logic 
container.


# Module-6
