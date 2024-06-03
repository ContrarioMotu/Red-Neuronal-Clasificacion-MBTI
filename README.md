# Red Neuronal de Clasificación de Personalidad Basada en el MBTI

## Objetivo
Este proyecto se enfoca en desarrollar un modelo de red neuronal capaz de identificar patrones en el estilo de escritura de las personas para determinar su personalidad según el MBTI (*Myers-Briggs Type Indicator*).

## Contexto
El *Myers-Briggs Type Indicator* es un instrumento de evaluación psicológica utilizado para determinar los tipos de personalidad de las personas. Se basa en la teoría de los tipos psicológicos de Carl Jung y clasifica a las personas en 16 tipos diferentes según sus preferencias en cuatro dimensiones: Extraversión (E) o Introversión (I), Sensación (S) o Intuición (N), Pensamiento (T) o Sentimiento (F) y Juicio (J) o Percepción (P).

## Funcionalidad
El conjunto de datos usado consiste en una colección de alrededor de 106000 textos pre-procesados de publicaciones en internet ([Reddit](https://www.reddit.com) y [Personality Cafe](https://www.personalitycafe.com)), junto con el tipo de personalidad del autor, cada texto contiene exactamente 500 palabras.

Como variables de entrada de la red se utilizan las 500 palabras de cada texto tokenizadas y como salida una lista con la probabilidad de pertenencia a cada una de las clases posibles.

## Fuentes

* MBTI Personality Types 500 Dataset. (2021, December 30). Kaggle. https://www.kaggle.com/datasets/zeyadkhalid/mbti-personality-types-500-dataset/data
* Why learn about personality type? (2023, July 20). 2003-2024, Myers & Briggs Foundation.
https://www.myersbriggs.org/my-mbti-personality-type/why-learn-type/
* Kim, Y. (2014, 25 agosto). Convolutional Neural Networks for Sentence Classification. arXiv.org. https://arxiv.org/abs/1408.5882
* Camacho, C. (s. f.). CNNs for Text Classification. https://cezannec.github.io/CNN_Text_Classification/