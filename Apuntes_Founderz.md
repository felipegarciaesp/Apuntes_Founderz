# CURSO: INTRODUCCION A LA IA Y PROMPT ENGINEERING - FOUNDERZ

## Origenes de la IA
Estamos en el inicio de la era de la IA.
Logica de Boole: decía que pensamiento lógico podía sistematizarse igual que la resolución de ecuaciones. A él le debemos el concepto de booleano, que corresponde a las variables que pueden verdaderas o falsas.
Test de Turing: sirve para determinar si estoy interactuando con una máquina o con un humano. Mide la capacidad que tiene la máquina para pasar como un humano.
El concepto de IA surge en 1956.

## Prompt Engineering, la IA como nuestro copiloto.
Prompt Engineering: forma como le hablamos y le preguntamos cosas a la IA. Puede cambiar la respuesta en función de como le preguntemos.
La idea es ocupar la IA en aquello que nos toma mucho tiempo y enfocarme en lo **que realmente puedo aportar con valor**.
Aprenderemos las funcionalidades de la IA entendiendolo como nuestro copiloto.

## Estructura de los prompts.
La calidad de la respuesta depende en gran medida de como lo preguntamos.

Prompting: el arte de guiar al modelo para que nos dé la mejor respuesta posible. Es importante ofrecer un buen contexto. A base de un buen prompting nos podemos asegurar de que el modelo nos va a responder con la mayor precisión posible.

Lo ideal sería crear prompts con estas tres partes:

    1) Objetivo. ¿Qué necesitas que haga: resumir, traducir, ordenar, generar un post, una carta, una poesía...?
    2) Contexto. ¿Por qué lo necesitas? ¿A quién impacta? ¿Qué intentas conseguir?
    3) Expectativas. ¿Cómo debería responder la IA para cumplir con tu petición? A nivel de formato, de tono, de origen de la información...

Lo ideal es que el objetivosea claro y directo. El prompt perfecto es dificil que salga a la primera. Es normal pedirle que añada o modifique cosas.

## Técnicas y prácticas 1

Ve al grano, sin protocolos. No hay que ser educado ni refinado. Ordenes directas y sencillas darán mejores resultados, al revés que con humanos.

Ejemplo:

En vez de: ¿Podrías explicarme, por favor, la estructura de una célula humana?
Reemplaza por: Explica la estructura de una célula humana.

Añadir palabras como por favor, me gustaría, podrías, es añadir información totalmente irrelevante para el modelo. Estas cosas no son importantes para el modelo. Tienes que ocupar frases simples y claras para que sean procesadas de forma más eficiente.

Usa delimitadores en tus prompts. Esto para que la IA pueda identificar cada parte de tu petición.

Ejemplo:

En vez de: Traduce esto al inglés. Hola, ¿cómo estás? Me gusta jugar en el parque. Mi color favorito es el azul. Esta traducción es para una clase de inglés para niños de primaria. Usa vocabulario snecillo y frases cortas.
Reemplaza por: 
                Traduce esto al inglés:
                //
                Hola, ¿cómo estás?
                Me gusta jugar en el parque.
                Mi color favorito es el azul.
                //
                Esta traducción es para una clase de inglés para niños de primaria. Usa vocabulario sencillo y frases cortas.
O por ejemplo esto otro:
                            Analiza las siguientes estadísticas y proporciona insights:
                            ---
                            Tasa de desempleo 2020: 8.9%
                            Tasa de desempleo 2021: 7.8%
                            Tasa de desempleo 2022: 6.3%
                            ---
                            Incluye posibles causas de la tendencia observada.

Cuando estructuramos el mensaje de esta forma, la IA puede identificar de manera mas eficiente cada segmento e identificar que es lo que tiene que hacer.

Usa ejemplos para guiar la respuesta. Ocupa ejemplos parecidos a lo que buscas. Los modelos de IA son muy buenos para captar y replicar patrones a aprtir de lo que le das como entrada. La IA no entiende de contexto como si lo haría un humano, pero sí sabe seguir patrones que se le dan.

Especifica el publico al que va dirigido. Para que estoy buscando esta respuesta? Esto permite a la IA ofrecer una salida mas efectiva. 

Divide las tareas complejas en pasos más sencillos. Puedes tranformar la petición en una conversación en donde le vayas pidiendo a la IA realizar una tarea pero que sea paso a paso, en vez de hacerlo en un único prompt.

Usa instrucciones en positivo. Ejemplo:

En vez de: Escribe este correo electrónico, no uses lenguaje coloquial, evita abreviaturas, no incluyas emojis, y asegúrate de no ser demasiado formal.

Reemplaza por: Escribe este correo electrónico formal utilizando un lenguaje profesional, incluyendo un saludo apropiado, manteniendo un tono respetuoso, y cerrando con una despedida cortés.

Los modelos son mas eficientes cuando le hablamos en positivos. Los modelos tienden a responder mejor cuando se les dice que deben hacer frente a cuando se les dice que no deben hacer. Las instrucciones afirmativas permiten que el modelo procese la solicitud de forma inmedita y clara sin tener que hacer interpretaciones adicionales.

Pide explicaciones adaptadas a distintos niveles. Si necesitamos entender algo o algún concepto, una estrategia es pedirle a la IA que nos la explique como si fuéramos un estudiante o un niño de 11 años.

Ejemplo:

En vez de: ¿Qué es la inflación?

Reemplaza por: Explícame como si no supiera nada de economía: ¿qué es la inflación?

**Menciona una propina ficticia o una penalización.** La IA responde bien tanto a refuerzos positivos como a consecuencias ficticias. Si le pides que lo haga mejor a cambio de una propina o lo penalizas por no cumplir con ciertos requisitos, el modelo va a interpretar estas señales como instrucciones para ofrecer una respuesta mas precisa y detallada. Estas palabras actúan como señales que indican que deben priorizar la calidad, creatividad o cumplimiento de requisitos solicitados.

Usa frases como "DEBES" para forzar a la IA a cumplir con un requisito.

Que hable como un humano. Pidele que responda de manera natural, o como un humano. Le estoy pidiendo que hable de manera más relajada. 

Usa palabras clave como 'piensa paso a paso'. Ejemplo:

    - Explica cómo hacer una tortilla española. Piensa paso a paso desde la compra de ingredientes hasta servirla.
    - Escribe un código en Python para iterar a través de 10 número y sumarlos todos. Piensa paso a paso.

Con decirle a la IA que actúe paso a paso activas su capacidad de razonamiento secuencial y organizará su respuesta de forma más lógica y estructurada. 

## Técnicas y prácticas 2

Añadir el comentario "sé imparcial". Añade a tu prompt la frase "asegúrate que tu respuesta es imparcial y no se basa en estereotipos". Esto para que la IA no se vaya a los primeros datos de suconocimiento que pueden ser datos sesgados. Con esto activamos mecanismos internos que sirven para eliminar sesgos.

Es bueno decirle a la IA que me pregunte lo que necesite. Con esto ayudo a la IA a que mejore el contexto y se ajuste a su respuesta.

Asinga un rol al modelo, para tener una respuesta desde una perspectiva específica. Con esto van a adaptar tanto el tono como el contenido.

Repetir palabras clave a la IA. Los modelos están hechos para identificar la relevancia de las palabras en función de la frecuencia de las palabras y el peso que tienen. Cuando repetimos palabras clave le indicamos al model oque esos elementos deben tener mayor protagonismo en su análisis y en su respuesta.

Empieza tu la respuesta. Asi estamos dirigiendo al modelo a que responda en un tono y adopte un estilo. Esta tecnica es muy efectiva por el concepto de Modelo Autorregresivo.

Añade toda la información necesaria en tu prompt, para que la IA me arroje la respuesta más completa posible.

Corregir sin cambiar el estilo. Algunas veces le pediremos a la IA que corriga algún texto (gramaticalmente hablando), por lo que es útil que no se pierda la esencia y estilo del texto original.

Define sus fuentes de información. Pide al prompt que use solo algunas fuentes o contenidos o que tipos de información debe emplear. Esto para que ajuste a lo que son tus indicaciones.

Pide a la IA que imite un estilo. 

Especifica un idioma y dialecto. Esto para que encaje a las personas a las que está dirigida la respuesta.

Reflexiones:

- Es importante verificar la información que proporciona la IA. A veces los modelos pueden alucinar (respuetas incorrectas o inventadas). Es fundamental corroborar.

- Recibir diferentes respuestas al hacer la misma pregunta, **no es un error.** Esto puede ser muy util para tener ideas variadas, no es necesariamente malo.

## Copilot, introducción y primeros pasos.

Podemos ingresar a copilot con los siguientes medios:

    Copilot en la web.
    Copilot en Edge, es una extensión.
    Copilot en el Móvil, para verlo desde el celular.

Iniciando desde una cuenta de empresa, nos aseguramos que la información que le entregue no saldrá del perímetro de seguridad de mi empresa.

Copilot permite controlar las fuentes de información que utiliza para proporcionar respuestas. Con cada pregunta a Copilot voy a poder verificar de donde viene lo que me está diciendo.

Es importante indicar si una respuesta de Copilot te gusta o no, pinchando el pulgar hacia arriba o hacia abajo.

## Copilot Web

Desde Edge podemos abrir Copilot como un plugin. Con éste puedo pedir un resumen de alguna página web en particular, puedo recortar una imagen de un video y pedirle a Copilot qué me diga qué es o puedo abrir un PDF desde el navegador y pedirle a Copilot que me responda algunas preguntas al respecto.

En la clase se ve que las respuestas de Copilot se pueden descargar en un archivo Word, pero yo no puedo hacer eso.

Puedes ocupar la funcionalidad de "Redactar" si lo que quieres es escribir algún texto para un blog o para LinkedIn. Puedes escoger el tono, el formato y la longitud. Puedes generar un borrador y pedirle que haga ajustes antes de publicarlo.

La función de re-escritura te permite re-hacer, por ejemplo, alguna reseña que hayas hecho a algún producto o servicio. Puedes cambiar el tono, formato, longitud, etc. Esto lo debes hacer desde Edge. Llegas a esta funcionalidad al seleccionar el texto, haces click derecho y presionas en "Reescribir con Copilot".

## Usando la IA desde el móvil

Todas las funcionalidades anteriores se pueden ocupar desde el celular. Tienes que descargar la App de Copilot en tu celular.

Puedes ocupar la opción de dictado por voz.

## Conclusiones

Copilot puede ser tu auténtico copiloto, sin perder de vista la seguridad y privacidad de tus datos. 

Es importante recordar que Copilot es un complemento que amplifica tus capacidades, te ayuda a ser más eficiente **pero siempre debes mantener tu creatividad y tu juicio como pilares fundamentales.** 

## Compositor de Software - Introducción y primeros pasos.

Vamos a programar una pequeña aplicación sin saber programar!

Un compositor de software es alguien que tiene una idea del software que quiere crear y va a saber explicar esta idea de forma efectiva a la IA.

Debe seguir un método para las instrucciones, ya que hay cosas que harán más fácil el proceso.

## Compositor de Software - Juego de detectives

Vamos a replicar el juego de "Where in the world is Carmen SanDiego?

El código se encuentra en el archivo juego-detectives.html

## Compositor de Software - Pomodoro Timer

Ojo que en ocasiones puede ocurrir que el código no se alcanza a generar, debes darte cuenta si la IA ha generado todo el código o aún le faltan cosas por generar. Para lograr que continue puedes pedírselo directamente en el prompt o hacer click en el botón "Continuar generando código" que aparecerá a continuación del código. 

El codigo se encuentra en el archivo pomodoro.html

## Compositor de Software - Creando a partir de una imagen

Se puede pedir a la IA que cree una aplicación sólo con darle una foto y un par de instrucciones al respecto.

## Compositor de Software - Guardando y leyendo datos - Diario Personal



































