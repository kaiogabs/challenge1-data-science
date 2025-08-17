# Alura Store — Análise e Recomendação

> Projeto de Data Science para analisar 4 lojas fictícias da **Alura Store** e recomendar **qual loja o Sr. João deve vender**, com base em faturamento, avaliações, categorias, produtos e frete.

[![Abrir no Colab](https://img.shields.io/badge/Abrir%20no%20Colab-Notebook-blue)](https://colab.research.google.com/github/kaiogabs/challenge1-data-science/blob/main/Desafio_Alura_Store_Final.ipynb)

---

## 🎯 Propósito da Análise

* Calcular as **métricas obrigatórias** por loja:

  * **Faturamento total**
  * **Categorias mais populares**
  * **Média de avaliação dos clientes**
  * **Produtos mais vendidos e menos vendidos**
  * **Frete médio**
* Gerar **3 visualizações diferentes** para apoiar a decisão.
* Escrever um **relatório final** justificando a loja recomendada para venda.

---

## 🗂️ Estrutura do Projeto

```
alura-store/
├─ Desafio_Alura_Store_Final.ipynb   # Notebook principal (Colab-ready)
├─ README.md                         # Este arquivo
├─ CHECKLIST.md                      # Lista de verificação da entrega
└─ base-de-dados-challenge-1/        # (opcional) CSVs da base oficial
   ├─ loja_1.csv
   ├─ loja_2.csv
   ├─ loja_3.csv
   └─ loja_4.csv
```

> Se a pasta `base-de-dados-challenge-1/` não estiver no repositório, o notebook baixa os CSVs diretamente do repositório oficial da Alura (RAW).

---

## 🧪 Exemplos de Gráficos e Insights

O notebook gera, no mínimo, 3 gráficos distintos:

1. **Barras — Faturamento por Loja**
   *Mostra a receita total por loja, útil para comparar desempenho financeiro.*
2. **Pizza — Participação no Faturamento Total**
   *Mostra a fatia (%) de cada loja no faturamento agregado.*
3. **Dispersão — Preço × Frete (exemplo com Loja 1)**
   *Ajuda a visualizar a relação entre preço dos produtos e custo de frete.*

### Principais insights (resultados do notebook)

* **Ranking de faturamento:** **Loja 1** > **Loja 2** > **Loja 3** > **Loja 4**
* **Avaliação média mais baixa:** **Loja 1** (≈ **3,98**)
* **Frete médio mais alto:** **Loja 1** (≈ **R\$ 34,69**)
* **Categorias líderes por loja (Top 1):**

  * Loja 1: **móveis** (465 vendas)
  * Loja 2: **móveis** (442 vendas)
  * Loja 3: **móveis** (499 vendas)
  * Loja 4: **móveis** (480 vendas)
* **Produtos (exemplos — mais/menos vendidos):**

  * Loja 1 — **Mais vendido:** *TV Led UHD 4K* (60) | **Menos vendido:** *Celular ABXY* (33)
  * Loja 2 — **Mais vendido:** *Iniciando em programação* (65) | **Menos vendido:** *Jogo de tabuleiro* (32)
  * Loja 3 — **Mais vendido:** *Kit banquetas* (57) | **Menos vendido:** *Blocos de montar* (35)
  * Loja 4 — **Mais vendido:** *Cama box* (62) | **Menos vendido:** *Guitarra* (33)

**Tabela-resumo**

| Loja   |    Faturamento total | Avaliação média |   Frete médio |
| ------ | -------------------: | --------------: | ------------: |
| Loja 1 | **R\$ 1.534.509,12** |        **3,98** | **R\$ 34,69** |
| Loja 2 |     R\$ 1.488.459,06 |            4,04 |     R\$ 33,62 |
| Loja 3 |     R\$ 1.464.025,03 |            4,05 |     R\$ 33,07 |
| Loja 4 |     R\$ 1.384.497,58 |            4,00 |     R\$ 31,28 |

> Observação: valores de frete e avaliação são médias.

**Conclusão (resumo do relatório):** considerando desempenho relativo (pior avaliação + maior frete, fatores que impactam satisfação e margem), a recomendação foi **vender a Loja 1**, apesar do maior faturamento. Essa decisão prioriza **qualidade percebida** e **eficiência operacional** no longo prazo.

---

## ▶️ Como Executar o Notebook

### Opção 1 — **Colab (recomendado)**

1. Clique no badge **“Abrir no Colab”** no topo (link já apontando para este repositório).
2. No Colab, vá em **Ambiente de execução > Executar tudo**.
3. Ao final, revise/edite o **Relatório Final** no próprio notebook (seção 6).

### Opção 2 — Local (opcional)

1. Clone este repositório.
2. Crie um ambiente e instale dependências (ex.: `pandas` e `matplotlib`).
3. Abra o `Desafio_Alura_Store_Final.ipynb` no Jupyter/VSCode e execute as células na ordem.

---

## 🧾 Relatório Final (estrutura utilizada)

* **Objetivo:** recomendar qual loja vender.
* **Principais métricas:** faturamento, avaliação média, frete médio, categorias e produtos por loja.
* **Comparação:** destaque dos pontos fracos da loja com pior desempenho relativo (no caso, avaliação e frete da Loja 1).
* **Recomendação:** vender a **Loja 1** pelos motivos acima.

---

## 📚 Fonte dos Dados

* Repositório oficial do desafio: `alura-es-cursos/challenge1-data-science` (Alura).
* CSVs: `loja_1.csv`, `loja_2.csv`, `loja_3.csv`, `loja_4.csv`.

---

## ✅ Checklist de Entrega

* [x] Notebook com **todas as métricas** e **3 gráficos diferentes**
* [x] **Relatório final** preenchido no notebook
* [x] **README.md** (este arquivo)
* [x] Repositório **público** no GitHub

---

## 📄 Licença

Projeto para fins educacionais (Alura / Programa One).
