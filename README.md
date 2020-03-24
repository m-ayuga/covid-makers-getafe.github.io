# Grupo de Getafe de Coronavirus Makers

En este sition mantenemos información útil para la coordinación del grupo de Getafe de [Coronavirus Makers](https://www.coronavirusmakers.org).

* [Qué estamos haciendo](#haciendo)
* [Proceso completo (datos para el grupo de Getafe)](#proceso)
* [Coordinación (Getafe, Madrid, general)](#coordinacion)
* [Más informción útil](#mas)
* [Licencia y contribuciones](#licencia)

## <a name="haciendo">Qué estamos haciendo</a>

El grupo de Madrid está, al menos por ahora, centrado en la impresión de viseras que, complementadas con un un plástico transparente de tamaño A4 (de PVC o PET, por ejemplo de los usados en encuadernación) y con una goma de sujección, permite tener un protector facial para usar en combinación con mascarillas y otros elementos. Desde el 23 de marzo estos dispositivos están aprobados para su uso por profesionales sanitarios en la Comunidad de Madrid.

Los modelos a imprimir son:

* Opción A ([STL](A-Principal_Visera_Madrid-Aprobada_1.0.stl)), con todo en una pieza, recomendado para imprimir si tu impresora tiene una cama de al menos 22x22 cm.

* Opción B ([STL parte 1](B1_Visera_Madrid-Aprobada_1.0.stl)  [STL parte 2](B2_Visera_Madrid-Aprobada_1.0.stl)), en dos piezas que se imprimen por separado, recomendado para imprimir si tu impresora tiene una cama de 22x22 cm. o más.

* Arandelas ([STL](Arandelas_Visera_Madrid-Aprobada_1.0.stl): en cualquiera de las dos opciones, hacen falta también estas arandelas. Al montar, estas arandelas irán encajadas en los palitos laterales.

Parámetros de impresión:

* Material: PLA 850 o PLA 870
* Altura de capa: 0.25 o 0.3mm
* Relleno: entre 15 y 20 %
* Soporte: solo para los modelo B (en cualquier caso se recomienda con un ángulo de inclinación ('support overhang angle') de 80 grados para reducir tiempos de impresión).
* Tamaño de boquilla de extrusor: Se han hecho pruebas con boquillas de 0.4 y 0.6 mm
* Perímetros:
  - Boquilla Extrusor 0.4mm: 2
  - Boquilla Extrusor 0.6mm: 1
* Sujección a la placa: "Skirt" o "Brim" ("Brim" implica post procesado, pues hay que retirarlo de la pieza una vez impresa, pero facilita adherencia de las patillas).
﻿
Es recomendable estar atento a las primeras capas, para interrumpir la impresión si no se adhieren bien.

AVISO: NO SE DEBE ESCALAR EL MODELO, debe imprimirse con las dimensiones que tienen los ficheros STL.


Antes de imprimir, conviene realizar el siguiente test:

* [Flow Calibator](https://www.thingiverse.com/thing:1662342) ([STL](https://cdn.thingiverse.com/assets/43/12/fc/91/0b/flow_calibrator.stl), [copia del STL](flow_calibrator.stl)), por si el anterior no te descarga] para hacer una prueba y calibrar adecuadamente, antes de imprimir. Se tarda unos 6 min en imprimir en mi Anet8. Una vez impreso, el cilindro ha de entrar en la anilla, y atravesarla, lo más justo posible pero sin que se atasque. Si no la atraviesa bien, modifica el parámero "Horizontal Expansion" en Cura. A mi me ha funcionado bien con un valor de -0.15.


Montaje: mientras se termina un manual de montaje más completo, puedes consultar estas [instrucciones de montaje](https://wikifactory.com/+covidmakersmadrid/visera-hospitales).


Para las pantallas de plástico transparente, se recomienda que sean de PVC O PET (parece que el acetato no aguanta los métodos de desinfección). Se recomeinda para este modelo que sean de 240 micras, las de 180 pueden caerse (pero se puede solucionar con cinta adhesiva, o utilizar el refuerzo diseñado al efecto ([fijación láminas.stl](https://cdn.thingiverse.com/assets/90/9a/52/09/6a/fijacion_laminas_finas_Visera_3.5.2.stl)) para la sujeción. 

## <a name="proceso">Proceso completo (datos para el grupo de Getafe)</a>

* Antes de empezar: Lee con detalle las [instrucciones sobre cómo imprimir lo que estamos haciendo](#haciendo), elije el modelo a imprimir, calibra tu impresora. Si necesitas ayuda, pregunta en el grupo de fabricación.

* Imprime. Si necesitas ayuda, pregunta en el grupo de fabricación.

* Cuando tengas material impreso en 3D, rellena la [hoja de cálculo de inventario](https://docs.google.com/spreadsheets/d/1K7m4dV5NfDMxKLav6jHCdzQTZqJiKSewGEd3d09-3ik/edit#gid=0). Si tienes problemas o dudas para hacerlo, pregunta en el grupo de logística.

* No  olvides rellenar la [hoja de Logística](https://docs.google.com/spreadsheets/d/1TF07XATJxQqFkj-0rwIvqJ4JImOIJKJ8Mxx6wXUWriM/edit#gid=0) con la zona en la que vives, para que el grupo de logística pueda organizar las rutas.

  - Importantísimo: rellena la columna  "metro" con la parada más cercana a tu domicilio.
  - Rellena la columna SANO/CON SINTOMAS: Con los siguientes valores: "SANO" (si estás bien con respecto al COVID19, ni tienes razones para pensar que podrías tener la infección), o "CON SINTOMAS" (si tienes síntomas, o has sido diagnosticado positivamente, o alguien en tu domicilio tiene síntomas o ha sido diagnosticado).

* Alguien del grupo de logística se pondrá en contacto contigo cuando pueda incluir tu domicilio en su ruta. Si ves que nadie se pone en contacto contigo, y ya tienes un cierto número de piezas impresas, puedes preguntar en el grupo de logística.

* Desinfecta y empaqueta el material (las piezas imprimidas, y los demás materiales que podamos tener, como hojas de plástico, gomas, etc.) según las [instrucciones de empaquetado y desinfección](#desinfeccion) y espera a que alguien del grupo de logística pase a buscarlo para llevarlo al punto de recogida. Si tienes problemas o dudas, pregunta en el grupo de logística (sobre la desinfección, mira más abajo).

* Imprime y rellena la [hoja de recogida](PROTOCOLO_ACTUACION_ENTREGA_V2.pdf), y tenla lista cuando llegue la persona que se encargará de llevarse tu bolsa. Sobre la primera línea incluye tu nombre, sobre la segunda el nombre de la persona que recogerá tu bolsa, y sobre la tercera, "DOMICILIO" si la recogida es en tu domicilio (o si no, el lugar donde tenga lugar la recogida). Si te fuera imposible imprimir el documento, pregunta a la persona de logística que pase a recoger si te puede llevar uno impreso, o prepara uno a mano.

* Las personas que se encargan de la logística recogerán la bolsa de tu domicilio y la hoja de recogida, y las llevarán al punto de entrega. Allí los recogerá Protección Civil de Getafe, que los entregará al hospital u otros orgaismos necesitados.

### <a name="desinfeccion">Desinfección y empaquetado de material</a>

**Atención: Este proceso deberá realizarse con guantes y mascarilla, para evitar que los materiales que producimos vayan infectados. Al terminar el proceso, es importante realizar una buena limpieza de manos.**

El proceso comienza preparando un pulverizador con líquido desinfectante. Puedes hacerlo de una de las siguientes formas:

* Con gel hidro-alcohólico

- Abrir el desinfectante de uso profesional como gel hidro-alcohólico
- Introducir el gel hidro-alcohólico en un pulverizador

* Con lejía:

- Realizar una mezcla de lejía con agua (1 parte de lejía y 9 partes de agua)
- Introducir la mezcla en un pulverizador

* Con alcohol de 96 grados

- Realizar una mezcla de alcohol de 96 con agua (7 partes de alcohol y 3 partes de agua)
- Introducir la mezcla en un pulverizador

**¡Importante!:** La solución que prepares solo es efectiva durante 24 horas.

Una vez tengas el pulverizador listo, puedes continuar con el procedimiento:

* Prepara una bolsa TRANSPARENTE.
* Introduce en ella la [hoja informativa de desinfección](DESINFECCION.pdf) (que habrás imprido previamente), escribiendo en ella, en la parte superior, tu usuario de Telegram (por trazabilidad).
* Ponte guante en la mano con la que vas a coger las viseras de una punta y rociar la visera por los dos lados, esperar a que no gotee y meterla en la bolsa transparente.
* Realiza un proceso similar con cualquier otro elemento que incluyas en la bolsa.
* Cuando esté todo en la bolsa, tienes que cerrarla lo más herméticamente que puedas. Para esto, puedes llenar un cubo con agua, sumerges la bolsa con los materiales dentro del cubo, sin que el agua llegue a entrar en la bolsa. Así sale el aire de la bolsa. Inmediatamente, cierra la bolsa con una pinza o un nudo, intentando que quede el mínimo de aire dentro. No olvides pulverizar después la bolsa con desinfectante.

Es importante que las bolsas sean transparentes, para que quien las transporta pueda ver qué hay en ellas.

Antes de su uso, el material debe volver a ser desinfectado (eso va indicado en la hoja informativa de desinfección).

Ten las bolsas listas y desinfectadas antes de que llegue la persona de logística que las lleve al punto de entrega, para evitar esperas innecesarias.

## <a name="coordinacion">Coordinación</a>

### Grupos y canales en Telegram (grupo de Getafe)

* [Noticias](): Canal de noticias, con la principal información para estar al día.
* [FABRICACIÓN](https://t.me/joinchat/N3nb20yJIMnOrUPWXF8w3g): Aspectos específicos relacionados con la fabricación (qué estamos fabricando, parámetros de impresión, problemas al imrimir, etc.)
* [LOGISTICA](https://t.me/joinchat/N3nb20vhjKKdFRdU1ezZ0Q): Qué hacer para que lo que hemos fabricado llegue a quien lo pueda usar (puntos y protocolos de recogida, cómo preparar el material, etc.)
* [GENERAL](https://t.me/joinchat/N3nb2xyLiFs4H2UzlqZL5w): Otros temas relacionados con la coordinación del grupo

### Puntos de coordinación (Comunidad de Madrid)

* Sitio web [COVIDMadrid.com](https://covidmadrid.com/): Sitio específico para información de coordinación de lo que se está haciendo en la Comunidad de Madrid.

* Canal de Telegram [CV19_INFO_MADRID](https://t.me/cv19_fab_info): Canal moderado donde sólamente se reciben unos pocos mensajes al día con la información fundamental (aconsejo empezar por este canal si alguien se acaba de apuntar a este jaleo). Incluye un formulario para indicar los materiales de que se dispone (piezas 3D que se han podido imprimir, y otros materiales auxiliares útiles).

* Grupo de Telegram de fabricación [CV19_FAB_MADRID](https://t.me/joinchat/Ec-3Ih0C2Wzr7OBkqfiEUQ): Es el sitio donde hacer preguntas (y sobre todo hace falta gente que ayude a responderlas) sobre fabricación con impresora 3D.

* Grupo de Telegram de logística [CV19_FAB_MADRID LOGISTICA](https://t.me/joinchat/MI8qJ0vZuLWeJOJlJgMguQ): Coordinación sobre cómo enviar lo que se vaya produciendo, y cómo hacerlo llegar a quien mejor lo pueda usar.

Si estás en la Comunidad de Madrid, pero no en Getafe, busca tu grupo local en el canal Telegram de información, donde podrás ver listados.

### Puntos de coordinación (España)

* Sitio web [Coronavirus Makers](https://www.coronavirusmakers.org): Es donde se está coordinando la mayor parte de la actividad maker en relación con la situación sanitaria causada por la epidemia de coronavirus. En él puede encontrarse una lista extensa de grupos especializados en elementos concretos (respiradores, mascarillas, protectores faciales, etc.), y de coordinación de las distintas comunidades autonómicas, que en general son grupos de Telegram.

## <a name="mas">Más informción útil</a>

En Euskadi tienen un sitio web con instrucciones muy claras para imprimir, desinfectar y avisar para la recogida: [Impresión 3D Comunidad Maker de Euskadi contra el Coronavirus](https://covideuskadi.net/impresion-3d/). Muy interesantes las indicaciones para desinfectar antes de embolsar, recuerda hacer esto si vas a hacer distribución local de lo que hayas imprimido.


## <a name="licencia">Licencia y contribuciones</a>

Los contenidos de este sitio web se distribuyen bajo la licencia
[Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/)
(CC BY-SA 4.0).

Todo el contenido de este sitio web se puede encontrar en un
[repositorio de GitHub](https://github.com/covid-makers-getafe/covid-makers-getafe.github.io).

Si quieres ves cualquier error, quieres proponer cualquier mejora, o tienes un comentario, por favor
[abre un *issue* en este repositorio](https://github.com/covid-makers-getafe/covid-makers-getafe.github.io/issues/new),
o [envía una *pull request* al mismo](https://github.com/covid-makers-getafe/covid-makers-getafe.github.io/pulls).

Si tienes cualquier problema en el proceso de proponer mejoras o hacer comentarios, coméntalo en el grupo general de Getafe (ver más arriba).
