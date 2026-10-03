# 📊 Análise de Dados do ENEM 2021

## 📌 Sobre o projeto

Este projeto apresenta uma análise exploratória dos Microdados do ENEM 2021, utilizando Python para analisar o desempenho dos participantes nas provas de Matemática e Redação.

A análise busca identificar diferenças no desempenho médio entre os estados brasileiros e comparar os resultados de estudantes de escolas públicas e privadas.

---

## 🎯 Objetivo

O principal objetivo deste projeto é analisar o desempenho dos participantes do ENEM 2021, utilizando as notas de Matemática e Redação.

Durante a análise foram realizadas:

- Análise da média das notas de Redação por estado;
- Ranking dos estados por desempenho em Redação;
- Análise da média das notas de Matemática por estado;
- Ranking dos estados por desempenho em Matemática;
- Comparação do desempenho entre escolas públicas e privadas;
- Comparação dos resultados de Matemática e Redação.

---

## 🛠️ Ferramentas utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Excel
- GitHub

---

## 📂 Base de dados

A análise utiliza os Microdados do ENEM 2021 disponibilizados pelo INEP.

Foram utilizadas as seguintes variáveis:

| Variável | Descrição |
|---|---|
| `SG_UF_PROVA` | Estado onde a prova foi realizada |
| `TP_SEXO` | Sexo do participante |
| `TP_ESCOLA` | Tipo de escola |
| `NU_NOTA_MT` | Nota de Matemática |
| `NU_NOTA_REDACAO` | Nota da Redação |

Para a análise, foram consideradas as observações que possuíam notas válidas de Matemática e Redação.

---

## 📈 Principais análises

### 📝 Ranking de Redação

Foi calculada a média da nota de Redação para cada estado, permitindo comparar o desempenho médio entre as diferentes unidades federativas.

### 🧮 Ranking de Matemática

Também foi calculada a média da nota de Matemática por estado, criando um ranking de desempenho.

### 🏫 Pública x Privada

O projeto também realiza uma comparação entre estudantes de escolas públicas e privadas, analisando as médias de Matemática e Redação.

### 📊 Comparação dos resultados

Por fim, os resultados de Matemática e Redação são comparados para observar como os estados se comportam nas duas áreas avaliadas.

---
## 💡 Conclusão

A análise mostra diferenças nas médias de desempenho entre os estados brasileiros nas provas de Matemática e Redação.

Também foi realizada uma comparação entre estudantes de escolas públicas e privadas, permitindo observar diferenças nas médias de desempenho entre os dois grupos.

O projeto foi desenvolvido com o objetivo de praticar análise exploratória de dados e transformar uma grande base de dados em informações mais fáceis de interpretar.

## 👨‍💻 Autor

**Yarlei Cavalcante**

Projeto desenvolvido para portfólio de Análise de Dados.

## 📁 Estrutura do projeto

```text
analise-enem-2021/
│
├── analise_enem.ipynb
├── analise_enem.xlsx
├── README.md
└── .gitignore
