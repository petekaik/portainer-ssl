# portainer-ssl
Docker Compose for Portainer with parametrable network, port and SSL cert &amp; key

Environment variables can be passed via .env file or by any other mechanism described in https://docs.docker.com/compose/environment-variables/

It's good to notice that this YAML disables Portainer's built-in authentication and is therefore not suitable for public deployments without any other authentication mechanisms.
Portainer's admin password can be implemented using https://portainer.readthedocs.io/en/stable/configuration.html#from-the-command-line
