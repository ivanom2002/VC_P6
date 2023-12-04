# VC_P6

# VC_P5

## Introducción 

El objetivo de esta práctica es tomando como punto de partida las utilidades de deepface, proporcionar alguna reacción en función de la información que estas nos proporcionen

Para ello hemos propuesto dos tareas:

1. Crear un filtro que detecte la cara de una persona y superponga un emoticono sobre ella, de tal forma que el emoticono represente el estado de ánimo de la persona en cada momento. 

![Resultado de la detección](https://github.com/ivanom2002/VC_P6/blob/main/Contento.jpg)

![Resultado de la detección](https://github.com/ivanom2002/VC_P6/blob/main/Enfadado.jpg)

![Resultado de la detección](https://github.com/ivanom2002/VC_P6/blob/main/Neutral.jpg)

2. Mostrar sobre el vídeo diferentes barras que se van a ir rellenando a medida que se reconoce la expresión del usuario. Es decir, hay 5 barras en la zona inferior de la ventana que representan Surprise, Fear, Happy, Angry y Sad. Todas tienen de valor inicial 0, y a medida que se van leyendo los frames de la webcam si se reconoce Happy se va rellenando la barra de Happy y mientras no se reconozca Happy, es decir, se reconozca cualquier otra emoción, esa barra irá disminuyando hasta que llegue a 0.
