# 🎮 Projeto de Análise de Assinaturas de Jogos

Este projeto tem como objetivo analisar os dados de assinaturas de diferentes planos de jogos (como Xbox Ultimate, Core e Standard), considerando a inclusão de serviços como EA Play e Minecraft, e apresentar insights por meio de dashboards e cálculos agregados.

## 📁 Estrutura da Planilha

A planilha `Projeto3.xlsx` é composta por quatro abas principais:

### 1. 🖌️ A̳ssets
Contém a **paleta de cores** e alguns elementos visuais utilizados no dashboard, como:
- Códigos hexadecimais para cores (ex: `#22C55E`, `#9BC848`)
- Informações de estilo visual para facilitar a padronização gráfica.

### 2. 🧾 B̳ases
Contém a base de dados dos assinantes:
- `Subscriber ID`: identificador único do assinante
- `Name`: nome do cliente
- `Plan`: tipo de plano contratado (Core, Standard, Ultimate)
- `Start Date`, `Auto Renewal`: data de início e renovação automática
- `Subscription Price`, `Subscription Type`: preço e periodicidade (mensal, anual, trimestral)
- Informações adicionais sobre **EA Play** e **Minecraft Season Pass**
- Valores dos cupons e **Total Value** gerado por cliente

### 3. 📊 C̳álculos
Apresenta análises derivadas da base:
- **Pergunta 1:** Total de vendas por tipo de plano
- **Pergunta 2:** Total de vendas por jogo (EA Play e Minecraft)
- **Pergunta 3:** Total de vendas por tipo de assinatura (Mensal, Anual etc.)
- Tabelas com **soma dos valores**, segmentadas por mês e tipo

### 4. 📈 D̳ashboard
Abas reservadas para visualização gráfica dos dados (atualmente vazia na planilha fornecida).

## 📌 Objetivos do Projeto

- Centralizar e organizar os dados de assinaturas
- Calcular indicadores de valor total por plano e por jogo
- Gerar visualizações que apoiem decisões estratégicas sobre os planos

## 🚀 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
