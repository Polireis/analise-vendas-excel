# Análise de Vendas Corporativas - ETL e Dashboard

Este projeto demonstra um fluxo completo de tratamento de dados (ETL) e análise visual, utilizando uma base de dados de vendas de uma empresa fictícia. O objetivo foi transformar dados brutos em insights estratégicos para a tomada de decisão.

## 📁 Estrutura do Repositório

* **`/data-raw`**: Contém o arquivo original (`dados_vendas_empresa_1.xlsx`) com informações de data, cliente, estado e valores brutos.
* **`/data-processed`**: Arquivo final (`dados_vendas_empresa_V1.xlsx`) após o processo de limpeza, tratamento e criação de métricas.
* **`/screenshots`**: Imagens do dashboard e das tabelas dinâmicas para visualização rápida.

## 🛠️ O Processo de Engenharia de Dados (ETL)

Para transformar os dados, foram aplicadas as seguintes etapas:

* **Limpeza e Padronização**: Tratamento de colunas de localização e categorias.
* **Enriquecimento de Dados**: 
    * Criação de colunas temporais (Ano, Mês, Dia, Dia da Semana) para análise de sazonalidade.
    * Cálculo de métricas de negócio: **Lucro** e **Gastos** baseados no total da venda.
* **Segmentação de Clientes**: Implementação de lógica para identificar clientes **VIP** e **NÃO VIP**.

## 📊 Insights e Resultados

O projeto foca em responder perguntas críticas como:
* Qual o comportamento de vendas ao longo dos meses?
* Qual a performance por categoria (Alimentos, Móveis, Eletrônicos)?
* Quais regiões possuem maior volume de vendas?

## 🖼️ Visualização do Dashboard

<div align="center">
  <img src="Captura de tela 2026-05-03 215854.png" width="800px">
  <p><i>Análise de vendas no tempo</i></p>
  
  <img src="Captura de tela 2026-05-03 215933.png" width="800px">
  <p><i>Categorias e Produtos</i></p>

  <img src="Captura de tela 2026-05-03 215942.png" width="800px">
  <p><i> Regiões e Segmentação de Clientes VIP</i></p>
</div>
