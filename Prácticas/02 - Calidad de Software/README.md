
# Práctica 2 – Calidad de Software

## Parte I: Conceptos generales

###  1. Una empresa desarrolla un sistema web para gestión de ventas. Luego de la entrega, los usuarios reportan que el sistema “no es fácil de usar” y hay errores ocasionales en los datos mostrados. El sistema cumple con todos los requerimientos funcionales definidos. 

- Explique por qué el sistema puede considerarse de baja calidad, aunque cumpla los requerimientos. 
	- La calidad es un concepto multidimensional que no se limita únicamente al cumplimiento de los requerimientos funcionales. Según la norma ISO/IEC 25010, un producto de calidad debe satisfacer características como la facilidad de uso usabilidad y la seguridad (integridad/ausencia de errores en datos). Aunque el sistema haga lo que debe, si no es fácil de usar o presenta inconsistencias, no cumple con la facilidad de uso ni con la seguridad, pilares fundamentales de la definición de calidad

- Identifique ejemplos de Calidad realizada / programada / necesaria. Indique cuál es el principal desalineamiento y por qué. 
	- Calidad necesaria: los usuarios necesitan que el sistema sea intuitivo y que los datos mostrados sean exactos para operar sin desconfianza
	- Calidad programada: el diseño inicial que se centró exclusivamente en las funcionalidades lógicas, omitiendo métricas de usabilidad o validaciones de datos
	- Calidad realizada: el sistema web entregado, que es funcional pero difícil de operar y con errores en la integridad de los datos.
	- El desalineamiento ocurre entre la calidad necesaria y la calidad realizada. Este es el problema más grave, ya que implica que el esfuerzo del equipo de desarrollo no resultó en un producto que satisfaga las expectativas reales del cliente

- Proponga tres acciones concretas para mejorar la calidad del producto.
	- Establecer métricas de facilidad de uso: definir indicadores de capacidad para ser usado (ej. porcentaje de tareas completadas sin ayuda)
	- Implementar controles de integridad de datos: incorporar validaciones automáticas en la carga de datos para asegurar la exactitud y consistencia (calidad de datos inherente)
	- Realizar pruebas de usuario: ejecutar sesiones con usuarios reales para identificar puntos de fricción y mejorar la interfaz, asegurando la estetica de la interfaz de usuario

### 2. Un equipo de desarrollo entrega un sistema de stock sin errores visibles, pero que no tiene ningún tipo de documentación, tiene un código que es difícil de mantener y cada cambio a realizar requiere mucho tiempo.

- Indique si el producto es de calidad y justifique 
	-  Aunque no tenga errores visibles (calidad externa), falla críticamente en su calidad interna, específicamente en la característica de facilidad de mantenimiento. Un código difícil de mantener e indocumentado viola las características de modularidad, reusabilidad, capacidad para ser analizado, capacidad para ser probado y capacidad para ser modificado 
	
- Indique si el proceso fue de calidad y justifique
	- El proceso no fue de calidad. Sin un buen proceso de desarrollo es casi imposible obtener un buen producto, en cambio, teniendo un proceso de calidad nos aseguramos tener un producto de calidad.
	
- Explique cómo un proceso deficiente puede impactar en la calidad futura del producto
	- Un proceso deficiente genera deuda técnica. La falta de estándares se traduce en una calidad futura degradada, ya que cada cambio será más costoso, propenso a errores y demandará más tiempo, pudiendo llevar al fracaso total del sistema ante la necesidad de actualizaciones
	
- Indique cuál considera que es el principal problema y por qué
	- La falta de mantenibilidad y documentación. Esto genera una dependencia crítica del conocimiento tácito de los desarrolladores actuales y un alto costo operativo a largo plazo, impidiendo que el software evolucione al ritmo del negocio

### 3. Una empresa de desarrollo de software decide mejorar la calidad de sus productos. Durante una reunión uno de los integrantes propone “usar ISO/IEC 25010”, otro sugiere “definir nuestros propios criterios internos” y un tercero plantea que “hay que seguir una norma obligatoria”. El equipo muestra confusión sobre qué significa cada uno de estos enfoques.

- Explique la diferencia entre norma y estándar en el contexto del caso e indique cuál de las propuestas del equipo corresponden a cada una y por qué
	- Norma: es una regla obligatoria que se debe seguir para ajustar conductas o tareas. Corresponde a la propuesta de "seguir una norma obligatoria".
	- Estándar: es un modelo de referencia, patrón o nivel de excelencia. Corresponde a la propuesta de "usar ISO/IEC 25010", ya que esta provee un marco de trabajo para evaluar la calidad
	- Criterios internos: es una definición propia de la empresa que, aunque puede ser útil, carece de validación externa si no se referencia a un estándar

- Indique qué enfoque considera más adecuado para esta empresa en una primera etapa, teniendo en cuenta el contexto del equipo y el objetivo planteado.
	- El enfoque más adecuado es utilizar un estándar como referencia (ISO/IEC 25010) para definir los criterios internos. Esto permite a la empresa adoptar un lenguaje profesional y probado, adaptándolo gradualmente a su contexto antes de intentar una certificación obligatoria más rígida

- Explique qué problema podría surgir si el equipo aplica una norma sin comprenderla o define criterios propios sin referencia externa.
	- Aplicar una norma sin comprenderla: puede generar una burocracia inútil, donde el equipo se enfoca en completar formularios o "papelería" sin mejorar realmente la calidad del código o la satisfacción del cliente **CONSULTAR**
	- Definir criterios propios sin referencia externa: se corre el riesgo de tener una visión subjetiva e incompleta de la calidad, ignorando características críticas que otros competidores sí consideran, perdiendo así competitividad en el mercado

## Parte II: Calidad de Producto

### 4. Se desea evaluar la calidad de una aplicación móvil de turnos médicos. Se busca analizar: facilidad de uso, portabilidad y desempeño. 

- Defina el objetivo de la evaluación y qué decisiones permitiría tomar.
	- Objetivos:
		- Determinar el grado en que la aplicación satisface las necesidades de los pacientes y médicos en diversos entornos (dispositivos), asegurando que sea intuitiva y responda de forma fluida.
	- Decisiones: 
		- Permitiría decidir si el producto está listo para ser lanzado al mercado, si requiere rediseñar interfaces críticas para usuarios no técnicos o si es necesario escalar la infraestructura del servidor para evitar caídas por saturación

- Para cada característica defina una métrica concreta e indique qué y cómo se mediría.
	- Facilidad de Uso: se utiliza la métrica "Capacidad para ser usado". Se mide como X=A/B, donde A es el número de tareas básicas (ej. reservar un turno) completadas con éxito sin ayuda externa y B es el total de tareas asignadas durante la prueba.
	- Portabilidad: se define como la "Capacidad para ser instalado". Se mediría intentando instalar la app en una muestra de diversos modelos de celulares y sistemas operativos (Android/iOS). El valor es el porcentaje de instalaciones exitosas sobre el total de intentos
	- Desempeño (Eficiencia): se aplica el "Comportamiento temporal". Se mediría el tiempo medio de respuesta del servidor ante la solicitud de confirmación de un turno. Se calcula promediando los segundos que tarda el sistema en responder bajo una carga simulada de usuarios

- Defina criterios de aceptación y explique su uso.
	- Criterios de aceptación: los criterios de aceptación son umbrales o rangos de valores (ej. Excede, Rango objetivo, Mínimamente aceptable, Inaceptable) definidos previamente para cada métrica. Su uso es fundamental para otorgar objetividad a la evaluación; si una métrica cae en el rango "Inaceptable" (ej. menos del 60% de éxito en usabilidad), el equipo debe rechazar esa versión del producto y realizar correcciones antes de la entrega

- Describa qué pruebas realizaría y en qué contexto. Explique la principal dificultad al evaluar calidad.
	- Se realizarían pruebas con usuarios reales en sesiones controladas para usabilidad, pruebas de carga concurrente simulando múltiples accesos para el desempeño, y pruebas en dispositivos físicos reales de distintas gamas para portabilidad
	- La calidad tiene un fuerte componente subjetivo. Aunque ciertos aspectos pueden medirse, la percepción final de "calidad" depende del juicio de valor del observador y de si el producto se adecúa satisfactoriamente a los propósitos particulares de cada usuario

## 5. Un sistema de e-commerce presenta problemas de lentitud en momentos de alta demanda

- Identifique la característica y subcaracterística de calidad afectada
	- Característica: eficiencia
	- Subcaracterística: capacidad (grado en que el sistema soporta la carga requerida) y comportamiento temporal (tiempos de respuesta en momentos de alta demanda).

- Proponga 2 métricas concretas para medirla. Defina valores aceptables y no aceptables
	- Métrica de Capacidad: proporción de transacciones de compra que se completan sin errores de tiempo de espera (_timeout_) durante picos de tráfico.
		-  Aceptable:  X≥0,7 (70% de éxito bajo carga máxima).
		-  No aceptable:  0,6≥X.
	- Tiempo de Respuesta: tiempo promedio en segundos para cargar la página de "Pago".
		 - Aceptable:  X≤3 segundos.
		 - No aceptable:  4 segundos ≤ X

- Justifique la elección de las métricas y explique por qué las considera adecuadas
	- Estas métricas son adecuadas porque cuantifican directamente la degradación del servicio que experimenta el cliente. La lentitud en un e-commerce suele deberse al agotamiento de recursos críticos (procesador o memoria) ante la concurrencia, y estas medidas permiten diagnosticar si el problema es de optimización del software o de capacidad de hardware

## 6. Se necesita realizar una evaluación de dos sistemas similares utilizando distintas métricas de usabilidad.

- Seleccione 2 métricas posibles y compárelas.
	- Capacidad para ser usado: mide si el usuario logra completar la tarea
	- Capacidad de aprendizaje técnico: mide el tiempo o esfuerzo que le toma a un usuario nuevo volverse competente en el sistema
	
- Indique ventajas y limitaciones de cada una.
	- Capacidad para ser usado:
		- Es muy objetiva, el resultado es binario (completó o no la tarea)
		- No identifica si el usuario tuvo que realizar un esfuerzo excesivo o "dar vueltas" para lograrlo
	- Capacidad de aprendizaje técnico:
		- Es vital para sistemas complejos donde la rotación de usuarios es alta
		- Es más difícil de medir, ya que requiere observar al mismo usuario durante un periodo de tiempo prolongado
		
- Elija una de ellas y expliqué el porqué de su elección.
	-  Depende del sistema que se está evaluando, si hablamos de una app médica me enfocaría mas en la caracteristica de capacidad para ser usado, ya que es escencial que los pacientes puedan realizar las tareas correctamente ya sea para leer una receta, pedir un turno, etc, son cosas que no se pueden dejar de lado.

## 7. Una empresa utiliza la siguiente métrica:
