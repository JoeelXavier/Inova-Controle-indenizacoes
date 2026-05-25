# Inova - Controle de Indenizações

## Objetivo
Com o objetivo de organizar e automatizar um fluxo de devoluções de produtos vencidos e avariados, o projeto criou um ecossistema organizado e contínuo. Com fluxo de aprovações, auditoria, histórico de anexos e painel de monitoramento atualizados automaticamente, o projeto otimizou e reduziu o tempo de trabalho de 3 setores com um sistema seguro e controlado. Sobretudo, o sistema criou um controle de prestação de contas, garantindo confiabilidade para os clientes e segurança para a empresa gestora.

## Premiações
O projeto foi premiado em 1º lugar na 1ª edição do programa Inova Nordesa Broker Nestlé. 

## Funcionalidades

* **Fluxo de Aprovação:** Processo automatizado e hierárquico para validação das solicitações.
* **Auditoria:** Registro seguro de todas as etapas do processo.
* **Painel de Monitoramento:** Indicadores (KPIs) atualizados automaticamente e evidência dos prazos e setores responsáveis por cada etapa.
* **Integração entre Setores:** Conexão fluida entre as 3 áreas envolvidas.
* **Chatbot interativo** Consultas rápidas sobre status das solicitações.  

##  Tecnologias Utilizadas

* **SharePoint:** Base de dados e formulário.
* **Power Apps:** Interface para aprovação de itens.
* **Power Automate:** Automatização do fluxo dos itens.
* **Power BI / Fabric:** Painel de monitoramento e prestação de contas.
* **Microsoft Copilot** Chatbot interativo.
* **SQL Server:** Base de dados complementares.

## Estrutura do Ecossistema

1. **Criação da solicitação de indenização:** Vendedor digita a solicitação de indenização via ERP.
2. **Consulta de dados SQL / Power BI:** Conjunto de dados com consulta SQL dos pedidos de solicitação de indenização é atualizado no Workspace via Gateway diariamente.
3. **Lançamento:** Solicitação de indenização enviada pelo vendedor via Forms com anexos (ficha de indenização + nota fiscal emitida pelo cliente), registrada na lista do SharePoint.
4. **Inserção de dados complementares:** Power Automate insere dados complementares à solicitação (endereço, razão social, ramo de atendimento).
5. **Aprovação:** Setor de suporte comercial valida as informações lançadas e aprova/reprova a solicitação. Fluxo do Power Automate define se é necessária a aprovação de supervisores e gerentes com base no valor da solicitação.
6. **Aprovação Power Apps:** Supervisores e gerentes realizam a aprovação da solicitação via Power Apps, se necessário.
7. **Tratativas de logística:** Uma vez a solicitação aprovada, é iniciado o processo de recolhimento da devolução solicitada pelo cliente. Produtos são recolhidos, e a finalização e data do recolhimento são confirmadas na lista do SharePoint.
8. **Fechamento - Setor de Faturamento:** Após recolhimento e conferência dos produtos devolvidos, é enviada a solicitação de pagamento da indenização para a indústria responsável.

Cada etapa é monitorada e registrada com datas, atualizações, mudança de status e visualização dos usuários que executaram cada ação, possibilitando auditorias e  identificação de gargalos. Cada etapa do fluxo é monitorada no Power BI.  





https://github.com/user-attachments/assets/db859722-e986-4e60-affb-9b54f9b3a5b7

https://github.com/user-attachments/assets/045231e8-d1fd-4ff1-8f20-7fb60c2cfaed

https://github.com/user-attachments/assets/b43f1829-b56a-466a-8790-94e196bc7263

https://github.com/user-attachments/assets/b9d585ef-34a4-4bb2-ae0f-2327e88c326a






