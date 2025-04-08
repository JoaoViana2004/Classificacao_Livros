# 📚 Classificador de Livros: Científico ou Não?

Este projeto consiste em um experimento de **classificação de livros** com o objetivo de identificar se um livro é **científico** ou **não científico**, utilizando técnicas de **aprendizado de máquina** com o algoritmo **Naive Bayes**.

O código principal está contido no notebook `Classificacao_Livros.ipynb`.

---

## 🎯 Objetivo

Desenvolver um modelo simples e eficiente que consiga, com base em características do livro (como título, descrição, palavras-chave, etc.), realizar a **classificação binária** entre:

- 📘 Livros científicos
- 📕 Livros não científicos

---

## 🧰 Tecnologias e Bibliotecas

- Python 3
- Pandas
- Scikit-learn (`MultinomialNB`, `CountVectorizer`, `confusion_matrix`, etc.)
- Matplotlib e Seaborn para visualizações

---

## 📊 Etapas do Projeto

1. **Coleta e preparação dos dados**  
   Organização dos livros com seus respectivos rótulos.

2. **Vetorização dos textos**  
   Conversão dos dados textuais em vetores numéricos usando `CountVectorizer`.

3. **Treinamento do modelo**  
   Utilização do algoritmo **Naive Bayes** (`MultinomialNB`) para treinamento e previsão.

4. **Avaliação do modelo**  
   - Acurácia
   - Matriz de confusão personalizada
   - Relatório de classificação (`precision`, `recall`, `f1-score`)

---

## 📈 Resultado

O modelo foi capaz de obter uma boa taxa de acerto para a tarefa proposta, demonstrando que mesmo algoritmos simples podem ser bastante eficazes em problemas de classificação textual com dados bem estruturados.

---
![download (4)](https://github.com/user-attachments/assets/e3d99b3a-a425-486a-b3ce-d70a54dd8d39)
![download (2)](https://github.com/user-attachments/assets/52a93061-f223-48c3-8116-ca2e83a08755)




