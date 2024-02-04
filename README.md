# Test Lab: Harvester HCI with Rancher on Proxmox

## Inception-style Solution :D

I'm experimenting with the integration between Harvester HCI and Rancher on Proxmox. Harvester HCI is an open-source hyper-converged infrastructure platform that uses Kubernetes to host VMs, capable of running a Kubernetes cluster on top of these VMs, while Rancher is a container management platform that enables easy deployment and management of Kubernetes with an interesting integration with Harvester.

My idea here is to try automating the creation of a LAB to run this dream within a dream within another dream.

I'm attempting to use Ansible to create the necessary VMs on Proxmox, still in testing phase to deploy the environment this way, as currently, I have the environment set up manually.

I've managed to configure Rancher to start via Docker-Compose, but I'm still unsure whether the best approach is to install it directly on the VM, use Docker, or even use Rancher on Harvester with Helm. I'm not sure if it's even possible yet.

Well, that's it for now, anyone willing and able to contribute, just give me a shout.

---

# LAB de Teste: Harvester HCI com Rancher no Proxmox

## Solução a lá Inception :D

Estou testando a integração entre o Harvester HCI e o Rancher no Proxmox. O Harvester HCI é uma plataforma de infraestrutura hiperconvergente de código aberto que usa Kubernetes para hospedar VMs e pode rodar um Cluster Kubernetes em cima dessas VMs, enquanto o Rancher é uma plataforma de gerenciamento de contêineres que permite a fácil implantação e gerenciamento de Kubernetes com uma Integração com o Harvester interessante.

Minha ideia aqui é tentar automatizar a criação de um LAB para rodar esse sonho dentro de sonho dentro de outro sonho.

Estou tentando usar o Ansible para criar as VMs necessárias no Proxmox, ainda em fase de testes para subir o ambiente dessa forma, pois na fase atual, já tenho o ambiente pronto de forma manual.

O Rancher consegui configurar para iniciar via Docker-Compose, não sei ainda se a melhor forma é instalar diretamente na VM ou usar o Docker ou mesmo usar o Rancher no Harvester com Helm, não sei ainda se é possível.

Bom, até o momento, é isso, quem quiser e puder contribuir, só chamar.
