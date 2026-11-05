# Unidad 5. Administración de recursos TI

[TOC]

Vamos con la unidad cinco, administración de recursos TI. TI es Tecnología de la Información, y en inglés se dice IT, Information Technology. Es una unidad larga, así que el repaso también lo es.

La unidad cuenta cómo una organización que ya existe decide y lleva adelante un cambio con tecnología. Primero aparece un problema. Después se define bien. Después se pregunta si vale la pena, si se puede, si conviene y si la gente lo va a poder llevar a la práctica. Y si todo da que sí, hay que comprar, y comprar en serio tiene su propio proceso.

Ese recorrido, en un dibujo:

```mermaid
flowchart LR
    A["Algo duele en la organización"] --> B["Se define el problema"]
    B --> C["Proyecto: viabilidad y riesgos"]
    C --> D["Factibilidad técnica, económica y operativa"]
    D --> E["Se compra: contratación y pliegos"]
    E --> F["Se ejecuta con una metodología"]
```

Si te llevás cuatro ideas, que sean estas.

La primera: un proyecto es temporal, único y con recursos escasos, y un proyecto de TI siempre es un proyecto del negocio.

La segunda: viabilidad y factibilidad no son lo mismo. La viabilidad pregunta si vale la pena. La factibilidad pregunta tres cosas: si se puede, si conviene y si la organización lo va a poder llevar a la práctica.

La tercera: los números no se miran solos. Punto de equilibrio, recuperación, valor presente, TIR (Tasa Interna de Retorno) y relación beneficio costo se cruzan con los riesgos.

Y la cuarta: comprar tiene reglas. Pliego, dos sobres, garantías, circulares y un orden de prelación que decide qué documento manda.

Y una advertencia sobre cómo está armado el repaso. Cada tema termina con dos cosas: "Lo importante", que es lo que tenés que poder decir de memoria, y "Ojo, trampa", que son las confusiones donde más se cae. Al final hay dieciocho preguntas tipo multiple choice, con la opción correcta y dónde está la trampa. Lo que el profesor marca en negrita en el apunte va también en negrita acá, las listas van con viñetas y las siglas se explican la primera vez que aparecen.

## Introducción: la transformación digital

El apunte abre con una introducción de cuatro párrafos. Los tres primeros dan el contexto y el cuarto, que el profesor marca en negrita, es la conclusión.

El contexto: estamos viviendo la mayor transformación social desde la era de la máquina industrial hacia la era de la información, del conocimiento, del *insight* (una comprensión profunda de algo, que va más allá del dato) y de lo digital. La digitalización implica cambios a gran escala en la forma de hacer negocios, y por eso exige una planificación y una orquestación multidimensional.

Después viene una metáfora. Vivimos en un "mar digital" y hay que cambiar con la "marea". Pero también hay que seguir principios bien definidos que guíen las decisiones, cómo nos relacionamos con los demás, con qué velocidad podemos nadar en agua desconocida, qué capacidades ayudan a sobrevivir y prosperar, y cómo concentrarse en el destino sin perderse. Y estos cambios están remodelando cómo pensamos, cómo nos vemos a nosotros mismos, los sistemas de los que somos parte y los entornos en los que vivimos.

Y la frase en negrita del apunte, textual:

**Las organizaciones tienen que transformar las funciones y los procesos subyacentes y crear un conjunto único de capacidades digitales para desarrollar la competencia empresarial central a fin de adaptarse a la velocidad digital.**

Para acordártela, tiene tres partes:

- Transformar las funciones y los procesos subyacentes.
- Crear un conjunto único de capacidades digitales.
- Todo eso para desarrollar la competencia empresarial central y adaptarse a la velocidad digital.

**Lo importante.** Digitalizar no es instalar una herramienta: obliga a transformar las funciones y los procesos de fondo y a crear capacidades digitales propias, para adaptarse a la velocidad digital. Esa es la frase que el profesor marca.

**Ojo, trampa.** Si una opción dice que alcanza con comprar tecnología, es la trampa: la frase habla de transformar procesos y de crear capacidades.

## Por qué cambiar y qué es un proyecto

Arrancamos por lo más simple. Ninguna organización está quieta: todos los días aparecen situaciones problemáticas, y cada una es una oportunidad de cambio. A veces es un ajuste chico en un proceso y a veces es una transformación radical. Y todo cambio tiene una motivación: a veces está clarísima, como querer crecer, y a veces es el síntoma de un problema que está más abajo.

Los motivos que da el apunte son seis:

- Lograr más eficiencia en un proceso.
- Reducir los tiempos de respuesta al cliente.
- Hacer un cambio tecnológico o de equipamiento.
- Cumplir una normativa externa.
- Cumplir nuevos objetivos que se puso la organización.
- Resolver disfunciones que traban el logro de esos objetivos.

Frente a cualquiera de esos síntomas, las TIC (Tecnologías de la Información y la Comunicación) son el habilitador estratégico: lo que la tecnología ofrece define qué tan bien se puede responder. Y el apunte lo dice en negrita: **Todo esto dará comienzo de un proceso de cambio que para nosotros será un proyecto.**

La definición es la del PMBOK (Project Management Body of Knowledge, o Cuerpo de Conocimiento de la Gestión de Proyectos), que es la guía del PMI (Project Management Institute, o Instituto de Gestión de Proyectos). Ojo con lo que es el PMBOK: un marco de referencia flexible, no una metodología rígida. Dice que un proyecto es un esfuerzo temporal que se emprende para crear un producto, servicio o resultado único.

Tres palabras clave, y si te las acordás tenés la definición:

- **Temporal**: tiene fecha de inicio y de fin.
- **Único**: el resultado no se hizo exactamente igual antes.
- **Recursos escasos**: personas, tecnología y plata.

Como los recursos son escasos, no se pueden hacer todos los proyectos aunque todos convengan. Es como el presupuesto de una casa: no podés renovar la cocina, el baño y el techo el mismo año. Por eso existe la evaluación de proyectos: elegir el más conveniente para el momento de la organización.

El apunte agrega una segunda forma de decirlo, que sirve para una pregunta a desarrollar: un proyecto es la combinación de todos los recursos necesarios, reunidos en una organización temporal, para transformar una idea en una realidad tangible y operante.

Un proyecto informático es un sistema de acciones, simultáneas o secuenciales, que integra personas, hardware (los equipos físicos), software (los programas) y comunicaciones para obtener resultados sobre un sistema de información.

Y la frase que la cátedra marca en negrita: **IMPORTANTE: IT Project es un concepto simplista, porque NO EXISTE un proyecto sin el Negocio que reciba el resultado del mismo.** "IT Project" quiere decir proyecto de tecnología de la información.

**Lo importante.** Proyecto es temporal, único y con recursos escasos, según el PMBOK. Y un proyecto de TI siempre es un proyecto del negocio.

**Ojo, trampa.** Una tarea que se repite todos los meses no es un proyecto, porque no es temporal ni única. El PMBOK es un marco flexible, no una metodología rígida. Y "los proyectos de TI son del área de sistemas" es justo lo que la cátedra dice que es simplista.

## Dónde nace un proyecto y transformación digital

Un proyecto puede iniciarse en cuatro lugares, y cada uno tiene su detalle.

Un proyecto puede iniciarse en cuatro lugares, y cada uno tiene su detalle:

- **Los gerentes de departamento**: hay que ver si hay otras áreas involucradas, para buscar una solución de conjunto y no un parche local.
- **Los ejecutivos de alto nivel**: suelen tener objetivos más amplios, que tocan varias áreas.
- **El área de sistemas**: detecta mejoras de tecnologías y metodologías, pero conviene que el pedido lo haga el gerente del área afectada.
- **Los grupos externos**: clientes, usuarios, proveedores o entes oficiales, como ARCA (Agencia de Recaudación y Control Aduanero, que es el organismo que antes se llamaba AFIP, Administración Federal de Ingresos Públicos; el apunte todavía la nombra AFIP) o el gobierno.

Un detalle que suelen preguntar: aunque sistemas tiene que estar atento, las personas que usan el sistema todos los días son la mejor fuente para saber qué mejorar. Son como los pasajeros del colectivo: el chofer maneja, pero quien sabe dónde falta una parada es quien viaja todos los días.

Ahora, transformación digital. Digitalizar no es meter herramientas. La transformación digital se centra en que el cambio sea sostenible y en construir una cultura digital. Y tiene dos pilares.

- El primero, la gestión del cambio: afecta a toda la empresa y necesita que participen empleados, directivos y ejecutivos, con concientización, capacitación y coaching (acompañamiento personalizado para desarrollar habilidades).
- El segundo, la colaboración: comunicación constante entre equipos, estructura interfuncional y software colaborativo para trabajar en tiempo real.

**Lo importante.** Un proyecto nace en gerentes, ejecutivos, sistemas o grupos externos. Los usuarios diarios son la mejor fuente de mejoras. Y la transformación digital es cultura, con dos pilares: gestión del cambio y colaboración.

**Ojo, trampa.** Que el área de sistemas detecte la mejora no significa que ella haga el pedido: conviene que lo haga el gerente del área afectada. Y digitalizar no es comprar herramientas.

## Definición del problema

Esto es más importante de lo que parece. Definir bien el problema exige distinguir causas, síntomas y necesidades. Si confundís síntoma con causa, resolvés lo que no era. Es como tomar un analgésico para el dolor de muela: el síntoma se va, la caries sigue. Y de esta definición sale el alcance del proyecto.

Las tareas son siete:

- Estudiar el sistema y el contexto actual.
- Analizar lo que se desea obtener.
- Clarificar qué áreas se verán afectadas.
- Definir el problema y sus componentes, priorizando en tres niveles.
- Identificar a los responsables.
- Definir con claridad qué se propone solucionar.
- Validar la definición con los interesados.

Los tres niveles de prioridad: 
 1 fundamental, que es indispensable; 
 2 deseable, que aporta mucho valor; y 
 3 opcional, que es secundario o queda para más adelante.

**Lo importante.** El problema se define distinguiendo causas, síntomas y necesidades, se prioriza en fundamental, deseable y opcional, y se valida con los interesados. De ahí sale el alcance.

**Ojo, trampa.** Resolver un síntoma no es resolver el problema. Y si el problema está mal definido, las tres factibilidades evalúan la solución equivocada.

## Factores que transforman la gestión de proyectos

El apunte agrupa los factores impulsores de la transformación de la gestión de proyectos en tres dimensiones, que van en negrita en el texto: **procesos y capacidades**, **factores externos** y **factores tecnológicos**. Si te piden factores impulsores, contestás con esta idea.

![IMAGEN 1](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-1.jpg)

La infografía del apunte está en inglés y tiene tres filas con cuatro factores cada una. De arriba abajo: Process & Capability Drivers (impulsores de procesos y capacidades), External Drivers (impulsores externos) y Technology Drivers (impulsores tecnológicos). Las tres filas se desarrollan a continuación.

Primero, **procesos y capacidades**: muestran cómo la gestión de proyectos se expandió a más áreas del negocio.

- Uso creciente de metodologías formales como PMBOK y PRINCE2 (PRojects IN Controlled Environments, versión 2: una metodología de gestión de proyectos de origen británico).
- Avance de las herramientas de software de gestión de proyectos, que facilitan planificar, seguir y controlar.
- Más formalización de procesos y estándares, que da más consistencia y control.
- Más inversión en proyectos estratégicos, que obliga a mejorar las capacidades de gestión.

Segundo, **factores externos** (el apunte también los llama impulsores externos): reflejan cómo el entorno global afecta la forma de gestionar los proyectos.

- La globalización, que obliga a operar en varios mercados y suma complejidad organizacional.
- Los equipos dispersos geográficamente, que exigen más coordinación y comunicación.
- La necesidad de responder rápido a las crisis y los eventos globales.
- Más regulaciones y normativas, que obligan a cumplir estándares y controles más estrictos.

Y tercero, **factores tecnológicos** (impulsores tecnológicos): destacan el papel de la tecnología en la gestión de proyectos.

- La ciberseguridad, que se vuelve prioridad por los riesgos digitales.
- El trabajo remoto, o sea, gestionar proyectos entre distintas geografías.
- El panorama de riesgos, que cambia todo el tiempo.
- La rápida evolución de tecnologías como la computación en la nube (cloud computing: usar servidores y servicios por internet en vez de tener los propios) y la automatización.

**Lo importante.** Tres dimensiones: procesos y capacidades, factores externos y factores tecnológicos.

**Ojo, trampa.** Cuidado con cambiar un factor de columna: el trabajo remoto y la ciberseguridad son tecnológicos; la globalización y las regulaciones son externos; las metodologías formales son de procesos.

## Gestión tradicional y gestión ágil

La gestión tradicional, también llamada cascada o *waterfall* (cascada, porque cada etapa cae sobre la siguiente), trabaja en **etapas secuenciales**: no se pasa a la siguiente sin terminar la anterior. Es como construir un edificio: no ponés el techo antes de los cimientos. La idea es bajar la incertidumbre planificando todo al principio, con requisitos claros desde el inicio. Sus rasgos, los que el apunte marca en negrita:

- **Etapas secuenciales**: iniciación, planificación, ejecución, monitoreo y cierre. Cada fase se completa antes de pasar a la siguiente.
- Mucho énfasis en la **documentación, los procesos formales y la gobernanza del proyecto**, con marcos como PMBOK y PRINCE2.
- **Definición clara de roles y responsabilidades**: el director del proyecto está en el centro y se usan cronogramas, diagramas de Gantt (barras sobre una línea de tiempo que muestran cuándo empieza y termina cada tarea), gestión del alcance y control de cambios.
- **Planificación detallada, control estructurado y ejecución secuencial**: sirve para proyectos con requisitos bien definidos, poca incertidumbre y entornos estables.

![IMAGEN 2](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-2.jpg)

El esquema del apunte, en inglés, muestra las cinco fases del ciclo en cascada, numeradas del 01 al 05: Project Initiation (inicio), Project Planning (planificación), Project Execution (ejecución), Project Monitoring and Control (monitoreo y control) y Project Closure (cierre).

La gestión ágil no es para todo. Sirve cuando los requisitos o la solución no se conocen del todo. Para decidir se usa la matriz de complejidad de Stacey. Un eje es qué tan claros están los requisitos, el qué. El otro es qué tan clara está la tecnología o la solución, el cómo.

Con eso salen cuatro tipos de proyecto:

- **Simple**: requisitos y solución conocidos, y va con enfoque tradicional.
- **Complicado**: el qué y el cómo se conocen parcialmente, y va en un punto intermedio.
- **Complejo**: alta incertidumbre, cambios frecuentes y mucho contacto con el cliente, y ahí va el enfoque ágil.
- **Caótico**: no hay ni requisitos ni solución, y no sirve ni uno ni otro: primero hay que estabilizar.

![IMAGEN 3](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-3.jpg)

La matriz del apunte está en inglés. El eje vertical es Requirements (requisitos), de Close to Agreement (cerca del acuerdo) abajo a Far from Agreement (lejos del acuerdo) arriba. El eje horizontal es Technology (tecnología), de Close to Certainty (cerca de la certeza) a la izquierda a Far from Certainty (lejos de la certeza) a la derecha. Las zonas, de la esquina de abajo a la izquierda hacia arriba a la derecha, son Simple, Complicated (complicado), Complex (complejo) y Anarchy (anarquía). Las flechas rojas marcan que Structured projects (proyectos estructurados) corresponden a lo simple, Agile projects (proyectos ágiles) a lo complejo y Chaotic projects (proyectos caóticos) a la anarquía.

Los marcos que nombra la unidad son cuatro:

- **Waterfall** (cascada): secuencial.
- **Agile** (ágil): iterativo e incremental. El esquema del apunte dice que deriva del *lean thinking* (pensamiento lean, que busca generar valor sin desperdicio).
- **Scrum**: también iterativo e incremental. Es un marco liviano que ayuda a equipos y organizaciones a generar valor con soluciones adaptables a problemas complejos.
- **Kanban**: gestión visual continua, con un tablero de tareas.

Y el objetivo de cualquier metodología es el mismo: resultados de calidad predecible con actividades ordenadas y eficientes.

![IMAGEN 4](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-4.jpg)

El apunte trae un esquema por cada marco, todos en inglés y sin traducción. Esta es la traducción de lo que muestran, y las aclaraciones entre paréntesis son mías, porque el apunte no las da:

- **Waterfall**: un proceso de diseño lineal y secuencial, que nace en el desarrollo de software. Sirve cuando se pueden definir los requisitos en detalle, no hay cambios o son mínimos, se necesita documentación robusta y se conocen las restricciones de diseño. Las etapas son Analyse (analizar), Design (diseñar), Develop (desarrollar), Test (probar), Deploy (poner en marcha) y Operate (operar).
- **Agile**: una metodología y enfoque que deriva del *lean thinking*. Los pasos son Define vision (definir la visión), Start in broad direction (empezar con una dirección general), Learn and adapt (aprender y adaptarse) y Evolve towards target (evolucionar hacia el objetivo). El ciclo es plan, design, develop, test, deploy, review y launch.
- **Scrum**: un marco liviano. Parte del Product Backlog (la lista priorizada de todo lo que hay que hacer en el producto), se planifica un Sprint (un ciclo corto de trabajo, de pocas semanas) en el Sprint Backlog (las tareas elegidas para ese ciclo), un Scrum Team (equipo Scrum) las hace con una reunión diaria breve, la Daily Scrum, y termina en el Sprint Review (revisión del Sprint, donde se muestra lo logrado). El equipo tiene tres roles: Product Owner (dueño del producto, que decide qué se hace primero), Scrum Master (quien facilita el proceso y remueve obstáculos) y Developers (desarrolladores).
- **Kanban**: un sistema de gestión que usa señales visuales para que el equipo se mantenga en carrera. Las tareas esperan en la Queue (cola), se toman con Pull (tirar: se toma una tarea cuando hay lugar) y pasan por las columnas Selected (seleccionadas), In Progress (en curso) y Done (hechas). Cada Increment (incremento) llega To Customer (al cliente).

¿Por qué hace falta una metodología? Porque el cambio es lo que permite que las organizaciones sobrevivan, pero no alcanza con elegir los proyectos correctos: hay que administrarlos bien para que no queden en ideas ni fracasen.

**Lo importante.** Tradicional para entornos estables con requisitos claros; ágil para proyectos complejos, con incertidumbre. La matriz de Stacey cruza qué tan claro está el qué y qué tan claro está el cómo.

**Ojo, trampa.** El caótico no es el candidato ideal para lo ágil: primero se estabiliza. Y "ágil es mejor que tradicional" es falso: depende del tipo de proyecto. Tampoco confundas Kanban, que es gestión visual continua, con Scrum, que es iterativo e incremental.

## Ciclo de vida del proyecto

Esto se pregunta mucho, así que vale aprenderse qué se hace en cada una de las cinco fases. En el apunte se dibujan como flechas encadenadas:

![IMAGEN 5](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-5.jpg)

El apunte repite este esquema una vez por fase, con la fase que explica resaltada en verde. Acá va una sola vez, con Inicio resaltado.

```mermaid
flowchart LR
    I["1. Inicio"] --> P["2. Planificación"]
    P --> E["3. Ejecución"]
    E --> C["5. Cierre"]
    M["4. Monitoreo y control"] -.-> P
    M -.-> E
```

Las listas de qué hacer en cada fase son las del apunte:

- **Inicio**:
  - Análisis de la situación inicial.
  - Análisis de los afectados.
  - Definición del producto o servicio.
  - Identificación de hitos (puntos de control importantes del proyecto, como la entrega de una parte).
  - Organización y estimación inicial de costos del proyecto.
  - Identificación y evaluación de riesgos.
  - Acuerdo con el cliente.
  - Constitución del proyecto.
- **Planificación**:
  - Plan detallado del proyecto.
  - Plan de comunicación.
  - Presupuesto del proyecto.
  - Reunión de arranque, que en inglés es el kick-off: la primera reunión formal con todos los involucrados.
  - Gestión del cambio.
- **Ejecución**:
  - Ejecución de actividades.
  - Dirigir y gestionar el proyecto.
  - Informe de avance del proyecto.
  - Revisión del comité de dirección.
- **Monitoreo y control**:
  - Monitoreo y control del trabajo.
  - Control del alcance.
  - Control del cronograma.
  - Control de costos y recursos.
  - Monitoreo de riesgos.
- **Cierre**:
  - After Action Review (revisión posterior a la acción: el equipo analiza qué se esperaba, qué pasó y por qué).
  - Resumen de aprendizaje.
  - Transferencia de conocimientos.
  - Cierre del proyecto.

Fijate que el monitoreo y control no es "después" de la ejecución: corre en paralelo y realimenta a la planificación. Por eso en el dibujo va con líneas punteadas. Es como el GPS del auto: no aparece al final del viaje, te va corrigiendo todo el camino.

![IMAGEN 6](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-6.jpg)

El gráfico del apunte muestra el nivel de interacción de procesos (eje vertical) a lo largo del tiempo, desde el inicio hasta el fin (eje horizontal). Hay una curva por cada grupo de procesos: inicio, planificación, ejecución, monitoreo y control, y cierre. Las curvas se superponen: no son compartimentos estancos. El inicio sube y baja temprano, la planificación llega a su pico antes que la ejecución, la ejecución es la más alta y está en el medio, el monitoreo y control es una curva baja y larga que acompaña casi todo el proyecto, y el cierre aparece al final.

**Lo importante.** Cinco fases: inicio, planificación, ejecución, monitoreo y control, y cierre. El monitoreo corre en paralelo. El kick-off es de la planificación y el After Action Review es del cierre.

**Ojo, trampa.** "El monitoreo y control es la fase que viene después de la ejecución" es falso. Y la estimación inicial de costos es del inicio; el presupuesto detallado, de la planificación.

## Stakeholders y director del proyecto

Un **stakeholder**, o interesado, es cualquier persona, grupo u organización que puede afectar, verse afectado o percibirse como afectado por una decisión, actividad o resultado del proyecto. Fijate que alcanza con que se perciba afectado. Esto incluye, pero no se limita a:

- Clientes y usuarios finales.
- Patrocinadores (en inglés, sponsors: quienes financian y respaldan el proyecto).
- Equipo del proyecto.
- Proveedores y contratistas.
- Reguladores y autoridades.
- Comunidades locales.
- Alta dirección.
- Otros proyectos o programas relacionados.

![IMAGEN 7](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-7.jpg)

El apunte los ordena en tres círculos concéntricos, del centro hacia afuera:

- Centro: el director del proyecto, el equipo de dirección del proyecto y el equipo de proyecto.
- Intermedio: los organismos de gobierno, las PMO (Project Management Office, oficina de gestión de proyectos) y los comités de dirección.
- Exterior: proveedores, clientes, usuarios finales y organismos reguladores.

El director del proyecto tiene que lograr que el resultado salga:

- Dentro del alcance acordado.
- Según las especificaciones.
- En los plazos.
- Con la calidad requerida.
- Dentro del presupuesto.
- Manejando bien la variable social, o sea, los conflictos.

Para eso necesita habilidades técnicas y también blandas:

- Comunicación.
- Negociación.
- Liderazgo.
- Toma de decisiones.
- Y, sobre todo, equilibrar la tensión entre calidad, costo y tiempo.

Sus tareas son tres verbos:

- Planificar.
- Organizar.
- Controlar.

Y tiene que documentar. La lista:

- Acta de iniciación.
- Especificación del alcance.
- Registro de incidencias.
- Minutas.
- Plan de trabajo.
- Cronograma.
- Línea base de documentos.
- Informes de avance.
- Incidentes clave.
- Aceptación del producto.
- Acta de cierre.

**Lo importante.** Stakeholder es quien puede afectar, verse afectado o sentirse afectado. El director planifica, organiza y controla, y equilibra calidad, costo y tiempo, con habilidades técnicas y blandas.

**Ojo, trampa.** No hace falta estar realmente afectado: alcanza con sentirse afectado. Y las habilidades del director no son solo técnicas.

## Matriz de stakeholders: poder e interés

Se cruzan dos ejes, poder e interés, y salen cuatro tipos. Cada uno pide una estrategia distinta. El apunte dice que hay que usar una estrategia de comunicación diferente para cada categoría.

![IMAGEN 8](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-8.jpg)

Es una matriz de dos por dos. El poder va en el eje vertical y el interés en el horizontal, los dos de bajo a alto. Arriba a la izquierda están los latentes (informar), arriba a la derecha los promotores (involucrar), abajo a la izquierda los apáticos (monitorizar) y abajo a la derecha los defensores (reportar). La imagen es del PMI de Valencia, España, y por eso los ejemplos del apunte hablan de ayuntamientos, que son los municipios en España.

- **Promotores**: poder alto e interés alto. La estrategia es **involucrarlos**: presentarles el proyecto y sus beneficios y lograr que colaboren. El ejemplo del apunte: los ayuntamientos.
- **Latentes**: poder alto e interés bajo. La estrategia es **informar de manera proactiva**, con reuniones periódicas, empatizando e integrando sus preocupaciones. El ejemplo: las ONG ambientales (organizaciones no gubernamentales).
- **Defensores**: poder bajo e interés alto. La estrategia es reportarles, o sea **comunicar** los avances, casi de forma unidireccional. El ejemplo: los comercios locales.
- **Apáticos**: **bajo poder e interés**. La estrategia es monitorizarlos, para ver si cambian de cuadrante. El ejemplo: los vecinos.

Un truco para no confundir latentes con defensores: los latentes tienen poder, por eso hay que escucharlos aunque no les interese. Los defensores tienen interés, por eso alcanza con contarles cómo va.

**Lo importante.** Promotores, involucrar. Latentes, informar. Defensores, reportar. Apáticos, monitorizar.

**Ojo, trampa.** Latentes y defensores se confunden todo el tiempo. Y los apáticos no se ignoran: se monitorizan, porque pueden cambiar de cuadrante.

## Viabilidad y riesgos

Primero, el estudio de viabilidad. Un proyecto nuevo siempre es un riesgo y se lleva recursos importantes. El apunte dice que es común que las empresas no respeten las mínimas normas de prudencia y que los proyectos queden a mitad de camino. El estudio de viabilidad sirve para averiguar si vale la pena convertir una idea en proyecto: si de verdad va a dar los beneficios que se esperan. Es una herramienta de decisión estratégica: aprobar o rechazar.

Lo que tiene que garantizar, como mínimo, son dos cosas:

- Que el esfuerzo humano y financiero que pide el proyecto quede justificado por los resultados.
- Que las condiciones técnicas de ejecución sean adecuadas.

Para eso hay que conocer de antemano:

- Las dificultades previsibles.
- Los medios necesarios.
- Las soluciones técnicas.
- Los fondos.
- Los beneficios.

Su profundidad depende de la envergadura, que se mide por:

- El riesgo.
- La inversión.
- El impacto interno.
- El impacto en el cliente.
- Los aspectos legales.

Y la regla es avanzar cuando hay un grado de confianza razonable de que el resultado va a ser satisfactorio.

Además de bajar el riesgo, el estudio sirve para:

- Ver alternativas.
- Descubrir oportunidades.
- Detectar señales de que conviene no seguir.
- Aumentar la probabilidad de éxito.
- Decidir con datos.
- Conseguir financiación.

Las actividades para hacerlo son siete:

- Identificar limitaciones, restricciones y supuestos.
- Detectar oportunidades.
- Analizar el modo actual de funcionamiento de la organización.
- Definir los requisitos que configuran el proyecto.
- Establecer el alcance: la solución al usuario y el ámbito de aplicación.
- Evaluar las distintas alternativas, estableciendo prioridades según su pragmatismo y viabilidad.
- Llegar a un acuerdo sobre la línea de acción.

Este proceso ayuda a ganar la confianza necesaria: confirma, o desmiente, que la iniciativa se puede hacer a tiempo y dentro del presupuesto.

![IMAGEN 9](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-9.jpg)

La infografía del apunte lista seis beneficios del análisis de viabilidad:

- Revela oportunidades que no se habían explorado antes.
- Mejora el enfoque de los miembros del equipo.
- Ofrece análisis sobre el modo en que opera la empresa.
- Aumenta la tasa de éxito de los proyectos.
- Mejora los procesos de toma de decisiones.
- Brinda claridad con respecto a las necesidades del proyecto.

Ahora, el riesgo. Es un evento o condición incierta que, si ocurre, tiene un efecto positivo o negativo sobre los objetivos del proyecto. Ojo con esto, que es de examen:

- Si los efectos son positivos, surgen oportunidades.
- Si los efectos son negativos, surgen amenazas.

Hace falta un equilibrio entre riesgos y oportunidades para tomar buenas decisiones. Y el apunte marca en negrita tres características del riesgo:

- **Concierne a lo que ocurra en el futuro.** ¿Cuáles son los riesgos que pueden hacer que fracase el proyecto?
- **El riesgo implica cambios.** ¿Cómo afectarán al éxito global y a los plazos los cambios en los requisitos del cliente, en las tecnologías de desarrollo, en los equipos y en todos los demás aspectos del proyecto?
- **El riesgo implica una elección.** ¿Qué métodos y herramientas debemos usar, cuánta gente debe estar involucrada, cuánta importancia hay que darle a la calidad?

Las categorías de riesgos de proyecto son cuatro:

- **Técnicos**: requerimientos, tecnologías, complejidad e interfaces, desempeño y confiabilidad, y calidad.
- **Externos**: subcontratistas y proveedores, normativa, mercado, cliente, y clima y entorno.
- **Organizacionales**: dependencias del proyecto, recursos, financiamiento y prioridades.
- **De administración del proyecto**: estimación, planificación, control y comunicación.

![IMAGEN 10](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-10.jpg)

Es el organigrama del apunte, titulado "Riesgos del proyecto (PM)", donde PM es Project Management, gestión de proyectos. Parte de "Riesgos del proyecto" y abre las cuatro ramas con las categorías de arriba.

La gestión del riesgo parte de la descripción, la probabilidad y el impacto de cada riesgo, y busca bajar una u otra. El ejemplo del apunte es la rotación de personal, y los pasos son:

- Determinar las causas.
- Mitigar antes de que empiece el proyecto.
- Asegurar la continuidad aunque haya rotación.
- Definir estándares de documentación de uso obligatorio.
- Hacer revisiones en equipo, para que más de una persona siga la marcha del proyecto.
- Asignar una persona de apoyo para cada tarea crítica.

Y la supervisión del riesgo tiene tres objetivos:

- Detectar si ocurrió un riesgo previsto.
- Asegurar que se estén aplicando los pasos de gestión.
- Recopilar información para futuros análisis.

**Lo importante.** La viabilidad decide si vale la pena convertir la idea en proyecto. El riesgo es un evento incierto con efecto positivo o negativo, y se gestiona por probabilidad e impacto.

**Ojo, trampa.** "Un riesgo siempre es negativo" es falso. Y la viabilidad no es la factibilidad: la viabilidad es la decisión estratégica de aprobar o rechazar la idea; la factibilidad, que viene después, analiza si se puede, si conviene y si se puede operar.

## Factibilidad: las tres preguntas

Acá está el corazón de la unidad. El estudio de factibilidad analiza la necesidad, la conveniencia y la oportunidad de poner en marcha un sistema, y busca una seguridad razonable de éxito. Se estudia en tres dimensiones, y la forma fácil de acordártelas es como tres preguntas.

- La **técnica** pregunta si se puede hacer. Mira la tecnología, la capacidad y las configuraciones de hardware y software.
- La **económica** pregunta si conviene hacerlo. Mira costos, beneficios y rentabilidad.
- La **operativa** pregunta si la organización lo va a poder llevar a la práctica. Mira personas, procesos, apoyo y adopción.

Y van en cadena:

- La técnica define un rango de soluciones posibles.
- La económica elige la más conveniente de ese rango.
- La operativa confirma que se pueda poner en práctica.

Pensá en comprar un auto: primero ves cuáles existen y te sirven, después cuál podés pagar, y al final si lo vas a poder estacionar en tu garage.

**Lo importante.** Técnica: ¿se puede? Económica: ¿conviene? Operativa: ¿se va a poder llevar a la práctica? Y se encadenan en ese orden.

**Ojo, trampa.** No confundas el orden ni lo que mira cada una. Y recordá que una solución técnicamente posible y económicamente conveniente puede fracasar igual si la operativa falla.

## Factibilidad técnica

Trata de demostrar que el proyecto se puede concretar. Las preguntas:

- ¿Existe la tecnología necesaria?
- ¿Alcanza la capacidad de almacenamiento?
- ¿Soporta el crecimiento de la demanda?
- ¿Hay garantías de exactitud, confiabilidad, acceso y seguridad de los datos?
- ¿Hay proveedores alternativos?

Después mira tres grupos de requerimientos.

**Los de la organización.** Se evalúan según la naturaleza y la complejidad de la organización:

- **Volumen de datos** a procesar y cómo fluctúa: por banda horaria, por día de la semana, por altura del mes.
- **Oportunidad**: la rapidez de respuesta que necesitan los usuarios, o sea, la frecuencia y los plazos para entregar la información.
- **Estimación de tiempo para el desarrollo de la aplicación**: la urgencia de satisfacer la necesidad.
- **Complejidad**: la cantidad de interrelaciones, interfaces y detalles específicos que debe manejar el sistema.
- **Requisitos de equipamiento**: por ejemplo, cantidad de dispositivos, tiempos y horarios de utilización.

**Los del funcionamiento de sistemas.**

- Tiempo de equipo para programar y testear aplicaciones nuevas, ampliar las existentes o mantenerlas.
- Fallas de equipo: el tiempo en que no se pueden usar por falla.
- Tareas especiales: tiempo para necesidades no estructuradas, de características únicas.
- Tiempos de reproceso: crecen cuanto más integrados están los procesos, porque un error se propaga más. Bajan con buenos controles de proceso y de consistencia de datos, capacitación del personal y programación confiable, porque la presión por resultados rápidos lleva a trabajar sin controles.

**Los de capacidad de equipos.**

- Estimar el equipamiento para las conexiones y las transacciones diarias, semanales y mensuales, y el almacenamiento que generan.
- Con eso y con el equipamiento disponible para instalar o comprar, se definen las configuraciones posibles.
- Se descartan las que no sirven. La configuración elegida tiene que superar con holgura la necesidad actual, para absorber el crecimiento.
- Y puede pasar que la empresa ya tenga la infraestructura, el HW y SW (hardware y software) necesarios.

**Lo importante.** La técnica demuestra que se puede hacer. Define los requisitos que después van al pliego. Y la configuración elegida tiene que superar con holgura la necesidad actual.

**Ojo, trampa.** La configuración justa para hoy no sirve: hay que dejar margen para crecer. Y que haya proveedores alternativos es parte de la técnica y es lo que después permite una contratación con competencia.

## Factibilidad económica: qué se compara

La económica compara costos y beneficios de cada alternativa técnica para elegir la más conveniente. El apunte lo resalta en azul: **la factibilidad económica permite comparar los beneficios y costos de cada una de estas soluciones a fin de determinar la más conveniente.** Lo que se considera:

- El costo de hacer la investigación de sistemas.
- El costo de hardware y software.
- Los beneficios, que pueden ser ingresos o reducción de costos y de errores.
- El costo de no hacer nada.

Este último se olvida mucho y es clave: no hacer nada también cuesta.

Después viene lo que en TI es fundamental: CapEx contra OpEx.

- **CapEx** (Capital Expenditure, gasto de capital): la inversión inicial, como hardware, licencias de software perpetuas, red y desarrollo.
- **OpEx** (Operational Expenditure, gasto operativo): los gastos recurrentes, como las suscripciones a la nube, el soporte, el mantenimiento, la energía, internet y los sueldos de TI.

Las suscripciones a la nube que menciona el apunte son SaaS (Software as a Service, software como servicio: alquilás una aplicación ya hecha) e IaaS (Infrastructure as a Service, infraestructura como servicio: alquilás servidores y almacenamiento). Pasar a la nube es, en el fondo, cambiar CapEx por OpEx: no comprás el servidor, pagás por mes. Es la diferencia entre comprar el auto y alquilarlo.

La evaluación financiera suma:

- La inversión: activos fijos, activos nominales (inversiones intangibles, como estudios y gastos de puesta en marcha) y capital de trabajo (la plata para operar hasta empezar a cobrar).
- La proyección de ingresos y gastos anuales.
- El financiamiento.
- Los estados proyectados: estado de resultados, flujo de efectivo y balance general.

Con el flujo de fondos netos se calculan los criterios de rentabilidad:

- **VAN** (Valor Actual Neto).
- **TIR** (Tasa Interna de Retorno).
- La relación beneficio costo.

La gestión de costos del proyecto es el proceso que asegura que el presupuesto se use bien y que los gastos se mantengan según lo planeado, sin sobrecostos. Aunque se llama gestión, incluye planificación, estimación y control. Cómo se gestionan los costos define tres cosas:

- La salud financiera del proyecto de principio a fin.
- La calidad de las decisiones, que son mejores si se basan en estimaciones correctas.
- La detección temprana de riesgos financieros.

El apunte los titula, en negrita, **4 tipos de costos de proyecto**, con sus propios ejemplos:

- **Fijos**: no cambian durante el proyecto, como los honorarios de una agencia que cobra un precio fijo por diseñar un logo.
- **Variables**: cambian según otros factores, como el sueldo del equipo, que depende de las horas que lleve una actividad.
- **Directos**: salen directamente del proyecto, como contratar un experto, hacer una campaña de publicidad o comprar material.
- **Indirectos**: no salen del proyecto pero igual forman parte de los costos, como los impuestos generales, el alquiler de la oficina o las máquinas y el software que usa toda la empresa.

Las diapositivas ordenan los costos y beneficios en tres pares:

- **Tangibles o intangibles**: el desgaste de un equipo contra la caída de la imagen de la empresa.
- **Fijos o variables**: el costo de un equipo contra la tinta de la impresora.
- **Directos o indirectos**: un equipo para operar el sistema contra la seguridad o el aire acondicionado.

Las categorías de costos por elemento son cuatro:

- Equipos.
- Instalaciones.
- Personal.
- Suministros y varios.

Y por instancia del proyecto son seis:

- **Desarrollo**: investigación, análisis, diseño, programación y pruebas.
- **Operativos de inicio**: migración y carga de datos, conversión, ejecución en paralelo y puesta en marcha.
- **Operacionales**: los recurrentes.
- **Financieros**: los intereses del financiamiento.
- **Hereditarios**: ya los pagó otro proyecto, y se restan.
- **Residuales**: lo que vale lo que queda al final de la vida útil, que también se resta.

Con los beneficios, igual: se estiman y se les pone un valor en plata. Los tangibles se comparan con los costos; los intangibles sirven para vender el proyecto. Un truco del apunte para encontrarlos: buscá los problemas del sistema actual y lo que cuestan. Si el sistema nuevo los elimina, ese costo es tu beneficio. Se agrupan en dos:

- **Beneficios de desempeño**: velocidad, acceso a información y mejor atención.
- **Beneficios por evitar costos**: menos errores administrativos, menos papel y menos conteo de inventario.

Cómo los define el apunte:

- Los **tangibles** son fáciles de cuantificar y, en general, tienen que ver con reducir recursos o personal.
- Los **intangibles** son difíciles de cuantificar y tienen que ver con el good will (la buena imagen y reputación de la empresa, que no figura en la contabilidad pero tiene valor) o con mejoras en otros procesos.

La lista de ejemplos del apunte:

- Más eficiencia en el área.
- Menos personal.
- Menos inversiones y costos futuros.
- Personal disponible para otras tareas.
- Mejor planeación y control de recursos.
- Insumos a tiempo.
- Cumplimiento de requisitos del gobierno.
- Mejores decisiones.
- Información apropiada y más confiable.
- Mejor servicio al cliente interno y externo.
- Ventajas competitivas.
- Valor agregado al producto.

Y la **recomendación clave** de las diapositivas: al presentar el proyecto, mostrá los beneficios específicos y también todos los intangibles, tanto los que mejoran el desempeño como los que bajan costos.

**Lo importante.** Se comparan costos y beneficios de cada alternativa, incluyendo el costo de no hacer nada. CapEx es la inversión inicial; OpEx, el gasto recurrente. Y los hereditarios y residuales se restan.

**Ojo, trampa.** "No hacer nada no cuesta" es falso. La nube es cambiar CapEx por OpEx, no al revés. Y no mezcles hereditarios, que ya pagó otro proyecto, con residuales, que es el valor que queda al final de la vida útil: los dos se restan, pero son distintos.

## Cómo se comparan costos y beneficios

Hay tres estrategias:

- **Punto de equilibrio**: compara el costo acumulado del sistema actual con el del nuevo. El punto de equilibrio es el instante en que se igualan, y de ahí en adelante el sistema nuevo da beneficio neto.
- **Período de recuperación**, o payback: cuánto tiempo pasa hasta que los beneficios acumulados igualan a los costos. Cuanto más corto, menos riesgo. La diapositiva del ejemplo concluye, como conclusión clave, que el período de recuperación comienza después del segundo año, cuando los beneficios superan a los costos.
- **Valor presente**: un peso de hoy no vale lo mismo que un peso dentro de tres años. Entonces se usa una tasa de descuento, que es el costo de oportunidad de la plata: lo que la empresa ganaría poniéndola en otro lado. El ejemplo del apunte: si un plazo fijo paga veinte por ciento anual, meter la plata en el proyecto es renunciar a ese veinte. Se multiplican los costos y beneficios de cada año por un factor y se comparan. Si los beneficios a valor presente superan a los costos, la inversión es buena.

Las fórmulas que conviene tener son las estándar. El apunte las nombra sin desarrollarlas.

$$VAN = -I_0 + \sum_{t=1}^{n} \frac{B_t - C_t}{(1+i)^t}$$

La TIR es la tasa $i$ que hace que el VAN sea cero. Si la TIR supera la tasa de descuento, el proyecto conviene.

$$\frac{B}{C} = \frac{\text{VP de los beneficios}}{\text{VP de los costos}}$$

Si $B/C$ es mayor que uno, conviene.

Las letras de las fórmulas: VP es valor presente, $I_0$ es la inversión inicial, $B_t$ y $C_t$ son los beneficios y los costos del año $t$, $n$ es la cantidad de años e $i$ es la tasa de descuento.

**Lo importante.** Equilibrio, recuperación y valor presente. VAN mayor que cero, TIR mayor que la tasa de descuento y beneficio costo mayor que uno: conviene. Cuanto más corto el payback, menos riesgo.

**Ojo, trampa.** La tasa de descuento es el costo de oportunidad, no el interés del préstamo. Y descontado, el payback sale más largo que el simple: el valor presente es más exigente. Lo vas a ver en el segundo ejemplo.

## Factibilidad operativa

Esta es la del TP diez (trabajo práctico número diez), así que vale contarla bien. Una solución puede ser técnicamente posible y económicamente conveniente y aun así fracasar. La pregunta es si se va a poder llevar a la práctica en el momento y las circunstancias deseadas, y si la organización tiene capacidad para operarlo.

La definición que la cátedra marca en azul y negrita: **La factibilidad operativa se refiere a la evaluación de la viabilidad de un proyecto o negocio, centrándose en si la organización cuenta con los recursos humanos, procesos operativos y capacidades necesarias para llevarlo a cabo con éxito. Es decir, se analiza si la empresa tiene la capacidad de ejecutar las actividades requeridas y superar los posibles obstáculos que puedan surgir.**

Las preguntas, casi textuales del apunte:

- ¿Hay suficiente apoyo de la gerencia, y de los usuarios?
- ¿Van a usar el sistema cuando esté instalado?
- ¿Los usuarios participaron en la planeación y el desarrollo?
- ¿Aumenta la productividad?
- ¿Mejora la integración con otras áreas?
- ¿Causa daño?

Daño es:

- Resultados más pobres en algún área.
- Pérdida de control.
- Pérdida de acceso a información.
- Trabajo más lento en algún sector.
- Clientes afectados.

Y los aspectos concretos de la puesta en marcha:

- Recursos humanos clave.
- Horas y equipos.
- Almacenamiento.
- Adecuación del sitio.
- Capacitación de sistemas y de usuarios.
- Conversión de datos del sistema viejo al nuevo.

El apunte advierte que el estudio teórico simplifica: hay que contrastarlo con la realidad, porque detalles chicos al principio pueden terminar en problemas operativos graves.

**Lo importante.** La operativa evalúa si la organización tiene los recursos humanos, los procesos y las capacidades para llevar el proyecto a la práctica. Se mira apoyo, uso, participación, productividad, integración y daño.

**Ojo, trampa.** La operativa no pregunta si la tecnología funciona, eso es la técnica. Pregunta si las personas y los procesos van a funcionar con ella. Y la resistencia al cambio no es un detalle: es un riesgo que se mitiga con participación de usuarios, capacitación y piloto.

## Herramientas de gestión de proyectos

Son aplicaciones para seguir tareas, recursos y equipos. Le sirven a todo el equipo y sobre todo al director, que sabe en todo momento cómo está el proyecto.

Para elegir una, conviene que sea:

- Fácil de usar, o sea, con baja curva de aprendizaje.
- Flexible, porque cada área trabaja distinto.
- Con temporizador y cargas de trabajo.
- Con plantillas e informes de horas por tarea.

Las funciones típicas son cuatro:

- Planificación.
- Colaboración.
- Documentación, con versiones y almacenamiento.
- Evaluación.

El apunte muestra logos de ejemplo de herramientas:

- Asana.
- ClickUp.
- Trello.
- Wrike.
- Jira.
- Basecamp.
- Notion.
- monday.com.

**Lo importante.** Cuatro funciones: planificación, colaboración, documentación y evaluación. Y se elige por facilidad de uso y flexibilidad.

**Ojo, trampa.** La herramienta no reemplaza a la metodología ni al director: sirve para seguir lo que ya se planificó.

## Contrataciones: pública y privada

Una vez que el proyecto se aprueba, hay que comprar. Y comprar en serio tiene un proceso.

La contratación pública es un acuerdo bilateral donde una de las partes está ejerciendo la función administrativa, o sea el Estado, para hacer una obra, prestar un servicio o comprar o vender un bien, con el fin de satisfacer necesidades generales. Se regula para que el Estado sea eficiente y transparente con los recursos públicos.

Entran:

- Compraventa.
- Suministros.
- Servicios.
- Locaciones.
- Consultoría.
- Alquileres con opción a compra.
- Permutas.
- Concesiones.
- Obras públicas.
- Licencias.

Quedan afuera:

- El empleo público.
- Las compras por caja chica.
- Los contratos con estados extranjeros.
- Los contratos con organismos internacionales o multilaterales de crédito, y lo que ellos financien.
- Las operaciones de crédito público.

Para elegir el procedimiento se mira:

- La economicidad, la eficiencia y la eficacia.
- Las características del bien o servicio.
- El monto estimado.
- Las condiciones del mercado.
- La urgencia o emergencia.

Una contratación típica tiene tres etapas:

- **Previa a la licitación**: donde se definen los requerimientos.
- **Proceso de licitación**: desde que se arma el pliego hasta la adjudicación.
- **Posterior**: desde la adjudicación hasta que se cumple la obligación.

**Lo importante.** Contratación pública es el Estado ejerciendo la función administrativa. Tres etapas: previa, proceso de licitación y posterior. El procedimiento se elige según el monto, el mercado y la urgencia.

**Ojo, trampa.** La caja chica y el empleo público quedan afuera. Y el proceso de licitación termina en la adjudicación: lo que sigue ya es la etapa posterior.

## El cronograma de una contratación

Esto es largo pero tiene lógica. Primero, el esquema del apunte, que ordena las etapas básicas de una contratación:

![IMAGEN 11](https://raw.githubusercontent.com/JHProyectos/administracion-sistemas-ASI-UTN-2026/refs/heads/main/imagenes/Unidad-5/imagen-11.jpg)

El esquema agrupa ocho etapas en tres bloques:

- **Previas**: definición de requerimientos; determinación del mecanismo de compra (licitación pública o privada); reserva y autorización presupuestaria.
- **Etapas del proceso de licitación**: elaboración de la documentación licitaria; llamado del concurso y recepción de ofertas; evaluación de ofertas; adjudicación.
- **Posteriores a la licitación**: formalización del contrato; ejecución del contrato; evaluación del proveedor.

El apunte dice que cada etapa tiene eventos, y que "en el cronograma de la siguiente figura" se describen. Esa figura no está en el PDF, pero los dieciséis eventos sí están en el texto. Contalo como una historia de dieciséis pasos.

```mermaid
flowchart TD
    A["1 Inicio: surge la necesidad"] --> B["2 Elaboración del pliego"]
    B --> C["3 Llamado a concurso"]
    C --> D["4 Análisis y consultas"]
    D --> E["5 Presentación de ofertas: Sobre I y Sobre II + garantía de oferta"]
    E --> F["6 Análisis y selección del Sobre I"]
    F --> G["7 Dictamen de selección: aptos y no aptos"]
    G --> H["8 Apertura del Sobre II de los aptos"]
    H --> I["9 Negociación de precios"]
    I --> J["10 Adjudicación"]
    J --> K["11 Firma de la contrata + garantía de ejecución"]
    K --> L["12 Elaboración"]
    L --> M["13 Recepción: acta de recepción"]
    M --> N["14 Plazo de garantía"]
    N --> O["15 Recepción final: acta definitiva"]
    O --> P["16 Evaluación del proveedor"]
```

- Uno, el inicio: aparece la necesidad, la causa del contrato.
- Dos, el pliego. La entidad licitante, que se llama comitente, arma el Pliego de Bases y Condiciones, también llamado documentación licitaria o simplemente pliego: la forma, las cantidades, las fechas y cómo se va a elegir a los oferentes. Participan Compras y el área que pide, el cliente interno, y a veces expertos y abogados. Se empieza a armar cuando un área hace el pedido y se termina antes del llamado.
- Tres, el llamado. Hay dos modalidades:
  - El **concurso privado de precios (CPP)**, que es la licitación privada: se invita a proveedores elegidos de la base de datos.
  - La **licitación pública**: se publica en medios masivos o en el Boletín Oficial, sin preselección.
  - La diferencia es el grado de competencia; el proceso es el mismo.
  - El privado es más rápido, pero la pública es obligatoria en algunos casos:
    - Servicios públicos privatizados que superan cierto monto.
    - Productos innovadores sin proveedores conocidos.
    - Productos clave para un sector del país.
- Cuatro, análisis y consultas. Toda consulta de un oferente se responde a todos mediante una circular con consulta, por transparencia. Se puede corregir el pliego, pero solo en este período y comunicándolo a todos. Si se modifica después, el proceso puede quedar viciado de nulidad.
- Cinco, presentación de ofertas, con dos sobres cerrados y separados:
  - El **Sobre uno** lleva, sin precios:
    - Los pliegos general y particular firmados, con sus anexos.
    - Los documentos que acreditan que el oferente es elegible.
    - Los certificados de laboratorio.
    - Los certificados de homologación.
    - Lo que pidan los organismos reguladores.
    - La documentación técnica, legal y societaria.
  - El **Sobre dos** lleva la oferta económica: la planilla de cotización y las ofertas alternativas, si se admiten.
  - La oferta básica cumple el cien por ciento de las especificaciones; la alternativa no cumple alguna.
  - Todo va foliado y firmado: la firma es una declaración jurada de que conocés el pliego, y si falta un documento, quedás descalificado.
  - Y se deposita la garantía de oferta, entre el uno y el dos por ciento del monto ofertado, en dinero o mediante caución.
- Seis, análisis y selección: un análisis interdisciplinario del Sobre uno solamente. Cada área revisa lo suyo, analiza muestras y pide pruebas, y también se miran los antecedentes del oferente en la base de proveedores. Se pueden pedir aclaraciones o correcciones de errores formales, siempre de forma transparente.
- Siete, el dictamen de selección: la lista de aptos, o calificados, y no aptos. Para calificar se mira que el oferente cumpla los aspectos formales y técnicos del pliego, los requisitos y documentos que pide y las condiciones de elegibilidad. No tiene una forma fija y es interno: los oferentes saben si son aptos, pero no leen el dictamen, y a los no aptos se les dice por qué.
- Ocho, la apertura del Sobre dos, solo de los aptos. Las ofertas de los no aptos se descartan o quedan solo como dato estadístico.
- Nueve, la negociación de precios y condiciones, o una subasta, conducida por Compras.
- Diez, la adjudicación: una carta al ganador. Tiene unos cinco días para constituir la garantía de ejecución y firmar la contrata.
- Once, la firma de la contrata. El oferente pasa a ser proveedor, desde esta fecha corren los plazos y se devuelven las garantías de oferta.
- Doce, la elaboración: el proveedor fabrica o prepara el servicio.
- Trece, la recepción. La entrega puede ser total o parcial. Control de calidad verifica y emite el acta de recepción, también llamada de conformidad o de aprobación. Desde la fecha del acta corre el plazo de garantía y el proveedor puede facturar: sin acta no se cobra. Si hay rechazos o mora, se aplica la cláusula penal, que son multas descontadas de la garantía de ejecución.
- Catorce, el plazo de garantía: el proveedor repara o reemplaza a su costo.
- Quince, la recepción final, con el acta de recepción definitiva. Se devuelve la garantía de ejecución menos las multas. En las locaciones de obra, la responsabilidad civil por vicios ocultos sigue después.
- Y dieciséis, la evaluación del proveedor: se registra su desempeño en la base de proveedores, para futuras adjudicaciones.

Y una pregunta clásica: ¿por qué dos sobres y en fechas distintas? Por dos razones. Cada área analiza lo suyo: Técnica y Legal el Sobre uno, Compras el Sobre dos. Y si ves los precios antes de evaluar lo técnico, te sesgás y te tienta saltear etapas. Es como corregir un examen sabiendo de quién es: ya no sos neutral.

**Lo importante.** Dos sobres, abiertos en fechas distintas: el Sobre uno es técnico, legal y sin precios; el Sobre dos es económico y solo se abre a los aptos. Toda consulta se responde a todos con una circular. Sin acta de recepción no se factura.

**Ojo, trampa.** Privada y pública solo difieren en el grado de competencia, no en el proceso. El pliego solo se corrige en el período de consultas y comunicándolo a todos. La garantía de oferta se devuelve al terminar la adjudicación, cuando se firma la contrata, y la de ejecución, al cumplir y menos las multas. Y el dictamen es interno: los oferentes no lo leen.

## Pliegos, garantías y cláusula penal

El pliego es el documento clave del contrato. Fija:

- Derechos, obligaciones y responsabilidades.
- Cómo se selecciona.
- Cómo se define el producto.
- Cómo se resuelven los conflictos.
- Las causales de rescisión.
- La forma de pago.
- Los plazos.
- Las penalidades.
- Las garantías.

Se divide en tres partes:

- **Pliego general**: cláusulas amplias que se repiten en todos los concursos del contratante.
- **Pliego de condiciones particulares**: específico e irrepetible para cada contrato, que es la clave del contrato. Lo que no dice, lo rige el general.
- **Documentación técnica**: los anexos con las especificaciones de requisitos, las normas técnicas y los métodos de instalación u operación. Esta define qué se compra.

Los anexos son complementarios: el pliego particular los menciona y se presentan como documentos aparte por lo largos que son.

Después del llamado también se generan documentos:

- Las **notas** con consultas de los oferentes, siempre por escrito.
- Las **circulares** con que el comitente responde a todos.

El orden de prelación, o sea, qué manda cuando dos documentos dicen distinto:

- Primero, las notas aclaratorias y circulares.
- Después, el pliego de condiciones particulares.
- Al final, el pliego general.

La regla para acordarte: cuanto más general es un documento, menos prioridad tiene.

La contrata repite los puntos más importantes del pliego y suma lo que salió del proceso:

- El precio de la contratación.
- El nombre o razón social del adjudicatario, que desde ahora es el proveedor o contratista.
- La fecha de entrega, contada desde la firma de la contrata.
- Las modificaciones y adendas (agregados) al pliego hechas entre el llamado y la presentación de ofertas.

Con las firmas queda el consentimiento de las partes, y en contratos formales que piden solemnidades se firma ante escribano.

Contrata contra orden de compra (OC) o de trabajo (OT). Las dos tienen el mismo efecto jurídico; la orden de compra o de trabajo es menos formal y de carácter comercial.

- En la **contrata**, las partes firman en el mismo momento, a veces ante escribano.
- En la **orden de compra** o de trabajo, firman en momentos distintos: el acuerdo vale cuando el proveedor la devuelve firmada.

Las garantías son dos:

- **Garantía de oferta**: del uno al dos por ciento de lo ofertado. Sirve para que el oferente no abandone, es una barrera de salida, y se devuelve al terminar la adjudicación.
- **Garantía de ejecución**: en general el diez por ciento del contrato. Sirve para asegurar que cumpla y se devuelve al cumplir, menos las multas.

Se pueden constituir en:

- Efectivo.
- Cheque de pago diferido.
- Títulos o bonos.
- Fianza bancaria.
- Seguro de caución.
- Pagaré.
- Caución juratoria.
- Créditos a favor del proveedor.

Y la cláusula penal. Si vence el plazo y no se cumplió, el proveedor entra en mora. La cláusula penal fija una multa automática, que se descuenta de la garantía de ejecución. Sus características:

- Es accesoria: solo actúa si hay incumplimiento.
- Su objetivo es asegurar el cumplimiento a término sin tener que rescindir.

**Lo importante.** Prelación: circulares, después el particular, después el general. Garantía de oferta del uno al dos por ciento; de ejecución, alrededor del diez. Y la cláusula penal asegura el cumplimiento sin rescindir.

**Ojo, trampa.** La contrata y la orden de compra tienen el mismo efecto jurídico: cambia cuándo se firma. El pliego general no manda sobre el particular. Y la garantía de oferta no es para cubrir el incumplimiento del contrato: es para que el oferente no abandone el concurso.

## Ejemplo resuelto uno: factibilidad operativa de NovaRetail

Este sale del TP diez. NovaRetail es una distribuidora mayorista del sur de Santa Fe. Sus números:

- Ciento veinte empleados: cuarenta y cinco operarios de depósito, treinta y cinco preventistas (los vendedores que toman los pedidos), veintidós administrativos, quince choferes y solo tres de TI.
- Tres depósitos: el central y dos satélites, a ciento veinte y doscientos cincuenta kilómetros.
- Mil doscientos comercios clientes.
- Entre trescientos cincuenta y quinientos pedidos por día.

Paso uno, el diagnóstico, buscando causas y no solo síntomas. Los problemas:

- Los pedidos tardan de cuarenta y ocho a setenta y dos horas en llegar a preparación, porque los preventistas los toman en libreta o por WhatsApp y seis administrativos los transcriben de noche.
- Hay doce por ciento de errores de digitación, por la carga manual sin validaciones.
- Los depósitos satélites quedan paralizados cuando se corta la luz o internet en Casa Central, porque hay un único servidor de dos mil diecisiete, una VPN (Virtual Private Network, red privada virtual: una conexión cifrada por internet) sobre internet hogareña y una UPS (Uninterruptible Power Supply, un equipo con batería que mantiene la energía cuando hay un corte) gastada. Es un punto único de falla.
- Hay riesgo de perder todos los datos, porque el backup (la copia de seguridad) es manual, semanal, a un disco USB y sin verificar.
- La central telefónica está colapsada, con doscientas cincuenta llamadas que ocupan el setenta por ciento del tiempo de los operadores, y clientes que se van, porque no tienen otra forma de consultar estado, saldo o stock.

Paso dos, el objetivo IT, que viene de la Unidad tres, con criterio SMART (Specific, Measurable, Achievable, Relevant, Time-bound: específico, medible, alcanzable, relevante y con plazo). En este caso, el objetivo es:

- En cuatro meses, tener nube, CRM (Customer Relationship Management, gestión de la relación con los clientes) móvil, agente de IA (inteligencia artificial) y licencias de desarrollo.
- Con disponibilidad de noventa y nueve coma cinco por ciento o más.
- Con quinientos pedidos por día.
- Y con errores de carga menores a uno por ciento.

Paso tres, el impacto humano, actor por actor. Esta es la parte que hace operativa a la factibilidad.

- **Los preventistas.**
  - Las barreras: la costumbre, la sensación de que la app agrega pasos, los distintos niveles digitales y la conectividad inestable en ruta.
  - Las medidas: capacitación con pedidos reales y referentes por zona, un piloto con un grupo antes de extender, una app con formularios simples y validaciones, y verificar con el proveedor que funcione offline (sin conexión), porque no se puede suponer.
- **Los administrativos.** Se reconvierten, no se despide automáticamente. Pasan de transcribir a:
  - Gestionar excepciones.
  - Conciliar stock y facturación.
  - Hacer cobranzas proactivas.
  - Mantener datos maestros.
  - Dar soporte de primer nivel.
- **La atención telefónica.** El chatbot responde lo repetitivo y los humanos atienden lo que requiere criterio. Hay derivación obligatoria a una persona en:
  - Reclamos.
  - Diferencias de saldo.
  - Acuerdos de pago.
  - Excepciones comerciales.
  - Datos sensibles.
  - Cuando no se puede verificar la identidad.
- **Los depósitos.** Para que el stock en tiempo real sea verdad, los cuarenta y cinco operarios tienen que registrar cada movimiento cuando ocurre:
  - Recepción.
  - Reservas.
  - Despacho.
  - Transferencias entre depósitos.
  - Conteos cíclicos.
  - Ajustes autorizados.

Paso cuatro, los riesgos, con una matriz de probabilidad por impacto, en una escala de uno a tres. La prioridad es probabilidad por impacto:

- La conectividad inestable en ruta y depósitos: tres por tres, nueve, crítica.
- El desfase entre el stock físico y el del sistema: nueve, crítica.
- La resistencia de los preventistas: seis, alta.
- La sobrecarga de los tres de TI: seis, alta.
- Los errores en la migración: seis, alta.
- La caída del proveedor cloud: tres, moderada.

Paso cinco, el plan de contingencia si se cae la nube o el enlace:

- Declarar la contingencia.
- Usar registros alternativos en papel prenumerado.
- Despachar solo lo que se verifica físicamente.
- Pedir autorización al jefe de depósito.
- Reconciliar al volver, con control de duplicados.
- Registrar el incidente para mejorar el procedimiento.

Y paso seis, el dictamen: factible de forma condicionada. La organización puede adoptar el cambio, pero cuatro meses con tres personas de TI es exigente. Se aprueba si hay:

- Liderazgo de la Dirección.
- Soporte externo.
- Capacitación.
- Piloto.
- Criterios medibles para pasar a producción.

**Lo importante.** La operativa no pregunta si la tecnología funciona, pregunta si las personas y los procesos van a funcionar con ella. Por eso el análisis se hace por actor, se mide la adopción y siempre termina con un plan de contingencia.

**Ojo, trampa.** Los administrativos se reconvierten, no se despiden automáticamente. La conectividad offline no se supone: se verifica con el proveedor. Y "factible condicionada" no es un no: es un sí con condiciones.

## Ejemplo resuelto dos: factibilidad económica con números

Estos números son inventados para practicar, en miles de pesos.

Una empresa evalúa reemplazar su sistema actual. Los datos:

- El actual le cuesta mil ochocientos por año, en errores, horas de carga y clientes perdidos.
- El nuevo requiere una inversión inicial, el CapEx, de tres mil.
- Tiene un costo operativo, el OpEx, de quinientos por año.
- El horizonte es de cuatro años.
- La tasa de descuento es veinte por ciento, el plazo fijo del apunte.

El beneficio anual del sistema nuevo es el costo que evita: mil ochocientos. El flujo neto anual es mil ochocientos menos quinientos: mil trescientos.

- Primero, el punto de equilibrio. El sistema actual acumula mil ochocientos más cada año. El nuevo arranca en tres mil y suma quinientos por año. Se igualan cuando mil ochocientos por $t$ es igual a tres mil más quinientos por $t$, o sea $t = 3000 / 1300$, que da unos dos coma tres años.

```grafico
tipo: lineas
titulo: Punto de equilibrio: costo acumulado
unidad: miles de $

Año, Sistema actual, Sistema nuevo
0, 0, 3000
1, 1800, 3500
2, 3600, 4000
3, 5400, 4500
4, 7200, 5000
```

Antes de los dos coma tres años el sistema nuevo es más caro; después, empieza a dar beneficio neto. Es exactamente lo que dice el apunte: el período de recuperación comienza después del segundo año.

- Segundo, el período de recuperación simple. El flujo acumulado es menos tres mil, menos mil setecientos, menos cuatrocientos, y en el año cuatro más novecientos. Se recupera durante el año tres: dos más cuatrocientos sobre mil trescientos, unos dos coma tres años.
- Tercero, el valor presente. El factor de cada año es uno sobre uno coma dos a la $t$. Los flujos de mil trescientos valen, descontados, mil ochenta y tres, novecientos tres, setecientos cincuenta y dos y seiscientos veintisiete. Sumados, restando los tres mil de inversión, dan un VAN de más trescientos sesenta y cinco. El VAN es mayor que cero: el proyecto conviene. Y fijate que, descontando, la recuperación ya no es a los dos coma tres años sino a los tres coma cuatro. Por eso el valor presente es más exigente que el payback simple.
- Cuarto, la TIR. Probando tasas, al veinticinco por ciento el VAN da más setenta, y al veintisiete da menos treinta y seis. La TIR es de aproximadamente veintiséis coma tres por ciento, mayor que el veinte de la tasa de descuento: conviene.
- Y quinto, la relación beneficio costo, a valor presente. Los beneficios valen mil ochocientos por dos coma cinco ocho ocho siete, cuatro mil seiscientos sesenta. Los costos, tres mil más quinientos por el mismo factor, cuatro mil doscientos noventa y cuatro. El cociente da uno coma cero nueve. Mayor que uno: conviene, aunque con poco margen.

**Lo importante.** El proyecto conviene por los tres criterios, pero el margen es chico: un VAN de trescientos sesenta y cinco sobre una inversión de tres mil. Por eso la factibilidad económica nunca se mira sola: se cruza con los riesgos.

**Ojo, trampa.** El payback simple da dos coma tres años y el descontado da tres coma cuatro: el segundo es el más exigente. Y con un margen así de chico, si la inversión se va un quince por ciento arriba, el VAN pasa a negativo y ya no conviene.

## Cómo se conecta todo

- Con la Unidad tres: el objetivo IT de NovaRetail se valida con SMART antes de evaluar su factibilidad. Primero se fija el objetivo, después se pregunta si se puede, si conviene y si la gente lo va a adoptar.
- La definición del problema alimenta el alcance, y el alcance alimenta la factibilidad. Si el problema está mal definido, con un síntoma en lugar de la causa, las tres factibilidades evalúan la solución equivocada.
- Los riesgos se cruzan con la factibilidad económica: un VAN chico con riesgos altos es una mala apuesta. Y se cruzan con la operativa: la resistencia al cambio es un riesgo, y se mitiga con lo que pide la operativa, que es participación de usuarios, capacitación y piloto.
- Los stakeholders se cruzan con la operativa: la pregunta de si hay apoyo de la gerencia y de los usuarios se responde con la matriz de poder e interés.
- La factibilidad técnica se cruza con la contratación: la técnica define los requisitos, y esos requisitos se convierten en la documentación técnica del pliego. Que haya proveedores alternativos es lo que hace posible un concurso con competencia.
- Y el ciclo de vida se cruza con la contratación: la contratación ocurre entre la planificación y la ejecución, y la recepción y el acta definitiva son parte del cierre.

**Lo importante.** Todo se encadena: objetivo, problema, alcance, factibilidades, riesgos, contratación, ejecución.

**Ojo, trampa.** Como los temas están conectados, una pregunta puede mezclarlos: por ejemplo, ofrecerte la resistencia al cambio como un tema de técnica, o los requisitos del pliego como algo que nace en la operativa. Preguntate siempre de qué tema es cada cosa.

## Preguntas tipo multiple choice

En cada una: las opciones, la correcta, por qué, y dónde está la trampa.

Pregunta uno. ¿Qué características tiene un proyecto según el PMBOK?

- Primera: es un esfuerzo permanente para mantener un servicio funcionando.
- Segunda: es cualquier tarea del área de sistemas.
- Tercera: es un esfuerzo temporal para crear un producto, servicio o resultado único.
- Cuarta: es un conjunto de actividades que se repiten cada mes.

La correcta es la tercera. ¿La trampa? La primera y la cuarta describen la operación, que es continua o repetitiva, y un proyecto es temporal y único.

Pregunta dos. ¿Por qué la cátedra dice que "IT Project" es un concepto simplista?

- Primera: porque no existe un proyecto sin el negocio que reciba su resultado.
- Segunda: porque los proyectos de TI no usan metodologías.
- Tercera: porque los proyectos de TI son siempre más caros.
- Cuarta: porque solo el área de sistemas puede iniciarlos.

La correcta es la primera. ¿La trampa? La cuarta: sistemas puede detectar mejoras, pero conviene que el pedido lo haga el gerente del área afectada.

Pregunta tres. Un proyecto tiene alta incertidumbre, cambios frecuentes y mucho contacto con el cliente. Según la matriz de Stacey, ¿qué enfoque corresponde?

- Primera: tradicional.
- Segunda: primero estabilizar, porque es caótico.
- Tercera: ágil.
- Cuarta: ninguno, porque es complicado.

La correcta es la tercera: es un proyecto complejo. ¿La trampa? La segunda: el caótico es otro caso, sin requisitos ni solución, y ahí primero se estabiliza.

Pregunta cuatro. ¿Qué se hace en la fase de cierre?

- Primera: la reunión de arranque.
- Segunda: el After Action Review, el resumen de aprendizaje, la transferencia de conocimientos y el cierre formal.
- Tercera: el control del alcance y del cronograma.
- Cuarta: la estimación inicial de costos.

La correcta es la segunda. ¿La trampa? La tercera, que es monitoreo y control, y la primera, que es el kick-off de la planificación.

Pregunta cinco. Un grupo tiene mucho poder pero poco interés en el proyecto, como una ONG ambiental. ¿Qué tipo de stakeholder es y qué estrategia corresponde?

- Primera: promotor, involucrar.
- Segunda: defensor, reportar.
- Tercera: apático, monitorizar.
- Cuarta: latente, informar de forma proactiva.

La correcta es la cuarta. ¿La trampa? La segunda: los defensores tienen interés, no poder.

Pregunta seis. ¿Qué afirmación sobre el riesgo es correcta?

- Primera: es un evento incierto que puede tener efecto positivo o negativo sobre los objetivos.
- Segunda: siempre es una amenaza.
- Tercera: es un problema que ya ocurrió.
- Cuarta: solo existe en proyectos de tecnología.

La correcta es la primera. ¿La trampa? La segunda, porque el riesgo también puede ser una oportunidad.

Pregunta siete. ¿Cuál es la diferencia entre viabilidad y factibilidad?

- Primera: son sinónimos.
- Segunda: la viabilidad es solo económica.
- Tercera: la factibilidad decide si vale la pena y la viabilidad analiza la tecnología.
- Cuarta: la viabilidad es la decisión estratégica de si vale la pena convertir la idea en proyecto; la factibilidad analiza si se puede, si conviene y si se puede operar.

La correcta es la cuarta. ¿La trampa? La primera, que las trata como sinónimos.

Pregunta ocho. En una evaluación económica aparece un costo que ya pagó otro proyecto y que el nuevo aprovecha. ¿Qué es y qué se hace con él?

- Primera: costo residual, se suma.
- Segunda: costo hereditario, se resta.
- Tercera: costo operacional, se suma.
- Cuarta: costo financiero, se resta.

La correcta es la segunda. ¿La trampa? El residual: también se resta, pero es el valor que queda al final de la vida útil, no lo que ya pagó otro proyecto.

Pregunta nueve. ¿Qué representa la tasa de descuento en el valor presente?

- Primera: la inflación esperada.
- Segunda: el interés del financiamiento.
- Tercera: el costo de oportunidad de la plata, lo que la empresa ganaría poniéndola en otro lado.
- Cuarta: el margen de ganancia del proyecto.

La correcta es la tercera, como el plazo fijo que paga veinte por ciento. ¿La trampa? La segunda: el interés del financiamiento es un costo financiero, no la tasa de descuento.

Pregunta diez. Un proyecto da una TIR de veintiséis por ciento y la tasa de descuento es veinte por ciento. ¿Qué se concluye?

- Primera: no conviene, porque la TIR es muy alta.
- Segunda: no se puede concluir nada.
- Tercera: conviene, porque la TIR supera la tasa de descuento.
- Cuarta: conviene solo si el payback es mayor a tres años.

La correcta es la tercera. ¿La trampa? La primera, que invierte la regla, y la cuarta: cuanto más corto el payback, menos riesgo.

Pregunta once. ¿Qué evalúa la factibilidad operativa?

- Primera: si la organización cuenta con los recursos humanos, los procesos y las capacidades para llevar el proyecto a la práctica.
- Segunda: si existe la tecnología necesaria.
- Tercera: si el proyecto da una buena rentabilidad.
- Cuarta: si hay proveedores alternativos.

La correcta es la primera. ¿La trampa? La primera y la cuarta son de la técnica, y la tercera es de la económica.

Pregunta doce. ¿Qué diferencia hay entre el concurso privado de precios y la licitación pública?

- Primera: el proceso es completamente distinto.
- Segunda: en el privado no se usan pliegos.
- Tercera: la pública no tiene garantías.
- Cuarta: el grado de competencia: en el privado se invita a proveedores elegidos y en la pública se publica sin preselección.

La correcta es la cuarta. ¿La trampa? La primera: el proceso es el mismo.

Pregunta trece. ¿Por qué se presentan dos sobres que se abren en fechas distintas?

- Primera: para que cada área analice lo suyo y para que ver los precios no sesgue la evaluación técnica.
- Segunda: para que los oferentes puedan cambiar su precio.
- Tercera: para poder publicar el dictamen.
- Cuarta: para reducir el costo del papel.

La correcta es la primera. ¿La trampa? La segunda, porque el sobre cerrado justamente evita cambios, y la tercera: el dictamen es interno.

Pregunta catorce. Dos documentos de un concurso se contradicen: una circular y el pliego general. ¿Cuál prevalece?

- Primera: el pliego general, porque es más completo.
- Segunda: el pliego de condiciones particulares.
- Tercera: la circular, porque cuanto más general es un documento, menos prioridad tiene.
- Cuarta: el que se firmó primero.

La correcta es la tercera. ¿La trampa? La primera: lo general nunca manda sobre lo específico.

Pregunta quince. ¿Qué afirmación sobre garantías y cláusula penal es correcta?

- Primera: la garantía de oferta es del diez por ciento y se devuelve al terminar.
- Segunda: la garantía de ejecución se devuelve al cumplir, menos las multas, y la cláusula penal asegura el cumplimiento sin tener que rescindir.
- Tercera: la cláusula penal actúa siempre, aunque no haya incumplimiento.
- Cuarta: la garantía de oferta sirve para cubrir las multas.

La correcta es la segunda. ¿La trampa? La primera: la de oferta es del uno al dos por ciento, y el diez es la de ejecución. Y la tercera: la cláusula penal es accesoria, solo actúa si hay incumplimiento.

Pregunta dieciséis. Según la introducción del apunte, ¿qué tienen que hacer las organizaciones para adaptarse a la velocidad digital?

- Primera: comprar las últimas herramientas tecnológicas del mercado.
- Segunda: reducir la cantidad de procesos para ir más rápido.
- Tercera: tercerizar todas las funciones de TI.
- Cuarta: transformar las funciones y los procesos subyacentes y crear un conjunto único de capacidades digitales para desarrollar la competencia empresarial central.

La correcta es la cuarta. ¿La trampa? La primera: la frase habla de transformar procesos y de crear capacidades, no de comprar tecnología.

Pregunta diecisiete. ¿Cuál es una de las tres características del riesgo que marca el apunte?

- Primera: es siempre negativo.
- Segunda: implica una elección, por ejemplo qué métodos y herramientas usar, cuánta gente involucrar y cuánta importancia darle a la calidad.
- Tercera: solo concierne a lo que ya ocurrió.
- Cuarta: no implica cambios.

La correcta es la segunda. ¿La trampa? La tercera: el riesgo concierne a lo que ocurra en el futuro. Y la cuarta, porque el riesgo implica cambios.

Pregunta dieciocho. Según las diapositivas, ¿qué conviene hacer al presentar un proyecto?

- Primera: mostrar los beneficios específicos del sistema y también todos los intangibles, tanto los que mejoran el desempeño como los que reducen costos.
- Segunda: mostrar solo los beneficios tangibles, que son los que se pueden medir.
- Tercera: dejar afuera el costo de no hacer nada.
- Cuarta: presentar solo el VAN, sin hablar de beneficios.

La correcta es la primera. ¿La trampa? La segunda: los intangibles sirven justamente para vender el proyecto.

## Lo que puede entrar en desarrollo

- **Tema uno: proyecto.**
  - Definí proyecto según el PMBOK con sus tres características.
  - Explicá por qué "IT Project" es simplista.
  - Explicá cuándo conviene gestión ágil y cuándo tradicional, con la matriz de Stacey.
  - Nombrá las cinco fases del ciclo de vida y dos actividades de cada una.
  - Qué dice la introducción sobre lo que tienen que hacer las organizaciones para adaptarse a la velocidad digital.
- **Tema dos: stakeholders y riesgos.**
  - Explicá la matriz de stakeholders con un ejemplo de cada cuadrante.
  - Qué es un riesgo y por qué puede ser positivo.
  - Cuáles son las tres características del riesgo.
  - Diferenciá viabilidad de factibilidad.
- **Tema tres: factibilidad.**
  - Qué pregunta responde cada una y en qué orden se encadenan.
  - Diferenciá CapEx de OpEx con ejemplos de TI.
  - Explicá punto de equilibrio, período de recuperación y valor presente.
  - Qué son los costos hereditarios y residuales y por qué se restan.
  - Qué preguntas se hace la factibilidad operativa.
  - Qué es la gestión de costos y qué tres cosas define.
  - Diferenciá beneficios tangibles e intangibles y para qué sirve cada uno.
- **Tema cuatro: contratación.**
  - Diferencia entre concurso privado de precios y licitación pública.
  - Por qué se usan dos sobres y se abren en fechas distintas.
  - Pliego general contra particular y el orden de prelación.
  - Garantía de oferta contra garantía de ejecución, y qué es la cláusula penal.
  - Contrata contra orden de compra, y qué datos nuevos aparecen en la contrata.
  - Qué se mira en el dictamen de selección para declarar apto a un oferente.

## Lo mínimo que te tenés que llevar

- Las organizaciones tienen que transformar sus funciones y procesos y crear capacidades digitales para adaptarse a la velocidad digital.
- Un proyecto es temporal, único y con recursos escasos, y un proyecto de TI siempre es del negocio.
- Gestión tradicional para entornos estables; ágil para proyectos complejos, con la matriz de Stacey. Las cinco fases son inicio, planificación, ejecución, monitoreo y control, y cierre, y el monitoreo corre en paralelo.
- Los stakeholders se ordenan por poder e interés: promotores, involucrar; latentes, informar; defensores, reportar; apáticos, monitorizar.
- El riesgo es un evento incierto con efecto positivo o negativo, y se gestiona por probabilidad e impacto.
- La viabilidad pregunta si vale la pena. La factibilidad pregunta tres cosas: técnica, si se puede; económica, si conviene, con equilibrio, recuperación, VAN, TIR y beneficio costo; y operativa, si las personas y los procesos lo van a poder llevar a la práctica.
- CapEx es la inversión inicial y OpEx es el gasto recurrente. La tasa de descuento es el costo de oportunidad.
- En la contratación, la licitación va con pliego, llamado, consultas, dos sobres, dictamen, adjudicación, contrata y recepción. Las garantías son: de oferta, del uno al dos por ciento, y de ejecución, alrededor del diez. Y la prelación es: circulares, después el pliego particular, después el general.
