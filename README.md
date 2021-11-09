# Classificação de Tumores Cerebrais em Imagens de Ressonâncias Magnéticas por Redes Neurais Convolucionais

## Problema e resolução

> As possíveis causas relacionadas aos tumores no Sistema Nervoso Central 
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

## Arquiteturas desenvolvidas

### Multi-Classification of Brain Tumor Images Using Deep Neural Network

> A primeira proposta realizada pela pesquisa Multi-Classification of Brain Tumor Images Using Deep Neural Network, aborda o conceito de classificações de multi classes, no qual utilizamos específicos parâmetros para montar a arquitetura da Rede Neural Convolucional (CNN). Nesse sentido, a arquitetura do modelo de aprendizado profundo possui 16 camadas a partir da entrada, no qual passa por pré-processamento, funções de ativação, camadas de pooling e camadas totalmente conectadas. Logo, o modelo de Rede Neural Convolcuinal é avaliado por métricas de desempenho, que através da separação de dados de treino e teste, obteve acurácia de 97.54%, 95.81% e 96.89%, respectivamente, na classificação de meningioma, glioma e hipófise.

### A new deep CNN for brain tumor classification

> A proposta da pesquisa promovida pela equipe W. Ayadi et al. (2020), consiste em desenvolver uma nova técnica, capaz de possuir alto desempenho comparado aos modelos especificados no tópico “Related Work” da pesquisa. Destarte, o modelo proposto detalha a arquitetura da Rede Neural Convolucional (CNN), nas quais são compostas por dez camadas que irão possuir a funcionalidade de extrair padrões, temos a camada de max-pooling a cada duas camadas, a fim de reduzir a dimensionalidade, cada camada convolucional utiliza filtros 3x3 enquanto na camada de pooling é utilizado 2x2, uma camada de não linearidade é desenvolvida para adaptar a rede, utiliza-se uma camada de normalização para se obter otimizações e por fim uma camada totalmente conectada.


## Os objetivos levantados na leitura e compreesão dos artigos acima (até agora) são:

* Análise comparativa:
  * A análise comparativa tem como finalidade entender o comportamento classificativo da Rede Neural Convolucional (CNN) em relação aos conjuntos de dados multi e binários.

## Referências:
 * [Multi-Classification of Brain Tumor Images Using Deep Neural Network](https://ieeexplore.ieee.org/document/8723045)
 * [Brain Tumor Detection and Classifiaction Using CNN Algorithm and Deep Learning Techniques](https://ieeexplore.ieee.org/document/9436599)
 * [A new deep CNN for brain tumor classification](https://ieeexplore.ieee.org/document/9329328)
