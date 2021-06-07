This ansible-playbook automatically installs the Docker Engine ( community edition ) on the Redhat Enterprise Linux 8.
It starts the docker daemon. After configuring the docker engine, it launches a Docker container with an httpd image.
In that container, it configures a webserver and copies the webpages into its document root. It also enables port forwarding. 
8000 port from the docker host.

note: make sure you change the path of the files you want to copy.
