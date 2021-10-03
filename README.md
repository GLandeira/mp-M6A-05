# DOCUMENTACIÓN Mini-Proyecto Agil

## COSAS GENERALES:
### ROLES:

<ins>Integrantes:</ins>
<ul>
    <li>Gaston </li>
    <li>Matias</li>
    <li>Iñaki</li>
</ul>


<ins>Roles:</ins>
Definimos los roles a base de preferencia.

Iñaki se ofrecio a ser el Product Owner.
Gaston no podia mas sin ser el CUM Master.
Matias no tuvo preferencia.

<ins>Los Roles quedaron:</ins>
<ul>
    <li>Scrum Master: Gaston </li>
    <li>Product Owner: Iñaki</li>
    <li>Developer: Matias</li>
</ul>


### Primer Marco de Trabajo:
Para el trabajo vamos a seguir las guías de Scrum (https://scrumguides.org/scrum-guide.html
), aunque no en su absoluta pureza:
<ul>
    <li>Para cada iteración planeamos entregar documentos, no necesariamente ejecutables.</li>
    <li>Los Daily Scrums se harán en los días en que el grupo se junta a trabajar. Esto se debe a que no se trabajara todos los días de la semana en equipo ya que cada uno tiene sus tiempos y responsabilidades en estos tiempos de emergencia sanitaria. Exceptuando los primeros días de sprint porque se desarrollará el sprint planning.</li>
</ul>


Fuera de estas excepciones, planeamos trabajar con el formato clásico de Scrum, iniciando un Sprint de 2 semanas de duración con un Sprint Planning, seguidas de Daily Scrum y concluyendo con un Sprint Review y Retrospective.

En el Sprint Planning definimos los objetivos del sprint.

En el día a día, hacemos un Daily Scrum inicial y al final del mismo se hace un registro de las horas trabajadas por miembro del equipo.

Hacia el final del Sprint hacemos el Sprint Review y vemos como nos acercamos al Product Goal.

Antes de entregar la iteración, hacemos un sprint retrospective donde re-definimos estos puntos que estamos definiendo ahora.

### Herramientas:
Las primeras dos herramientas definidas fueron:
<ul>
    <li>Para división de tareas: Trello</li>
    <li>Para llevar cuenta del tiempo trabajado: Toggl Track</li>
    <li>Documentación: Markdown</li>
    <li>Versionado: GitHub y GitHub Desktop.</li>
</ul>

En Toggl Track cada miembro del Scrum Team debe activar el contador sobre el proyecto llamado “Mini-Proyecto Ágil” cuando estemos trabajando. Este primer día de planificación no fue monitoreado (2 horas todos).

En Trello tenemos un Kanban board:

Donde iremos monitoreando cada iteración.

## Iteracion 1 

### Sprint planning

##### Valor del Sprint
Este primer sprint habilita a las demás iteraciones mediante la planificación del proyecto. En este primer sprint, buscaremos determinar el Product Backlog del producto mediante el listado de posibles funcionalidades logrado por la identificación de stakeholders y el estudio de competidores.

##### Que hay que hacer:
<ul>
    <li>Identificación de interesados</li>
    <li>Lista de funcionalidades por interesado </li>
    <li>Estudio de competidores.</li>
    <li>Historias de usuario (BDD)</li>
    <li>Criterios de aceptación</li>
    <li>Product backlog</li>
</ul>

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

<ul>
    <li>Adolescentes y Adultos Jóvenes entre 13 - 35 años.</li>
</ul>

Son la gente activa de la población más propensa a las actividades sociales. Su interés se encuentra en balancear entre poder realizar actividades sociales y asegurar la seguridad de él mismo y sus allegados. Son gente que están acostumbrados a manejar la tecnología y las aplicaciones móviles. Alta cantidad de gente.

<ul>
    <li>Adultos entre 35 - 60 años</li>
</ul>

Son gente activa que es un poco menos propensa a las actividades sociales fuera de las familiares. Son la población que hay más probabilidades de que estén instauradas con una familia en el Uruguay. Su interés se encuentra en asegurarse que su núcleo familiar esté protegido e informado de la situación de la pandemia. El manejo de la tecnología sigue siendo bueno, pero varía fuertemente por cuartil del grupo. Alta cantidad de gente.

<ul>
    <li>Adultos mayores de 60 años</li>
</ul>

Son gente no muy activa, pero que son población de riesgo. Su interés se encuentra en estar informados sobre la situación sanitaria y minimizar lo más posible el riesgo de contagio (ya que son población de riesgo). Quieren poder ver a sus familias con la conciencia limpia de que tanto ellos como su núcleo familiar están a salvo de la enfermedad. Suelen tener un mal manejo de la tecnología y no estar muy acostumbrados a las aplicaciones móviles. Como Uruguay es un país que se reconoce por tener una población mayor, hay una alta cantidad de este stakeholder en comparación con otros países.

Los tres grupos de stakeholders anteriores presentan una gran parte de la población como muestra la siguiente información:
![Informacion del censo 2011.](imagenes/Informacion-Censo-2011.png "Censo Uruguayo 2011")

(Información del censo Uruguayo del 2011, source: [Instituto Nacional de Estadística](https://www.ine.gub.uy/documents/10181/35289/analisispais.pdf))

Como muestra el censo, aproximadamente el 80% de la población uruguaya comprende a nuestros stakeholders más importantes. Es decir, idealmente cerca de al menos 2.700.000 personas utilizarían la aplicación extensivamente.

Estos tres stakeholders también son fuertes candidatos a ser la fuente de información sobre los casos de contagio, ya que la población es tan numerosa, se requiere de un esfuerzo comunitario para poder tener toda la información posible sobre casos de contagio. Además, los usuarios estarían interesados a compartir su información siempre y cuando se respete la privacidad de la misma. Es de su interés poder acceder a su carnet de vacunación, un documento validado por el gobierno que afirma que la persona está efectivamente vacunada.

<ul>
    <li>Gobierno Uruguayo</li>
</ul>

La aplicación es de un alto interés para el gobierno uruguayo ya que asiste con su interés principal de mantener sanitariamente al país con la acción de informar al pueblo uruguayo. Sería un agente importante en la recolección y aprobación de la información requerida para que funcione la aplicación.

<ul>
    <li>Sociedades médicas</li>
</ul>

Son todos los prestadores de salud. Estos intentan asegurar el bienestar de sus pacientes frente al peligro provocado por la contracción del virus COVID-19. Estas sociedades presentan mucha inquietud ante los incrementos de casos exponenciales y desean minimizar la curva de contagio para no sobresaturar sus camas de CTI y poder atender a todos sus afiliados. Al ser aquellos que se encuentran en el frente combatiendo la enfermedad, son los candidatos principales a otorgar la primera información sobre los casos activos de COVID-19.

<ul>
    <li>Laboratorios de test de COVID-19</li>
</ul>

Tanto públicos como privados tienen el objetivo de minimizar el tiempo de espera ante un resultado manteniendo una alta tasa de eficacia. Son responsables de informar la cantidad de casos positivos que se dieron por día.

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

### Anexo
#### Bitacora 

##### Día 2
###### Daily scrum 

-Iñaki Etchegaray
¿Qué hiciste ayer?
Prepare los aspectos generales del proyecto como las herramientas a utilizar y el sprint planning.
¿Qué vas a hacer hoy?
La identificación de stakeholders del proyecto. A su vez, también arreglar el sprint planning sacandole el definition of done que no es requisito.
¿Qué dificultades tienes?
Tener completamente en claro que stakeholders pueden haber del proyecto. Entender completamente mi rol como Product Owner.

-Gaston Landeira
¿Qué hiciste ayer?
Realice el estudio de competidores de dos aplicaciones. COVID-19MX y CoronaMadrid.
¿Qué vas a hacer hoy?
Realizaré el taskboard y continuaré con el estudio de competidores. Además para honrar mi posición de scrum master, documentare el daily scrum de hoy.
¿Qué dificultades tienes?
Distinguir la diferencia entre sprint backlog y product backlog.

-Matías González
¿Qué hiciste ayer?
Ayudar al Scrum master en el desarrollo del scrum planning.
¿Qué vas a hacer hoy?
Estudio de competidores, particularmente el caso de la app CoronavirusUy
¿Qué dificultades tienes?
Conseguir distintas fuentes al respecto de la app CoronavirusUy y sus funcionalidades

##### Día 3
###### Daily scrum 
-Iñaki Etchegaray
¿Qué hiciste ayer?
Identifique los stakeholders del proyecto. Y arreglos en la documentación.
¿Qué vas a hacer hoy?
La identificación de funcionalidades por interesado.
¿Qué dificultades tienes?
No logro poder llevar a cabo el rol de Product Owner de manera independiente. Es decir, mi rol lo estamos llevando a cabo entre muchos y no me siento el especialista en ello.

-Gaston Landeira
¿Qué hiciste ayer?
Realice la identificación de stakeholders
¿Qué vas a hacer hoy?
Realizaré la valoración de estudio de competidores y creare user cases. Finalizando con sprint review y retrospective.
¿Qué dificultades tienes?
Documentar las prácticas de scrum realizadas, se dejarán en un anexo más abajo.


-Matías González
¿Qué hiciste ayer?
Estudio de competidores, particularmente el caso de la app CoronavirusUy
¿Qué vas a hacer hoy?
En conjunto con el Scrum master realizar la valoración de competidores y comenzar los user cases. Luego realizar sprint review y retrospective
¿Qué dificultades tienes?
Encontrar información ya que las apps no poseen grandes archivos de documentación o informativo. Esto debido a la urgencia con la que fueron hechas.


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