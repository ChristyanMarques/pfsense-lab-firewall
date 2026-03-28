# 🔥 pfSense Firewall Lab

## 📌 Overview
Este projeto é um laboratório prático de redes onde implementei um firewall utilizando **pfSense** em um ambiente virtualizado com **VirtualBox**.

O objetivo foi simular um cenário real de rede corporativa, com controle de tráfego entre cliente e internet.

---

## 🛠️ Tecnologias utilizadas

- pfSense (Firewall)
- Ubuntu (Cliente)
- Oracle VM VirtualBox
- Networking (NAT + Host-Only)

---

## 🧱 Arquitetura da Rede

[ Ubuntu Client ] ---> [ pfSense Firewall ] ---> [ Internet ]
LAN WAN (NAT)


---

## 🌐 Configuração das Máquinas

### 🖥️ pfSense
- WAN: NAT (acesso à internet)
- LAN: Host-Only
- IP LAN: `192.168.1.1`
- DHCP: Ativo

### 💻 Ubuntu
- Adaptador: Host-Only
- IP: via DHCP (`192.168.1.100`)
- Gateway: pfSense

---

## 📸 Demonstração

### 🔹 pfSense Dashboard
![pfSense Dashboard](images/pfsense-dashboard.png)

---

### 🔹 Teste de conectividade (ping)
![Ping Test](images/ubuntu-ping.png)

---

### 🔹 Acesso à internet
![Internet Access](images/internet-test.png)

---

## 🧪 Testes realizados

- ✔ Comunicação entre cliente e firewall
- ✔ Acesso à interface web do pfSense
- ✔ Navegação na internet via firewall
- ✔ Testes com `ping` e conectividade

---

## 🔐 Próximos passos

- 🔒 Criar regras de firewall (bloqueio de tráfego)
- 🌍 Bloquear acesso a sites específicos
- 📊 Monitoramento de tráfego
- 🧠 Implementar controle de acesso

---

## 🧠 Aprendizados

- Diferença entre NAT e Host-Only
- Funcionamento de WAN vs LAN
- Configuração de firewall pfSense
- Troubleshooting de rede
- DHCP e atribuição de IP

---

## 🚀 Objetivo do projeto

Desenvolver habilidades práticas em redes e segurança, simulando um ambiente real de firewall utilizado em empresas.

---

## 👨‍💻 Autor

Projeto desenvolvido por Christyan 🚀
