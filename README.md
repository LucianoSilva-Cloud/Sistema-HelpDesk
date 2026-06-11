# Sistema-HelpDesk
Desenvolvimento de uma solução automatizada de HelpDesk integrada via Activepieces, reduzindo o tempo de resposta e centralizando chamados do Tally.so diretamente no Airtable com notificações automáticas via Gmail.
# Sistema de HelpDesk Automatizado (Tally → Airtable → Gmail)

Este projeto foi desenvolvido como uma atividade prática na **Escola da Nuvem**. Consiste na construção e implementação de um sistema automatizado de HelpDesk para triagem e gerenciamento de chamados de suporte técnico (TI e Design), eliminando processos manuais através da integração de ferramentas No-Code e automação de fluxos de trabalho.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Tally.so:** Criação e estilização do formulário dinâmico de captura de chamados em Dark Mode.
* **Activepieces:** Orquestração e automação do fluxo de dados baseado em eventos (Triggers e Actions) em tempo real.
* **Airtable:** Banco de dados relacional para armazenamento, organização, centralização e controle do status dos chamados.
* **Gmail (Google Workspace API):** Envio automatizado de e-mails de confirmação e notificações de suporte.

---

## 🔄 Fluxo de Integração e Funcionamento

1. **Geração do Chamado:** O usuário acede ao formulário personalizado no Tally.so e preenche os campos solicitados: *Nome Completo*, *E-mail* e *Tipo de Solicitação* (TI ou Design).
2. **Gatilho (Trigger):** O Activepieces deteta a nova submissão do formulário instantaneamente através de Webhooks.
3. **Armazenamento de Dados (Ação 1):** Os dados coletados são mapeados e enviados automaticamente para criar um novo registo estruturado na base de dados do Airtable.
4. **Notificação Automática (Ação 2):** O fluxo dispara de forma imediata um e-mail de confirmação personalizado para o remetente através da API do Gmail, assegurando ao usuário que o seu chamado foi recebido com sucesso.

---

## 📂 Estrutura do Repositório

* `03_merged.pdf`: Documentação em PDF com o passo a passo completo do projeto.
* `Fluxo_teste_activepieces.png`: Print do fluxo de automação estruturado no Activepieces.
* `README.md`: Documentação principal do projeto.

---

## 🎯 Resultados e Aprendizagem

Este projeto permitiu consolidar conhecimentos práticos em:
* Integração de sistemas via Webhooks e APIs.
* Modelagem de bases de dados relacionais simples para controle de fluxos de atendimento.
* Otimização de processos corporativos através de automações No-Code robustas e escaláveis.
