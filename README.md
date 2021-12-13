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

A base de dados é composta pelo total de 3.264 imagens de ressonâncias magnéticas, no qual separamos em conjunto de dados de treino e teste, respectivamente, 80% e 20%. Dessa forma, ao visualizar o gráfico que apresenta o número de arquivos vinculados a cada categoria, podemos observar que a categoria de não tumores é visivelmente minoritária quando comparada às demais classes existentes. Logo, a metodologia abordada no trabalho foi random undersample, que será responsável por separar as imagens de cada diretório de classe de maneira randômica, a fim de igualar as classes majoritárias de acordo com a categoria de não tumor, ou seja, utilizou-se tranferência de arquivos para uma pasta externa, que denominamos como "lixeira", de modo que independentemente se usaríamos ou não futuramente o dataset, não iríamos perder os dados, apenas guardá-las em um lugar que não chamaríamos quando for necessário utilizar o conjunto de treino e teste. Segue abaixo o antes e depois da tranferência de arquivos:

<img src="https://raw.githubusercontent.com/wander-asb/MRI_CLASSIFICATION/main/teste_treino_dataset.png" width="1177" height="450" />
<img src="https://raw.githubusercontent.com/wander-asb/MRI_CLASSIFICATION/main/teste_treino_dataset_apos.png" width="1177" height="380" />

* Visualização da base de treino e teste
* Balanceamento (Random Undersample & Oversampling)
* Augmentation 
* Visualizção de dados 

## Arquitetura desenvolvida

<img src="https://github.com/wander-asb/MRI_CLASSIFICATION/blob/main/multi-classification%20architecture%20CNN.png?raw=true" width="949" height="250" />

## Métodos e resultados

Diante da modelagem da arquitetura apresentada na pesquisa, não houve empasses relacionados a GPU, o modelo tem como arquitetura as mesmas características vinculadas ao tópico acima, o número de mapas de características são representados por 64, lote de preparação divididos em 32 (batch_size=32) e shuffle = true, tamanho de kernel´s definidos por matrizes 3x3. Diante disso, o conjunto de dados estão separados ... , não houve ainda aplicações de filtros (augmentation), apenas o resize das imagens de tamanho 256x256 para 128x128.

Em relação aos dados que irão passar pelo modelo binário de classificação, um dos empasses foi a proporção de dados de tumores em contraste aos não tumores. Por motivos de análise, poderemos tratar essa proporção e diminuir o numero de dados tumorais a ponto de que esteja satisfatório para ser classificado, respectivamente, temos 500 dados não tumorais e mais de 1500 dados tumorais. Diante desse empasse, podemos ter um problema de aprendigem na rede neural.


## Os objetivos:

* Análise comparativa:
  * A análise comparativa tem como finalidade entender o comportamento classificativo da Rede Neural Convolucional (CNN) em relação aos conjuntos de dados multi e binários.

## Resultados e discussão: 

## Referências:
 * [Multi-Classification of Brain Tumor Images Using Deep Neural Network](https://ieeexplore.ieee.org/document/8723045)
