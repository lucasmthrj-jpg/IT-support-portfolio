# 💻 Computador não recebe endereço IP (DHCP)

## 🧠 Cenário

Um computador não conseguia acessar a rede, mesmo estando fisicamente conectado ao roteador.

---

## 🎯 Objetivo

Diagnosticar e resolver o problema de conectividade relacionado à configuração de endereço IP.

---

## ⚠️ Problema

O computador estava com um endereço IP configurado manualmente em uma rede diferente da rede do roteador.

Exemplo:

- IP configurado: 192.168.50.10  
- Rede correta: 192.168.0.x  

Isso impedia a comunicação com o gateway e com outros dispositivos da rede.

---

## 🔍 Diagnóstico

Etapas realizadas:

1. Verificação do endereço IP com `ipconfig`  
2. Identificação de rede incorreta (192.168.50.x)  
3. Teste de conectividade com o gateway utilizando `ping`  
4. Confirmação de falha de comunicação  

---

## 🛠️ Solução

- Alteração da configuração de IP de **Static** para **DHCP**
- Obtenção automática de endereço IP válido fornecido pelo roteador

---

## ✅ Resultado

Após a correção:

- O computador recebeu um IP válido (192.168.0.x)  
- A comunicação com o gateway foi restabelecida  
- A conectividade da rede voltou a funcionar normalmente  

---

## 📚 O que aprendi

Como identificar problemas de rede relacionados à configuração de IP e a importância de utilizar DHCP em ambientes onde a atribuição automática de endereços é necessária.
