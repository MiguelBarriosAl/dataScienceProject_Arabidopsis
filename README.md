# PROYECTO DATA SCIENCE PARA ESTUDIO DE LOS GENES DE LA PLANTA ARABIDOPSIS THAILIANA


## CONTEXTO DE NEGOCIO
Arabidopsis Thailiana es una planta herbácea que presenta un genoma muy
pequeño distribuido 5 cromosomas, lo cual facilita mucho su
utilización en estudios genéticos ya que se conoce una gran cantidad de
ensayos en sus genes para averiguar el comportamiento en su expresión según
los estímulos externos a los que se someta.
El siguiente caso de uso tiene como objetivo averiguar el nivel de relación de los
genes de una planta Arabidopsis Thailiana a través de métodos Data Science, 
es decir, si conocemos el nivel de relación de los genes, se aporta una
gran información al mundo de la investigación vegetal para posibles
predicciones del comportamiento de la planta según a las condiciones que se le
someta.

## OBJETIVOS
El objetivo del “Challenge Data Science” es:
- En primer lugar, modelo capaz de predecir el nivel de expresión de un gen según los ensayos
- En segundo lugar, interpretar la magnitud de error asociado a la predicción.

## RESULTADOS ESPERADOS
Se espera que, si todos los genes son independientes, maximizaría el
procesamiento de la información del sistema y, por lo tanto, esperaríamos un
error de predicción muy alto. Al mismo tiempo, los genes se organizan en redes
para evitar redundancias (es decir, varios genes pueden participar en las mismas
funciones), por lo que este error puede no ser tan alto.
Para ello, los pasos a seguir son:
Seleccionar un conjunto de experimentos, y extraer a su vez un conjunto de
genes con el fin de obtener el nivel de expresión de los mismos. Se debe tener
en cuenta los genes que se encuentran superpuestos en el mismo nivel de
expresión. Para ello se realiza una separación manteniendo su valor de
expresión para no interferir en la predicción.
Por cada gen y experimento, se prepara el siguiente conjunto de datos:
Features o los datos de entradas del modelo es el nivel de expresión de todos
los genes, y en todos los experimentos.
Target o el valor a predecir, es el nivel de expresión del gen objetivo en todos
los experimentos.
El modelo debe de ser entrenado usando los valores "target", y posteriormente
la predicción del nivel de expresión en el experimento seleccionado.
Por último, el proceso se repite con el fin de conseguir un error promedio.

## ASIGNATURAS/MÓDULOS RELACIONADOS
- Fundamentos de Tratamiento de Datos para Data Science
- Modelos y Aprendizaje Estadístico usando R
- Aprendizaje Automático Aplicado

## MÉTODOS, MATERIALES Y TECNOLOGÍAS DE USO POTENCIAL
Los datos están disponibles a través del un enlace de AWS, en el que consiste
un archivo .RAR de 40 gb, por lo que se recomienda tener suficiente espacio
en el disco.
Los datos se deberán disponer de manera que se pueda implementar en los
algoritmos, dipsoniéndolo en matriz con ayuda de Numpy o de dataframe con
la ayuda de Pandas.
Para este proyecto se pretende trabajar en su mayoría bajo lenguaje Python,
con librerías de Machine Learning y TensorFlow.
Con la ayuda de las librerías se estudiará e implementará los algoritmos de
Machine Learning que presente mejores resultados a través de medidas de
calidad del algoritmo.
También se pretende hacer uso de redes neuronales con ScikitLearn(MLP).
Tras reunir los diferentes resultados de los algoritmos, se realizará
visualizaciones a través de gráficas con la ayuda de librerías como
MatplotLib.pyplot.
