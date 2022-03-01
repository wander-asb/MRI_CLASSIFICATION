![MRI](http://mmmoficial.org/mo_includes/img/publicacion/milagro-de-dios-cinco-tumores-cerebrales-desaparecen-luego-de-orar-a-dios_mmmoficial_2020-03-12-16-33-31_8765.jpg)

# Classificação de Tumores Cerebrais em Imagens de Ressonâncias Magnéticas por Redes Neurais Convolucionais

## Introdução

De acordo com a incidência de câncer no Brasil, disponibilizado pelo Instituto Nacional de Câncer José Alencar Gomes da Silva (2019), onze mil e cem novos casos de tumores no cérebro foram contabilizados no ano de 2020. Os tumores vinculados ao cérebro são uma das doenças relacionadas aos tipos de câncer no Sistema Nervoso Central (SNC), sua origem ou causa pode ocorrer de forma indeterminada, como também pode ser dividido em duas características conforme sua classificação ou epidemiologia. 

As Redes Neurais constituem-se pelo desenvolvimento do processo humano de aprendizado, em que determinados parâmetros encontram-se a possibilidade de obter as interações e pensamentos que um cérebro humano pode realizar, intensificou-se então, a busca pelo ganho de modelos computacionais capazes de exercer papéis cognitivos humanos. Na realização de análises clínicas, por exemplo, as Redes Neurais Artificiais (RNA) desempenharam importante papel no diagnóstico feito pelo responsável.

## Métodos e desenvolvimentos

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
