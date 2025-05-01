#### **Título**

**Sistema de Identificação de Pessoas por Reconhecimento Facial com Filtragem Inteligente Baseada em Gênero e Faixa Etária**

---
### 1. **[[Introdução]]**

- Contextualização e apresentação do tema e da delimitação
- Problema
- Hipótese
- Objetivo Geral
- Objetivo Específicos
- Justificativa
---
### 2. **[[Fundamentação Teórica]]**

- **Biometria e Identificação Humana**
    - Características físicas usadas: altura, peso, cor dos olhos, formato do rosto, etc.
- **Redes Neurais Artificiais**
- **Aprendizado Supervisionado**
    - Classificação e regressão.
- **Redes Neurais Convolucionais (CNNs)**
- **Dataset e Pré-processamento**
    - Explicação da importância do balanceamento, normalização, aumento de dados (data augmentation), etc.
- **Ferramentas**
    - Python, TensorFlow, Keras, PyTorch, OpenCV.

---
### 3. **[[Metodologia]]**

- Coleta ou uso de base de dados pública.
- Definição das classes: sexo, idade estimada, etnia
- Pré-processamento das imagens: redimensionamento, normalização, etc.
- Arquitetura da rede usada.
- Critérios de avaliação: acurácia, precisão, recall, F1-score, matriz de confusão.

---
### 4. **[[Resultados]]**

- Desempenho do modelo nos testes.
- Comparação entre arquiteturas (se fizer mais de uma).
- Exemplos de acertos e erros.
- Análise das limitações do modelo (ex: viés, iluminação, pose da imagem).

---
### 5. **[[Conclusão]]**

- Discussão sobre os resultados.
- Possíveis aplicações práticas.
- Sugestões para trabalhos futuros (ex: reconhecimento por vídeo, fusão de características físicas e comportamentais, redes siamesas para verificação de identidade).

---

### Ferramentas e Tecnologias
- Dataset: [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) (características faciais anotadas), [VGGFace2](https://www.robots.ox.ac.uk/~vgg/data/vgg_face2/), ou datasets gerados com ferramentas como MakeHuman ou StyleGAN.

### Mapeamento da Pesquisa
[[Hipóteses]]
[[Objetivos]]
[[Motivação]]
[[Motivação]]
[[Delineamento do Problema]]
[[Pergunta de Pesquisa]]
[[Perguntas Norteadoras]]
[[Revisão Sistemática]]