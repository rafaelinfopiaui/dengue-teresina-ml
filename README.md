# Previsão de Casos de Dengue em Teresina-PI com IA e Machine Learning

Este repositório contém o projeto **Aplicação de Inteligência Artificial e Machine Learning para previsão de casos de dengue em Teresina-PI (2020–2024)**, desenvolvido a partir da integração de dados epidemiológicos (SINAN/DATASUS) e climáticos (INMET).  

Foram testados e comparados modelos de regressão — **Regressão Linear, Random Forest e XGBoost** — para avaliar sua capacidade preditiva na ocorrência de dengue.  

---

## 🎓 Contexto Acadêmico

Este trabalho foi desenvolvido como **Atividade em Grupo** da disciplina **Deep Learning e Machine Learning**, 
do **Curso de Engenharia de Computação com Inteligência Artificial**  do **Centro Universitário Tecnológico de Teresina – UNI-CET**,  ministrada pelo  
Prof. Me. **Artur Felipe da Silva Veloso**.

---

## 👥 Integrantes do Grupo
- Rafael Sampaio Oliveira  
- Ailton Medeiros Rodrigues  
- Lais Liborio Neiva Eulalio  
- Paula Iranda Sousa Duarte  
- Mauricio Matheus dos Santos Lima  

---

## 📂 Estrutura do Repositório

/dados
/raw
dengue_raw.csv <- dados brutos de casos de dengue (SINAN/DATASUS)
clima_raw.csv <- dados brutos climáticos (INMET)
/processed
dengue.csv <- dados tratados de dengue
clima.csv <- dados tratados climáticos

/notebooks
dengue_predicao.ipynb <- notebook principal com análise, modelagem e resultados

/artigos
artigo_dengue.pdf <- artigo científico (versão final em PDF)

README.md <- este arquivo


---

## ⚙️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/rafaelinfopiaui/dengue-teresina-ml.git
   cd dengue-teresina-ml

2. Abra o notebook no Google Colab:

O projeto foi desenvolvido e testado no Google Colaboratory (Colab),
utilizando Python 3 com suporte a GPU T4.

3. Estrutura de dados esperada:

/dados/raw/       -> arquivos originais
/dados/processed/ -> arquivos já tratados para modelagem

---

📊 Resultados

O XGBoost (implementação de Gradient Boosting) obteve o melhor desempenho:

R² ≈ 0.86

RMSE ≈ 126

MAE ≈ 81

Esses resultados evidenciam a capacidade do modelo em capturar padrões temporais e sazonais da dengue, com destaque para a importância das variáveis médias móveis e defasagens de casos.

---

📖 Referência ao Artigo

O artigo completo pode ser acessado em:
📄 Aplicação de Inteligência Artificial à Modelagem Preditiva da Dengue em Teresina-PI (2020–2024)

---

📜 Licença

Este projeto está licenciado sob a MIT License – veja o arquivo LICENSE
 para mais detalhes.

---

✍️ Sugestão de Citação:

Oliveira, R. S.; Rodrigues, A. M.; Eulalio, L. L. N.; Duarte, P. I. S.; Lima, M. M. S.; Veloso, A. F. S.
Aplicação de Inteligência Artificial à Modelagem Preditiva da Dengue em Teresina-PI (2020–2024).
Centro Universitário Tecnológico de Teresina – UNI-CET, 2025.
