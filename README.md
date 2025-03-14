# -Clasificador-de-perros-y-gatos

 Para entender este proyecto primero tenemos que saber y relacionar conceptos clave. La inteligen
cia artificial crea sistemas que simulan capacidades humanas como aprender o tomar decisiones.
 Dentro de esta disciplina encontramos el aprendizaje autom´atico que ense˜ na a las m´aquinas
 aprender de los datos, si desglosamos a´ un m´as dentro de esta rama existe el aprendizaje super
visado y no supervisado, nosotros trabajaremos con el supervisado ya que este aprende de datos
 etiquetados.
 
 Si continuamos con la jerarqu´ ıa nos conducir´a a redes neuronales, que es un modelo matem´ati
co que imita al cerebro humano. Para este proyecto se usar´an las redes neuronales convolucionales
 (CNN), que es una categor´ ıa dentro de las redes neuronales especializada en procesar im´agenes.
 
 El objetivo de este proyecto es, mediante lo antes mencionado, hacer un modelo que pueda
 predecir si la imagen procesada es un perro o un gato.
 
Para el clasificador de gatos y perros, la arquitectura que suele seguir una CNN incluye las
 siguientes capas principales:
 
 Capas Convolucionales: Estas capas son responsables de detectar patrones en las im´age
nes, como bordes, texturas, y partes de objetos.

 Capas de Pooling: Se emplean para reducir la dimensionalidad de las caracter´ısticas
 extra´ ıdas, disminuyendo la cantidad de par´ametros y el costo computacional.
 
 Capas Densas (Fully Connected): Estas capas conectan todas las neuronas de la capa
 anterior y se encargan de usar las caracter´ısticas extra´ ıdas para realizar la clasificaci´on.
