**6. LAS BASES DE DATOS MULTIMEDIA.**

> *Lecturas recomendadas*: CHORAFAS, 1994; MCKNIGHT, DILLON y
> RICHARDSON, 1991; LÓPEZ YEPES, 1993; NICHOLLS y RIDLEY, 1996; KOEGEL,
> 1994; FIDEL *et alii*, 1994; BIANCHI *et alii*, 1996; APERS, BLANKEN y
> HOUTSMA, 1997; AZORÍN y LÓPEZ, 1994; DÍAZ, CATENAZZI y AEDO, 1996;
> FONG y SIU, 1996; MEGHANI, RABITTI y THANOS, 1991; OZKARAHAN, 1995.

**6.1. Multimedia y nuevos documentos.**

El término multimedia ofrece dos problemas. En primer lugar, el entorno,
mercado o ámbito que delimitan a multimedia todavía no ha sido bien
definido, y sus límites resultan difusos. en segundo lugar, multimedia
es un término que puede significar diferentes cosas, según quién lo
utilice. Originalmente, el término multimedia, a finales de la década de
1970, resultaba ser la integración de voz, texto, datos y gráficos, a
los que habría que añadir, actualmente, los gráficos interactivos, la
imagen en movimiento, la composición de documentos electrónicos y la
realidad virtual (KOEGEL, 1994).

La aparición de aplicaciones multimedia sólo ha sido posible gracias al
desarrollo de entornos gráficos de usuario para el aprovechamiento de
los computadores. La aparición de estos entornos gráficos (Macintosh,
Windows, X-Window, NextStep\...), basados en la presentación de
información en paneles o ventanas, posicionables en la pantalla, y en la
utilización de representaciones pictóricas (iconos) como indicadores de
elementos, así como de menús de opciones rápidas seleccionables por el
usuario, ha modificado en profundidad la manera de presentar y de
interactuar sobre los elementos informativos.

Uno de los problemas a resolver ha correspondido al almacenamiento y
acceso a la información de tipo gráfico. A lo largo de los últimos años
han proliferado gran cantidad de formatos de almacenamiento para
gráficos (PICT, TIFF, GIF, JPEG y otros), que han hecho necesario la
creación de filtros y programas de transferencia entre unos y otros.
Afortunadamente, se comienzan a establecer ciertos niveles de
compatibilidad, con vista a su utilización en bases de datos, a través
de metaficheros gráficos, que faciliten el acceso a todos los formatos,
independientemente de cual se trate y de las aplicaciones que los
manipulen.

Por último, el auge de multimedia debe gran parte de su éxito a la
popularización de los medios ópticos y magneto-ópticos de almacenamiento
masivo. La gran cantidad de espacio necesaria para el almacenamiento de
ficheros de imagen de calidad adecuada, y el acceso y manipulación de
éstos, dentro de un tiempo de respuesta prudencial, ha recibido una
respuesta adecuada con el desarrollo de las últimas generaciones de
CD-ROM y de lectores de alta velocidad. Tampoco puede pasarse por alto
que la gran cantidad de espacio de almacenamiento requerida por imágenes
y grandes volúmenes de información textual demanda, a pesar de los
medios ópticos de almacenamiento, la utilización de técnicas de
compresión y descompresión de ficheros de alta velocidad, que en su
mayor parte se realizan mediante software específico, de forma que se
combine un aceptable nivel de ocupación de recursos con una garantía de
calidad elevada, en lo que respecta al contenido.

Los párrafos anteriores cubren cuestiones eminentemente relacionadas con
los soportes la información. Sin embargo, un sistema multimedai debe
contemplarse desde dos niveles. En primer lugar un nivel intencional,
superior, en el que se recogen los constructos del conocimiento humano
que son creados o representados. En segundo lugar, un nivel extensional,
inferior, que engloba la organización de los datos. Los conceptos de
procesamiento de la información multimedia se distribuyen en ambos
niveles. Los nuevos desarrollos en las bases de datos multimedia
extienden las concepciones de los sistemas de información y de sus
usuarios más allá de la simple integración. Técnicas de inteligencia
artificial y sistemas expertos, mecanismos de representación y
recuperación de información gráfica, desarrollo de nuevas interfaces de
usuario, integración general de hipertexto e hipermedia, aplicaciones en
el campo de la edución y la formación, etc., (APERS, BLANKEN y HOUTSMA,
1997): Los STRID que se impondrán en el mercado de pocos años
incorporarán al tratamiento documental tradicional todas estas
herramientas.

**6.2. La integración de multimedia en las bases de datos.**

La aparición y desarrollo de la tecnología multimedia ha revolucionado
el concepto tradicional de base de datos, entendidas como elementos de
información textual y numérica, los cuales a su vez eran organizados de
acuerdo a un conjunto preestablecido de normas. Estos componentes se ven
enriquecidos por la posibilidad de completar los objetos a los que
representan mediante elementos gráficos y/o sonoros, en un entorno
integrado. El usuario obtiene entonces una representación compleja,
múltiple, de los objetos del mundo real, y de sus categorías de
información, que son representados en la base de datos. El ambiente de
un sistema de gestión de bases de datos multimedia integra texto, datos,
video, imagen (estática y dinámica) y sonido.

La integración de diferentes tipos de información en un único documento
pone de relieve la importancia de las tareas de representación del
contenido informativo, especialmente la indización de imágenes y
documentos sonoros. Los mecanismos de recuperación de información de
estos sistemas siguen utilizando, (excepto aquellos más punteros,
todavía en fase de investigación) términos como elemento de formulación
de requerimientos. La utilización de complejos mecanismos y normas de
indización de estos documentos merece cada vez en mayor volumen la
atención de los investigadores (WALKER y JONES, 1994; AZORÍN Y LÓPEZ,
1994), por lo menos hasta que se difundan mecanismos de recuperación
basados en patrones gráficos o técnicas similares.

En una base de datos multimedia se está trabajando con un marco que no
sólo incorpora los datos. Esos datos pueden tener variabilidad espacial
y temporal. Por lo tanto, un documento introducido en una base de datos
multimedia es una composición temporal, en la cual hay que introducir
los diferentes tipos de datos, tanto como las relaciones de
configuración y temporales existentes entre ellos. Los datos deben estar
sincronizados, controlando tanto su estado como su comportamiento.

*6.2.1. Los documentos multimedia.*

Los documentos multimedia se forman mediante la agregación de objetos de
diferentes tipos, objetos que pueden ser de gran tamaño, y llegan a
mostrar gran variedad en lo referido a estructura y representación. La
representación del documento multimedia busca comunicar de forma
efectiva no sólo el documento y su contenido, sino también la semántica,
los conceptos subyacentes y la relación entre ellos. Una comunicación de
información que siga estas normas tiene asegurado un adecuado nivel de
calidad. Por lo tanto, resulta ineludible fijar como uno de los enfoques
básicos el análisis de las características de los usuarios humanos del
sistema, para lo cual deben analizarse los patrones de comportamiento
del usuario en el acceso y comprensión de las estructuras informativas
(BIANCHI *et alii*, 1996):

Sirva el párrafo anterior como introducción para establecer una primera
conclusión: en el momento en el que se comienza a diseñar e implantar
una base de datos multimedia, el objeto de trabajo ya no resulta ser el
registro tradicional: el usuario está tratando con un documento
electrónico. Este ha sido creado procesando los diferentes tipos de
información (texto, gráficos, imágenes, datos, imágenes animadas,
sonidos) presentes en un almacén o repositorio de información. A esto
hay que añadir que tras largos años de implantación y desarrollo de las
tecnologías de bases de datos, las organizaciones y empresas disponen de
grandes volúmenes de información almacenadas en bases de datos,
generalmente en diferentes plataformas y aplicaciones, distribuidas en
diferentes localizaciones geográficas. Estas circunstancias exigen que
la implantación y explotación de bases de datos multimedia exija dos
elementos:

> 1\. La disponibilidad de bases de datos avanzadas, en un entorno de
> fácil utilización por parte del usuario.
>
> 2\. El establecimiento de redes de telecomunicaciones de alta
> velocidad.

*6.2.2. Los sistemas de gestión de bases de datos multimedia.*

De hecho, es la heterogeneidad de los tipos de información que son
necesarios en la actualidad unas las razones que ha favorecido, por
parte de la industria y los usuarios, el desarrollo de sistemas de
gestión de bases de datos multimedia, que han sido llamados también
"gestores de información hipermedial" (DÍAZ, CATENAZZI y AEDO, 1996:
174). Las aplicaciones SGBD tradicionales ofrecían limitaciones en
aspectos como el acceso complejo a datos, la transferencia de datos con
otros sistemas, o la inexistencia de adecuados interfaces de usuario.
Como respuesta, se tiende a diseñar e implementar nuevos SGBD que sean
capaces de utilizar \"inteligentemente\" los datos disponibles, e
integrar las viejas y las antiguas aplicaciones de forma no traumática.
Una base de información hipermedial tiene varios componentes:

1.  Base de presentación: parámetros a aplicar para mostrar la
    > información al usuario.

2.  Base de estructura: visión lógica del hiperdocumento, según un
    > modelo.

3.  Base de contenido: conjunto de documentos que se integran en el
    > hiperdocumento.

4.  Base de utilización: información sobre hábitos y comportamiento de
    > cada usuario.

En este mismo sentido, la concepción de una base de datos multimedia, en
su modelo conceptual (correspondiente al esquema conceptual definido por
ANSI/X3/SPARC), debe cumplir dos fases (CHORAFAS, 1994: 312):

> 1\. Cognición, centrado en cómo reconocer el mundo real, sus entidades
> y relaciones.
>
> 2\. Modelización, centrado en cómo representar los conocimientos
> obtenidos en la fase anterior, de manera que sean manipulables por la
> máquina.

A pesar de ser la integración de bases de datos heterogéneas una de las
razones del desarrollo de sistemas de gestión de bases de datos
multimedia, la industria todavía no ha establecido todavía estándares de
formato entre ellas, por lo que se repite la misma situación que en
momentos anteriores, entre ficheros de base de datos correspondientes a
aplicaciones como dBASE, Paradox, etc. Aunque las aplicaciones
tradicionales ya ofrecen \"puentes\" para compartir sus bases de datos,
por el momento esto no es posible en lo que respecta a las bases de
datos multimedia. Sin embargo, están comenzando a aparecer en el mercado
nuevas aplicaciones que, sin cumplir los requerimientos clásicos de un
SGBD, pueden generar documentos multimedia, tomando como base
información y datos contenidos en otros tipos de fichero. Los límites
entre la base de datos \"real\", y el documento multimedia resultante
\"virtual\", son difíciles de establecer en el estado actual de la
tecnología. Si puede decirse que es posible establecerse un algoritmo
que define el proceso de formateo y composición del documento, en dos
niveles:

> 1\. Jerarquía lógica del contenido del documento.
>
> 2\. Jerarquía física del documento formateado.

Esta es la premisa que define la norma ODA (Open Document Architecture)
de ISO. En lo que respecta a otros estándares, la norma ISO que define
el EDI (Electronic Document Interchange, y su versión EDIFACT), y el
protocolo ANSI X.12 están más orientados a la estructura del documento
que a sus posibles aspectos multimedia, lo que por el momento dificulta
su aplicación real.

**Fig.6.1. Los tres niveles de un sistema de bases de datos
multimedia.**

**6.3. La metodología en una base de datos multimedia.**

La creación e implantación de un sistema de bases de datos multimedia no
puede separarse de la adopción de una metodología adecuada para ello. De
la misma forma que en los sistemas \"tradicionales\" de bases de datos,
el enfoque a utilizar es el basado en un sistema integrado de
información:

> 1\. Definición de las tareas y objetivos a cumplir por la unidad
> informativa.
>
> 2\. Desarrollo de un metamodelo y de una metodología para el
> desarrollo de un sistema de información estratégica.
>
> 3\. Inventario de los elementos de tecnologías de la información
> disponibles.
>
> 4\. Inventario de las herramientas y de los repositorios de
> información existentes.
>
> 5\. Creación de un diccionario de metadatos y de su metodología.
>
> 6\. Consolidación de las conclusiones obtenidas, a través de
> metamodelos.

La utilización de este tipo de bases de datos, en lo que se incluyen
representaciones complejas de la realidad, hace necesario la utilización
de dos niveles de organización y de descripción. En primer lugar, una
nivel de conocimiento, de metadatos, conceptual y difuso. En segundo
lugar, un nivel de datos, concreto y analítico. El concepto clave de las
nuevas bases de datos, a partir de la presente década, será
\"significado\", superando el clásico \"dato\" o \"información\".

**6.4. Documentación y bases de datos multimedia.**

En lo que respecta al ámbito documental, las bases de datos multimedia
facilitarán el enriquecimiento de la representación de la información
(LÓPEZ YEPES, 1993). El documento no se reducirá a la utilización de
unas categorías descriptivas, complementadas con la aplicación de un
lenguaje documental. La inclusión de nuevos elementos descriptivos de
los documentos, como una imagen, gráficos, o complementos sonoros,
requerirán la experimentación, el desarrollo y la utilización de nuevos
mecanismos de recuperación de información, de los cuales ya se están
utilizando, a determinados niveles, algunos de ellos, como el
reconocimiento e identificación de imágenes según esbozos de líneas
maestras. La aplicación de representaciones semánticas de la
información, seguramente basada en el enfoque orientado a objetos, que
incluye tanto los datos como las acciones a ejecutar sobre los mismos o
sobre terceros, será uno de los paradigmas a emplear en este entorno.

Una cuestión clave, en los nuevos sistemas de bases de datos multimedia,
es el tratamiento de la imagen de los documentos, tanto en lo referido a
su almacenamiento, como en lo referido a su procesamiento. De hecho,
esta es una de las mayores áreas de expansión de la informática
documental en los próximos años, sirviendo como indicador el auge que
están alcanzado los llamados SGD (Sistemas de Gestión Documental). Los
documentos, en cuyo origen suelen encontrarse en soporte papel, son
introducidos en el sistema a través de algún mecanismo de captura,
generalmente un escáner. Se almacenan como gráficos (en cuyo caso se
pierde la posibilidad de efectuar búsqueda a texto completo), o como
texto, mediante la utilización de una aplicación de tipo OCR (Optical
Character Recognition), que permite integrarlo como un texto
perfectamente manipulable y accesible, desde una perspectiva documental.
Evidentemente, una aplicación que incorpore la segunda posibilidad, o
ambas, posee una importante ventaja sobre los meros almacenes de
imágenes de documentos.

Esta última cuestión pone de manifiesto que un adecuado sistema de
gestión de bases de datos multimedia debería ofrece herramientas para
buscar, recuperar, manipular, ordenar y organizar los textos y las
imágenes en un entorno de formato libre, de tal forma que pueda utilizar
documentos de muy diverso formato, tamaño y disposición (NICHOLLS y
RIDLEY, 1996; OZKARAHAN, 1995). El sistema de gestión de bases de datos
multimedia debería ofrecer lenguajes de descripción de documentos
avanzados, permitir el diseño de estructuras de datos muy flexibles, y
ofrecer mecanismos de búsqueda altamente efectivos. Como corolario, un
sistema de este tipo debería (CHORAFAS, 1994: 338-339):

> 1\. Encontrar rápidamente la información multimedia, buscando
> cualquier número de objetos referidos a un contenido de información,
> en un contexto de texto completo (y, a poder ser, en un contexto
> totalizador de la información)
>
> 2\. Conectar documentos según su contenido informativo, relacionando
> extractos de información relacionada de varios documentos, en uno
> nuevo.
>
> 3\. Facilitar el acceso instantáneo a los ficheros pertinentes,
> incluyendo los mecanismos necesarios de compresión y descompresión
> para la manipulación de aquellos.
>
> 4\. Conocer y manipular, por parte del usuario, la estructura misma de
> la información.
>
> 5\. Crear relaciones entre grupos de elementos informativos.

Los documentos pueden encontrarse en una única localización, en un
computador local, o bien ser el resultado de la integración de datos y
representaciones dispuestos en ordenadores dispersos espacialmente. Esta
última situación obliga a tratar el asunto de las bases de datos
distribuidas. Se está hablando de una única base de datos a nivel
lógico, pero de diferentes bases de datos a nivel físico. Esto supone
que las aplicaciones deben acceder a diferentes tipos de información, en
diferentes estructuras, a través de redes de ordenadores, en entornos
sumamente heterogéneos. La necesidad que se deriva del panorama esbozado
es la presencia de un diccionario de datos, repositorio general a través
del cual se disponen las definiciones estándares de los objetos
presentes en toda la extensión de la base de datos.

**6.5. Hipermedia.**

Un desarrollo de las bases de datos multimedia distribuidas, combinadas
con el hipertexto, es el servicio hipermedia (*vid. supra*). Hipermedia
es un enfoque flexible y muy eficiente, para la gestión de información,
que permite la navegación a través de la información distribuida. Su
principio básico es la posibilidad de navegar, de forma interactiva, en
una red formada por nodos conectados entre sí. El hipertexto sería un
subconjunto del hipermedia, principalmente referido a información
textual. La navegación se realiza saltando por la información,
cualquiera que sea su tipo, de forma no secuencial, a través de links o
punteros, establecidos según ciertos principios inteligentes, e
inteligibles. De esta forma, un sistema hipermedia mostraría todo tipo
de información almacenada en diferentes bases de datos y en diferentes
formatos, de manera completamente transparente para el usuario.

Una hiperbase debería cumplir los siguientes requisitos (DÍAZ, CATENAZZI
y AEDO, 1996: 185-191):

1.  Toda información es enlazable.

2.  El hiperdocumento es dinámicamente modificable.

3.  Es necesario guardar información sobre la presentación física de los
    > contenidos.

4.  Se debe dar soporte a todos los tipos de acceso a los sistemas
    > hipermediales.

5.  El hiperdocumento debe ser abierto y puede estar físicamente
    > distribuido.

6.  El sistema debe incluir mecanismos de recuperación ante fallos.

7.  Debe permitirse el acceso concurrente.

8.  Hay que preservar la seguridad de la información.

9.  Hay que posibilitar el trabajo en cooperación.

10. El hiperdocumento puede estructurarse siguiendo uan determinada
    > jerarquía.

11. Existen contenidos virtuales enlazados dinámicamente.
