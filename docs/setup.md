# 🛠 pfSense Lab — Setup

## 1. Objetivo
Criar um laboratório de rede com firewall usando pfSense e um cliente Ubuntu no VirtualBox, simulando uma rede real.

## 2. Ambiente

### pfSense (Firewall)
- Adaptador 1 → NAT (WAN)
- Adaptador 2 → Host-Only (LAN)
- IP LAN: 192.168.1.1

### Ubuntu (Cliente)
- Adaptador → Host-Only
- Recebe IP da rede do pfSense (192.168.1.x)

## 3. Passo a passo realizado

1. Instalou e configurou o pfSense.
2. Configurou interfaces WAN e LAN.
3. Conectou o Ubuntu à rede do pfSense.
4. Acessou o pfSense via navegador.
5. Fez login e alterou a senha.
6. Executou o Setup Wizard.
7. Configurou timezone e rede.
8. Testou conexão com `ping`.
9. Corrigiu problemas de IP e acesso.
10. Ubuntu navegou na internet pelo pfSense.

## 4. Aprendizados
- Diferença entre NAT, Host-Only e Internal Network.
- Como funciona WAN x LAN.
- Conceito de cliente x servidor.
- Acesso a firewall via web.
- Troubleshooting de rede (ping, IP, etc.)

## 5. Próximos passos
- Criar regras de firewall.
- Bloquear sites no pfSense.
- Monitorar tráfego da rede.
- Restringir acesso ao painel do pfSense.
