# Projeto Rede para Show da Banda - Packet Tracer

## Introdução

Este projeto foi desenvolvido como parte do desafio proposto pelo Curso Preparatório da PROZ para "AWS Certified Solutions Architect - Associate", no módulo "Redes e Linux Essentials para AWS".

**Desafio:** Configurar uma rede de computadores para o show da banda de Miguel, utilizando o Cisco Packet Tracer para criar uma topologia em estrela que permita a comunicação entre os membros da equipe de produção.

## Descrição do Projeto

O objetivo é criar uma rede local que conecte quatro computadores da equipe de produção a um switch central, permitindo a comunicação entre eles.  A topologia em estrela foi escolhida por sua simplicidade e eficiência.

## Topologia da Rede

![Topologia da Rede](https://github.com/arturcosta86/Desafio-Projeto-Rede-Computadores-Banda-Miguel-Proz-Artur-Costa/blob/main/TOPOLOGIA%20-%20Projeto%20Rede%20de%20Computadores%20Banda%20Miguel%20-%20Proz%20-%20Artur%20Costa.jpeg)

A imagem acima ilustra a topologia da rede, com o switch no centro e os quatro PCs conectados a ele.

## Arquivo Packet Tracer

[Baixar arquivo Packet Tracer](https://github.com/arturcosta86/Desafio-Projeto-Rede-Computadores-Banda-Miguel-Proz-Artur-Costa/blob/main/Projeto%20Rede%20de%20Computadores%20Banda%20Miguel%20-%20Proz%20-%20Artur%20Costa.pkt)

Este arquivo `.pkt` contém a configuração completa da rede no Cisco Packet Tracer.  Você pode abri-lo no Packet Tracer para visualizar e modificar a topologia e as configurações.


## Configuração dos Endereços IP

Os seguintes endereços IP foram atribuídos aos dispositivos:

* **Switch (VLAN 1):** 192.168.1.1 / 255.255.255.0
* **PC1:** 192.168.1.10 / 255.255.255.0
* **PC2:** 192.168.1.20 / 255.255.255.0
* **PC3:** 192.168.1.30 / 255.255.255.0
* **PC4:** 192.168.1.40 / 255.255.255.0

## Teste de Comunicação

A comunicação entre os PCs foi testada utilizando o comando `ping`. Os resultados dos testes podem ser visualizados nas imagens abaixo:

![Ping do PC1 para o PC2,PC3 e PC4](https://github.com/arturcosta86/Desafio-Projeto-Rede-Computadores-Banda-Miguel-Proz-Artur-Costa/blob/main/PING%20-%20Projeto%20Rede%20de%20Computadores%20Banda%20Miguel%20-%20Proz%20-%20Artur%20Costa.jpeg)

## Passos para Reproduzir o Projeto

1. Baixe o arquivo `.pkt` do Packet Tracer.
2. Abra o arquivo no Cisco Packet Tracer.
3. Observe a topologia da rede e as configurações dos dispositivos.
4. Execute os comandos `ping` nos PCs para verificar a comunicação.

## Conclusão

Este projeto demonstra a configuração básica de uma rede em estrela usando o Cisco Packet Tracer.  A comunicação entre os membros da equipe de produção foi estabelecida com sucesso, cumprindo os requisitos do desafio.


## Autor

[Artur Costa](https://github.com/arturcosta86)
