# 🌐 pfSense Lab — Network Topology

## 1. Overview
Este diagrama descreve a rede virtual criada com pfSense como firewall e Ubuntu como cliente.

## 2. Estrutura de Rede

### pfSense (Firewall)
- **WAN**: NAT → acesso à Internet
- **LAN**: Host-Only → rede interna para clientes
- **IP LAN**: 192.168.1.1

### Ubuntu Client
- Adaptador Host-Only → recebe IP do pfSense via DHCP
- IP exemplo: 192.168.1.100

### Comunicação
Internet → NAT → pfSense (WAN/LAN) → Host-Only → Ubuntu Client (192.168.1.x)

## 3. Próximos passos
- Adicionar imagens do dashboard do pfSense e do Ubuntu navegando na internet na pasta `images/`.
- Atualizar o diagrama/topologia visual com prints reais.
