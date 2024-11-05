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

Pide explicaciones adaptadas a distintos niveles. Si necesitamos entender algo y algún concepto, una estrategia es pedirle a la IA que nos la explique como si fuéramos un estudiante o un niño de 11 años.

Ejemplo:

En vez de: ¿Qué es la inflación?

Reemplaza por: Explícame como si no supiera nada de economía: ¿qué es la inflación?