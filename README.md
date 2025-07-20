# Reconhecimento Facial com Métricas de Aprendizado (Metric Learning)

Este projeto aplica **métricas de aprendizado (Metric Learning)** para realizar **reconhecimento facial**, utilizando embeddings extraídos de rostos humanos e técnicas como **Triplet Loss** para aprender uma representação discriminativa entre identidades.

---

## 📌 Objetivo

Desenvolver um sistema de reconhecimento facial que:

- Extraia embeddings faciais de imagens.
- Aprenda uma métrica que minimize a distância entre imagens da mesma pessoa e maximize entre pessoas diferentes.
- Avalie a similaridade facial com base nesses embeddings.

---

## 🧠 Técnicas Utilizadas

- **Metric Learning** com `Triplet Loss`
- Extração de características com redes neurais pré-treinadas (ex: `FaceNet`)
- Redução de dimensionalidade e análise exploratória com `PCA` e `t-SNE`
- Avaliação de distância euclidiana e cosseno para verificação facial
- Visualização de clusters de identidades com `matplotlib`

---

## 📁 Estrutura do Projeto

📦 reconhecimento_facial_Metric_Learning
┣ 📒 reconhecimento_facial_Metric_Learning.ipynb
┣ 📁 dataset/
┃ ┣ 📁 pessoa_1/
┃ ┣ 📁 pessoa_2/
┃ ┗ ...
┗ README.md


---

## ⚙️ Dependências

Certifique-se de instalar as bibliotecas abaixo:

```bash
pip install numpy matplotlib scikit-learn keras tensorflow opencv-python

Execute o notebook:

Abra reconhecimento_facial_Metric_Learning.ipynb em um ambiente como Jupyter Notebook, VS Code ou Google Colab.

