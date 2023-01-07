# ansible-fermyon

Automates the deployment of Fermyon Stack local on a single node (local) debian system
as described at https://github.com/fermyon/installer

Fermyon runs on Nomad, so deployment scenarios will first configure and install this software, in tandem with Consul.

Afterwards, the components comprising Fermyon are deployed in the form of Nomad jobs, including a Bindle server, Traefik as the reverse proxy/load balancer and Hippo, the web UI for managing Spin-based applications.

