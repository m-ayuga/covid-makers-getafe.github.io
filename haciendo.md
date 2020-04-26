## Qué estamos haciendo

El grupo de Madrid está, por ahora, centrado en la impresión de viseras y salvaorejas. Las viseras, complementadas con un un plástico transparente de tamaño A4 (de PVC o PET, por ejemplo de los usados en encuadernación) y con una goma de sujeción, permite tener un protector facial para usar en combinación con mascarillas y otros elementos. Entre el 23 y el 28 de marzo uno de estos dispositivos estuvo aprobado para su uso por profesionales sanitarios en la Comunidad de Madrid. Los salvaorejas sirven para sujetar las mascarillas de forma más agradable a nuestras orejas.

Conviene que antes de empezar a imprimir (especialmente si vas a fabricar viseras) sigas estas [instrucciones de calibración para tu impresora](#calibracion).

Los modelos que estamos imprimiendo son los que puedes ver en la **[carpeta de archivos de impresión](https://drive.google.com/drive/folders/1y5VXhVkt2rt9M6kXWbEymleaHbHLJWUH?usp=sharing)**, donde los podrás encontrar por orden de preferencia de fabricación (según la información de que dispone el grupo de coordinación). En general, las viseras son más lentas de fabricar que los salvaorejas, y requieren más precisión, así que elige lo que vayas a fabricar teniendo en cuenta también las características de tu impresora.

Todos los modelos de visera se completan con una pantalla de plástico transparente (normalmente una lámina tamaño A4). Puedes ver más [detalles sobre las características de estas pantallas](#pantallas).

En el pasado hemos imprimido estos modelos:

* [Modelo que estuvo aprobado por la Comunidad de Madrid para uso sanitario](#aprobado), recomendado para imprimir salvo que tengas problemas debido a las características de tu impresora.

* [Modelo diseñado por el 3D Fab Lab en el Hospital Gregorio Marañón](#gregorio), más simple de imprimir, puedes imprimirla si tienes problemas con el otro modelo.

Cuando tengas un lote de piezas 3D listo para que te lo recojan, sigue el [procedimiento de recogida](/proceso.md). No hace falta que dispongas de las pantallas de plástico, o de las gomas que complementan el modelo aprobado por la Comunidad de Madrid: estamos organizando [donaciones](/donaciones.md) de láminas y gomas que incorporaremos a lo que fabriques.

### <a name="aprobado">Modelo que estuvo aprobado por la Comunidad de Madrid</a>

Este modelo puede imprimirse en impresoras con cama de 20x20cm.

* Opción A ([STL](A-Principal_Visera_Madrid-Aprobada_1.0.stl)), con todo en una pieza, recomendado para imprimir si tu impresora tiene una cama de al menos 22x22 cm.

*  Opción B ([STL parte 1](B1_Visera_Madrid-Aprobada_1.0.stl)  [STL parte 2](B2_Visera_Madrid-Aprobada_1.0.stl)), en dos piezas que se imprimen por separado, recomendado para imprimir si tu impresora tiene una cama de 22x22 cm. o más.

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
* Sujeción a la placa: "Skirt" o "Brim" ("Brim" implica post procesado, pues hay que retirarlo de la pieza una vez impresa, pero facilita adherencia de las patillas).
﻿
Es recomendable estar atento a las primeras capas, para interrumpir la impresión si no se adhieren bien.

AVISO: NO SE DEBE ESCALAR EL MODELO, debe imprimirse con las dimensiones que tienen los ficheros STL.

Montaje: Puedes ver las [instrucciones detalladas de impresión](https://wikifactory.com/+covidmakersmadrid/visera-hospitales), donde verás alguna foto.


### <a name="gregorio">Modelo del Gregorio Marañón</a>

Este diseño es más simple, más rápido de imprimir y no requiere de gomas para completarlo (sí de pantalla de plástico transparente). Pero no está aceptado (por ahora) por la Comunidad de Madrid. Se está usando, de todas formas, en muchos lugares. Puede imprimirse en impresoras con cama más pequeña que el aprobado por la Comunidad de Madrid.

* Diseño V3 ([STL](SIMPLE_V3.stl)): estamos trabajando con la versión 3 de este documento.

Puedes consultar este [vídeo sobre cómo se fabrica y monta](https://www.youtube.com/watch?v=PltnknIDqJg).

### <a name="calibracion">Instrucciones de calibración para la impresora 3D</a>

Antes de imprimir, conviene realizar el siguiente test:

* [Flow Calibrator](https://www.thingiverse.com/thing:1662342) ([STL](https://cdn.thingiverse.com/assets/43/12/fc/91/0b/flow_calibrator.stl), [copia del STL](flow_calibrator.stl)), por si el anterior no te descarga] para hacer una prueba y calibrar adecuadamente, antes de imprimir. Se tarda unos 6 minutos en imprimir en una impresora Anet 8, por ejemplo. Una vez impreso, el cilindro ha de entrar en la anilla, y atravesarla, lo más justo posible pero sin que se atasque. Si no la atraviesa bien, modifica el parámetro "Horizontal Expansion" en Cura. A mi me ha funcionado bien con un valor de -0.15.


### <a name="pantallas">Características de las pantallas de plástico transparente</a>

Para las pantallas de plástico transparente, se recomienda que sean de PVC O PET (parece que el acetato no aguanta los métodos de desinfección). Se recomienda para este modelo que sean de 240 micras, las de 180 pueden caerse (pero se puede solucionar con cinta adhesiva, o utilizar el refuerzo diseñado al efecto ([fijación láminas.stl](https://cdn.thingiverse.com/assets/90/9a/52/09/6a/fijacion_laminas_finas_Visera_3.5.2.stl)) para la sujeción. 

