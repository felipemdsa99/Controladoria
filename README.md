# 📊 Dashboard de Controladoria e Produção

Dashboard interativo desenvolvido para análise de indicadores industriais utilizando HTML, JavaScript, Chart.js e SheetJS.

O projeto foi criado com foco em demonstrar conhecimentos em análise de dados, visualização de informações e desenvolvimento de dashboards totalmente executados no navegador, sem necessidade de servidor ou banco de dados.

---

## Objetivos

Transformar uma base de produção industrial em informações úteis para tomada de decisão através de:

- KPIs operacionais
- Indicadores de qualidade
- Indicadores de perdas
- Ranking de operadores
- Comparativo entre produtos
- Evolução mensal da produção

---

## Tecnologias utilizadas

- HTML5
- CSS3
- Tailwind CSS
- JavaScript ES6
- Chart.js
- SheetJS (XLSX)
- Gemini
---

## Funcionalidades

✔ Upload de arquivos Excel (.xlsx)

✔ Upload de arquivos CSV

✔ Atualização automática dos gráficos

✔ Reprocessamento dos indicadores em tempo real

✔ Dashboard responsivo

✔ KPIs automáticos

✔ Ranking de operadores

✔ Resumo por produto

✔ Resumo por operador

✔ Indicadores de Setup

✔ Indicadores de Paradas

✔ Indicadores de Refugo

✔ Evolução mensal da produção

---

## Indicadores calculados

O dashboard calcula automaticamente:

- Volume produzido
- Volume aprovado
- Refugo
- Taxa de qualidade
- Taxa de perdas
- Horas de Setup
- Horas de parada
- Produção por mês
- Produção por operador
- Produção por produto
- Ranking de qualidade

---

## Estrutura esperada da planilha

A planilha deve conter as seguintes colunas:

| Coluna |
|---------|
| Data |
| Produto |
| OP |
| Qtde_Total |
| Qtde_Boa |
| Nome_Operador |
| Tempo_Setup_min |
| Tempo_Parada_min |

---

## Como executar

Clone o repositório

```bash
git clone https://github.com/felipemdsa99/Controladoria.git
```


Abra o arquivo

```
index.html
```

em qualquer navegador moderno.

Não é necessário instalar bibliotecas nem utilizar servidor.

---

## Base de dados

O projeto acompanha uma base de dados exemplo contendo registros simulados de produção industrial.

Após abrir o dashboard basta clicar em **Atualizar Base** para importar outro arquivo Excel ou CSV.

Todos os indicadores são recalculados automaticamente.

---

## Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conceitos de:

- Manipulação de dados
- ETL em JavaScript
- Agrupamento de dados
- Cálculo de indicadores (KPIs)
- Visualização de dados
- Desenvolvimento Front-end
- Construção de dashboards
- Organização de código
- Responsividade

---

## Possíveis melhorias

- Filtros por período
- Exportação para PDF
- Exportação para Excel
- Dark Mode
- Dashboard com múltiplas páginas
- Banco de dados
- API REST
- Power BI
- Python para tratamento de dados

---

## Autor

Felipe Martins de Sá

Graduado em Análise e Desenvolvimento de Sistemas

Pós-graduando em Ciência de Dados e Inteligência Artificial

LinkedIn:
(coloque aqui)

GitHub:
(https://github.com/felipemdsa99))
