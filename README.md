Dashboard de Vendas - Xbox Game Pass

📊 Sobre o Projeto

Este projeto apresenta um dashboard de vendas completo desenvolvido no Microsoft Excel, focado na análise de dados de assinaturas do Xbox Game Pass. O objetivo é transformar dados brutos em informações visuais claras e úteis, permitindo uma análise eficaz do desempenho de vendas e a tomada de decisões baseadas em dados.

🎯 Objetivo

Criar um dashboard de vendas no Excel que permita:

•
Visualizar métricas-chave de desempenho (KPIs)

•
Analisar a distribuição de vendas por plano e tipo de assinatura

•
Acompanhar a evolução temporal das vendas

•
Identificar padrões de comportamento dos assinantes

•
Facilitar a tomada de decisões estratégicas

📁 Estrutura do Projeto

Plain Text


dashboard-vendas-xbox/
│
├── README.md                          # Documentação do projeto
├── dashboard_vendas_xbox.xlsx         # Dashboard completo no Excel
└── dados/                             # (Dados originais - não incluídos por privacidade)



📈 Estrutura do Dashboard

O arquivo Excel contém 4 abas principais:

1. Dados

Contém todos os dados brutos das assinaturas, incluindo:

•
Subscriber ID: Identificador único do assinante

•
Name: Nome do assinante

•
Plan: Tipo de plano (Core, Ultimate, Standard)

•
Start Date: Data de início da assinatura

•
Auto Renewal: Renovação automática (Yes/No)

•
Subscription Price: Preço da assinatura

•
Subscription Type: Tipo de assinatura (Monthly, Quarterly, Annual)

•
EA Play Season Pass: Adesão ao EA Play (Yes/No)

•
Minecraft Season Pass: Adesão ao Minecraft Pass (Yes/No)

•
Coupon Value: Valor do cupom de desconto aplicado

•
Total Value: Valor total da transação

2. Cálculos

Apresenta métricas agregadas e análises detalhadas:

Métricas Gerais:

•
Total de Assinantes

•
Receita Total

•
Ticket Médio

•
Total de Descontos

•
Preço Médio de Assinatura

•
Valor Médio de Cupom

Análises Segmentadas:

•
Vendas por Plano (Core, Ultimate, Standard)

•
Vendas por Tipo de Assinatura (Mensal, Trimestral, Anual)

•
Distribuição de Renovação Automática

•
Adesão ao EA Play Season Pass

•
Adesão ao Minecraft Season Pass

•
Evolução de Vendas Mensais

3. Dashboard

Visualizações gráficas interativas:

•
KPIs Principais: Cards com métricas-chave destacadas

•
Gráfico de Pizza: Distribuição por Plano

•
Gráfico de Barras: Vendas por Tipo de Assinatura

•
Gráfico de Linha: Evolução de Vendas Mensais

•
Gráfico de Pizza: Renovação Automática

4. Assets

Paleta de cores e elementos visuais utilizados no dashboard, seguindo a identidade visual do Xbox.

📊 Principais Insights

Com base na análise dos dados de 295 assinantes no período de janeiro a dezembro de 2024:

Receita e Performance

•
Receita Total: R$ 7.633,00

•
Ticket Médio: R$ 25,87

•
Total de Descontos: R$ 2.122,00

•
Preço Médio de Assinatura: R$ 9,95

Distribuição por Plano

•
Core: 101 assinantes (34,2%)

•
Ultimate: 98 assinantes (33,2%)

•
Standard: 96 assinantes (32,5%)

A distribuição equilibrada entre os três planos indica uma boa aceitação de todas as opções oferecidas, sem concentração excessiva em um único plano.

Tipo de Assinatura

•
Mensal: 139 assinantes (47,1%)

•
Trimestral: 85 assinantes (28,8%)

•
Anual: 71 assinantes (24,1%)

A preferência por assinaturas mensais demonstra que os clientes valorizam a flexibilidade, embora quase 53% optem por compromissos mais longos (trimestral ou anual).

Renovação Automática

•
Sim: 148 assinantes (50,2%)

•
Não: 147 assinantes (49,8%)

A divisão praticamente igual indica oportunidades de aumentar a retenção através de incentivos para ativação da renovação automática.

Season Passes

•
EA Play Season Pass: 98 assinantes (33,2%)

•
Minecraft Season Pass: 194 assinantes (65,8%)

O Minecraft Season Pass apresenta adesão significativamente maior, representando uma importante fonte de receita adicional.

🛠️ Tecnologias Utilizadas

•
Microsoft Excel: Ferramenta principal para criação do dashboard

•
Python 3.11: Utilizado para processamento e análise dos dados

•
pandas: Manipulação e análise de dados

•
openpyxl: Criação e formatação de arquivos Excel



•
Git/GitHub: Controle de versão e compartilhamento do projeto

📋 Como Reproduzir o Projeto

Pré-requisitos

•
Microsoft Excel 2007 ou superior

•
(Opcional) Python 3.11+ com bibliotecas pandas e openpyxl para regenerar o dashboard

