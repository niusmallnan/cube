# CUBE

To enable the cube console on RancherOS, try the following steps:

```
sudo ros engine switch docker-17.03.2-ce # or docker-1.12.6 docker-17.03.1-ce

sudo ros config set rancher.repositories.cube.url https://raw.githubusercontent.com/cnrancher/cube/master/consoles

sudo ros console switch cube-ubuntu-console

```
