# Projeto de Análise de Vendas de Cursos
### Trilha inicial ***Codigo Certo Coders***

## Descrição

Este projeto tem como objetivo realizar uma análise básica de dados utilizando Python, explorando um conjunto de dados pré-definido para extrair insights simples através de estatísticas descritivas e visualizações gráficas.

## Estrutura do Projeto

1. **Dados**:
   - ID do Curso
   - Nome do Curso
   - Quantidade de Vendas
   - Preço Unitário
   - Data da Venda

2. **Análise**:
   - Total de Vendas por Curso
   - Distribuição das Vendas ao Longo do Tempo

3. **Visualização**:
   - Gráfico de Vendas por Curso
   - Gráfico das Vendas por Tempo

## Dados

Os dados analisados são organizados da seguinte forma:

| ID | Nome do Curso | Quantidade de Vendas | Preço Unitário | Data       |
|----|---------------|----------------------|----------------|------------|
| 0  | Introdução à Programação em Python | 50 | 39.9 | 2023-01-01 |
| 1  | Desenvolvimento Web com HTML e CSS | 30 | 59.9 | 2023-01-02 |
| 2  | JavaScript Avançado: Frameworks e Bibliotecas | 20 | 79.9 | 2023-01-03 |
| 3  | Introdução ao Machine Learning | 15 | 99.9 | 2023-01-04 |
| 4  | Desenvolvimento Mobile com React Native | 25 | 69.9 | 2023-01-05 |

**Total de Vendas por Curso:**

| Nome do Curso | Total de Vendas |
|---------------|-----------------|
| Arquitetura de Microserviços | 2697.0 |
| Banco de Dados SQL e NoSQL | 2397.0 |
| Cloud Computing com AWS | 3696.3 |
| Desenvolvimento Mobile com React Native | 4403.7 |
| Desenvolvimento Web com HTML e CSS | 4492.5 |
| DevOps: Integração e Entrega Contínua | 1678.6 |
| Introdução ao Machine Learning | 3696.3 |
| Introdução à Programação em Python | 3790.5 |
| JavaScript Avançado: Frameworks e Bibliotecas | 4234.7 |
| Segurança da Informação: Fundamentos | 1648.5 |

## Análise

- O curso de **Desenvolvimento Web com HTML e CSS** foi o mais vendido.
- O curso de **Segurança da Informação: Fundamentos** teve o menor número de vendas.

## Visualização

Foi gerado um gráfico mostrando a distribuição de vendas por curso, e outro a distribuição das vendas ao longo do tempo. O gráfico mostra que as vendas foram positivas e consistentes, com nenhum dia sem vendas.

## Requisitos
pandas
numpy
matplotlib
notebook
Você pode instalar as bibliotecas necessárias usando o arquivo requirements.txt:
```pip install -r requirements.txt```
