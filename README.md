# Chatbot Estefanini :space_invader:

## Problemas :anger:

TELMOBI es una de las principales empresas de telecomunicaciones en México que actualmente provee servicios de telefonía móvil e Internet y, en menor medida, telefonía fija. A partir de junio de este año, el Instituto Federal de Telecomunicaciones (IFT), aprobó la fusión de TELMOBI con Verne, empresa con liderazgo mundial en medios y contenidos. El objetivo de esta megafusión es ofrecer servicios de cuádruple play: telefonía fija y móvil, internet y televisión.

Tras esta fusión y la implementación de nuevos servicios aumentó la carga de trabajo de varias áreas, entre ellas el área de call center que atiende los casos de atención a clientes para resolver problemas y levantar números de reporte con relación a fallas de servicio, problemas de hardware, software, aplicaciones y otros.

Para resolver este exceso repentino en la carga de trabajo, TELMOBI ha decidido implementar la inteligencia cognitiva "Sophie" adoptando el nombre de “ARI” el cual es un asistente virtual (Chatbot) cuyo objetivo es reducir un porcentaje de llamadas que ingresan al call center ayudando al usuario a resolver los problemas más frecuentes.

Actualmente las empresas están buscando nuevas formas de innovación a través de interacciones contextuales, relevantes, personales y conversacionales. Es por ello que muchas de ellas están experimentando con los chatbots para mejorar la experiencia con sus clientes, su atención personalizada, y explorando nuevas e innovadoras formas para relacionarse con ellos.

De acuerdo con un estudio de la consultora tecnológica Gartner, se estima que más del 85% de los centros de atención al cliente serán operados por “bots” en el 2020 y que en el 2018 los asistentes digitales reconocerán a sus clientes por su voz y su cara a través de diferentes canales.

También hay que tener en cuenta el “Informe Estadístico Soy Usuario Abril - Junio 2018” del Instituto Federal de Telecomunicaciones (IFT) el cual nos dice que en esta temporalidad existieron un total de 2,892 quejas en todo México que trascendieron a instancias como la Procuraduría Federal del Consumidor (PROFECO) relacionadas con telefonía móvil, de ese número 48.51% fueron relacionadas a fallas en la señal.

Por lo que centraremos nuestra investigación en la solución en primera instancia de la telefonía móvil.

# Cómo solucionaremos el problema :sparkles:

Para solucionar este problema nosotras proponemos la implementación de un chatbot cognitivo y que el usuario no se dé cuenta que es atendido por un bot, esto lo haremos por medio del reconocimiento de palabras claves; también localizaremos los problemas más comunes que tienen los usuarios de telefonía móvil y analizar si estos problemas pueden ser solucionados por ellos mismo con un poco de ayuda, si es así entonces hacer que nuestro bot, llamada Sofía, les ayude con guías visuales, en este caso se propone el flujo de dar de alta el APN; uno de los puntos importantes de Sofía es que este chatbot no solo será el primer contacto con el puente, sino que también ayudará a homologar los procesos internos en toda el área de atención a clientes de Telmobi y así evitar los silos de información. Esto se logrará implementando un ticket de 5 dígitos que se le será proporcionado al usuario si su problema necesita seguimiento o que se canalice a otro departamento, este ticket incluirá el nombre del usuario, el número de celular con el problema, el problema que tiene y los pasos que siguió con Sofía.
![Blueprint](img/bp1.jpg)
# Cómo llegamos a esos insights :question:

Para hacer las cosas bien hay que fijarse en lo que hace bien la competencia y también en lo que hace mal. Para tener una visión general de los problemas en la atención a clientes decidimos hacer journey maps de los 3 servicios más importantes a nivel nacional; empathy map de estos servicios, entrevistas a usuarios para conocer los pain points y hacer dos user persona y enfocar nuestra investigación en solucionar a estas persona sus problemas.

## Journey Maps :chart_with_downwards_trend:

![Journey Map AT&T](img/jmatt.jpg)

![Journey Map Movistar](img/jmatt.jpg)

![Journey Map Telmex](img/jmt.jpg)

De los tres servicios nos dimos cuenta que solo Movistar tiene un bot. Tanto AT&T como Telcel no cuentan con bot y en el caso de AT&T la falta de uno es más que evidente ya que los usuarios tardan en hablar con un agente hasta más de media hora.

Tanto en Telcel como en AT&T los usuarios tienden a abandonar el chat pues no se les da solución a su problema y los agentes tardan mucho en contestar.

El mayor problema detectado en Movistar es que el bot no reconoce muchas palabras incrementando paulatinamente la frustración del usuario.

**Entrevistas** :hear_no_evil:

Para hacer nuestras user personas decidimos basarnos en entrevistas e información recabada en el IFT.

Los principales insights de estas entrevistas fueron los siguientes:

Los usuarios notan que la espera para contactar a un agente es larga y tediosa, muchas veces los agentes son mal educados y poco pacientes, en muchos casos su problema no se resuelve en la primera consulta.

El mayor problema que encontramos es que si el usuario era redirigido a otro departamento tenía que volver a dar todos sus datos y volver a contar todos sus problemas.

Regresando al trato con los agentes de atención a clientes, muchos de nuestros entrevistados nos comentaron que se notaba que no sabían que hacer con el problema en cuestión y que percibían que se inventaban excusas o solo los redirigían a otros departamentos.
![User Persona Rodrigo](img/upr.jpg)
![User Persona Georgina](img/upg.jpg)

**Soluciones con el chatbot** :exclamation:

Las soluciones a las que llegaremos al implementar a Sofía, el chatbot, son:

- Hacer que los usuarios solucionen los problemas más sencillos con ayuda del chatbot.

- Hacer que la espera entre que el usuario entra y el usuario se contacta con un asesor sea menos y rellenar ese tiempo con interacción con el bot.

- Hacerlos sentir acompañados en sus procesos.

- Darles un seguimiento por medio de la implementación de los tickets.

**Soluciones a largo plazo** :fire:

Pero el chatbot por si solo no resolverá los problemas que se pueden presentar en atención a clientes, por lo que nosotras proponemos profundizar en los procesos de esta área de Telmobil.

También proponemos la creación de una capacitación efectiva para que los agentes que estarán a cargo del chat adopten la misma forma que tiene Sofía al dirigirse a ellos para que el usuario no perciba el cambio entre nuestro bot y una persona, también para que den una verdadera atención a las personas que acudan a ellos y, así como Sofía, sean pacientes con la gente que no sabe de tecnicismos y necesitan que los lleven paso a paso en su proceso.