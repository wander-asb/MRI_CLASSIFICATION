![MRI](http://mmmoficial.org/mo_includes/img/publicacion/milagro-de-dios-cinco-tumores-cerebrales-desaparecen-luego-de-orar-a-dios_mmmoficial_2020-03-12-16-33-31_8765.jpg)

# Classificação de Tumores Cerebrais em Imagens de Ressonâncias Magnéticas por Redes Neurais Convolucionais

## Problema e resolução

As possíveis causas relacionadas aos tumores no Sistema Nervoso Central 
(SNC) ainda não obtiveram total consenso científico sobre sua origem, mas os 
diagnósticos responsáveis nas análises de detecção de tumores evoluem 
gradativamente com o avanço da tecnologia na área da saúde. Por conseguinte, na 
realização do diagnóstico médico, estão vinculados aos aparecimentos de sintomas 
em um determinado intervalo de tempo, no qual está referente ao início dos sintomas 
até o momento da realização do diagnóstico, nas quais os tumores precisam ser 
detectados o mais rápido possível para maximizar a probabilidade de melhora do 
paciente. Logo, esta pesquisa possui principal finalidade informar, auxiliar e propor a 
possibilidade do diagnóstico por meio de um modelo de Redes Neurais 
Convolucionais, cujo objetivo será validar a revelação de Meningiomas, Gliomas e 
tumores da Glândula Pituitária por intermédio do modelo de aprendizado profundo, 
responsável por classificar os três tipos de tumores do conjunto de dados.

### Multi-Classification of Brain Tumor Images Using Deep Neural Network

A proposta de pesquisa promovida pela equipe H. H. Sultan et al. (2019), Multi-Classification of Brain Tumor Images Using Deep Neural Network, aborda o conceito de classificações, no qual utilizamos específicos parâmetros para montar a arquitetura da Rede Neural Convolucional (CNN). Nesse sentido, a arquitetura do modelo de aprendizado profundo possui 16 camadas a partir da entrada, no qual passa por pré-processamento, funções de ativação, camadas de pooling e camadas totalmente conectadas.

## Pré-processamento

A base de dados é composta pelo total de 3.264 imagens de ressonâncias magnéticas, no qual separamos em conjunto de dados de treino e teste, respectivamente, 80% e 20%. Entretanto, ao avaliar o conjunto formado por mais de 3.000 imagens, visualiza-se que, existe classes que estão desbalanceadas em relação com a classe de cérebros que não apresentam tumor. Logo, a metodologia abordada no trabalho foi random undersample, que será responsável por separar as imagens de cada diretório de classe de maneira randômica, a fim de igualar as classes majoritárias de acordo com a categoria de não tumor, de maneira que, em seguida, separamos os dados de treino em teste como antes citado.

Vale saliuentar que, utilizou-se tranferência de arquivos para uma pasta externa, que denominamos como "lixeira", de modo que independentemente se usaríamos ou não futuramente o dataset, não iríamos perder os dados, apenas guardá-las em um lugar que não chamaríamos quando for necessário utilizar o conjunto de treino e teste.

## Arquitetura desenvolvida

<img src="https://github.com/wander-asb/MRI_CLASSIFICATION/blob/main/multi-classification%20architecture%20CNN.png?raw=true" width="949" height="250" />

## Métodos e resultados

...


## Os objetivos:

* Análise comparativa:
  * A análise comparativa tem como finalidade entender o comportamento classificativo da Rede Neural Convolucional (CNN) em relação aos conjuntos de dados multi e binários.

## Resultados e discussão: 

## Referências:
 * [Multi-Classification of Brain Tumor Images Using Deep Neural Network](https://ieeexplore.ieee.org/document/8723045)
