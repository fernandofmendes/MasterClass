# Aula 1 - Funcionamento Internet e comunicações

Ola GitHub

Treinamento para nivelamento de conhecimento

## Índice ##

 - Apresentação sobre o treinamento
 - Informações de contato para grupo no WhatsApp
 - Overview de comunicações
 - Comandos utilizados

## Overview de comunicações ##

Imagem representando uma rede interna

Figura: rede-interna.png

![alt rede-interna.png](/Aula-01/img/rede-interna.png)

--

Imagem representando a configuração da interface de rede de um computador Windows

Figura: manual-ip-configuration-windows-7.jpg

![alt manual-ip-configuration-windows-7.jpg](/Aula-01/img/manual-ip-configuration-windows-7.jpg)

--

Imagem representando a segregação de redes internas

Figura: multiplas-rede-interna.jpg

![alt multiplas-rede-interna.jpg](/Aula-01/img/multiplas-rede-interna.jpg)


![alt dns_resolve.png](/Aula-01/img/dns_resolve.png)


![alt iis-10-binding-01.png](/Aula-01/img/iis-10-binding-01.png)


![alt Hr3VC.png](/Aula-01/img/Hr3VC.png)

## Comandos utilizados ##

nslookup

```
C:\Users\Lisnei>nslookup newton.ag
Servidor:  UnKnown
Address:  fe80::e626:8bff:feeb:835b

Não é resposta de autorização:
Nome:    newton.ag
Address:  45.14.89.17


C:\Users\Lisnei>
```

host

```
$ host newton.ag
newton.ag has address 45.14.89.17
newton.ag mail is handled by 5 newton-ag.mail.protection.outlook.com.
```

ping

```
$ ping newton.ag
PING newton.ag (45.14.89.17) 56(84) bytes of data.
64 bytes from newton.ag (45.14.89.17): icmp_seq=1 ttl=51 time=135 ms
64 bytes from newton.ag (45.14.89.17): icmp_seq=2 ttl=51 time=136 ms
64 bytes from newton.ag (45.14.89.17): icmp_seq=3 ttl=51 time=149 ms
^C
--- newton.ag ping statistics ---
3 packets transmitted, 3 received, 0% packet loss, time 2005ms
rtt min/avg/max/mdev = 134.524/139.982/148.964/6.399 ms
```
