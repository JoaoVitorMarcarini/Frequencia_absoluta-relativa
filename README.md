# 📊 Frequência Absoluta e Relativa com Python

Este projeto tem como objetivo demonstrar, de forma simples e prática, o cálculo de **frequência absoluta** e **frequência relativa** utilizando a linguagem Python. A ideia surgiu durante meus estudos em estatística básica, onde percebi o quanto o código pode otimizar análises que, manualmente, se tornam repetitivas e lentas com grandes quantidades de dados.

---

## 🧠 Conceitos abordados

- **Frequência absoluta**: número de vezes que um valor aparece nos dados.
- **Frequência relativa**: proporção percentual que esse valor representa.
- Agrupamento de dados por **classes** (ex: faixas de altura).
- Manipulação e análise de dados com **Pandas**.

---

## 📁 Arquivos do projeto

- `Frequencia_absoluta_e_relativa.ipynb` → Código em Jupyter Notebook, criado no Google Colab.
- `alunos.csv` → Arquivo com dados simulados de 10 alunos (nota e altura).
- `README.md` → Descrição do projeto.

---

## 📌 Estrutura dos dados

O arquivo `alunos.csv` contém:

| Nome     | Nota | Altura |
|----------|------|--------|
| Aluno 1  | 7    | 1.75   |
| Aluno 2  | 6    | 1.68   |
| ...      | ...  | ...    |

Os dados são utilizados para gerar tabelas de frequência com base:
- Nas **alturas** (divididas em faixas de 10 cm)

---

## ▶️ Como executar

1. Acesse o Google Colab ou Jupyter Notebook.
2. Faça upload dos arquivos `alunos.csv` e `Frequencia_absoluta_e_relativa.ipynb`.
3. Execute as células do notebook passo a passo.

---

## 🖼️ Exemplo de saída

O notebook irá gerar tabelas como estas:

**Frequência das Alturas (em faixas)**  
| Altura (m)       | Freq. Absoluta | Freq. Relativa |
|------------------|----------------|----------------|
| 1.60 ≤ x < 1.70  | 3              | 30%            |
| 1.70 ≤ x < 1.80  | 4              | 40%            |

---

## ✍️ Motivação pessoal

> “Durante a revisão de estatística básica para iniciar meus estudos em Machine Learning, percebi como o Python pode potencializar análises simples como essa. Automatizar esse tipo de processo é um dos primeiros passos para quem quer entender dados de forma eficiente.”

---

## 👨‍💻 Tecnologias utilizadas

- Python 3
- Pandas
- Google Colab / Jupyter Notebook

---

## 🤝 Contato

📬 [João Vitor Marcarini](https://www.linkedin.com/in/joaovitormarcarini/)
