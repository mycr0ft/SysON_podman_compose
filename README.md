# SysON_podman_compose

A `compose.yaml` for starting the SysMLv2 development environment
[SysON](https://mbse-syson.org/). This replaces the docker compose file the
developers typically use. The only significant changes made are the full path
for the containers involved (docker assumes [docker.io](https://docker.io) as a
repository location for container files.

Use `podman compose up` to get started. This can be run as an ordinary user. 

Navigate to [http://localhost:8080](http://localhost:8080) to get started. 


