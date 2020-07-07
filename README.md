# TG1 - 5º semestre de BD

 

Professor da Disciplina: Giuliano Bertoti 

 

# TG

 

Aluno: Leonardo Rodrigues Miranda Lins - 1460281813023 \
Orientador: Giuliano Bertoti

 

Título do TG: Instrutor Inteligente de atividades físicas

# 1. Introdução

 É notória a proporção atual do sedentarismo. Segundo a Organização Mundial da Saúde (2018), 80% dos adolescentes não praticam atividade física com frequência e intensidade adequada para sua faixa etária. \
 O sedentarismo, segundo Barros, é considerado como a doença do próximo milênio, motivada pela falta de execícios físicos, decorrente dos confortos trazidos da vida moderna. \ 
 Com a evolução da tecnologia e a tendência cada vez maior da troca de atividades ocupacionais que demandem algum gasto energético por facilidades automatizadas, o ser humano adota cada vez mais a lei do menor esforço reduzindo assim o consumo energético de seu corpo (BARROS, 2000). \
 São muitos os trabalhos científicos que demonstram o papel fundamental da atividade física evitando e ajudando a tratar doenças muito frequentes e graves como as doenças das coronárias, a hipertensão arterial, a diabetes melitus e algumas formas do câncer. (JOÃO, 2001, p.16). \
 Com o avanço da tecnologia, portanto, a prática de esportes, sobretudo, os meios de diversão entre os mais jovens, tendem a ser naturalmente substituídos por entretenimento digital. Em contrapartida, softwares que envolvam a atividade física podem contribuir neste cenário, trazendo aos usuários uma divertida experiência, sem sair do nicho digital.


## 1.1 Objetivos do trabalho

O objetivo geral deste trabalho é desenvolver uma aplicação utilizando conceitos de Deep learning que estimule a prática de exercícios físicos entre jovens.
\
Para a consecução deste objetivo foram estabelecidos os objetivos específicos: \
• Desenvolver um protótipo com a biblioteca Posenet para identificação de poses previamente treinadas. \
• Criar uma interface Web. \
• Propor cenários de melhoria aos treinos. 

## 1.2. Conteúdo do Trabalho

O presente trabalho está estruturado em seis Capítulos, cujo conteúdo é sucintamente apresentado a seguir:
No Capítulo 2 é feita a fundamentação das tecnologias...
O Capítulo 3 apresenta o desenvolvimento da solução...
No Capítulo 4 são apresentados os resultados ...
O Capítulo 5 apresenta as considerações finais  deste trabalho a partir da análise dos resultados obtidos...

## 1.3 Metodologia

Utilizando principalmente o conceitos de redes neurais convolucionais será desenvolvida uma aplicação que estima a pose do usuário e apresenta em uma interface Web. Em formato de game a aplicação desafiará o usuário na execução de poses, em um esquema de pontuação.

# 2. Fundamentação Técnica


## 2.1 Machine Learning
 Segundo Hebert Alexander Simon[7], aprendizado é qualquer processo pelo qual um sistema melhora sua performance pela experiência. No campo da computação a aprendizagem é formada através de um modelo matemático-computacional, que por meio de algoritmos, consegue adaptar-se e aprender de acordo com a experiência.\
 A aprendizagem de máquina pode ser dividida em sub-campos: Aprendizado Supervisionado, Aprendizado por Reforço e Aprendizado Não-Supervisionado.\
 Em modelos de aprendizagem supervisionada, o aprendizado ocorre pela entrada de dados à rede neural com exemplos de entrada e saída(processo conhecido como treinamento). Dependendo da dispersão e dos pesos atribuidos ao treinamento o modelo será capaz de estimar a saída de uma nova entrada desconhecida.  
## 2.1 Métodos de Aprendizagem profunda
 Em métodos de aprendizagem profunda, é feita uma composição aninhada de modelos de aprendizagem dando a possibilidade de se resolver problemas mais complexos.[6] \
 ![DeepLearning](https://www.institutodeengenharia.org.br/site/wp-content/uploads/2019/04/2.png) \
     _Figura 1. Diferenciando arquitetura de modelos de redes neurais simples e profundas._ 
     
## 2.2 Redes Neurais Convolucionais (CNN)
  Redes Neurais Convolucionais recebem este nome por serem compostas de camadas convolucionais que processa as entradas considerando campos receptivos locais.  A principal aplicação de CNN's é no processamento de imagens pelo fato de a convolução permitir criar filtros considerando sua dimensão espacial.[6] 
  ### 2.2.1 Camada Convolucional
   
## 2.3 Aplicações Web
  Uma aplicação web é a junção de tecnologias que permitem através de um modelo cliente-servidor, pode disponibilizar via rede esta aplicação para qualquer cliente, desde que tenha um navegador de acesso. As aplicações web atuais são em maioria formadas pelo conjunto das tecnologias: \
  • Hyper Text Marcation Language (HTML) \
  • Cascading Style Sheets(CSS) \
  • ECMAScript Programming Language (JavaScript) 
  
  A aplicação criada para este trabalho segue o padrão Single Page Application, no lado cliente e API Restful no campo do servidor.

## 2.5 ml5.js

 O ml5.js é uma biblioteca javascript desenvolvida com a finalidade de tornar mais acessível o aprendizado de máquina. Sua implementação é amigável e de fácil uso. Possui implementações de CNN e de modelos já treinados como PoseNet, que dada uma imagem de uma pessoa, é capaz de estimar sua pose.   
 
 # 3. Desenvolvimento
 
  A aplicação desenvolvida utilizará da biblioteca ml5.js em detecção de pose de um indivíduo. A aplicação dispõe de uma interface de usuário que sugere a pose que deve ser feita, para então receber uma pontuação respectiva. Esta interface apresentará qual a pontuação geral do jogador bem como a sua imagem de fundo. \
  O ml5.js provê uma matriz do posicionamento x, y dos ombros do usuário, quadril, cabeça, braços e pernas, e em tempo real submete estes dados à rede já treinada da pose, retornando a classificação. \
  Para auxiliar no treinamento da rede será utilizado o Teachable Machine desenvolvido pela Google. O modelo então treinado é importado pela biblioteca ml5.js que fará a predição da pose dado input da câmera do usuário.
  
  ## 3.1 Treinamento da rede
   
  
# Referências

[1] Organização Mundial da Saúde. Disponível em https://www.who.int/news-room/fact-sheets/detail/physical-activity >, Acessado em 25/09/2019. \
[2] BARROS, T.L. Exercício, saúde e desempenho físico. Ed.Atheneu, 1 edição, São Paulo, Brasil, 1997. \
[3] FERREIRA. E. Atividade física, lazer e qualidade de vida. IN. Anais: X Congresso Brasileiro de ciências do esporte, Goiãnia. Vol.ll, 1997. \
[4] JOAO, MH. Sedentarismo: A hipocinesia nos dias atuais. UNICAMP, 2001. \
[5] TENSORFLOW ORG. Vision model that can used to estimate the pose. https://www.tensorflow.org/lite/models/pose_estimation/ \
[6] IAN GOODFELLOW, YOSHUA BENGIO, and AARON COURVILLE. Deep Learning. MIT Press, 2016. Disponível em http://www.deeplearningbook.org
[7] SIMON, Herbert A. (1955) “A behavioral model of rational choice”, The Quarterly Journal of Econo‑
mics, vol. 69, n. 1, February: 99‑118, compiled in, and quoted from, Simon (1957: 241‑260). \
