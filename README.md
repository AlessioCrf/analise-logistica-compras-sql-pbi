# 🚚 Performance Logística, Compras e Gestão de Fornecedores

## 📌 Visão Geral
Este projeto analisa uma operação logística com mais de 9.000 pedidos, focando na identificação de gargalos financeiros causados por atrasos de entregas.

## 🛠️ Tecnologias Utilizadas
- **SQL Server** → tratamento, limpeza e modelagem de dados.    
- **Power BI** → criação de relatórios e storytelling visual.  
- **Figma** → design da capa e telas de fundo do dashboard.  
- *(Excel apenas como apoio inicial para recebimento da base).*

## 📂 Estrutura do Repositório
* **/SQL**: Scripts de DDL (criação), ETL (limpeza) e Views analíticas.
* **/PowerBI**: Capturas de tela das análises.

## 🛠️ Tratamento e Engenharia de Dados (SQL Server)
Diferente do projeto anterior, aqui o foco foi a **performance**:
1. **Modelagem**: Criação da tabela Calendário para otimização de consultas.
2. **Transformação**: Padronização de datas de entrega e cálculo de "Lead Time" direto via script.
3. **Qualidade**: Consultas, para conseguir entender melhor os pontos fortes e fracos

## 📊 Business Intelligence (Power BI)
O dashboard foi dividido em duas visões estratégicas:
* **Análise Geral**: Monitoramento de faturamento (66.67 Mi) e saúde financeira.
* **Gestão de Entregas**: Foco em eficiência operacional e monitoramento de 52.40 Mi em risco por atrasos.


## 💡 Insights de Conselheiro Estratégico
* **Risco Financeiro**: Identificamos que a maioria do valor retido em atrasos pertence ao fornecedor Minerva.
* **Gargalo Operacional**: A média de entrega de 18 dias está acima da meta estipulada, sugerindo revisão de contratos.

## 🔍 Transparência
Os dados são **fictícios** e utilizados apenas para fins de estudo, mas todo o fluxo de **ETL → SQL → Power BI** reflete práticas aplicáveis em cenários reais.  





✍️ Desenvolvido por [Alessio Ricardo]  
🔗 (https://www.linkedin.com/in/alessio-ricardo/) | (https://github.com/AlessioCrf)
