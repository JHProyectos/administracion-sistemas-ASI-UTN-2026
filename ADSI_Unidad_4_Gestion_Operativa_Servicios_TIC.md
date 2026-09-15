# Unidad N.º 4 — Gestión Operativa de los Servicios TIC

Cátedra: Administración de Sistemas de Información (ADSI) — UTN, Facultad Regional Venado Tuerto. Año 2026. Transcripción completa del material original.

## Índice de Temas

- Modelo de prestador de Servicios TI
- Gestión de Servicios de TI. Conceptos. Evolución. Beneficios. Desafíos.
- Procesos Operativos: Gestión de eventos, Gestión de incidencias, Gestión de

Problemas, Gestión de Solicitudes, Gestión de accesos, Gestión de acuerdo de Servicios.

- Mesa de servicios de TI: objetivo, estructura, recursos

## Introducción

En el contexto actual de las organizaciones, la Gestión Operativa de los Servicios de Tecnologías de la Información (TI) se consolida como un componente crítico para la continuidad del negocio, la eficiencia operativa y la generación de valor sostenible.

Lejos de concebirse como un mero soporte técnico, la función de TI ha evolucionado hacia un rol estratégico, donde la calidad, disponibilidad y confiabilidad de los servicios tecnológicos impactan de manera directa en los procesos centrales del negocio y en la experiencia de clientes y usuarios.

La Unidad 4 aborda esta problemática desde una perspectiva integral, focalizándose en la operación de los servicios TI como la fase del ciclo de vida donde el valor diseñado y planificado se materializa efectivamente. Es en la operación diaria donde los servicios son consumidos, evaluados y percibidos, y donde se pone a prueba la madurez de los procesos, las capacidades técnicas y la alineación entre TI y negocio.

Para un futuro Ingeniero en Sistemas de Información, comprender esta dinámica resulta esencial, ya que su rol se sitúa precisamente en la intersección entre la tecnología, los procesos y los objetivos organizacionales.

El enfoque de Gestión de Servicios de TI (ITSM) que atraviesa toda la unidad se sustenta en la adopción de marcos de buenas prácticas, principalmente ITIL, complementados por conceptos de Gobierno de TI (COBIT, ISO/IEC 38500) y Arquitectura Empresarial. Estos marcos permiten estructurar la gestión de TI a partir de procesos formales, roles definidos, métricas objetivas y mecanismos de control, garantizando que la operación no dependa de acciones reactivas o individuales, sino de capacidades organizacionales repetibles y medibles.

Dentro de este marco, la unidad desarrolla los procesos operativos fundamentales que sostienen la prestación de servicios: Gestión de Eventos y Monitoreo, Gestión de Incidencias, Gestión de Problemas, Gestión de Solicitudes, Gestión de Accesos y Gestión de Niveles de Servicio. Cada uno de estos procesos cumple un rol específico, pero interdependiente, orientado a asegurar la estabilidad operativa, minimizar interrupciones, gestionar riesgos y mantener los compromisos asumidos con el negocio a través de los SLA. La correcta articulación entre estos procesos permite pasar de un enfoque reactivo a uno proactivo, donde la detección temprana, el análisis de causa raíz y la mejora continua se convierten en prácticas habituales.

Asimismo, la unidad enfatiza el rol central de la Mesa de Servicios como función organizativa y punto Único de contacto (SPOC), responsable de canalizar la interacción entre los usuarios y la organización de TI. La Mesa de Servicios no solo actúa como ejecutora de procesos, sino también como sensor clave de la percepción del servicio, fuente de información para la toma de decisiones y habilitadora de la mejora continua.

Otro aspecto relevante abordado es el concepto de madurez en ITSM, que permite evaluar el grado de evolución de la organización TI, desde modelos básicos orientados al control de costos hasta niveles avanzados donde TI se posiciona como socio estratégico del negocio, Esta visión proporciona un marco para diagnosticar situaciones actuales, identificar brechas y planificar la evolución de capacidades operativas.

En síntesis, esta unidad propone una visión sistémica de la Gestión Operativa de Servicios TI, donde personas, procesos, tecnología y datos se integran para asegurar que los servicios tecnológicos cumplan su propósito fundamental: habilitar los procesos de negocio con niveles adecuados de calidad, costo y riesgo, alineando la operación diaria con los objetivos estratégicos de la organización.

## Modelo de Prestador de Servicios TI

Clientes
[IMAGEN 1] La imagen muestra un modelo conceptual de alineación estratégica entre el negocio y las Tecnologías de la Información (TI), organizado en una arquitectura multinivel donde cada capa representa un dominio funcional dentro de la organización. La representación enfatiza la interdependencia entre clientes, procesos de negocio y la infraestructura tecnológica.

En la capa superior, se visualizan usuarios finales (clientes), que consumen servicios habilitados por procesos digitalizados.

La capa intermedia representa el core operacional del negocio, donde se observan operadores trabajando sobre aplicaciones corporativas. Esta capa actúa como middleware funcional, integrando Servicios y productos del negocio, ejecutados mediante aplicaciones empresariales. Los Procesos del negocio, son ejecutados a través de ERP, CRM, BPM, SCM, y otros sistemas verticales.

La capa inferior muestra explícitamente Servidores, data centers, racks y equipamiento físico, indicando la infraestructura on-premise. Aquí el Personal técnico monitorea los sistemas núcleo del negocio. Esta capa constituye

- La infraestructura tecnológica (hardware, redes, almacenamiento, sistemas operativos).

- Plataformas que soportan la ejecución de las aplicaciones del negocio.

- Los servicios de TI, que proveen disponibilidad, continuidad y seguridad operacional.

Este modelo es consistente con marcos referenciales como:

- COBIT, en su enfoque de alineación estratégica.
- TOGAF, en su estructura de dominios (Business, Application, Data,

Technology).

- ITIL, en la provisión y soporte de servicios.

En definitiva, se representa un modelo tridimensional de arquitectura empresarial, donde:

- La infraestructura tecnológica provee capacidades.
- Los servicios TI habilitan procesos de negocio.

- Los procesos del negocio generan valor.

- Los clientes consumen ese valor a través de servicios digitales.

En este esquema conceptual, la TI deja de ser un soporte pasivo y pasa a ser un habilitador estratégico del negocio.

[IMAGEN 2]

- Modelo de Prestador de Servicios TI
- Proveedor
- de Servicios TI

La imagen representa un modelo que describe como opera un Proveedor de Servicios de Tecnologías de la Información (TI) En el lado izquierdo, se identifican las fuentes de requerimientos que impulsan la operación del proveedor:

- Necesidades de los usuarios, relacionadas con funcionalidad, performance y disponibilidad de los servicios.
- Necesidades del negocio, centradas en eficiencia operativa, reducción de costos y habilitación de nuevos modelos operativos.
- Necesidades de los stakeholders, que abarcan cumplimiento normativo, transparencia, métricas e impacto organizacional.
- Necesidades tecnológicas, tales como actualización tecnoldégica, capacidad, seguridad y continuidad operativa.

Estos insumos representan el conjunto de demandas que debe absorber el proveedor para diseñar, operar y mejorar sus servicios. Funcionan como elementos que disparan procesos de planificación, análisis de impacto, evaluación de capacidades, diseño de soluciones y gobernanza TI.

En el centro del modelo, el proveedor de servicios TI se presenta como un sistema de transformación que integra y gestiona estos requerimientos mediante su estructura operacional. Esta estructura descansa en cuatro pilares fundamentales:

- Personas y Procesos: incluye recursos humanos, competencias técnicas, procesos ITIL, procedimientos operativos estándar (SOP), flujos de trabajo de soporte y prácticas de mejora continua.

- Clientes y Usuarios: considerados como entidades con expectativas funcionales y de experiencia; son el punto central de la entrega de valor.

- Tecnologías y Activos: contempla plataformas, aplicaciones, infraestructura, redes, herramientas de monitoreo y activos gestionados bajo prácticas de ITAM/ITSM.

- Datos e Información: abarca repositorios de información, métricas, información de configuración (CMDB), bases de conocimiento y sistemas analiticos.

Estos pilares conforman la capacidad habilitadora del proveedor, determinando su nivel de madurez, su capacidad de respuesta y la calidad de los servicios entregados.

En el lado derecho, se presentan los resultados esperados que se generan a partir del accionar del proveedor de servicios TI, los cuales representan la creación de valor para la organización:

- Usuarios satisfechos, reflejo directo de la calidad del servicio, la experiencia de uso y el cumplimiento de SLA/OLA.
- Mejoras en los procesos del negocio, consecuencia de la digitalización, automatización y optimización de servicios y aplicaciones.
- Stakeholders satisfechos, producto de la alineación estratégica, cumplimiento de KPI, gobernanza adecuada y retorno de inversión tecnológica.
- Nuevos servicios, aplicaciones y tecnologías, que surgen como parte del ciclo continuo de innovación, actualización tecnológica e integración de capacidades emergentes.

El modelo describe la operación de un proveedor de servicios TI como un ecosistema de gestión integral, donde las necesidades del entorno se transforman en valor organizacional a través de capacidades técnico-operativas. La estructura permite visualizar la logica de funcionamiento basada en marcos como ITIL, COBIT y la Arquitectura Empresarial, destacando la importancia de la alineación, la madurez y la mejora continua en la prestación de servicios. Esta representación sintetiza la función central del proveedor de TI como habilitador estratégico de resultados de negocio.

Gestión de Servicios de TI IT Service Management (Gestión de los Servicios TI) define procesos y procedimientos para la prestación y el soporte de servicios de IT de calidad dentro de los costes permitidos, que soportan a su vez los procesos de negocio de la organización Objetivos:

- Alinear los servicios de TI con las necesidades presentes y futuras del negocio
- Mejorar la calidad del servicio de IT en su totalidad
- Reducir a largo plazo el costo de provisión y soporte del servicio

## Cuál es el foco de la Gestión de los servicios TI ?

[IMAGEN 3] 
El objetivo central del modelo es evidenciar que Gestión de Servicios de TI (IT Service Management, ITSM) no se concentra exclusivamente en la infraestructura tecnológica, sino en cdmo los servicios TI posibilitan y potencian los procesos del negocio, generando valor estratégico y operacional.

La imagen presenta una estructura organizada en capas, ordenadas desde elementos puramente tecnológicos hacia componentes de valor de negocio. La capa inferior, denominada Technology, representa las plataformas técnicas fundamentales:

hardware, redes, sistemas operativos, middleware y servicios de base. Encima de esta se ubica Tools, que agrupa sistemas de soporte como plataformas de monitoreo, automatización, ITAM, CMDB, ticketing y herramientas de orquestación.

Ambas capas conforman el núcleo tecnológico, necesario pero insuficiente por si mismo para crear valor para el negocio.

Las capas superiores introducen elementos operativos y procesuales. Tasks y Activities representan el trabajo técnico cotidiano y las acciones estandarizadas que conforman la operación de TI.

A continuación, IT Processes refleja la formalización de las actividades mediante procesos alineados a marcos como ITIL, tales como Gestión de Incidentes, Problemas, Cambios, Configuración y Niveles de Servicio. Estas capas definen la estructura operativa que permite gestionar TI de manera controlada, repetible y medible.

El foco real de ITSM se identifica en las capas resaltadas en la imagen: IT Services y Business Processes. En esta zona, el modelo evidencia que el objetivo principal de la gestión de servicios es asegurar que los servicios TI —definidos como capacidades que entregan valor mediante la fácilitación de resultados del cliente— estén alineados y sean coherentes con los procesos del negocio que soportan.

La relación entre servicios TI y procesos del negocio es el punto donde TI deja de ser un proveedor de tecnología para convertirse en un habilitador estratégico.

En la parte derecha, un diagrama complementario refuerza la misma lógica: la estructura de valor del negocio se articula a través de una interacción entre actividades de negocio, actividades TI, actividades de infraestructura y recursos tecnológicos. Sobre este conjunto actúan tres capas de gestión: Business Service Management, IT Service Management e IT Systems Management, mostrando como cada una se relaciona con distintos niveles de valor entregado tanto al negocio como aTl.

El eje horizontal de valor demuestra que, a medida que ascendemos desde tecnología hacia procesos de negocio, aumenta la contribución de TI al logro de objetivos organizacionales. Esto subraya que el foco del ITSM no es la administración técnica de infraestructura, sino la gestión integral de servicios como mecanismos que habilitan procesos críticos de negocio, optimizan la productividad, reducen riesgos operativos y aseguran el cumplimiento de niveles de servicio específicos.

En síntesis, la imagen posiciona claramente el foco de la Gestión de Servicios TI en la intersección entre los servicios TI y los procesos del negocio, demostrando que el propósito estratégico de ITSM es asegurar que la tecnología, los procesos operativos y las capacidades organizativas converjan para entregar valor real al negocio y mejorar su desempeño. Esta visión es coherente con los principios de ITIL, COBIT y la Arquitectura Empresarial orientada al valor.

## Relación Gobierno TI-Gestión TI

[IMAGEN 4]

La imagen presenta un modelo conceptual que explica la interacción estructural entre el Gobierno de TI (IT Governance) y la Gestión de TI (IT Management) dentro de una organización. Este esquema destaca cómo ambas funciones, aunque complementarias, operan a niveles distintos: el gobierno de TI orientado a la dirección estratégica y la gestión de TI enfocada en la ejecución operativa. La representación integra de manera clara los principios de marcos como COBIT, ITIL y ISO/IEC 38500, los cuales establecen la separación y articulación entre “dirigir” y “gestionar” TI como una práctica esencial para generar valor, reducir riesgos y garantizar cumplimiento.

En la parte superior se encuentra la capa de Gobierno de TI, conformada por tres funciones clave: Dirigir, Evaluar y Monitorear, que enmarcan el ciclo de toma de decisiones estratégicas.

- Dirigir implica definir prioridades, políticas, expectativas de desempeño y marcos de actuación.
- Evaluar refiere al análisis de condiciones externas, internas, riesgos, recursos, capacidades y desempeño historico.
- Monitorear consiste en el seguimiento sistémico de resultados, cumplimiento, indicadores críticos y desviaciones respecto de lo planificado.

Esta capa opera a nivel estratégico y es responsabilidad de roles como CIO, comité de TI, dirección ejecutiva o áreas de gobierno corporativo. Su propósito es asegurar que la TI esté alineada con el negocio, que se gestione adecuadamente el riesgo tecnológico y que las inversiones generen valor.

La sección inferior representa la Gestión de TI, orientada a la ejecución táctica y operativa de las decisiones provistas por el gobierno. Se presenta dividida en dos grandes dominios:

- Iniciativas y Proyectos TI, que incorporan gestión de portafolio, proyectos de innovación, actualización tecnológica, implementación de soluciones y evolución de capacidades. Esta sección se relaciona con metodologias como

PMI, PRINCE2, Agile y DevOps, según el contexto.

- Operación de los Servicios TI, que incluye la entrega y soporte continuo de servicios mediante procesos estructurados (incident management, change management, service request, problem management, availability management, capacity management, entre otros). Este dominio se enmarca principalmente en ITIL y define la forma en que se sostiene la operación diaria y la experiencia del usuario final.

Lainteracción entre ambas capas esta representada por flechas que muestran un flujo bidireccional: el Gobierno de TI establece directrices que guian proyectos y operación, mientras que la Gestión de TI provee información operacional y resultados, retroalimentando el proceso de evaluación y monitoreo. Esto configura un ciclo continuo de mejora y control, donde decisiones estratégicas se apoyan en datos operativos y los servicios se ajustan a las prioridades del negocio.

El elipse amarillo destaca la idea central del modelo: la Gestión de TI es responsable tanto de la ejecución de proyectos como de la operación de servicios, y ambas actividades deben estar alineadas a lo dirigido por el Gobierno de TI. No se trata de funciones aisladas, sino interdependientes dentro de un Único modelo integrado.

En síntesis, la imagen muestra un modelo integrado de Gobierno + Gestión de TI, donde el gobierno se orienta al “qué y por qué”, mientras que la gestión ejecuta el “como”. Este modelo garantiza que las TI operen de manera controlada, alineada al negocio y con una gobernanza efectiva que permita maximizar el valor generado por los servicios y proyectos tecnológicos.

## Gestión de Servicios de TI

[IMAGEN 5]

Este diagrama refleja que la Gestión de Servicios de TI depende de la integración equilibrada de cuatro componentes críticos:

- Personas: Las habilidades, competencias y la cultura organizacional determinan cómo se entregan los servicios.

- Procesos: Definen los pasos, roles y responsabilidades para ejecutar y controlar los servicios.

- Productos / Tecnología: Incluyen las herramientas, plataformas y tecnologías necesarias para soportar los servicios de TI.

- Partners: Organizaciones externas que proveen servicios o capacidades que complementan los recursos internos.

El modelo sugiere que estos elementos deben trabajar de forma integrada para alcanzar una entrega de servicios de TI eficaz y alineada a las necesidades del negocio.

[IMAGEN 6]

La imagen muestra el cambio de paradigma organizacional desde una estructura funcional tradicional basada en silos hacia un enfoque holístico de Gestión de Servicios de TI (ITSM).

El modelo de silos (ej. Desarrollo de Aplicaciones, DBAs, Técnicos de Redes, Control de Producción) opera con poca coordinación, como si se tratara de compartimentos estancos, es decir aislados unos de otros; enfocándose en la tarea individual más que en la entrega de valor al negocio. Esto genera ineficiencias y una perspectiva fragmentada del servicio.

La transición a la ITSM propone la entrega de servicios de punta a punta (end-to-end) mediante un Equipo Multidisciplinario. Los pilares de este nuevo modelo son la Colaboración, la Consistencia, la Confiabilidad y la Eficiencia. Este enfoque asegura que todas las funciones de TI contribuyan de manera estandarizada y coherente al valor final que recibe el cliente de negocio. La ITSM se posiciona así como el marco para transformar las capacidades técnicas en resultados de negocio gestionables.

## Servicios de TI

[IMAGEN 7]

La definición de servicio es el concepto fundacional de la ITSM. Un servicio se define como "la entrega de valor al cliente facilitandole las salidas o resultados que desea obtener sin ser el dueño ni tener la propiedad directa sobre costos específicos y sus riesgos".

Desde la perspectiva de sistemas, esto implica un proceso de abstracción. El equipo de TI gestiona la complejidad subyacente (el costo y el riesgo) de los activos y procesos de soporte, permitiendo que el cliente se enfoque únicamente en el resultado o el valor funcional (ej. "capacidad de facturación electrónica" en lugar de "servidor de base de datos"). El valor se genera cuando la tecnología soporta un proceso de negocio específico, y la gestión se orienta a asegurar que esa funcionalidad de negocio se entregue de manera confiable.

## Cómo se producen los Servicios TI?

[IMAGEN 8]

Esta imagen presenta el modelo de producción de un Servicio de TI como la combinación sinérgica de dos componentes esenciales: Activos TI y Procesos TI.

- Activos TI (Capacidades y Recursos): Son los componentes técnicos y lógicos que habilitan el servicio, incluyendo hardware (Servidores, Redes, UPS, A/A), software (Aplicaciones de Negocio, Bases de Datos) y datos.
- Procesos TI (Gestión y Control): Son las actividades estructuradas que aseguran el correcto funcionamiento, disponibilidad y evolución de los activos.

Incluyen procesos como Gestión de Incidencias, Gestión de Cambios, Gestión de Disponibilidad y Gestión de Proyectos.

La conjunción de Activos y Procesos permite entregar Servicios TI para clientes que soportan funciones críticas del negocio (ej. facturación, finanzas). Este modelo subraya que el valor no reside solo en la tecnología, sino en la manera disciplinada y repetible (proceso) en que esta se utiliza.

## Qué es un proceso TI?

[IMAGEN 9]

Un proceso es una secuencia lógica de actividades diseñada para transformar un conjunto de Entradas previamente definidas en Productos u objetivos específicos. En el contexto de TI, la estandarización por procesos es clave para la escalabilidad y la calidad.

Los elementos fundamentales que constituyen un proceso incluyen: - Roles y Responsabilidades: Quién realiza la acción (ej. Dueño, Gestor).

- Herramientas: Sistemas de soporte que automatizan o registran las actividades (ej. un Service Desk).
- Controles de Gestión: Mecanismos para asegurar que las actividades se realicen según lo planeado y se alcancen los resultados.

Desde un punto de vista predictivo, se establece que "Un proceso no garantiza el resultado, garantiza la posibilidad del resultado". Esto resalta la importancia de la ejecución, el monitoreo y la Mejora Continua para transformar la posibilidad en realidad consistente.

## Roles Claves asociados a procesos TI

[IMAGEN 10]

Para asegurar la gobernanza y la ejecución de un proceso de TI, se definen dos roles principales con responsabilidades distintas:

- Dueño del Proceso (Process Owner): Es el responsable estratégico y responde por la integridad y el diseño del proceso. Sus funciones incluyen: asegurar que el proceso sea ejecutable y gestionable, velar por el balance de las 3Ps (Proceso,

Personas, Productos) y garantizar que las herramientas de soporte estén

- Gestores del Proceso (Process Managers): Son responsables de la gestión operacional y la ejecución diaria. Su foco es táctico: planifican, coordinan las actividades, ejecutan y revisan los resultados específicos del proceso.

Esta clara división (Diseño/Estrategia vs. Ejecución/Tactica) evita conflictos de interés y asegura que tanto la eficiencia operativa como el alineamiento estratégico del proceso sean monitoreados por diferentes niveles de responsabilidad.

## ITSM - Visión General

[IMAGEN 11]

Los proveedores de servicios entregan valor a sus consumidores al facilitarles el logro de resultados y, al hacerlo, asumir algunos de los riesgos y costos asociados.

Este diagrama utiliza una balanza para ilustrar el concepto central de ITSM: la entrega de Valor. El valor no es solo la tecnología (Producto), sino el balance entre los resultados fácilitados al cliente y los costos/riesgos que el proveedor asume en su nombre.

Componentes de la Balanza El balance del valor requiere que los beneficios superen a los costos y riesgos asumidos:

- Lado Izquierdo (Costo/Inversión): Representa lo que se invierte y se incurre para ofrecer el servicio.

- Costs introduced: La cantidad de dinero gastada en actividades o recursos específicos.
- Risks introduced: El evento posible que podría causar dafio o dificultar el logro de los objetivos.
- Affected outcomes: Los resultados no deseados o negativos generados por la provisión.
- Lado Derecho (Valor/Beneficio): Representa el valor entregado y el riesgo/costo reducido para el cliente. co Supported outcomes: El resultado deseado que obtiene un interesado por uno o más productos.
- Costs removed: Ahorros o reducción de costos para el cliente.
- Risks removed: Riesgos operativos que son transferidos del cliente al proveedor de servicios.
- Producto: Un entregable tangible o intangible de una actividad (ej. un servidor virtual, una aplicación).
- Resultado (Supported Outcome): El beneficio funcional que el cliente obtiene del producto.

El mensaje clave es que los proveedores de servicios entregan valor al facilitar el logro de resultados a sus consumidores, asumiendo algunos de los riesgos y costos asociados. Se debe enfocar el diseño de los servicios en maximizar los Supported outcomes, mientras se gestionan eficientemente los Costs/Risks introduced.

## Operación de los Servicios

## Qué es la Operación de Servicios TI ??

[IMAGEN 12]

La Operación de Servicios TI es la fase del ciclo de vida del servicio donde se ejecuta el valor real y donde los diseños se ponen a prueba; es esencialmente "gestionar la diaria". Es el punto de contacto donde el cliente percibe y consume el valor de TI.

Los Fundamentos de la Operación de Servicios se centran en:

- Provisión de Valor: Ejecutar los servicios para habilitar el negocio y permitirle alcanzar sus objetivos, optimizando el costo y la calidad.
- Mantenimiento Operativo: Asegurar el funcionamiento efectivo de los componentes tecnológicos y la ejecución de las actividades de control de gestión.
- Optimización: Buscar la Mejora Continua a corto y largo plazo, lo que implica la mejora incremental y la optimización del funcionamiento.

La Operación busca mantener la satisfacción del usuario y cumplir con los SLA (Acuerdos de Nivel de Servicio) a un costo aceptable.

## Ejemplos de Operación de Servicios TI

## Modelo de Relación de Servicios de TI

[IMAGEN 13]

La imagen representa un modelo integral de provisión, gestión y control de servicios de TI, estructurado desde la capa operativa hasta la percepción final del usuario. En la parte superior se ubica la User Community, compuesta por distintos clientes internos, quienes consumen los servicios especificados en el Service Catalog. Este catálogo funciona como referencia formal de los servicios disponibles y de los compromisos asociados.

Los usuarios interactúan con los Business Services, que son servicios orientados al negocio y cuya calidad se evalúa mediante SLAs (Service Level Agreements). Los SLAs definen los niveles de servicio comprometidos —o “promises”— y permiten comparar las expectativas previas del usuario con el rendimiento real del servicio (performance). La diferencia entre desempeño percibido y expectativa determina el nivel de Service Satisfaction.

Debajo de los servicios de negocio se ubica la capa de IT Services, que agrupa los servicios técnicos necesarios para soportar los servicios de negocio. Estos servicios dependen de múltiples IT Systems, como aplicaciones, plataformas, redes o infraestructura. La calidad y disponibilidad de esos sistemas están reguladas mediante OLAs (Operational Level Agreements), que representan acuerdos internos entre diferentes áreas de soporte técnico.

Las funciones operativas se clasifican entre Internal Support (soporte interno) y External Support (soporte provisto por terceros). Las interacciones con proveedores externos están formalizadas mediante UCs (Underpinning Contracts), que establecen compromisos necesarios para garantizar que los servicios internos puedan cumplir los SLAs acordados con los usuarios.

El modelo, en su conjunto, evidencia la cadena de dependencias entre:

- 1. las expectativas del usuario,
- 2. las promesas documentadas (SLAs),
- 3. los acuerdos internos (OLAs), y
- 4. los contratos con proveedores (UCs). 

Esta estructura asegura consistencia, trazabilidad y alineación entre los servicios de TI y los requerimientos del negocio, permitiendo una evaluación clara de la satisfacción del servicio entregado.

Desafíos:

- Como conseguir efectividad y eficiencia en la operación de servicios activos
- Cómo mantener la estabilidad en operaciones, permitiendo cambios controlados en los servicios desde dos perspectivas: reactiva y proactiva
- Como mejorar de toma de decisiones en temas como disponibilidad de los servicios, control de la demanda, optimizar el uso de la capacidad, resolver problemas... Es decir, mejorar el día a día

Para buscar el *equilibrio* se requiere lo siguiente:

- Una comprensión de qué servicios son utilizados por el negocio y por qué
- Una comprensión de la importancia relativa y el impacto de esos servicios en el negocio
- Comprensión de como se utiliza la tecnología para proporcionar servicios de TI
- Participación de la operación de servicios en proyectos CSI que buscan identificar maneras de entregar más, aumentar la calidad del servicio y reducir costos 
- Procedimientos y manuales que describen el papel de las operaciones de TI tanto en la gestión de la tecnología como en la prestación de servicios de TI 
- Un conjunto claramente diferenciado de métricas para informar al negocio sobre el logro de los objetivos del servicio; E informar a los gerentes de TI sobre la eficiencia y eficacia de la operación de servicio 
- Todo el personal de operaciones de TI entiende exactamente cómo el desempeño de la tecnología afecta la prestación de servicios de TI y, a su vez, como afectan al negocio y a las metas de negocio 
- Una estrategia de costes orientada a equilibrar las necesidades de diferentes unidades de negocio 
- Una estrategia de ROI basada en el valor, y no en los costos 
- Participación del personal de operaciones de TI en las etapas de transición del diseño y servicio del servicio del ciclo de vida del servicio 
- Contribución y retroalimentación a CSI para identificar áreas en las que existe un desequilibrio y los medios para identificar y hacer cumplir mejoras 
- Un claro plan de comunicación y formación para las empresas. Si bien muchas organizaciones son buenas en el desarrollo de planes de comunicación para proyectos, esto a menudo no se extiende hasta su etapa operacional.

CSI= Continual Service Improvement 

Procesos/Prácticas de la Gestión TI

[IMAGEN 14]

Los procesos de gestión ubicados en la base del modelo son fundamentales para garantizar tanto el éxito de las iniciativas de TI como el funcionamiento estable de los servicios tecnológicos. Estos procesos sirven como soporte estructural, permitiendo controlar, evaluar y ejecutar actividades técnicas de forma ordenada y segura.

Procesos de Gestión que Impactan en Iniciativas y Proyectos TI Las iniciativas y proyectos tecnológicos se apoyan en tres procesos clave:

- Gestión de la Demanda y Requerimientos: Permite captar, analizar y priorizar las necesidades del negocio. Asegura que los proyectos respondan a necesidades reales y estén correctamente fundamentados.
- Gestión de Proyectos: Coordina la planificación, seguimiento y control del alcance, tiempos, costos y riesgos. Es el proceso que garantiza la ejecución ordenada y la entrega de resultados dentro de los parámetros acordados.
- Gestión de Aplicaciones: Administra el ciclo de vida de las aplicaciones y define estándares técnicos que los proyectos deben seguir. Además, asegura la correcta integración con los sistemas existentes y la continuidad funcional.

Estos procesos combinados permiten que los proyectos se desarrollen con una base solida, minimizando riesgos y asegurando una alineación técnica adecuada.

Procesos de Gestión que Impactan en la Operación de los Servicios TI La operación diaria de los servicios tecnológicos requiere estabilidad, disponibilidad y una rápida respuesta ante fallas o solicitudes. Para esto intervienen varios procesos fundamentales:

- Gestión de Eventos y Monitoreo: Supervisa continuamente la infraestructura para detectar fallas potenciales. Facilita la operación proactiva y reduce incidentes críticos.

- Gestión de Disponibilidad: Se encarga de asegurar que los servicios cumplan sus niveles de funcionamiento y tiempo activo. Evalúa puntos críticos y planifica mantenimientos.

- Gestión de Incidencias y Problemas: Restaura rápidamente el servicio ante fallas y analiza causas raíz para evitar recurrencias. Reduce el impacto en los usuarios.

- Gestión de Solicitudes y Accesos: Administra pedidos estándar y controla los accesos a sistemas. Contribuye a la seguridad y a la eficiencia operativa.

- Gestión de Cambios: Ordena y autoriza modificaciones técnicas. Minimiza riesgos al introducir nuevas versiones, configuraciones o actualizaciones.

Estos procesos garantizan la continuidad operativa, evitando interrupciones y manteniendo la experiencia del usuario final.

En conclusión, los procesos de gestión inferiores constituyen la base que permite ejecutar proyectos de TI de forma controlada y operar servicios con estabilidad. Su correcta integración asegura un equilibrio entre innovación y continuidad operativa, permitiendo que la función de TI aporte valor real y sostenible a la organización.

#Gestión de Eventos y Monitoreo
## Introducción

Una vez que el servicio está operando es necesario monitorizar todos los sucesos importantes que se produzcan para poder anticiparse a los problemas, resolverlos o incluso prevenirlos. Esta función representa una tarea en si misma y por tanto constituye un proceso independiente dentro del ciclo de vida: la Gestión de Eventos

- Evento: Todo suceso detectable que tiene importancia para la estructura de la organización TI, para la prestación de un servicio o para la evaluación del mismo.

Ejemplo de eventos:

- Eventos que indican que el servicio está operando con normalidad.
- Eventos que indican una excepción.
- Eventos que indican una operación inusual pero no excepcional, y que requieren una monitorización exhaustiva.

Los objetivos de la Gestión de Eventos y Monitoreo son:

- Detectar y escalar condiciones de excepción para así contribuir a una operación normal del servicio
- Posibilitar la comparación entre el rendimiento real del servicio con los estándares de diseño y los SLAs.
- Contribuir a la Mejora Continua del Servicio mediante informes de mejora.
- Ayudar a la detección temprana de incidentes y reaccionar eficientemente.

[IMAGEN 15]

## Beneficios: 
Algunas de las ventajas que una correcta Gestión de Eventos y Monitoreo aporta a la organización TI son:

- Ayuda a la detección temprana de incidentes, llegando incluso a evitar que éstos se manifiesten a los usuarios.
- Además, la coordinación directa con otros procesos hace posible que éstos reaccionen con mayor rapidez, resultando en una mayor eficiencia de toda la organización TI.
- Posibilita la monitorización automatizada de determinadas actividades. Es más barata que una monitorización en tiempo real y disminuye considerablemente el período de inactividad del servicio que media entre la aparición del incidente y su resolución definitiva.
- Proporciona la base para las operaciones automatizadas, que incrementan la eficiencia y descargan de trabajo a los recursos humanos que, así, pueden ser empleados en otras tareas como diseñar nuevas funcionalidades, etc.

## Gestión de Incidencias

Incidencia: Cualquier evento que no forma parte de la operación estándar de un servicio y que causa, o puede causar, una interrupción o una reducción de calidad del mismo.

Incidencia de Seguridad: Acceso físico o lógico no autorizado a sistemas de información, redes o datos. Intentos internos o externos por acceder a sistemas de información, redes o datos.

- Virus, gusanos, virus troyanos que afectan los procesos de negocio.
- Correos falsos
- Desastres (terremotos, inundaciones, incendios, errores humanos, etc..)
- Defalcos o Fraudes de información, Sabotajes

**Solicitudes de Servicio:** Cualquier requerimiento iniciado por un usuario, que no es clasificado como una falla o potencial falla en la Infraestructura de IT.

**Error Conocido:** Un Incidente cuya causa se ha diagnosticado con éxito y para el cual se ha identificado una Solución Definitiva o Temporal.

## Objetivos de Gestión de Incidencias

El Objetivo principal de la Gestión de Incidencias es restablecer el servicio al cliente lo más pronto posible, a través de soluciones temporales o definitivas.

Alcance de Gestión de Incidencias
- Manejo de Incidencias
- Manejo de Incidencias de Seguridad
- Manejo de Incidencias Mayores

La administración de incidentes incluye cualquier evento que interrumpa, o que podría interrumpir, un servicio. Esto incluye eventos que son comunicados directamente por los usuarios, ya sea a través de la mesa de servicio o a través de una interfaz desde la gestión de eventos hasta las herramientas de gestión de incidentes.

Los incidentes también pueden ser reportados y / 0 registrados por el personal técnico (si, por ejemplo, advierten algo adverso con un hardware o un componente de red, pueden informar o registrar un incidente y remitirlo al servicio de asistencia). Esto no significa, sin embargo, que todos los eventos son incidentes. Muchas clases de eventos no están relacionadas con interrupciones en absoluto, pero son indicadores de funcionamiento normal o son simplemente informativos. Aunque los incidentes y las solicitudes de servicio se comunican al servicio de asistencia técnica, esto no significa que sean iguales.

Las solicitudes de servicio no representan una interrupción del servicio acordado, sino que son una forma de satisfacer las necesidades del cliente y pueden estar respondiendo a un objetivo acordado en un SLA. Las peticiones de servicio son atendidas por el proceso de cumplimiento de solicitudes.

La **Gestión de Incidencias** tiene como objetivo principal restablecer el servicio al cliente lo antes posible. La diapositiva detalla el ciclo de vida o Estado de una Incidencia:

- Nuevo / Asignado / En curso / Pendiente: Fases de gestión activa hasta la resolución.
- Resuelto: Se ha encontrado una solución, pendiente de la aprobación del cliente. 
- Cerrado / Cancelado: Fases finales que confirman la restauración del servicio y el cierre administrativo.

Para una gestión y escalado eficientes, la incidencia debe registrarse con Información Crítica, incluyendo:

- Priorización: Determinada por Urgencia (rapidez de la necesidad) e Impacto (efecto en el negocio).
- Clasificación: Categoria funcional (ej. Redes, Aplicaciones). 
- CI Relacionada: El Elemento de Configuración específico afectado (clave para el análisis posterior de Problemas).
- Descripción de Síntomas: Lo que el usuario experimenta. 

La calidad de estos datos es fundamental para el diagndéstico y el correcto encaminamiento a las lineas de soporte adecuadas.

## Relación entre incidencia y disponibilidad: 

[IMAGEN 16]

Este diagrama establece la relación crítica entre la Gestión de Incidencias y la Disponibilidad del servicio. La disponibilidad se define como la capacidad de un servicio o elemento de configuración (Cl) para operar cuando es requerido.

Métricas Fundamentales de Disponibilidad El ciclo de vida de la falla permite calcular métricas clave de ingenieria y gestión:

- Time Between System Incidents (TBSI): Representa el tiempo total entre dos incidentes consecutivos. Se utiliza para calcular el MTBF (Mean Time Between Failures), una métrica de fiabilidad. 
- Uptime (Time between failures): Es el período operativo durante el cual el servicio está funcionando correctamente y disponible para el usuario.
- Downtime (Time to restore): Es el tiempo total que el servicio no esta disponible, desde que ocurre el incidente hasta que se alcanza el Restore Point. Se utiliza para calcular el MTTR (Mean Time To Restore Service), una métrica de mantenimiento.

###Desglose del Ciclo de Vida del Incidente (Downtime)

El *Downtime* se descompone en fases secuenciales que la Gestión de Incidencias debe optimizar:

- Detection time: Tiempo transcurrido hasta que la falla es identificada, ya sea por monitoreo automático (proactivo) o por el usuario (reactivo).
- Resolution time: Tiempo total desde la detección hasta el restablecimiento del servicio. Este se subdivide en:
	- Diagnosis time: Tiempo dedicado a identificar la causa o el camino hacia la solución.
	- Repair time: Tiempo de aplicación de la solución (ej. reemplazo de hardware, parcheo de software).
	- Recovery time: Tiempo para reiniciar sistemas y validar que el servicio esta funcional.

La meta es minimizar el Resolution time y el Downtime total para maximizar el Uptime y, por ende, la disponibilidad del servicio.

## Estado de una Incidencia (ejemplo)

|Nuevo: |La incidencia no esta asignada.| 
|Asignado: |Se asigné la incidencia a un grupo de soporte o a un individuo pero aún no se la reconoció.|
|En curso: |Se acepto la asignación y el recurso asignado se encuentra trabajando para resolverla.|
|Pendiente: |Se suspendió provisionalmente el trabajo en la incidencia.|
|Resuelto: |Se llegó a una resolución para restaurar el servicio y ésta se encuentra a la espera de la aprobación del cliente.|
|Cerrado: |Una resolución o solución temporal restauré el servicio y el cliente aprobó la resolución.|
|Cancelado: |Ya no se requiere restauración del servicio.|

La información necesaria para cada incidente puede incluir:

- Número de referencia único
- Clasificación de incidentes
- Urgencia / Impacto incidente
- Priorización de incidentes
- Fecha / hora registrada
- Nombre / Identificación de la persona y / 0 grupo que registra el incidente
- Método de notificación (teléfono, automático, correo electrénico, en persona,
- Descripción de los síntomas
- Estado del incidente (activo, en espera, cerrado, etc.)
- Grupo de apoyo / persona a la que se asigna el incidente
- Problema relacionado / error conocido
- Actividades emprendidas para resolver el incidente y cuando éstas tuvieron lugar
- Fecha y hora de la resolución
- Categoría de cierre
- Fecha y hora de cierre

###Beneficios:
Los principales beneficios de una correcta Gestión de Incidencias incluyen:

- Mejorar la productividad de los usuarios.
- Cumplimiento de los niveles de servicio acordados en el SLA.
- Mayor control de los procesos y monitorización del servicio.
- Optimización de los recursos disponibles.
- Una CMDB más precisa, pues se registran los incidentes en relación con los elementos de configuración.
- Y principalmente: mejora la satisfacción general de clientes y usuarios.

# Matriz de Impacto y Urgencia

[IMAGEN 17]

La imagen muestra una Matriz de priorización basada en Impacto y Urgencia, utilizada comtnmente para la toma de decisiones operativas y tácticas dentro de áreas de sistemas, ya que permite asignar prioridades objetivas a eventos, incidentes El eje vertical corresponde al Impacto, y se refiere al grado de afectación que un incidente o requerimiento produce sobre el negocio, los usuarios o la infraestructura tecnológica (por ejemplo, indisponibilidad de un sistema crítico, degradación del servicio o afectación a un proceso core).

El eje horizontal representa la Urgencia, medida en tiempo (horas), indicando el margen disponible para actuar antes de que el impacto se materialice o escale. A menor tiempo disponible, mayor urgencia. Este enfoque temporal es tipico en la definición de SLA (Service Level Agreements) y OLA (Operational Level Agreements).

###Zonas de priorización 
La matriz se encuentra segmentada en cuatro zonas diagonales, identificadas por colores y una leyenda asociada:

- **Crítica:** Alta combinación de impacto y urgencia. Corresponde a eventos que requieren atención inmediata, escalamiento automático y asignación prioritaria de recursos. Ejemplo: caida total de un sistema productivo crítico.
- **Alta:** Incidentes con impacto relevante pero con algo más de margen temporal. Requieren planificación rápida y seguimiento continuo.
- **Media:** Situaciones con impacto o urgencia moderados. Suelen resolverse mediante colas de trabajo priorizadas.
- **Baja:** Bajo impacto y baja urgencia. Pueden ser gestionadas de manera programada o diferida

La disposición diagonal de las zonas refleja que la prioridad no depende exclusivamente de una sola variable, sino de la relación combinada entre impacto y urgencia, alineándose con buenas prácticas de frameworks como ITIL.

## Puntos de referencia

Los puntos marcados en la matriz ejemplifican casos concretos de incidentes o requerimientos, ubicandolos según su nivel de impacto y el tiempo máximo tolerable de resolución. Las lineas punteadas indican cómo un evento puede evaluarse objetivamente dentro del modelo, reduciendo la subjetividad en la asignación de prioridades.

## Aplicación práctica 
Desde una perspectiva informática de gestión, esta matriz es una herramienta fundamental para:

- Definir reglas de priorización automática en herramientas de Service Desk.
- Establecer criterios formales de escalamiento.
- Alinear la gestión operativa de TI con los objetivos del negocio.
- Optimizar el uso de recursos técnicos y humanos. 
- Mejorar el cumplimiento de SLA y la percepción de calidad del servicio.

Problema: causa aun no identificada, de una serie de incidentes o un incidente aislado de importancia significativa.

**Error conocido:** Un problema se transforma en un error conocido cuando se han determinado sus causas.

**Escalamiento:**
- Escalamiento funcional: Se requiere el apoyo de un especialista de más alto nivel de conocimiento para resolver el incidente.
- Escalamiento jerárquico: Debemos acudir a un responsable de mayor autoridad para tomar decisiones que se escapan de las atribuciones asignadas

**Solución Temporal:** Método Temporal para resolver un incidente, el cual permite restablecer el servicio al cliente pero no se resuelve la Causa Raíz que ocasiona el incidente o error.

**Causa Raíz:** Se define como la causa real que interrumpe el servicio al cliente o podría causar interrupción.

## Objetivos de Gestión de Problemas

La **Gestión de Problemas** tiene como objetivo reducir la interrupción del negocio a largo plazo mediante la identificación proactiva y el análisis de la Causa Raíz de incidentes (diferenciándose de la Gestión de Incidencias, que busca la solución temporal).

[IMAGEN 18]
!(/imagenes/Unidad-4/imagen-18.png)

La imagen representa el funcionamiento del proceso de Gestión de Problemas dentro de un entorno de gestión de servicios TI, mostrando sus componentes principales y su interacción con otros procesos clave. La Gestión de Problemas tiene como objetivo identificar causas raíz de incidentes, prevenir su recurrencia y minimizar el impacto de fallas en los servicios.

En el centro del modelo se encuentran los dos subprocesos fundamentales: Control de Problemas y Control de Errores.

- El Control de Problemas se encarga de registrar, clasificar y analizar los problemas detectados, generalmente derivados de incidentes repetitivos o de alto impacto.
- El Control de Errores gestiona los errores conocidos, analiza soluciones temporales (workarounds) y valida la información necesaria para la corrección definitiva.

Los Errores Conocidos se documentan en la PKB (Problem Known Base), una base de datos que almacena causas raíz identificadas, soluciones temporales y antecedentes técnicos. Esta base se alimenta tanto del análisis de problemas como de la información proveniente de la CMDB (Configuration Management Database), la cual contiene el inventario de componentes y relaciones de configuración relevantes para comprender el origen y el alcance de las fallas.

El proceso también genera y recibe RFCs (Requests for Change), que representan cambios solicitados para corregir errores o evitar reincidencias. Estas RFCs se envian al proceso de Gestión de Cambios, y en algunos casos influyen en la Gestión de Liberaciones, cuando la solución requiere actualizaciones de software, parches o despliegues controlados.

Asimismo, la Gestión de Problemas mantiene una relación bidireccional con otros procesos operativos.

- Con la Gestión de Incidencias, recibe información sobre incidentes recurrentes y proporciona soluciones temporales documentadas en la PKB.
- Con la Gestión de Disponibilidad, comparte datos que permiten evaluar y mejorar la disponibilidad del servicio, especialmente en servicios críticos.
- Con la Gestión de Capacidad, contribuye al análisis de rendimiento cuando los problemas se originan por saturación o recursos insuficientes.
- Con la Gestión de Nivel de Servicios, intercambia información para medir el impacto que los problemas tienen en el cumplimiento de los SLAs y definir planes de mejora.

En su conjunto, el modelo refleja como la Gestión de Problemas actúa como un proceso centralizado de análisis profundo y mejora continua, conectado con los demas procesos de operación para reducir interrupciones, mejorar la estabilidad del entorno TI y aportar información clave para la toma de decisiones técnicas.

Después de cada problema grave se debe realizar una revisión para extraer conclusiones de cara al futuro. En particular, la revisión debe analizar:

- Qué es lo que ha funcionado.
- Qué es lo que no ha funcionado.
- Qué es lo que se puede mejorar en el futuro.
- Como se puede evitar que vuelva a ocurrir el mismo problema.
- Si hay terceras partes responsables y si se necesita alguna acción de seguimiento.

Los principales beneficios de una correcta Gestión de Problemas: 

- Un aumento de la calidad general de los servicios TI.
- Se minimiza el número de incidentes. 
- Los incidentes se solucionan más rápidamente y, generalmente, en la primera linea de soporte TI, ahorrando recursos e innecesarios escalados.
- La documentación desarrollada es de gran utilidad para la Gestión de la Capacidad, Disponibilidad y Niveles de Servicio.

#Solicitudes
## Gestión de Solicitudes

El término "solicitud de servicio" se utiliza como una descripción genérica para muchos tipos diferentes de demandas que son colocadas a la organización de TI por los usuarios.

Muchos de estos son tipicamente peticiones de pequeños cambios que son de bajo riesgo, frecuentemente realizados, de bajo costo, etc. (por ejemplo, una solicitud para cambiar una contraseña, una solicitud para instalar una aplicación de software adicional en una estación de trabajo en particular, una solicitud para reubicar algunos elementos del equipo de escritorio) o puede ser solo una solicitud de información.

Su escala y la naturaleza frecuente y de bajo riesgo significa que se manejan mejor mediante un proceso separado, en lugar de permitir que se congestionen y obstruyan los procesos normales de incidencia y cambio de gestión.

El cumplimiento efectivo de las solicitudes tiene un papel muy importante en el mantenimiento de la satisfacción del usuario final con los servicios que están recibiendo y puede impactar directamente en lo bien que se percibe la TI en todo el negocio.

Los objetivos principales son: 
- Mantener la satisfacción del usuario y del cliente a través del manejo eficiente y profesional de todas las solicitudes de servicio 
- Proporcionar un canal para que los usuarios soliciten y reciban servicios estándar para los cuales una autorización y calificación predefinidas 
- Proporcionar información a los usuarios y clientes sobre la disponibilidad de los servicios y el procedimiento para su obtención 
- Obtener y entregar los componentes de los servicios estándar solicitados (por ejemplo, licencias y soportes de software) 
- Ayudar con información general, quejas o comentarios.

Los principales beneficios de la implementación del proceso de Gestión de Solicitudes en la organización TI son:

- Proporciona a las áreas de negocio un acceso rápido y efectivo a servicios estándar. Esto mejora su productividad, la calidad de los servicios comerciales y los propios productos.
- Reduce la burocracia asociada al proceso de petición de acceso a servicios nuevos o ya existentes, reduciendo asimismo los costes.
- Incrementa el nivel de control sobre los servicios al centralizar la concesión de acceso a los mismos.
- Reduce costes al centralizar la negociación con proveedores respecto al acceso alos servicios, y también al reducir el coste del soporte.

#Accesos

## Gestión de Accesos

El objetivo de la gestión de accesos es otorgar permisos de acceso a los servicios a aquellos usuarios autorizados e impedirselo a los usuarios no autorizados.

Los principales retos a que se enfrenta habitualmente la Gestión de Acceso a los Servicios TI son:

- Verificar la identidad de los usuarios. 
- Verificar que el usuario esta solicitando el acceso a un determinado servicio.
- Gestionar cambios en los requisitos de acceso de los usuarios. 
- Restringir los permisos de acceso a los usuarios no autorizados.
- Mantener una base de datos actualizada donde figuren todos los usuarios y los derechos de los que gozan.

Fuerte relación con: 
- User Life Cycle Management 
- Identity & Access Management 
- IT Security Management 

El acceso (o la limitación del mismo) se puede solicitar a través de diversos mecanismos, como:
- Una solicitud estándar generada por el departamento de Recursos Humanos, generalmente en caso de nueva contratación, promoción o abandono de la empresa.
- Una solicitud de cambio (RFC).
- Una solicitud de cambio presentada a través del proceso de gestión de peticiones.
- Una solicitud interna de una apps.

La Gestión de Acceso a los Servicios TI proporciona una serie de ventajas a la organización TI que justifican su implantación:

- Mayor garantía de confidencialidad de la información, gracias a un acceso controlado a los servicios.
- Mayor efectividad de los empleados, al minimizarse los conflictos y problemas derivados de la asignación de permisos.
- Menor probabilidad de errores en servicios críticos relacionados con la actividad de usuarios no cualificados.
- Capacidad de monitorizar el uso de los servicios y detectar casos de abuso de los mismos.
- Mayor rapidez y eficacia al revocar permisos en caso de ser necesario, algo que puede ser crítico para la seguridad en determinadas circunstancias.
- La Gestión de Acceso puede, además, ser un requisito indispensable para la adecuacioén a determinados estándares de calidad e incluso, a la legislación vigente (en el sector sanitario, por ejemplo).

# Acuerdo de Servicio

## Gestión de Niveles de Servicios (SLA) 

El SLA - Service Level Management, se encarga de negociar, acordar y documentar niveles de servicio apropiados. Además, monitorea y reporta la capacidad del proveedor de servicios de cumplir con los niveles acordados.

Contenido del SLA

- Introducción: participantes del acuerdo, título, breve descripción, signatarios, fechas (inicio, fin, revisión), alcance y cobertura, responsabilidades mutuas.
- Horario del servicio: horario en el cual es servicio es requerido (24x7, 5x8,...), procedimientos para extensión en el horario, días especiales, feriados.
- Disponibilidad: Disponibilidad dentro de los objetivos acordados, normalmente expresado en porcentajes. Por ejemplo: disponibilidad del 99.5% para enlaces Wi Max. 
- Confiabilidad: expresado como número de fallas en el servicio, o tiempo medio entre fallos (Mean Time Between Failures - MTBF) 0 tiempo medio entre incidentes del sistema (Mean Time Between System Incidents - MTBSI).
- Soporte: horas en las que se brindara el soporte (no horario del servicio), acuerdos para extensión del horario de soporte, horarios y días especiales, feriados, tiempos de respuesta ante solicitudes de soporte (i.e.: 15 min para poner el incidente en “work in progress”), tiempo para la resolución de los incidentes (i.e.: 1 hora para incidentes severity one).
- Rendimiento: referencia al volumen de trafico, número de transacciones a procesar, número de usuarios concurrentes, volumenes de datos transferidos por la red, tiempos de respuestas de transacciones (96% en 3 minutos), etc. Es importante porque permite identificar problemas de performance (i.e.:lentitud general en el public web site) generados por excesivo uso, fuera de los términos del acuerdo.
- Costos: detalles de la formulación de cobros y períodos asociados a los importes.

Otros acuerdos relacionados al SLA 
- Contratos de soporte - Underpinning Contracts (UC): contrato con un proveedor externo que cubre un servicio que la soporta la organización de IT 
- Acuerdos de nivel operacional - Operational Level Agreements (OLA): contrato interno con un área que cubre un servicio que la soporta la organización de IT or ft fay 

# Mesa de servicio TI
##MESA DE SERVICIOS 
La Mesa de Servicio (Service Desk) es una FUNCION —un equipo u organización— y no un proceso, cuyo rol es ser el Punto Único de Contacto (SPOC) para los usuarios de servicios TI.

El Objetivo Principal es establecer este SPOC para gestionar todas las solicitudes (incidencias, peticiones) y asegurar que se atiendan según los SLA.

Los Objetivos Específicos se centran en la eficiencia operativa y la satisfacción del cliente:

- Gestión Completa: Administrar el ciclo de vida completo de cada solicitud.
- Resolución en Primer Nivel: Procurar que el mayor número de solicitudes se resuelva en los primeros niveles de atención para reducir el costo y el tiempo (First Call Resolution).
- Medición: Medir la satisfacción del usuario final con los servicios, usando la Mesa como fuente de retroalimentación para la mejora. 

La Mesa de Servicio ejecuta los procesos de Gestión de Incidencias y Gestión de Solicitudes, siendo esencial para la percepción del cliente sobre el proveedor de servicios.

**IMPORTANTE: el Service Desk NO es un proceso, es una función, que ejecuta procesos!**

[IMAGEN 19] 

Estructura organizativa 
- Local: Co-ubicados dentro o físicamente cerca de la comunidad de usuarios que sirve 
- Centralizado: Reducir el número de mostradores de servicio al fusionarlos en una sola ubicación 
- Virtual: A través del uso de la tecnología, en particular de Internet, y del uso de herramientas de apoyo corporativo, es posible dar la impresión de un Servicio centralizado Único cuando de hecho el personal puede ser distribuido o localizado en cualquier número o tipo de Ubicaciones estructurales 
- Follow the sun: Algunas organizaciones globales o internacionales tal vez deseen combinar dos o más de sus Servicios de Servicio geograficamente dispersos para proporcionar un servicio de seguimiento del sol de 24 horas.

Responsabilidades:

- Registrar y administrar el ciclo de vida de cada incidente que puede afectar la operación normal del negocio.
- Pasar a los equipos de ayuda de segunda o de tercera línea para su diagnóstico y la resolución
- Si siguen quedando sin resolver más alld de su objetivo del SLA, pueden referirlos a la administración de problemas.
- Mantener al cliente informado del progreso o avisarlo de cualquier work-around que pueda permitir que continúe trabajando.

En el siguiente grafico, se muestran los procesos soportados por la Mesa de Ayuda, y su relación aproximada en la atención y resolución de incidentes, con los equipos técnicos de soporte interno Service Desk Tecnologías ITSM Consideraciones de tecnologías

[IMAGEN 20]

# Tecnologías ITSM

## Consideraciones de tecnologías

- Algunos requisitos genéricos
	- ITSM tools
	- Autoayuda
	- Flujo de trabajo o motor de proceso
	- CMS integrado
	- Tecnología de descubrimiento / despliegue / licencias
	- Control remoto
	- Utilitarios de diagnóstico
	- Informes
	- Paneles
	- Integración con la gestión de servicios empresariales

## Herramientas ITSM

[IMAGEN 21]

## Madurez ITSM

[IMAGEN 22]

**Nivel de madurez 1: Centro de costos:** los diversos departamentos de servicio de su organización operan de forma aislada y trabajan de forma independiente para administrar los costos. Estos departamentos aislados utilizan herramientas de gestión de servicios dispares, sus procesos no están documentados, son ad hoc y están desconectados. Hay operaciones de TI mínimas.

**Nivel de madurez 2: Mesa de servicio de TI:* el equipo de servicio brinda soporte a pedido con una naturaleza predominantemente reactiva. El servicio se centra en los procesos de gestión de problemas con funciones de gestión de alertas y eventos que se solicitan. El inventario del cliente esta comenzando a medirse debido a los costos y gastos generales. Existe la ambición de crear y administrar acuerdos de nivel de servicio con los clientes, con los primeros pasos para comprender el rendimiento en la gestión de incidentes con paneles básicos.

**Nivel de madurez 3: Cumplimiento del servicio:** la función de servicio se ha movido a un enfoque proactivo, con procesos y pautas establecidos en todo el negocio con propietarios designados. La colaboración aumenta con las funciones de la base de conocimientos dentro de una Única solución de gestión de servicios. Se analizan el rendimiento y las necesidades del cliente, se detectan tendencias y se establecen umbrales en paralelo con la gestión de SLA.

**Nivel de madurez 4: Alineación de servicios:** el enfoque cambia de la mera gestión de costos a enfoques centrados en el cliente en todas las actividades de servicio. El proveedor de servicios de TI puede garantizar los acuerdos de nivel de servicio con el apoyo de una amplia gestión de capacidad e informes de KPI. Los procesos de gestión de cambios y versiones son avanzados y forman parte del trabajo diario.

**Nivel de madurez 5: socio de servicios estratégicos:** la prestación de servicios de TI se vincula intrinsecamente con las estrategias comerciales con valor agregado demostrado en términos reales.

## Conclusión

El análisis integral de la Unidad 4 permite concluir que la Gestión Operativa de los Servicios de TI constituye uno de los pilares más críticos para la efectividad global de la función de TI dentro de las organizaciones modernas. La operación no es simplemente la “ejecución rutinaria” de tareas técnicas, sino el espacio donde se concreta —o se pierde— el valor prometido por la tecnología al negocio. Desde esta perspectiva, la madurez operativa de TI se convierte en un factor determinante para la competitividad, la continuidad y la resiliencia organizacional.

A lo largo de la unidad se evidencia con claridad que el enfoque tradicional, basado en estructuras funcionales aisladas y en la resolución reactiva de problemas, resulta insuficiente para responder a entornos dinámicos y altamente dependientes de la tecnología. La transición hacia un modelo de Gestión de Servicios de TI orientado a procesos end-to-end implica un cambio cultural, organizativo y técnico, donde el foco deja de estar en los componentes tecnológicos individuales para centrarse en los servicios como unidades de valor consumidas por el negocio.

Los procesos operativos analizados —Gestión de Eventos, Incidencias, Problemas, Solicitudes, Accesos y Niveles de Servicio— conforman un_ ecosistema interrelacionado que permite gestionar la operación de forma controlada y predecible. La Gestión de Incidencias asegura la restauración rápida del servicio; la Gestión de Problemas aporta una visión estructural y preventiva mediante el análisis de causa raíz; la Gestión de Eventos habilita la operación proactiva; mientras que la Gestión de Solicitudes y Accesos contribuye a la eficiencia, la seguridad y la satisfacción del usuario. La Gestión de Niveles de Servicio, por su parte, actúa como nexo formal entre TI y el negocio, transformando expectativas en compromisos medibles.

Un aspecto central que se desprende del contenido es la importancia de la priorización objetiva, ejemplificada mediante la matriz de Impacto y Urgencia. Esta herramienta sintetiza uno de los principios clave de ITSM: no todos los eventos tienen la misma relevancia para el negocio, y la correcta asignación de prioridades permite optimizar recursos, reducir riesgos y cumplir con los SLA. Este enfoque resulta esencial, ya que traduce variables técnicas en decisiones alineadas con el impacto organizacional.

La Mesa de Servicios emerge como un componente estratégico dentro del modelo operativo. Al actuar como punto Único de contacto, no solo canaliza la demanda, sino que estructura la experiencia del usuario y provee información crítica para la mejora continua. Su correcta implementación, apoyada por herramientas ITSM adecuadas, posibilita la automatización, la trazabilidad y el control de la operación, elementos indispensables para organizaciones de mediana y gran escala.

Asimismo, el modelo de madurez ITSM presentado en la unidad permite comprender que la excelencia operativa no se alcanza de forma inmediata, sino a través de un proceso evolutivo. Pasar de un enfoque reactivo y fragmentado a uno proactivo, alineado al negocio y orientado al valor requiere inversión en procesos, capacitación, herramientas y gobernanza. En los niveles más avanzados de madurez, TI deja de ser percibida como un centro de costos y se consolida como un socio estratégico, capaz de influir activamente en las decisiones del negocio.

Finalmente, la unidad refuerza la idea de que la Gestión Operativa de Servicios TI no puede analizarse de manera aislada del Gobierno de TI. La separación conceptual entre dirigir y gestionar, entre definir el “qué” y ejecutar el “como”, garantiza que la operación diaria responda a lineamientos estratégicos claros, con mecanismos de control, medición y retroalimentación continua. Esta integración entre gobierno y gestión es la base para asegurar que los servicios TI generen valor sostenido y gestionen adecuadamente los riesgos.

En conclusión, la Unidad 4 proporciona un marco sólido y coherente para comprender la operación de los servicios. Su correcta aplicación permite transformar la complejidad tecnológica en servicios confiables, medibles y alineados al negocio, consolidando a TI como un habilitador esencial del desempeño organizacional y de la creación de valor a largo plazo.
