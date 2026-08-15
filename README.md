# Cisco - Rede Hierárquica

Atividade prática de redes hierárquicas realizada no Cisco Packet Tracer.

## Atividade Prática: Introdução às Redes Hierárquicas

Nesta atividade, montei uma rede no Cisco Packet Tracer usando o modelo de redes hierárquicas, dividido em três camadas:

* **Núcleo:** 1 roteador Cisco 4331
* **Distribuição:** 1 switch Cisco 3650
* **Acesso:** 2 switches Cisco 2960
* **Computadores:** 4 PCs

## O que eu fiz

Primeiro montei a topologia e conectei os computadores aos switches de acesso. Depois conectei os switches ao switch de distribuição e, por fim, o switch de distribuição ao roteador.

Também configurei os endereços IP dos computadores e o gateway.

No roteador, configurei a interface `GigabitEthernet0/0/0` com o IP `192.168.1.1` e ativei a interface.

## Testes

Depois de configurar a rede, fiz testes usando o comando `ping` para verificar se os dispositivos conseguiam se comunicar.

Também usei o modo **Simulation** do Packet Tracer com o protocolo **ICMP** para visualizar o caminho dos dados pela rede.

## Objetivo

O objetivo foi entender na prática como funciona uma rede dividida nas camadas de **Acesso, Distribuição e Núcleo**, além de praticar configuração de IP e testes de conectividade.

**Ferramenta:** Cisco Packet Tracer
## Topologia

![Topologia da rede](Topologia Rede Hierarquicas.png)
