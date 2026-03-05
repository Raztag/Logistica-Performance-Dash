# 📊 Inteligência de Dados e Performance Logística - Estudo de Caso (V2)

## 📋 Sobre o Projeto
Este projeto simula um ambiente real de monitoramento de custos e faturamento de uma operação logística. O objetivo principal é transformar dados brutos em indicadores estratégicos (KPIs), permitindo identificar gargalos financeiros e oscilações operacionais que impactam a rentabilidade direta do negócio.

A solução foi desenvolvida de ponta a ponta: desde a **estruturação da base de dados do zero no Microsoft Excel** até a criação de um dashboard avançado no **Power BI**.

<img width="1312" height="736" alt="Screenshot_7" src="https://github.com/user-attachments/assets/7bd764ed-8fe2-4d63-8cf6-ace9e455b11d" />
<img width="1313" height="739" alt="Screenshot_9" src="https://github.com/user-attachments/assets/97dcf45b-f092-436f-b1d9-6e8b3aab58bd" />



## 🛠️ Problema de Negócio Resolvido
O desafio era centralizar o acompanhamento de fretes e custos operacionais que, muitas vezes, ficam dispersos. A solução foca em responder:
* Qual a nossa margem de lucro real por operação?
* Quais cidades estão apresentando custos acima da meta estabelecida?
* Quais notas fiscais precisam de auditoria por excesso de custo?

## 🏗️ Engenharia de Dados e Ferramentas
Este repositório destaca a capacidade de modelagem desde a origem:

* **Microsoft Excel:** Construção da "Fonte da Verdade". Estruturação completa de tabelas de Clientes, Notas Fiscais, Transportadoras e Cidades (Canoas, Viamão, Cachoeirinha e Porto Alegre), garantindo a integridade dos dados para o BI.
* **Power BI:** ETL (Extração, Transformação e Carregamento) via Power Query e modelagem de dados no padrão Star Schema.
* **DAX Avançado:** Desenvolvimento de fórmulas inteligentes para indicadores de performance, como Margem de Lucro (%) e Status Operacional Condicional.

## 🚀 Diferenciais Técnicos (V2)
Nesta segunda versão do projeto, implementei melhorias focadas em **User Experience (UX)** e inteligência analítica:

* **Inteligência de Alertas:** Lógica condicional para sinalizar automaticamente (ícones amarelos) notas fiscais com custo operacional elevado.
* **Tooltips Dinâmicos:** Implementação de "dicas de ferramenta" com gráficos de rosca. O gestor pode ver a composição dos custos de cada cidade apenas passando o mouse, mantendo o visual principal limpo.
* **Monitoramento de Metas:** Inserção de linhas de referência (benchmarks) para controle de teto operacional (R$ 1.500,00 por operação).
* **Design Dark Mode:** Interface focada em alta legibilidade, simetria e navegação intuitiva.

## 📸 Demonstração das Funcionalidades
### Detalhamento por Cidade (Tooltip)
O uso de Tooltips permite um "drill-down visual".

<img width="1313" height="738" alt="Screenshot_8" src="https://github.com/user-attachments/assets/1d6ce66a-b64b-489b-b63e-dbd4546dbf15" />
