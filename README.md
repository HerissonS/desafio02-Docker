# UTILIZANDO O VAGRANT

O script utilizado no arquivo Vagrantfile tem como objetivo criar um Cluster Swarm local, as máquinas virtuais são criadas no Virtual Box.

São criadas 4 máquinas, com os seguintes nomes: master, node01, node02, node03.

As máquinas possuem IP Fixo, 512 Mb de memória e 1 CPU.

Todas as VM's possuem o Docker pré-instalado, a instalação é feita através do script docker.sh

A máquina master é o nó manager do cluster e as demais máquinas são incluídas no cluster swarm como workers.