
# Zabbix Atacarejo - Monitoramento de Infraestrutura

Projeto de monitoramento com Zabbix 7.0 em ambiente real de laboratório / produção interna.

## Ambiente
- Servidor: Debian 13 - 192.168.1.11
- Zabbix: 7.0
- Banco: MariaDB
- Web Server: Nginx com HTTPS na porta 443
- DNS Interno: Bind9 - zabbix.atacarejo.net
- Certificado: Auto-assinado com SAN para o domínio interno

## Hosts Monitorados
- srv01-backoffice - Debian 13
- pdv02 - Debian 13
- Windows 11 - Zabbix Agent 2
- Router da rede local
- Google - Monitoramento externo via ICMP / HTTP

## O que foi configurado
- Instalação do Zabbix 7.0 + MariaDB + Nginx
- Agentes Zabbix em Windows 11 e Debian
- DNS interno com Bind9 resolvendo atacarejo.net
- HTTPS com redirecionamento de HTTP (80) para HTTPS (443)
- Monitoramento de disponibilidade, CPU, memória, disco e rede

## Acesso
https://zabbix.atacarejo.net

## Autor
Jairo Barboza - Analista de Redes / Infraestrutura
Formado em Redes de Computadores - Estácio
Pós em Engenharia de Redes e Telecomunicações

