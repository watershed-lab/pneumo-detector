# pneumo-detector
Machine Learning project for pneumonie detection with X-Ray images

### SISTEMA DE INTELIGENCIA ARTIFICIAL PARA DETECCION DE PNEUMONÍA EN RADIOGRAFIAS CON UNA MÍNIMA POTENCIA DE PROCESADO

Clasificador de radiografías para detectar neumonía en pacientes, y clasificar su origen en vírica o bacteriana. 

Ejecutable en pc's domésticos. Recomendado i5 de 4 procesadores o superior y memoria RAM de 16Gb o superior.

En cuadernos Jupyter separados se exploran las alternativas más eficientes de preparación de datos, carga y persistencia, transformación y segmentación de imágenes, modelos clásicos de clasificación y modelos de aprendizaje profundo. 

Se realiza un análisis de rendimientos y se crea un ensamblado con los modelos óptimos, que se usa para realizar las predicciones con un elevado grado de confianza.


### Rutas para la ejecución

Los archivos con los modelos y pesos se encuentran dentro de la subcarpeta "modelos y pesos", que debe situarse como tal subcarpeta en la ruta del usuario, dentro de ./data/chest_xray. 
Los archivos comprimidos .zip de esta subcarpeta deben descomprimirse allí mismo. Por su tamaño no pudieron subirse directamente a github.

En esta ruta ./data/chest_xray también debe situarse el dataset, que no se incluye aquí pero puede descargarse desde [https://www.kaggle.com/paultimothymooney/chest_xray_pneumonia](https://www.kaggle.com/paultimothymooney/chest_xray_pneumonia)

Los cuadernos de Jupyter deben ponerse en la ruta del usuario.

