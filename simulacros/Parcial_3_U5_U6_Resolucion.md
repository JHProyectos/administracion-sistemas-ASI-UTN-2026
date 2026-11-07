# Parcial 3 (U5 y U6) · Resolución del caso OmniChannel Retail

[TOC]

Resolución propuesta del parcial real de las unidades cinco y seis. El enunciado original está en "Parcial 3 ( u5 y u6 ) - Alumnos.docx", en esta misma carpeta.

## El enunciado, en corto

"OmniChannel Retail S.A." es una cadena de retail regional. Su plataforma de ventas online y de gestión de stock se cae una y otra vez en los picos de tráfico estacional, como el Hot Sale o las Fiestas. La Dirección decidió encarar un proyecto urgente de modernización tecnológica, y Sistemas presentó tres alternativas:

- **Alternativa A, desarrollo tradicional a medida (in-house):**
  - Un sistema monolítico nuevo, hecho desde cero con personal propio y servidores locales (on-premise) de alta gama.
  - Alta previsibilidad técnica inicial, porque se conoce la tecnología. Pero baja certeza operativa a largo plazo, por los cambios bruscos del mercado y las posibles demoras del equipo interno.
- **Alternativa B, adopción híbrida SaaS/Cloud con proveedor tercerizado:**
  - Migrar en parte los servicios críticos a la nube, con pago por uso, e integrarlos con el sistema actual (legacy) mediante APIs. Se trabaja con Scrum.
  - Certeza media-alta en plazos y escalabilidad, con costos operativos (OpEx) predecibles. Hay incertidumbre moderada por la dependencia del proveedor (vendor lock-in) y la coordinación con equipos externos.
- **Alternativa C, transformación ExO con un MVP cloud-native disruptivo:**
  - Descartar el sistema actual y reemplazarlo por una arquitectura serverless de microservicios, con inteligencia artificial para predecir la demanda. Se lanza un MVP en pocas semanas con staff a demanda.
  - Altísima incertidumbre económica y técnica inicial, con riesgo de sobrecostos y una curva de aprendizaje compleja. A cambio, adaptabilidad máxima y potencial de crecimiento exponencial si el mercado responde.

La consigna, actuando como líder del proyecto de sistemas, tiene tres partes:

1. Evaluar las tres alternativas según su factibilidad técnica, económica (CapEx contra OpEx) y operativa.
2. Elegir la alternativa más adecuada para el contexto actual de la compañía.
3. Justificar la elección con los conceptos de la unidad cinco: gestión de riesgos, nivel de incertidumbre de los requisitos, adecuación metodológica y viabilidad a largo plazo.

## 1. Evaluación de las tres alternativas

| | A · A medida, on-premise | B · Híbrida SaaS/Cloud con Scrum | C · ExO, MVP cloud-native |
|---|---|---|---|
| **Técnica** (¿se puede?) | Sí, la tecnología se conoce. Pero los servidores se dimensionan para el pico y quedan ociosos el resto del año. | Sí: la nube escala en los picos y las APIs la integran con el sistema actual. Hay proveedores alternativos. | Incierta: microservicios, serverless e IA tienen una curva de aprendizaje compleja. |
| **Económica** (¿conviene?) | CapEx alto, por los servidores de alta gama y el desarrollo propio. Recupera la inversión lento, y el costo de no hacer nada sigue corriendo mientras se desarrolla. | OpEx predecible y de pago por uso, que acompaña la estacionalidad. Aprovecha el sistema actual. | OpEx, pero con riesgo de sobrecostos. El VAN y el período de recuperación son muy inciertos. |
| **Operativa** (¿se puede llevar a la práctica?) | Riesgo de demoras del equipo interno. La operación de los servidores propios queda a cargo de la empresa. | Cambio gradual: el sistema actual sigue andando, los usuarios se adaptan por partes y hay menos resistencia. Depende de coordinar con equipos externos. | Impacto máximo: descarta el sistema actual y exige convertir los datos y capacitar a todos. Además, el conocimiento queda en staff temporal. |

## 2. Elección

**La Alternativa B, la híbrida en la nube con Scrum.** Es la única que resuelve rápido el problema concreto, las caídas en los picos de tráfico, con un riesgo que se puede manejar.

## 3. Justificación con los conceptos de la unidad cinco

### Incertidumbre de los requisitos: la matriz de Stacey

- El qué está claro: que la plataforma no se caiga en los picos. El cómo se conoce solo en parte, por la integración con el sistema actual y la escalabilidad. Eso ubica al proyecto entre lo complicado y lo complejo, donde corresponde un enfoque ágil o intermedio.
- B usa Scrum, que entrega por partes y permite ir ajustando.
- A aplica un enfoque tradicional en un entorno que la propia consigna describe con "cambios bruscos del mercado".
- C tiene una incertidumbre altísima, técnica y económica a la vez, cerca de lo caótico. Según el apunte, en lo caótico primero hay que estabilizar, no lanzarse.

### Gestión de riesgos: probabilidad por impacto

- **A:** la probabilidad de demoras es alta, y el impacto también, porque el problema es urgente y estacional.
- **C:** la probabilidad de sobrecostos es alta y el impacto, altísimo, porque reemplaza todo el sistema.
- **B:** sus riesgos son moderados y se pueden mitigar.
  - El vendor lock-in se mitiga en la contratación, con requisitos de portabilidad en el pliego, la garantía de ejecución, la cláusula penal por incumplir los plazos y la existencia de proveedores alternativos.
  - La coordinación con los equipos externos se mitiga con Scrum.
- El riesgo también tiene un lado positivo: la nube abre la oportunidad de escalar sin invertir de más.

### Factibilidad económica

- Pasar a la nube es cambiar CapEx por OpEx. En un negocio con picos estacionales, pagar por uso evita comprar capacidad que después queda ociosa.
- El costo de no hacer nada es alto: cada caída en un Hot Sale son ventas perdidas. Por eso pesa la rapidez de B.

### Factibilidad operativa

- B no rompe los procesos actuales. Tiene más chances de lograr el apoyo de la gerencia y de los usuarios, y causa menos daño durante la transición, como pérdida de control o trabajo más lento.
- C es la que más falla en la operativa.

### Viabilidad a largo plazo

- B no le cierra la puerta a C. Una vez estabilizada la operación, se pueden seguir migrando servicios y después sumar IA o microservicios con menos incertidumbre.
- O sea, B da previsibilidad hoy y adaptabilidad mañana.

## Cierre para escribir en el parcial

> Elijo B porque equilibra las tres factibilidades. Técnicamente, resuelve la escalabilidad. Económicamente, convierte una inversión grande y rígida en un gasto variable y predecible. Y operativamente, permite un cambio gradual. Sus riesgos son moderados y se pueden mitigar, a diferencia de las demoras de A y la incertidumbre extrema de C.

## Consejos para escribirlo

- Arrancá nombrando la alternativa elegida. Después poné la tabla.
- Usá el vocabulario de la unidad: matriz de Stacey, CapEx y OpEx, costo de no hacer nada, probabilidad por impacto, mitigación.
- Respondé las tres partes de la consigna por separado, así el profesor ve cada una.
