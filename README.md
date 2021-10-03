# DOCUMENTACIÓN Mini-Proyecto Agil

## COSAS GENERALES:
### ROLES:

<ins>Integrantes:</ins>
- Gaston
- Matias
- Iñaki

<ins>Roles:</ins>
Definimos los roles a base de preferencia.

Iñaki se ofrecio a ser el Product Owner.
Gaston quiso ser el Scrum Master.
Matias no tuvo preferencia.

<ins>Los Roles quedaron:</ins>
- Scrum Master: Gaston
- Product Owner: Iñaki
- Developer: Matias

### Primer Marco de Trabajo:
Para el trabajo vamos a seguir las guías de Scrum (https://scrumguides.org/scrum-guide.html
), aunque no en su absoluta pureza:
- Para cada iteración planeamos entregar documentos, no necesariamente ejecutables.
- Los Daily Scrums se harán en los días en que el grupo se junta a trabajar. Esto se debe a que no se trabajara todos los días de la semana en equipo ya que cada uno tiene sus tiempos y responsabilidades en estos tiempos de emergencia sanitaria. Exceptuando los primeros días de sprint porque se desarrollará el sprint planning.

Fuera de estas excepciones, planeamos trabajar con el formato clásico de Scrum, iniciando un Sprint de 2 semanas de duración con un Sprint Planning, seguidas de Daily Scrum y concluyendo con un Sprint Review y Retrospective.

En el Sprint Planning definimos los objetivos del sprint.

En el día a día, hacemos un Daily Scrum inicial y al final del mismo se hace un registro de las horas trabajadas por miembro del equipo.

Hacia el final del Sprint hacemos el Sprint Review y vemos como nos acercamos al Product Goal.

Antes de entregar la iteración, hacemos un sprint retrospective donde re-definimos estos puntos que estamos definiendo ahora.

### Herramientas:
Las primeras dos herramientas definidas fueron:
- Para división de tareas: Trello
- Para llevar cuenta del tiempo trabajado: Toggl Track
- Documentación: Markdown
- Versionado: GitHub y GitHub Desktop

En Toggl Track cada miembro del Scrum Team debe activar el contador sobre el proyecto llamado “Mini-Proyecto Ágil” cuando estemos trabajando. Este primer día de planificación no fue monitoreado (2 horas todos).

En Trello tenemos un Kanban board:

Donde iremos monitoreando cada iteración.

## Iteracion 1 

### Sprint planning

##### Valor del Sprint
Este primer sprint habilita a las demás iteraciones mediante la planificación del proyecto. En este primer sprint, buscaremos determinar el Product Backlog del producto mediante el listado de posibles funcionalidades logrado por la identificación de stakeholders y el estudio de competidores.

##### Que hay que hacer:

- Identificación de interesados
- Lista de funcionalidades por interesado
- Estudio de competidores
- Historias de usuario (BDD)
- Criterios de aceptación
- Product backlog

##### Cómo lo haremos:
###### 1er semana
| Tareas      | Duracion(hs) | Esfuerzo(hs) |
| ----------- | --- | ---|
| Identificación de interesados      | 2       | 2|
| Lista de funcionalidades por interesado    | 2        | 6 |
| Estudio de competidores.    | 2        | 4 |

###### 2da semana
| Tareas      | Duracion(hs) | Esfuerzo(hs) |
| ----------- | --- | ---|
| Historias de usuario (BDD)      | 3       | 9 |
| Product backlog   | 1        | 3 |
| Creación de taskboard de Product backlog  | 1        | 3 |

##### Sprint Goal
Una identificación clara del problema acompañado de un product backlog que define las funcionalidades más importantes del sistema de manera ordenada


#### Identificación de Stakeholders:

La naturaleza de la aplicación nos permite identificar los siguientes stakeholders:

- Adolescentes y Adultos Jóvenes entre 13 - 35 años

Son la gente activa de la población más propensa a las actividades sociales. Su interés se encuentra en balancear entre poder realizar actividades sociales y asegurar la seguridad de él mismo y sus allegados. Son gente que están acostumbrados a manejar la tecnología y las aplicaciones móviles. Alta cantidad de gente.

- Adultos entre 35 - 60 años

Son gente activa que es un poco menos propensa a las actividades sociales fuera de las familiares. Son la población que hay más probabilidades de que estén instauradas con una familia en el Uruguay. Su interés se encuentra en asegurarse que su núcleo familiar esté protegido e informado de la situación de la pandemia. El manejo de la tecnología sigue siendo bueno, pero varía fuertemente por cuartil del grupo. Alta cantidad de gente.

- Adultos mayores de 60 años

Son gente no muy activa, pero que son población de riesgo. Su interés se encuentra en estar informados sobre la situación sanitaria y minimizar lo más posible el riesgo de contagio (ya que son población de riesgo). Quieren poder ver a sus familias con la conciencia limpia de que tanto ellos como su núcleo familiar están a salvo de la enfermedad. Suelen tener un mal manejo de la tecnología y no estar muy acostumbrados a las aplicaciones móviles. Como Uruguay es un país que se reconoce por tener una población mayor, hay una alta cantidad de este stakeholder en comparación con otros países.

Los tres grupos de stakeholders anteriores presentan una gran parte de la población como muestra la siguiente información:
![Informacion del censo 2011.](imagenes/Informacion-Censo-2011.png "Censo Uruguayo 2011")

(Información del censo Uruguayo del 2011, source: [Instituto Nacional de Estadística](https://www.ine.gub.uy/documents/10181/35289/analisispais.pdf))

Como muestra el censo, aproximadamente el 80% de la población uruguaya comprende a nuestros stakeholders más importantes. Es decir, idealmente cerca de al menos 2.700.000 personas utilizarían la aplicación extensivamente.

Estos tres stakeholders también son fuertes candidatos a ser la fuente de información sobre los casos de contagio, ya que la población es tan numerosa, se requiere de un esfuerzo comunitario para poder tener toda la información posible sobre casos de contagio. Además, los usuarios estarían interesados a compartir su información siempre y cuando se respete la privacidad de la misma. Es de su interés poder acceder a su carnet de vacunación, un documento validado por el gobierno que afirma que la persona está efectivamente vacunada.

- Gobierno Uruguayo

La aplicación es de un alto interés para el gobierno uruguayo ya que asiste con su interés principal de mantener sanitariamente al país con la acción de informar al pueblo uruguayo. Sería un agente importante en la recolección y aprobación de la información requerida para que funcione la aplicación.

- Sociedades médicas

Son todos los prestadores de salud. Estos intentan asegurar el bienestar de sus pacientes frente al peligro provocado por la contracción del virus COVID-19. Estas sociedades presentan mucha inquietud ante los incrementos de casos exponenciales y desean minimizar la curva de contagio para no sobresaturar sus camas de CTI y poder atender a todos sus afiliados. Al ser aquellos que se encuentran en el frente combatiendo la enfermedad, son los candidatos principales a otorgar la primera información sobre los casos activos de COVID-19.

- Laboratorios de test de COVID-19

Tanto públicos como privados tienen el objetivo de minimizar el tiempo de espera ante un resultado manteniendo una alta tasa de eficacia. Son responsables de informar la cantidad de casos positivos que se dieron por día.

#### IDENTIFICACIÓN DE FUNCIONALIDADES

De la identificación de Stakeholders identificamos las siguiente funcionalidades por stakeholder:

Un punto importante encontrado en la identificación de stakeholders fue que gran parte de los usuarios buscan información relevante a la situación sanitaria en busca de sentirse que ellos y sus familias están seguros. Por lo tanto identificamos que la aplicación debe:

- Otorgar información sobre el estado de los casos de la enfermedad:
    - Cantidad de casos activos en el Uruguay.
        - En el dia.
        - Totales.
    - Índices y estadísticos relevantes a estos (índice Harvard).
    - Cantidad de tests realizados.
        - En el dia.
        - Totales.
    - Cantidad de tests positivos en el dia.
    - Cantidad de dosis de vacunas otorgadas.
        - En el dia.
        - Totales.
    - Localización de los centros de vacunación conocidos.
        - Y la cantidad de dosis que poseen
- Esta información debe ser relevante geográficamente, como nuestro público objetivo es el pueblo uruguayo, solo interesa otorgar la información anterior en Uruguay. Pero además, segmentar esta información para todos los departamentos del país.
    - Debe de poder darnos un heatmap del país que nos indica la situación en cada departamento.
- Poder saber si hubo contacto con un positivo o si un usuario estuvo cerca de un positivo.
    - Para poder saber esto, es necesario poder trackear al usuario geográficamente.
    - Esto último puede ir en contra de otra funcionalidad identificada más adelante.
- Otorgar información sobre posibles síntomas de la enfermedad, que significan estos en términos de probabilidad de contagios y qué hacer si se identifica alguna de estas. Además, sería necesario dar la posibilidad de agendar un hisopado en la aplicación.
- Otorgar información sobre atención psicológica, ya que se ha estado hablando mucho de la pandemia psicológica que vino con la situación sanitaria.
    - Puntos de contacto con expertos en psicología.
    - Mecanismos para tratar la soledad en estos tiempos de pandemia.
- En relación con lo anterior, debería de también ser posible agendar la vacunación de uno mismo para cierto horario en cierta agencia.
- Otorgar la posibilidad de registrar varias personas por teléfono (multiusuario), ya que en un núcleo familiar lo más normal es que uno sea el conocedor tecnológico, y este lo haría para toda su familia.

Para poder otorgar las funcionalidades anteriores, y dado que el público objetivo es masivo (al menos 2.7 millones de personas), es necesario otorgar una infraestructura de recolección de información escalable:
- La aplicación debe de tener acceso a la base de datos de COVID del Uruguay. A medida que se agregue información, esta se debe reflejar en la aplicación.
- Los usuarios deben de poder alimentar información al sistema, como por ejemplo el hecho de que un usuario haya estado en contacto con un positivo.
- Debe ser accesible por una cantidad de dispositivos masivos. Los dispositivos móviles son los más masivos del mercado hoy en día, por lo cual debería de ser una aplicación móvil por lo menos.

Para los usuarios más jóvenes es de suma importancia poder mantener movimiento en sus vidas. Para ello, la información otorgada les sirve para poder manejarse de manera segura, pero además es de su interes que ellos puedan comprobar su sanidad a empresas (e.g: empresas hoteleras, empresas de fiestas) las cuales desean mantener la sanidad en sus establecimientos:
- La aplicación debe de poder emitir documentos oficiales gubernamentales que comprueben que alguien se encuentra vacunado.

La aplicación es de distribución masiva, esto significa que los usuarios mayores también van a tener mano en la aplicación, los cuales identificamos que no necesariamente tienen buen manejo de la tecnología, por lo que:
- Es necesario que la aplicación sea fácil e intuitiva de utilizar para toda la población.
- Por encima de esto, se debe otorgar una guía de uso o un tutorial que sea fácil de entender, concisa y efectiva.
- Fuera de la guía, debe de haber un punto de acceso a todas las guías y tutoriales, los cuales otorgan aún más información para los interesados.

Vivimos en una época en la cual la seguridad de la información es vital para los usuarios, por lo tanto:
- Es necesario mantener un nivel básico de seguridad informática, encriptados y demás.
- Se debe mantener la privacidad de la información del usuario.
- En caso de publicar información del usuario, se debe pedir el consenso al mismo antes de llevar a cabo la publicación.
El usuario debe de poder editar qué información desea compartir. E.g: Localización geográfica.

Como ya mencionamos, cerca de 3 millones de usuarios van a utilizar la aplicación, por lo cual:
- La infraestructura de base de datos de la misma debe de poder ser rápida y efectiva incluso para cantidades masivas de información.
- La eficiencia de los mecanismos de redes no debe de bajar a pesar de la cantidad de usuarios activos.

Para las sociedades médicas, es de especial interés que la aplicación acerque a los pacientes a acceder sus servicios por lo que:
- La aplicación debe de otorgar puntos de contacto con sociedades médicas del país.
    - Por ejemplo, un botón de emergencia que notifica a cierta sociedad médica del país.
- La aplicación debe de poder recomendar centros de salud cercanos al usuario en caso de que los usuarios no se encuentren en un buen estado por el COVID.
- La aplicación debe de poder otorgar información sobre la cantidad de camas disponibles de CTI.


#### Estudio de competidores:
<ul>
    <li>COVID-19MX</li>
</ul>

Comentarios:
- Brinda una pequeña serie de preguntas para saber si el usuario tiene posibilidades de tener covid
“Autodiagnóstico: En caso de sospecha de que tu o algún familiar sufrieron el contagio, responde al cuestionario y tendrás las recomendaciones para actuar y de ser necesario acudir para atención médica.”
- Acceso directo al teléfono de atención epidemiológica sanitaria.
- Permite la entrada a la app de forma anónima pero se restringen funciones. Estas funciones son las de registrar datos. Se restringen para no permitir el descontrol estadístico.
- Identifica los Centros de Atención más cercanos a tu ubicación, puedes consultar por Estados o mediante un mapa que te muestra el domicilio y ruta para llegar.
- Ofrece la información más importante para entender qué es, cómo se transmite y los grupos más vulnerables en torno al COVID. Además da consejos.
- Noticias: Acceso a la información oficial incluyendo conferencias de prensa y comunicados de la Secretaría de Salud.
- Desescalada: información sobre la fase en la que se encuentran los estados. Permite guardar favoritos y te avisan si hay cambio de fase.
- Permite el ingreso de más de una persona por teléfono.

Contras: 
- Es un bombardeo de información que puede no resultar muy clara al usuario.
- Los formularios requieren demasiados datos para completar

Se encuentra disponible en la [app store](https://play.google.com/store/apps/details?id=mx.gob.www) para android 6.0 y versiones posteriores, Requiere iOS 13.5 o posterior.


<ul>
    <li>CoronaMadrid</li>
</ul>

Comentarios
- Cuenta con una guía para uso primerizo.
- Para acceder a la app se debe ingresar usuario, si no no permite acceso a las demás funciones.
- Posee un cuestionario para la autoevaluación de los síntomas y unas recomendaciones personalizadas según la respuesta del usuario.
- En caso de estado grave las autoridades serán conocedoras de la situación y podrán comunicarse directamente con el afectado.
-Permite el ingreso de más de una persona por teléfono.

Contras
- No ofrece ninguna función diferente más que las mencionadas.


Se encuentra disponible en la [app store](https://play.google.com/store/apps/details?id=org.madrid.CoronaMadrid) para android 5.1 y versiones posteriores, Requiere  iOS 11.0 o posterior.


<ul>
    <li>CoronavirusUy</li>
</ul>

¿Qué permite la app?

- Visualización de información sobre el estado de la pandemia en Uruguay, incluye:
    - Datos numéricos sobre cantidad de casos.
    - Mapa con código de colores con índice Harvard por departamento.
    - Evolución de casos activos y fallecidos con respecto a la vacunación.
    - Pie chart con ocupación en cuidados intensivos (CTI).
    - Gráfica representativa de casos/dia.
    - Gráfico con tests realizados diarios.
    - Casos confirmados/casos recuperados durante los meses.
- reporte de síntomas
- consulta por telemedicina
- alertas de exposición
- Agendarse para las vacunaciones
- Acceso a tu certificado de vacunación
- Pedir declaración jurada de salud del viajero para entrar en Uruguay

Es importante aclarar que tanto el reporte de síntomas como la consulta por telemedicina se realizan a tu prestador de salud, la app solo funciona como un puente de fácil acceso entre ambos. Además las alertas de exposición pueden ser desactivadas en caso de ser deseado y son de ámbito anónimo. Esto significa que la app te informará si estuviste en contacto con alguien que dió positivo por covid, pero no te dirá con quién o en donde ocurrió.

El servidor de alertas de exposición es una adaptación de la implementación del [Exposure Notification Server](https://github.com/google/exposure-notifications-server) creado por google.

Además de la app ser bastante explicativa por sí misma con botones claros y descriptivos, existe un [pdf](https://www.gub.uy/ministerio-salud-publica/sites/ministerio-salud-publica/files/2020-06/disen%CC%83o%20gacetilla%20coronavirus%202%20copia_0.pdf) a modo de guía explicando el funcionamiento y los usos de ella.

#### Valoración de competidores:

| Funcionalidad | CoronavirusUy | COVID19-MX | CoronaMadrid|
|---------------|---------------|------------|-------------|
|Consulta por Telemedicina | 3 | 2 | 5 |
| Reporte de síntomas | 5 | 4 | 2 |
|Alertas de exposición | 4 | 0 | 1 |
| Agenda para vacunaciones | 5 | 3 | 0 |
| Claridad del diseño y navegabilidad | 5 | 3 | 4 |
| Guía de facil acceso | 5 | 0 | 4 |
|Información acerca del estado actual del pais | 3 | 4 | 2 |
| Funcionalidad multi-usuario | 5 | 5 | 5 |


### Anexo
#### Bitacora 

##### Día 2
###### Daily scrum 

- Iñaki Etchegaray
<ins>¿Qué hiciste ayer?</ins>
Prepare los aspectos generales del proyecto como las herramientas a utilizar y el sprint planning.
<ins>¿Qué vas a hacer hoy?</ins>
La identificación de stakeholders del proyecto. A su vez, también arreglar el sprint planning sacandole el definition of done que no es requisito.
¿Qué dificultades tienes?</ins>
Tener completamente en claro que stakeholders pueden haber del proyecto. Entender completamente mi rol como Product Owner.

- Gaston Landeira
<ins>¿Qué hiciste ayer?</ins>
Realice el estudio de competidores de dos aplicaciones. COVID-19MX y CoronaMadrid.
<ins>¿Qué vas a hacer hoy?</ins>
Realizaré el taskboard y continuaré con el estudio de competidores. Además para honrar mi posición de scrum master, documentare el daily scrum de hoy.
<ins>¿Qué dificultades tienes?</ins>
Distinguir la diferencia entre sprint backlog y product backlog.

- Matías González
<ins>¿Qué hiciste ayer?</ins>
Ayudar al Scrum master en el desarrollo del scrum planning.
<ins>¿Qué vas a hacer hoy?</ins>
Estudio de competidores, particularmente el caso de la app CoronavirusUy
<ins>¿Qué dificultades tienes?</ins>
Conseguir distintas fuentes al respecto de la app CoronavirusUy y sus funcionalidades

##### Día 3
###### Daily scrum 
- Iñaki Etchegaray
<ins>¿Qué hiciste ayer?</ins>
Identifique los stakeholders del proyecto. Y arreglos en la documentación.
<ins>¿Qué vas a hacer hoy?</ins>
La identificación de funcionalidades por interesado.
<ins>¿Qué dificultades tienes?</ins>
No logro poder llevar a cabo el rol de Product Owner de manera independiente. Es decir, mi rol lo estamos llevando a cabo entre muchos y no me siento el especialista en ello.

- Gaston Landeira
<ins>¿Qué hiciste ayer?</ins>
Realice la identificación de stakeholders
<ins>¿Qué vas a hacer hoy?</ins>
Realizaré la valoración de estudio de competidores y creare user cases. Finalizando con sprint review y retrospective.
<ins>¿Qué dificultades tienes?</ins>
Documentar las prácticas de scrum realizadas, se dejarán en un anexo más abajo.


- Matías González
<ins>¿Qué hiciste ayer?</ins>
Estudio de competidores, particularmente el caso de la app CoronavirusUy
<ins>¿Qué vas a hacer hoy?</ins>
En conjunto con el Scrum master realizar la valoración de competidores y comenzar los user cases. Luego realizar sprint review y retrospective
<ins>¿Qué dificultades tienes?</ins>
Encontrar información ya que las apps no poseen grandes archivos de documentación o informativo. Esto debido a la urgencia con la que fueron hechas.

