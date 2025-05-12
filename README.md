# Project_N8N
# 🤖 Automação com n8n – Alertas de Incidentes e Pedidos via WhatsApp

Este repositório contém dois fluxos criados com o [n8n](https://n8n.io/) para automatizar tarefas do dia a dia com foco em eficiência, integração e produtividade.
Tela do meu projeto:![Image](https://github.com/user-attachments/assets/f20b9888-fd5d-4a53-8f5e-4f3d61af9887)

## 🚀 Funcionalidades

### 1. 📊 Relatórios Automáticos de Incidentes (Grafana/Zabbix + Google Sheets)
- Recebe alertas via Webhook
- Organiza os dados recebidos (host, severidade, mensagem, timestamp)
- Salva automaticamente em uma planilha no Google Sheets
- Envia resumo diário por e-mail para a equipe

### 2. 📦 Registro de Pedidos via WhatsApp + Google Sheets
- Captura mensagens recebidas via Twilio (WhatsApp)
- Identifica pedidos com base em palavras-chave
- Extrai informações do cliente e do pedido
- Armazena automaticamente no Google Sheets
- Retorna mensagem de confirmação ao usuário

## 🧩 Stack Utilizada

- [n8n](https://n8n.io/) – Ferramenta de automação low-code
- Twilio API – Integração com WhatsApp
- Google Sheets API – Armazenamento dos dados
- SMTP – Envio de e-mails automáticos
- Webhook – Integração com Grafana/Zabbix

## 📸 Exemplos Visuais

### Fluxo 1: Relatório de Incidentes
![Relatório de Incidentes](caminho/para/fluxo1.png)

### Fluxo 2: Pedidos via WhatsApp
![Pedidos WhatsApp](caminho/para/fluxo2.png)

## 💡 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/projeto-n8n-automacoes.git

       Importe os fluxos .json no seu ambiente n8n

    Configure suas credenciais (Google, Twilio, SMTP etc.)

    Execute os fluxos e monitore os resultados

📬 Contato

Caso tenha interesse em aplicar essa automação na sua empresa ou queira trocar ideias, fique à vontade para me chamar:

📧 leandrosrs2012@email.com
🔗 LinkedIn: https://www.linkedin.com/in/leandro-chagas-/
