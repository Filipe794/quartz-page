Nas últimas décadas, o avanço da inteligência artificial (IA) e da visão computacional tem impulsionado significativamente o desenvolvimento de sistemas capazes de interpretar, analisar e extrair informações de imagens e vídeos. No contexto da segurança pública, do monitoramento de ambientes e da análise demográfica, cresce a demanda por soluções tecnológicas que automatizem a identificação de pessoas de forma precisa, rápida e confiável.

Entre essas soluções, o reconhecimento facial se destaca como uma das técnicas mais promissoras da biometria moderna. Ao utilizar características únicas do rosto humano para identificar indivíduos, esse método vem sendo amplamente adotado em aeroportos, instituições financeiras, sistemas de vigilância urbana e dispositivos pessoais. O uso de redes neurais profundas permitiu elevar os níveis de acurácia e robustez desses sistemas, tornando possível identificar rostos mesmo em condições adversas, como variações de iluminação, ângulo e expressões faciais.

Apesar dos avanços, a identificação de pessoas em grandes bases de dados ainda representa um desafio computacional, especialmente quando se busca otimizar o tempo de resposta sem comprometer a precisão do reconhecimento. Nesse cenário, a filtragem inteligente baseada em atributos físicos, como gênero e faixa etária, surge como uma estratégia eficaz para restringir o escopo de busca e melhorar o desempenho do sistema.

Diante desse contexto, o presente trabalho propõe o desenvolvimento de um sistema de identificação de pessoas por reconhecimento facial, que utiliza o framework DeepFace para realizar a detecção e o reconhecimento de rostos, bem como a classificação dos indivíduos com base em gênero e idade estimada. A partir dessas informações, o sistema aplica uma filtragem inteligente que reduz o número de comparações necessárias, otimizando o processo de identificação em ambientes com grande fluxo de pessoas.
## Definição do Problema

Com o avanço das tecnologias de visão computacional e inteligência artificial, o reconhecimento facial tornou-se uma ferramenta poderosa para sistemas de segurança, controle de acesso e análise comportamental. No entanto, mesmo com o uso de redes neurais profundas, muitos sistemas ainda enfrentam desafios quando precisam identificar indivíduos em ambientes com grande fluxo de pessoas e extensos bancos de dados faciais.

O processo de verificação da identidade, que exige a comparação do rosto detectado com todos os registros existentes, pode resultar em tempo de resposta elevado, especialmente em contextos que exigem decisões em tempo real. Isso gera um gargalo de eficiência, reduzindo a aplicabilidade prática desses sistemas em situações críticas, como estações de transporte público, instituições bancárias ou grandes eventos.

Nesse cenário, surge a necessidade de investigar estratégias que otimizem o desempenho desses sistemas sem comprometer a acurácia das identificações. Uma dessas estratégias é a filtragem inteligente baseada em atributos físicos visuais, como gênero e faixa etária estimada, que poderia restringir o conjunto de dados a ser analisado, acelerando o processo de correspondência facial.

Dessa forma, o problema central deste trabalho pode ser formulado da seguinte maneira: 
- “Como tornar o processo de identificação facial mais rápido e eficiente, sem comprometer a acurácia, em ambientes com grande fluxo de pessoas e bases de dados extensas?”


## Premissas e Hipóteses

Parte-se das seguintes premissas:
- O reconhecimento facial com redes neurais profundas, como os modelos integrados no framework DeepFace, possui alta acurácia, mas apresenta limitações de desempenho quando confrontado com grandes volumes de dados.
- A classificação prévia de imagens faciais por gênero e faixa etária pode ser feita de forma automatizada e com boa confiabilidade.
- A filtragem do banco de dados com base nesses atributos reduz significativamente o número de comparações necessárias para identificar um indivíduo.

A hipótese central do trabalho é: A aplicação de uma filtragem prévia baseada em características físicas como gênero e faixa etária reduz o tempo necessário para identificar uma pessoa em um banco de dados facial, aumentando a eficiência do sistema sem comprometer a acurácia do reconhecimento.

## Objetivos
### Geral

Propor um sistema de identificação de pessoas por reconhecimento facial que utilize filtragem inteligente baseada em características físicas — como gênero e faixa etária — para otimizar a eficiência do processo de busca em bases de dados visuais, sem comprometer a acurácia do reconhecimento.
### Objetivos Específicos

- Implementar um sistema de reconhecimento facial utilizando o framework DeepFace com foco na extração de atributos físicos visuais (gênero e faixa etária).
- Desenvolver um mecanismo de filtragem inteligente que restrinja a busca de identificação no banco de dados com base nos atributos estimados.
 - Avaliar a eficiência e a acurácia do sistema proposto em comparação com métodos tradicionais de reconhecimento facial sem filtragem prévia.


## Estrutura da Monografia

Esta monografia está organizada em cinco capítulos, além das seções introdutória e final, conforme descrito a seguir:

Capítulo 1 – Introdução: Apresenta a contextualização do tema, a definição do problema, os objetivos da pesquisa, a justificativa da escolha e a estrutura do trabalho.

Capítulo 2 – Fundamentação Teórica: Aborda os principais conceitos relacionados ao reconhecimento facial, redes neurais profundas, biometria facial, classificação de atributos físicos (gênero e idade), e frameworks utilizados como o DeepFace.

Capítulo 3 – Metodologia: Descreve os métodos e técnicas aplicados no desenvolvimento do sistema proposto, incluindo a preparação dos dados, as etapas de classificação e filtragem, a arquitetura do sistema e os critérios de avaliação.

Capítulo 4 – Resultados e Discussão: Apresenta os testes realizados, os resultados obtidos em termos de tempo de processamento e acurácia, e discute as vantagens e limitações da abordagem proposta.

Capítulo 5 – Considerações Finais: Traz as conclusões do trabalho, as contribuições alcançadas, possíveis aplicações práticas e sugestões para pesquisas futuras.
