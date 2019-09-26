# WordPress automation with Ansible 

An Ansible Playbook for automated WP & MySQL setup under nginx with TLS.
Aims to provide a one-click hassle free deployment of a WordPress instance
backed by MySQL database and hidden under NGINX proxy with HTTPS turned on.

There is plenty of possible interpretations of this stack varied by
complexity, security, reliability etc. The original motivation behind this
project is to make a minimalist setup that would be robust & extendable
at the same time, requiring minimum of DevOps knowledge to be used.


## Current status: WIP

Supported:
 - common packages and Docker setup
 - deployment of a MySQL container with mounted volume
 - deployment of a WP container connected to the DB
 - nginx proxy setup
 - LE proxy companion, to enable HTTPS

TODO:
 - proper setup of secrets & env vars
 - a neat readme with instructions