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

## Arquiteturas desenvolvidas

### Multi-Classification of Brain Tumor Images Using Deep Neural Network

A proposta de pesquisa promovida pela equipe H. H. Sultan et al. (2019), Multi-Classification of Brain Tumor Images Using Deep Neural Network, aborda o conceito de classificações, no qual utilizamos específicos parâmetros para montar a arquitetura da Rede Neural Convolucional (CNN). Nesse sentido, a arquitetura do modelo de aprendizado profundo possui 16 camadas a partir da entrada, no qual passa por pré-processamento, funções de ativação, camadas de pooling e camadas totalmente conectadas.

> Diante da modelagem da arquiteura apresentada na pesquisa, não houve empasses relacionados a GPU, o modelo tem como arquitetura as mesmas características vinculadas ao parágrafo acima, porém, o número de mapas de características foram alterados, a pesquisa apresenta o uso de 64 features maps, enquanto na modelagem realizada nesse repositório utiliza-se 128 camadas que visam encontrar padrões nas fotos. Diante disso, o conjunto de dados estão separados de acordo com o download fornecido pelo Kaggle, isto é, não ocorreu ainda manipulação, aplicação de filtros ou alterações do conjunto de dados de treino e teste, apenas o resize para 128x128.

### A new deep CNN for brain tumor classification

A proposta da pesquisa promovida pela equipe W. Ayadi et al. (2020), consiste em desenvolver uma nova técnica, capaz de possuir alto desempenho comparado aos modelos especificados no tópico “Related Work” da pesquisa. Destarte, o modelo proposto detalha a arquitetura da Rede Neural Convolucional (CNN), nas quais são compostas por dez camadas que irão possuir a funcionalidade de extrair padrões, temos a camada de max-pooling a cada duas camadas, a fim de reduzir a dimensionalidade, cada camada convolucional utiliza filtros 3x3 enquanto na camada de pooling é utilizado 2x2, uma camada de não linearidade é desenvolvida para adaptar a rede, utiliza-se uma camada de normalização para se obter otimizações e por fim uma camada totalmente conectada.

> Vale salientar que, ocorreu erros durante o processo de treinamento da arquitetura promovida na pesquisa do parágrafo logo acima, não tive como rodar devido os limites concedidos pela GPU, porém, como base de direcionamento e entender o comportamento da CNN diante do objetivo que desejamos alcançar, um modelo de figura exemplo foi utilizado como molde e direcionamento na construção e treinamento da Rede Neural Convolucional. A figura apresenta uma arquiteura de CNN composta por uma camada convolucional, inicialmente com 16 mapas de características, seguida por uma função de ativação ReLU, normalização e logo após uma camada de pooling. Em diante, segue-se pela segunda camada, que comporta 64 features maps, função de ativação, normalização e pooling.


## Os objetivos:

* Análise comparativa:
  * A análise comparativa tem como finalidade entender o comportamento classificativo da Rede Neural Convolucional (CNN) em relação aos conjuntos de dados multi e binários.

## Resultados e discussão: 

## Referências:
 * [Multi-Classification of Brain Tumor Images Using Deep Neural Network](https://ieeexplore.ieee.org/document/8723045)
 * [Brain Tumor Detection and Classifiaction Using CNN Algorithm and Deep Learning Techniques](https://ieeexplore.ieee.org/document/9436599)
