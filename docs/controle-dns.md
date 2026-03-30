# Controle de DNS e Bloqueio de Sites

## Objetivo
Controlar o tráfego DNS e bloquear acesso a sites específicos.

## Bloqueio de DNS externo

Foi criada uma regra de firewall:

- Bloqueio de TCP/UDP na porta 53 para qualquer destino

Resultado:
Todo o tráfego DNS passa pelo pfSense.

## Bloqueio de site

Foi utilizado o DNS Resolver:

- youtube.com → 0.0.0.0

## Teste

ping youtube.com

## Problema encontrado

O cliente ainda acessava o site.

## Causa

O Ubuntu estava utilizando DNS externo.

## Solução

Alteração do arquivo resolv.conf:

nameserver 192.168.x.1

## Resultado final

Bloqueio funcionando corretamente.
