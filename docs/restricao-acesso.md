# Restrição de Acesso ao pfSense

## Objetivo
Restringir o acesso ao painel do pfSense apenas a um host autorizado.

## Implementação

Foram criadas regras de firewall na interface LAN:

- Permitir acesso HTTPS (porta 443) apenas para um IP específico
- Bloquear acesso ao restante da rede

## Resultado

Apenas o host autorizado consegue acessar o painel do pfSense.

## Conclusão

Foi possível aumentar a segurança restringindo o acesso administrativo.
