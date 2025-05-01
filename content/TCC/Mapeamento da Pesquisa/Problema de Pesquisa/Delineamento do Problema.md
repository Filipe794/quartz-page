### 1. Definição Clara
Como desenvolver um sistema de visão computacional que realize a contagem de pessoas, identifique o gênero (masculino/feminino) e estime a faixa etária dos indivíduos que circulam no Shopping de Caxias, com precisão, a partir de imagens capturadas por câmeras?

### 2. Relevância

1. O monitoramento inteligente do fluxo de pessoas em centros comerciais tem se tornado cada vez mais importante para fins de segurança, marketing estratégico e alocação de recursos.

2. A implementação de um sistema que automatize a coleta de dados demográficos (gênero e idade) pode otimizar campanhas publicitárias, melhorar o atendimento ao cliente e fornecer insights relevantes para a gestão do shopping, impactando diretamente o setor varejista e a experiência do consumidor.

### 3. Contextualização

1. Com o crescimento do uso de **visão computacional e inteligência artificial** no setor de varejo, surgem oportunidades para automatizar a análise do público em tempo real, substituindo métodos manuais e menos precisos.
2. De acordo com a consultoria **Gartner**, o uso de **analytics em tempo real** para análise de comportamento do consumidor tende a crescer 25% ao ano até 2026. Tecnologias como YOLOv8 e redes neurais convolucionais (CNNs) já vêm sendo aplicadas para estimar idade e gênero com alta acurácia.
3. Estudos mostram que sistemas de contagem de pessoas e segmentação demográfica têm sido implementados em shoppings e aeroportos em países como Estados Unidos, China e Reino Unido, mas ainda são pouco explorados no Brasil em escala regional.

### 4. Delimitação

- **Espaço**: Shopping de Caxias.
- **Tempo**: A definir
- **População-alvo**: Indivíduos que circulam pelas áreas monitoradas do shopping, capturados pelas câmeras instaladas.
- **Tecnologia**: Câmeras de vigilância já existentes ou de baixo custo; uso de ferramentas de código aberto como OpenCV, PyTorch e modelos pré-treinados.
- A pesquisa **não abordará** questões relacionadas à identificação individual (biometria ou reconhecimento facial nominal), respeitando a privacidade dos indivíduos.

### 5. Objetividade

- O objetivo é propor, implementar e testar um sistema automatizado que consiga:
    - Contar o número de pessoas.
    - Classificar o gênero (homem/mulher).
    - Estimar a faixa etária (ex: criança, jovem, adulto, idoso).
- Os dados obtidos devem ser quantitativos, com métricas como acurácia, tempo de processamento (FPS), taxa de erro e taxa de classificação correta por categoria.

### 6. Viabilidade

1. O sistema será implementado utilizando um conjunto de ferramentas acessíveis (YOLOv8, OpenCV, MediaPipe, etc.), com treinamento de modelos usando datasets públicos como **UTKFace**, **Adience** e **FairFace**.

2. Os testes poderão ser realizados com vídeos capturados no local com autorização, ou por simulação em ambiente controlado com vídeos semelhantes disponíveis online.

3. O hardware necessário (notebook com GPU ou Google Colab Pro) está disponível.

### 7. **Relacionamento com Hipóteses e Objetivos**

**Hipóteses:**

- É possível identificar automaticamente o número de pessoas, o gênero e a faixa etária com alta precisão usando modelos de deep learning.
    
- A aplicação desse sistema contribuirá para tomadas de decisão mais estratégicas dentro do shopping.
    

**Objetivos:**

- Desenvolver um protótipo funcional de um sistema de contagem e classificação de público.
- Avaliar a precisão e o desempenho do sistema em condições reais ou simuladas.
- Fornecer relatórios de análise demográfica automatizada.

**Perguntas que se busca responder:**

- Qual a precisão do sistema na contagem de pessoas em ambientes com diferentes níveis de ocupação?
    
- Qual a taxa de acerto na classificação de gênero e faixa etária?
    
- O sistema consegue operar em tempo real com os recursos computacionais disponíveis?