This ansible playbook automatically installs the  Docker Engine ( community edition ) on the Redhat Enterprise Linux 8.
It starts the docker deamon. 
After configuring the docker engine , it launches a docker container with httpd image.
In that container it configures a webserver and copies the webpages into its document root .
It also enables port forwarding. 8000 port from the docker host.

**note** : make sure you change the path of the files you want to copy.
