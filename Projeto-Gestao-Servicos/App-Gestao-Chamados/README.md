# Sistema de Gestão de Ordens de Serviço - Solução de Conectividade

## 💡 Sobre o Projeto
Este projeto nasceu de uma iniciativa própria ao identificar um gargalo crítico em uma operação de provedor de internet onde presto serviço. O aplicativo utilizado anteriormente apresentava falhas constantes e, o mais grave: **não notificava os técnicos sobre novos chamados.**

Como desenvolvedor, tomei a frente para criar uma solução robusta que garantisse que nenhum serviço ficasse parado por falta de comunicação.

## 🛠️ Tecnologias e Integrações
* **Microsoft Power Apps:** Interface 100% responsiva (ajuste automático para mobile sem necessidade de zoom).
* **Microsoft Dataverse:** Banco de dados relacional para alta performance e segurança.
* **Power Automate:** Automatização completa do fluxo de trabalho.
* **API Twilio (SMS):** Integração para envio imediato de SMS e notificações Push ao técnico assim que uma OS é aberta.

## 📱 Estrutura da Solução
* **Tela de Login:** Autenticação segura por perfil.
* **Painel Administrativo:** Gestão completa de chamados e atribuições.
* **Portal do Técnico:** Interface focada na agilidade do atendimento em campo.
* **Dashboard em Tempo Real:** Monitoramento visual de status (Aguardando, Em Atendimento, Realizado).
* **Cadastro de Funcionários:** Controle centralizado de usuários no Dataverse.

## 🚀 Diferencial
O grande diferencial deste app é a **notificação ativa**. O sistema não depende de o técnico abrir o aplicativo para conferir a agenda; o alerta "bate" no celular via SMS e Push no exato momento da criação da ordem de serviço, otimizando o tempo de resposta e a satisfação do cliente final.

---
*Desenvolvido por Marciel.*