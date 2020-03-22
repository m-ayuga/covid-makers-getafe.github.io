# Grupo de Getafe de Coronavirus Makers

En este sition mantenemos información útil para la coordinación del grupo de Getafe de [Coronavirus Makers](https://www.coronavirusmakers.org).

## Grupos y canales en Telegram (grupo de Getafe)

* [Noticias](): Canal de noticias, con la principal información para estar al día.
* [FABRICACIÓN](https://t.me/joinchat/N3nb20yJIMnOrUPWXF8w3g): Aspectos específicos relacionados con la fabricación (qué estamos fabricando, parámetros de impresión, problemas al imrimir, etc.)
* [LOGISTICA](https://t.me/joinchat/N3nb20vhjKKdFRdU1ezZ0Q): Qué hacer para que lo que hemos fabricado llegue a quien lo pueda usar (puntos y protocolos de recogida, cómo preparar el material, etc.)
* [GENERAL](https://t.me/joinchat/N3nb2xyLiFs4H2UzlqZL5w): Otros temas relacionados con la coordinación del grupo

## Puntos de coordinación (Comunidad de Madrid)

* Sitio web [COVIDMadrid.com](https://covidmadrid.com/): Sitio específico para información de coordinación de lo que se está haciendo en la Comunidad de Madrid.

* Canal de Telegram [CV19_INFO_MADRID](https://t.me/cv19_fab_info): Canal moderado donde sólamente se reciben unos pocos mensajes al día con la información fundamental (aconsejo empezar por este canal si alguien se acaba de apuntar a este jaleo). Incluye un formulario para indicar los materiales de que se dispone (piezas 3D que se han podido imprimir, y otros materiales auxiliares útiles).

* Grupo de Telegram de fabricación [CV19_FAB_MADRID](https://t.me/joinchat/Ec-3Ih0C2Wzr7OBkqfiEUQ): Es el sitio donde hacer preguntas (y sobre todo hace falta gente que ayude a responderlas) sobre fabricación con impresora 3D.

* Grupo de Telegram de logística [CV19_FAB_MADRID LOGISTICA](https://t.me/joinchat/MI8qJ0vZuLWeJOJlJgMguQ): Coordinación sobre cómo enviar lo que se vaya produciendo, y cómo hacerlo llegar a quien mejor lo pueda usar.

Si estás en la Comunidad de Madrid, pero no en Getafe, busca tu grupo local en el canal Telegram de información, donde podrás ver listados.

## Puntos de coordinación (España)

* Sitio web [Coronavirus Makers](https://www.coronavirusmakers.org): Es donde se está coordinando la mayor parte de la actividad maker en relación con la situación sanitaria causada por la epidemia de coronavirus. En él puede encontrarse una lista extensa de grupos especializados en elementos concretos (respiradores, mascarillas, protectores faciales, etc.), y de coordinación de las distintas comunidades autonómicas, que en general son grupos de Telegram.

## Qué estamos haciendo

El grupo de Madrid está, al menos por ahora, centrado en la impresión de viseras que, complementadas con un un plástico transparente de tamaño A4 (de PVC, por ejemplo de los usados en encuadernación) y según modelo, con una goma de sujección, permite tener un protector facial para usar en combinación con mascarillas y otros elementos. Actualmente estos dispositivos no están certificados para su uso por profesionales sanitarios, pero son útiles para otros sectores que los pueden necesitar (protección civil, policía, distribución, pequeño comercio, etc.). Por lo que veo en los canales, también hay profesionales de la salud que los demandan por no tener nada mejor.

Antes de imprimir, conviene realizar el siguiente test:

* [Flow Calibator](https://www.thingiverse.com/thing:1662342) ([STL](https://cdn.thingiverse.com/assets/43/12/fc/91/0b/flow_calibrator.stl), [copia del STL](covid-data/flow_calibrator.stl)), por si el anterior no te descarga] para hacer una prueba y calibrar adecuadamente, antes de imprimir. Se tarda unos 6 min en imprimir en mi Anet8. Una vez impreso, el cilindro ha de entrar en la anilla, y atravesarla, lo más justo posible pero sin que se atasque. Si no la atraviesa bien, modifica el parámero "Horizontal Expansion" en Cura. A mi me ha funcionado bien con un valor de -0.15.

Los modelos a imprimir son los que están del canal ["3D printed Face Mask A4 sheet" de Thingiverse](https://www.thingiverse.com/thing:4228123). Después de ver la descripción en este enlace, puedes ver los ficheros en la pestaña de ficheros. Actualmente (21 de marzo), el que está recomendado para imprimir es:

* Visera3.6b_cerrada_mas_simple ([STL](https://www.thingiverse.com/download:7842326), [copia del STL](covid-data/Visera_3.6b_cerrada__mas_simple.stl)). Se recomienda imprimir con los siguientes parámetros (que se pueden ajustar en Cura), para un boquilla (nozzle) de 0.4 mm de diámetro: altura de capa (layer height), 0.28mm; relleno (infill), 50%, sin soporte (con "skirt"), 2 capas de base (bottom layers), 4 capas superiores (top layers). En mi Anet8 tarda unas cuatro horas (si alguien sabe cómo bajar este tiempo que me diga), y he tenido que imprimir con cama caliente porque si no, se me acaba despegando después de hacer unas pocas capas.

(Como Thingiverse está un poco colapsado y a veces tarda mucho en cargar o no carga, incluyo enlaces directos y enlace copia de los diseños STL (pero siempre que puedas, intenta descargarlos de Thigiverse, por si se hubieran actualizado):

Para las pantallas de plástico transparente, se recomienda que sean de PVC O PET (parece que el acetato no aguanta los métodos de desinfección). Se recomeinda para este modelo que sean de 240 micras, las de 180 pueden caerse (pero se puede solucionar con cinta adhesiva, o utilizar el refuerzo diseñado al efecto ([fijación láminas.stl](https://cdn.thingiverse.com/assets/90/9a/52/09/6a/fijacion_laminas_finas_Visera_3.5.2.stl)) para la sujeción. 

## Proceso completo (datos para el grupo de Getafe)

* Antes de Empezar: Lee este manual de impresión, elije el modelo a imprimir, calibra tu impresora. Si necesitas ayuda, pregunta en el grupo de fabricación.

* Imprime. Si necesitas ayuda, pregunta en el grupo de fabricación.

* Cuando tengas material impreso en 3D, rellena la hoja de cálculo de inventario [https://docs.google.com/spreadsheets/d/1K7m4dV5NfDMxKLav6jHCdzQTZqJiKSewGEd3d09-3ik/edit#gid=0](https://docs.google.com/spreadsheets/d/1K7m4dV5NfDMxKLav6jHCdzQTZqJiKSewGEd3d09-3ik/edit#gid=0). Si tienes problemas o dudas para hacerlo, pregunta en el grupo de logística.
* No olvides rellenar la hoja de Logística con la zona en la que vives 
[https://docs.google.com/spreadsheets/d/1TF07XATJxQqFkj-0rwIvqJ4JImOIJKJ8Mxx6wXUWriM/edit#gid=0](https://docs.google.com/spreadsheets/d/1TF07XATJxQqFkj-0rwIvqJ4JImOIJKJ8Mxx6wXUWriM/edit#gid=0)

  - Importantísimo: rellena la columna  "metro" con la parada más cercana a tu domicilio.
  - Rellena la columna SANO/CON SINTOMAS: Con los siguientes valores: "SANO" (si estás bien con respecto al COVID19, ni tienes razones para pensar que podrías tener la infección), o "CON SINTOMAS" (si tienes síntomas, o has sido diagnosticado positivamente, o alguien en tu domicilio tiene síntomas o ha sido diagnosticado).

* Desinfecta y empaqueta el material cuando vayas a llevarlo a un punto de recogida o hayas acordado que vengan a recogerlo a tu casa. Si tienes problemas o dudas, pregunta en el grupo de logística (sobre la desinfección, mira más abajo).

## Desinfección y Empaquetado de Material

**Atención: Este proceso deberá realizarse con guantes y mascarilla, para evitar que los materiales que producimos vayan infectados**

Una vez tengas piezas listas para entregar, tienen que ser desinfectadas. La bolsa donde las vayas a entregar también.

La solución desinfectante que vamos a usar va a ser la recomendada por la OMS: 30ml de lejía por cada litro de agua.

**¡Importante!:** La solución SOLO es efectiva durante 24 horas.

## Más informción útil

En Euskadi tienen un sitio web con instrucciones muy claras para imprimir, desinfectar y avisar para la recogida: [Impresión 3D Comunidad Maker de Euskadi contra el Coronavirus](https://covideuskadi.net/impresion-3d/). Muy interesantes las indicaciones para desinfectar antes de embolsar, recuerda hacer esto si vas a hacer distribución local de lo que hayas imprimido.


## <a name="license">Licencia y contribuciones</a>

Este documento se distribuye bajo la licencia
[Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/)
(CC BY-SA 4.0) y es una traducción del [original](https://github.com/jgbarah/Notes/foss-distance-learning.html)

Todo el contenido original de este documento se puede encontrar en un
[repositorio de GitHub](https://github.com/jgbarah/Notes/).

Si quieres ves cualquier error, quieres proponer cualquier mejora, o tienes un comentario, por favor
[abre un *issue* en este repositorio](https://github.com/jgbarah/Notes/issues/new),
o [envía una *pull request* al mismo](https://github.com/jgbarah/Notes/pulls).

