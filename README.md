# TG1 - 5º semestre de BD

 

Professor da Disciplina: Giuliano Bertoti 

 

# TG

 

Aluno: Leonardo Rodrigues Miranda Lins - 1460281813023 \
Orientador: Giuliano Bertoti

 

Título do TG: Instrutor dev IOGA Mobile


# 1ª Quinzena de maio

# Introdução

## 1.0 O problema
Sedentarismo entre jovens.


## 1.1 Motivação

	É notória a proporção atual do sedentarismo. Segundo a Organização Mundial da Saúde (2018), 80% dos adolescentes não praticam atividade física com frequência e intensidade adequada para sua faixa etária.
	O sedentarismo, segundo Barros, é considerado como a doença do próximo milênio, motivada pela falta de execícios físicos, decorrente dos confortos trazidos da vida moderna. Com a evolução da tecnologia e a tendência cada vez maior da troca de atividades ocupacionais que demandem algum gasto energético por facilidades automatizadas, o ser humano adota cada vez mais a lei do menor esforço reduzindo assim o consumo energético de seu corpo (BARROS, 2000).
	São muitos os trabalhos científicos que demonstram o papel fundamental da atividade física evitando e ajudando a tratar doenças muito frequentes e graves como as doenças das coronárias, a hipertensão arterial, a diabetes melitus e algumas formas do câncer. (JOÃO, 2001, p.16). Com o avanço da tecnologia, portanto, a prática de esportes, sobretudo, os meios de diversão entre os mais jovens, tendem a ser naturalmente substituídos por entretenimento digital. Em contrapartida, softwares que envolvam a atividade física podem contribuir neste cenário, trazendo aos usuários uma divertida experiência, sem sair do nicho digital.

## 1.2 Proposta de solução

	Criar uma aplicação para dispositivos móveis que facilite a prática de ioga como exercício físico, aplicando inteligência artificial às imagens obtidas da câmera de um celular, com uma rede neural previamente treinada que identifique o que seria uma movimento correto, auxiliando o aluno durante a prática.
	Para a construção desta aplicação, serão utilizadas as seguintes tecnologias:
•	PoseNet Model
•	TensorFlow Lite
•	Flutter
•	Text to Speech

	O principal algoritmo que é responsável pelo reconhecimento dos movimentos corporais e usa inicialmente o PoseNet - Trata-se de uma biblioteca para machine learning que detecta as poses criadas pelo usuário na aplicação. A sequência de poses detectadas serão usadas para validar se o usuário está realmente realizando os movimentos corretamente, auxiliando-o então com feedbacks.
	Para realizar a instrução ao usuário, será utilizado o Flutter Text to Speech, que trata-se de um plugin do framework Flutter, que gera através de uma instrução trazida do algoritmo uma frase falada artificialmente.

	## 1.2.1 Modelos
	
	Inicialmente o input deve ser tratado, por uma classificação de imagens. Para este tratamento será utilizado o modelo MobileNet.
	Após o tratamento da imagem, é necessário a utilização de um detector de objetos para ambientar a análise e evitar detecções indesejadas. Será utilizado o modelo Yolov2 Tiny para esta finalidade.
	Finalmente o PoseNet trará um esqueleto para viabilização do algoritmo. O conjunto destes modelos, gerará como produto um algoritmo que em tempo real é capaz de detectar os movimentos de um atleta de yoga.
 
## Referências

	Organização Mundial da Saúde. Disponível em < https://www.who.int/news-room/fact-sheets/detail/physical-activity>, Acessado em 25/09/2019.
	BARROS, T.L. Exercício, saúde e desempenho físico. Ed.Atheneu, 1 edição, São Paulo, Brasil, 1997.
	FERREIRA. E. Atividade física, lazer e qualidade de vida. IN. Anais: X Congresso Brasileiro de ciências do esporte, Goiãnia. Vol.ll, 1997.
	JOAO, MH. Sedentarismo: A hipocinesia nos dias atuais. UNICAMP, 2001.
	TENSORFLOW ORG. Vision model that can used to estimate the pose. < https://www.tensorflow.org/lite/models/pose_estimation/ >



(coloque aqui tudo que você fez referente ao capítulo 1 no formato exato de BD)

 

# 2ª Quinzena de maio

 

(coloque aqui tudo que você fez referente ao capítulo 2 no formato exato de BD)

 

# 1ª Quinzena de junho
 
(coloque aqui tudo que você fez referente ao capítulo 3 no formato exato de BD)

 

# 2ª Quinzena de junho

 

(coloque aqui tudo que você fez referente ao capítulo 3 no formato exato de BD) + crie um pasta chamada "Desenvolvimento" e coloque o início do código

 

# 1ª Quinzena de julho

 

(coloque aqui tudo que você fez referente ao capítulo 3 no formato exato de BD) + atualize a continuação do código
