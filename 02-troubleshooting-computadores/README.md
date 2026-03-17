# Troubleshooting de Computadores

Esta seção do portfólio contém laboratórios práticos de diagnóstico e resolução de problemas comuns encontrados no suporte técnico de TI.

Os cenários simulam situações reais enfrentadas no dia a dia de profissionais de suporte, utilizando ferramentas do sistema operacional Windows e comandos do PowerShell para identificar e resolver falhas.

O objetivo é desenvolver experiência prática em troubleshooting, seguindo um fluxo profissional de diagnóstico:

1. Identificar o problema
2. Testar conectividade ou funcionamento
3. Investigar possíveis causas
4. Aplicar a correção
5. Validar a solução

---

# Ferramentas utilizadas

Durante os laboratórios desta seção são utilizadas ferramentas comuns no suporte técnico:

- Windows
- PowerShell
- Comandos de rede do Windows
- Máquina virtual (VirtualBox)
- Ferramentas de diagnóstico do sistema

---

# Casos de troubleshooting

Os seguintes cenários são documentados nesta seção:

### 01 — Computador sem acesso à internet
Simulação de perda de conectividade causada por desativação do adaptador de rede.

Comandos utilizados:

- `Get-NetAdapter`
- `ping`
- `ipconfig`
- `Disable-NetAdapter`
- `Enable-NetAdapter`

Arquivo:

```
01-sem-internet-windows.md
```

---

# Próximos laboratórios planejados

Esta seção continuará sendo expandida com novos cenários comuns de suporte técnico, como:

- Wi-Fi conectado mas sem acesso à internet
- Problemas de DNS
- Computador não recebe endereço IP
- Computador lento
- Serviços do Windows parados
- Problemas de driver de rede
- Disco cheio ou falta de espaço
- Falhas de atualização do Windows

---

# Objetivo desta seção

Demonstrar habilidades práticas em:

- diagnóstico de problemas em computadores
- troubleshooting de rede
- uso de PowerShell
- análise de comandos de sistema
- documentação técnica de incidentes

Cada laboratório apresenta o processo completo de investigação, identificação da causa do problema e aplicação da solução.
