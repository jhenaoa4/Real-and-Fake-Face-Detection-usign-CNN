# Real and Fake Face Detection usign CNN

este proyecto está motivado por una tecnología insurgente causada por lo avanzada que está el área de inteligencia artificial, y es el Deepfake. El Deepfake es la manipulación de imagenes o videos por la cual se logra, o bien hacer mover una imagen inanimada, o colocar la cara de alguien en un video en el que no aparecía, donde, ha llegado a tal punto que puede ser indetectable para el ojo humano. No hay que forzar mucho a la intuición para imaginarse qué se podría hacer con esta tecnología, es por esto que es perentorio desarrollar en paralelo una tecnología capaz de contrarrestar los efectos nocivos que pudiera causar el Deepfake. Con este objetivo en mente, en el proyecto a realizar, se ha elegido la implementación de una herramienta, desarrollada con redes neuronales, para la identificación de imagenes reales o artificiales.

## Datos 🎭
Los datos usados para el desarrollo de esta investigacion fueron tomados del siguiente link de [Kaggle](https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection), el cual cuenta con un total de 3993 fotos, de los cuales se tienen 1961 fotos reales y 2032 fotos generadas por una inteligencia artificial.

## Instrucciones para replicar los resultados ⚗
Los datos deben ser descargados y simplemente se debe correr el [notebook CNN_real_fake_faces.ipynb](https://github.com/jhenaoa4/Real-and-Fake-Face-Derection-usign-CNN/blob/main/CNN_real_fake_faces.ipynb). El notebook genera automáticamente el archivo requirements.txt. De igual manera hay un archivo [requirements.txt](https://github.com/jhenaoa4/Real-and-Fake-Face-Derection-usign-CNN/blob/main/requirements.txt) en este repositorio.

## Métodología y Redes Neuronales Convolucionales 🧠
Las convolutional neural networks o redes neuronales convolucionales (CNN), solucionan este problema ya que asumen ciertas características espaciales de los inputs que
permiten simplificar las arquitecturas de la red reduciendo, en gran medida, el número de variables de entrada. Por tanto, son especialmente útiles en problemas de visión por computador, y en particular, en el reconocimiento de objetos.

Por tanto, se realizo un método bagging con múltiples modelos simples de la red neuronal utilizada y explicada a detalle en el paper [Trabajo_final_Estad_stica_multivariada_avanzada.pdf](https://github.com/jhenaoa4/Real-and-Fake-Face-Derection-usign-CNN/blob/main/Trabajo_final_Estad_stica_multivariada_avanzada.pdf).


## Resultados y detalles 🥇
La descripción de la Red Neuronal Convolucional, análisis y conclusiones de los resultados están en el paper [Trabajo_final_Estad_stica_multivariada_avanzada.pdf](https://github.com/jhenaoa4/Real-and-Fake-Face-Derection-usign-CNN/blob/main/Trabajo_final_Estad_stica_multivariada_avanzada.pdf).
