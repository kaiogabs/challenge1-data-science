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

### Principais insights (preencha após rodar)

* **Ranking de faturamento:** Loja \[preencher] > Loja \[preencher] > …
* **Avaliação média mais baixa:** Loja \[preencher] (ponto de atenção para satisfação de clientes).
* **Frete médio mais alto:** Loja \[preencher] (pode reduzir margem e conversão).
* **Categorias líderes por loja:**

  * Loja 1: \[preencher]
  * Loja 2: \[preencher]
  * Loja 3: \[preencher]
  * Loja 4: \[preencher]
* **Produtos (exemplos):**

  * Loja \[preencher] — **Mais vendido:** \[preencher] | **Menos vendido:** \[preencher]

> Depois de executar o notebook, você pode copiar os números do `resumo_df` e colar aqui.

**Tabela-resumo (substitua os valores):**

| Loja   | Faturamento total | Avaliação média |  Frete médio |
| ------ | ----------------: | --------------: | -----------: |
| Loja 1 |      \[preencher] |    \[preencher] | \[preencher] |
| Loja 2 |      \[preencher] |    \[preencher] | \[preencher] |
| Loja 3 |      \[preencher] |    \[preencher] | \[preencher] |
| Loja 4 |      \[preencher] |    \[preencher] | \[preencher] |

---

## ▶️ Como Executar o Notebook

### Opção 1 — **Colab (recomendado)**

1. Clique no badge **“Abrir no Colab”** no topo (ajuste a URL com **seu usuário**/**seu repositório**).
2. No Colab, vá em **Ambiente de execução > Executar tudo**.
3. Ao final, revise/edite o **Relatório Final** no próprio notebook (seção 6).

### Opção 2 — Local (opcional)

1. Clone este repositório.
2. Crie um ambiente e instale dependências (ex.: `pandas` e `matplotlib`).
3. Abra o `Desafio_Alura_Store_Final.ipynb` no Jupyter/VSCode e execute as células na ordem.

---

## 🧾 Relatório Final (exemplo de estrutura)

No final do notebook há uma célula de **Markdown** para o relatório. Estruture assim:

* **Objetivo** (1–2 linhas): recomendar qual loja vender.
* **Principais métricas** (números resumidos por loja).
* **Comparação** (2–4 linhas): destaque **pontos fracos** da loja recomendada para venda.
* **Recomendação** (1 linha): “Recomendo vender a **Loja X** pelos motivos A, B, C.”

---

## 📚 Fonte dos Dados

* Repositório oficial do desafio: `alura-es-cursos/challenge1-data-science` (Alura).
* Os CSVs usados são `loja_1.csv`, `loja_2.csv`, `loja_3.csv`, `loja_4.csv`.

---

## ✅ Checklist de Entrega

* [ ] Notebook com **todas as métricas** e **3 gráficos diferentes**
* [ ] **Relatório final** preenchido no notebook
* [ ] **README.md** (este arquivo)
* [ ] Repositório **público** no GitHub

---

## 📄 Licença

Projeto para fins educacionais (Alura / Programa One).
