
# Práctica 1 – Administración de Proyectos y Costos

## Parte I: Conceptos generales

### 1. Una startup de salud digital quiere lanzar una app de gestión de turnos médicos en un plazo de 4 meses, con el objetivo de comenzar a operar en una red de clínicas privadas. El sistema deberá permitir que los pacientes reserven turnos online, que los médicos gestionen su agenda y se enviarán recordatorios de forma automática. 

a) Defina con sus palabras el objetivo del proyecto. 

El objetivo del proyecto es desarrollar e implementar una app de gestión de turnos médicos que permita a los pacientes reservar turnos online, que los médicos gestionen su agenda y que se envien recordatorios de forma automática, todo en un plazo de 4 meses, para ser desplegada en una red de clínicas privadas.

b) Identifique al menos 4 restricciones y explique cómo afectan al proyecto. 

- **Calidad**: en un sistema de salud, la confiabilidad es crítica. Un turno mal registrado o un recordatorio que no llega puede tener consecuencias no deseadas al tratarse de vidas humanas. Esto exige estándares de calidad altos que deben sostenerse dentro de las restricciones de tiempo y costo planteados.
- **Costo**: una startup tiene generalmente un presupuesto acotado. El presupuesto disponible condiciona las decisiones tecnologicas (infraestructura, servicios de notificaciones, etc) y la cantidad de personas que se pueden contratar.
- **Tiempo**: el plazo de 4 meses fijado por la startup puede presionar al equipo a priorizar funcionalidades y reduce el margen para imprevistos. Al tratarse de un sistema complejo los problemas son seguros.
- **Recursos**: lo más probable es que el equipo de desarrollo sea pequeño y con recursos humanos limitados. Esto puede generar cuellos de botella si algún integrante falta o si se necesita un perfil específico (por ejemplo, un especialista en seguridad de datos de salud).

c) Indique 3 riesgos concretos del proyecto y para cada uno de ellos indique la causa, el impacto y proponga un posible plan de mitigación.


| Riesgo | Causa |Impacto |Plan de mitigación |
|--|--|--|--|
| Retraso en la integración con sistemas existentes de las clínicas | Las clínicas pueden tener sistemas legacy con APIS sin documentar  | Retraso en la entrega, posible reducción del alcance funcional | Relevar los sistemas de cada clínica antes de comenzar el desarrollo. Definir desde el inicio los protocolos de integración |
| Baja adopción por parte de los médicos | Resistencia al cambio o interfaz poco intuitiva para usuarios finales |El sistema se lanza pero no se usa, lo que hace fracasar el negocio |Relizar pruebas con médicos desde las etapas tempranas de diseño (entrevistas, prototipos) |
| Incumplimiento de regulaciones de privacidad de datos de salud | Los datos médicos y de pacientes están sujetos a normativas específicas |Problemas legales, suspensión del sistema, pérdida de confianza de las clínicas |Consultar con un especialista legal desde el inicio. |

### 2. Elija dos proyectos reales (pueden ser conocidos o hipotéticos): uno exitoso y uno fallido. 

*la dejo sin hacer porque no conozco ninguno a profundiad*

a) Describa brevemente cada uno de los proyectos (objetivo, contexto, resultado final). 
b) Identifique al menos 3 factores clave en cada caso que expliquen el éxito/fracaso del proyecto. 
c) Explique las diferencias entre ambos proyectos y proponga 3 acciones concretas que podrían haberse tomado para evitar los problemas del proyecto fallido.

### 3. Elija una organización y describa a qué se dedica (cuál es su misión). Formule un objetivo estratégico para el cual se necesite la ejecución de un programa y luego: 

> ### Organización elegida: Hospital Público Municipal
>**Misión:** Brindar atención médica integral, gratuita y de calidad a la comunidad, promoviendo la salud y el bienestar de la población mediante servicios de prevención, diagnóstico y tratamiento.
>### Objetivo estratégico
> Digitalizar y modernizar los procesos de atención al paciente para mejorar la calidad del servicio y reducir los tiempos de espera en un plazo de 2 años.

a) Identifique un programa para la implementación del objetivo estratégico que incluya al menos tres proyectos. 

**Nombre del programa:** Programa de Transformación Digital del Hospital

**Descripción:** Conjunto coordinado de proyectos orientados a digitalizar los procesos clave de atención, desde el primer contacto del paciente hasta el seguimiento post-consulta, con el fin de mejorar la eficiencia operativa y la experiencia del paciente.

- Proyecto 1 – Sistema de turnos online:
	- Desarrollar e implementar una plataforma web que permita a los pacientes sacar turnos de forma online, reduciendo las filas presenciales y las llamadas.
	- Duración estimada: 6 meses.
	- Entregable principal: aplicacion web en producción.

- Proyecto 2 - Historia Clínica Electrónica (HCE):
	- Digitalizar historias clínicas en papel y desarrollar un sistema que permita a los médicos registrar, consultar y actualizar la información clínica de cada paciente de forma centralizada.
	- Duración estimada: 8 meses.
	- Entregable principal: sistema de HCE integrado con los servicios del hospital.

- Proyecto 3 - Capacitacion del personal en herramientas digitales:
	- Diseñar e implementar un plan de capacitación para los empleados en el uso de los nuevos sitemas digitales adpotados.
	- Duración estimada: 3 meses.
	- Entregable principal: personal capacitado.

b) Explique por qué los proyectos forman parte del programa.

**CONSULTAR**

Porque ninguno de los tres proyectos por sí solo logra el objetivo estratégico. La combinación coordinada de los tres en el mismo programa es lo que permite alcanzar el objetivo.

## Parte II: Planificación y WBS

### 4. Una universidad necesita desarrollar un sistema de inscripción a materias online. Dicho sistema deberá permitir que los alumnos se inscriban a las materias, validar las correlatividades y generar listados para los docentes.

a) Proponga una descomposición del proyecto en actividades principales (nivel 1) y descompónganla en tareas (nivel 2).

**subido como imagen**

b) Explique qué criterio utilizó (por fases, entregables, etc.) y justifique por qué es adecuado para este proyecto.

Utilicé un enfoque por fases de ciclo de vida del proyecto. Es adecuado para este proyecto porque tiene una secuencialidad donde cada fase depende de la anterior. También, cada fase produce un entregable concreto y verificable, lo que facilita medir el avance y cumple con los criterios de completitud.

### 5. Revise el siguiente conjunto de tareas y determine cuáles NO cumplen criterios de completitud. Justifique y corríjalas: 
- “Desarrollar sistema”
	- Criterios que no cumple:
		- No es acotada, no tiene fecha de inicio ni de fin definida.
		- Estado no medible, no hay forma de saber en qué porcentaje está completa
		- No produce un entregable claro, no específica qué parte del sistema ni qué se entrega.
		- Tiempo y costo no estimables, es tan amplia que es imposible estimar con precision.
	- Corrección: descomponerla en tareas más específicas. 
- “Hacer pruebas” 
	-	Criterios que no cumple:
		-	Estado no medible, no se sabe qué se prueba ni cuánto falta.
		-	No produce un entregable claro, no se específica qué tipo de pruebas ni qué documento se genera.
		-	No es acotada, no tiene inicio ni fin definidos.
	- Corrección: escribirla de manera más clara, por ejemplo "Ejecutar pruebas de integración entre módulos"	
- “Diseñar base de datos en 2 días”
	- Criterios que no cumple:
		- Estado no medible, no se específica qué tablas o entidades deben quedar diseñadas.
	- Corrección: escribirla de manera más clara, por ejemplo "Diseñar esquema de base de datos (tablas de alumnos, materias y correlatividades)"

### 6. Explique con un ejemplo la diferencia entre duración y esfuerzo, mostrando cómo cambia al agregar recursos.

La duración es el tiempo transcurrido en días laborables para finalizar una actividad, mientras que esfuerzo es la cantidad de trabajo real requerido para completarla, independientemente del tiempo calendario.

- Desarrollar el módulo de inscripción a materias
	- 1 Desarrollador:
		- Esfuerzo: 40 horas.
		- Trabaja 8 horas por día en este modulo.
		- Duración: 5 días.
	- 2 Desarrolladores:
		- Esfuerzo: 40 horas + aprox 4 horas de coordinación y comunicación = ~44 horas
		- Cada uno trabaja 8 horas por día en este módulo:
		- Duración: ~2,5 días
	- 3-4 Desarrolladores:
		- Esfuerzo: 40 horas + horas de coordinación, capacitación y supervisión = ~60 horas.
		- Duración: ~2 días, pero el esfuerzo total aumentó mucho. 

Con 3-4 desarrolladores nos acercamos al crashpoint de la actividad. 

## Parte III: Costos

### 7. Una empresa quiere desarrollar un sistema pequeño de gestión interna (aproximadamente 10 KLOC):
- a) Clasifique el tipo de sistema (orgánico / semi-embebido / embebido) y justifique.
	- El tipo de sistema es orgánico porque involucra procesamiento de datos, uso de bases de datos, y se focaliza en transacciones y recuperación de datos, características que son típicas de un sistema de gestión interna.

- b) Identifique al menos 5 factores que podrían afectar la estimación. Explique cómo impacta cada uno.
	- ACAP (Capacidad de los analistas): si el equipo tiene baja capacidad de análisis, el esfuerzo necesario aumenta (en la tabla tiene un factor de hasta 1.46 en el nivel más bajo).
	- AEXP (Experiencia en la aplicación): la falta de experiencia previa en sistemas de gestión similares incrementa el esfuerzo requerido.
	- RELY (Confiabilidad requerida): si el sistema de gestión maneja datos críticos donde un fallo implica grandes pérdidas financieras, la estimación de tiempo y costo debe aumentar para asegurar esa calidad.
	- CPLX (Complejidad del producto): la puntuación puede variar de Muy Baja si el módulo está compuesto de expresiones matemáticas simples a Extra Alta para módulos que utilizan muchos recursos de planificación.
	- TOOL (Uso de herramientas de software): el uso de herramientas sofisticadas funciona como un multiplicador de productividad, reduciendo el tiempo estimado.

### 8. Explique por qué las estimaciones iniciales suelen ser inexactas y proponga dos estrategias concretas para mejorar la estimación.

En Ingeniería de Software somos notoriamente inexactos porque, a diferencia de otras profesiones, no hay muchas tareas repetitivas; cada proyecto difiere en dominio, herramientas, hardware y personal. Somos más "creadores" que constructores. Además, existen problemas políticos, donde las estimaciones se vuelven objetivos impuestos, y técnicos, como la falta de datos históricos.

Se pueden usar varias estrategias para mejorar las estimaciones iniciales, como por ejemplo:
1. Utilizar datos históricos: registrar las estimaciones y resultados de proyectos pasados en una base de datos para comparar similitudes en lugar de confiar solo en la memoria.
2. Uso de modelos combinados: no confiar ciegamente en un solo modelo como COCOMO, se debe complementar el uso de herramientas con el juicio experto y la intuición del equipo.

### 9. Compare al menos dos técnicas de estimación aplicadas a un mismo caso práctico. Indique ventajas y limitaciones.

|Técnica|Ventajas|Limitaciones|
|-|-|-|
|**Juicio Experto**|Aprovecha la experiencia de personal senior y es rápida de aplicar cuando se conocen los parámetros| Es subjetiva y puede verse influenciada por intereses externos (ej. vendedores)|
|**Analogía**| Es más visible y transparente al identificar similitudes y diferencias con proyectos pasados. | Requiere que la organización posea un registro confiable de datos históricos.|
|**WBS**|Al definir tareas con alto nivel de detalle, permite que las estimaciones de costo y tiempo sean más exactas|Un enfoque "bottom-up" puede fallar si no se logra la granularidad adecuada en las tareas menores.|

### 10. Elija una situación en un proyecto de software en la que una mala estimación haya generado un problema relevante durante su desarrollo.

- Descríbalo brevemente, teniendo en cuenta el tipo de sistema, tamaño, complejidad, plazo, etc.
- Indique cuál fue la estimación incorrecta y explique los motivos.

no se

## Parte IV: Gestión de proyectos

### 11. Una municipalidad quiere implementar un sistema digital para gestionar reclamos ciudadanos.

- Identifique al menos 4 stakeholders.
	- Ciudadanos/Residentes (externos)
	- Personal administrativo municipal (internos)
	- Intendente y gabinete ejecutivo (internos)
	- Prensa y medios locales (externos)
	
- Para cada stakeholder explique el interés, la influencia y las expectativas sobre el sistema.

|**Stakeholder**|**Interés**|**Influencia**|**Expectativas**|
|-|-|-|-|
|**Ciudadanos**|Alto: desean que sus problemas locales se resuelvan|Alta: tienen derecho a desafiar decisiones y afectar la imagen pública| Facilidad de acceso, respuestas rápidas y transparencia en el estado del reclamo|
|**Personal Administrativo**|Alto: el sistema cambia sus procesos de trabajo diarios|Media/Alta: su apoyo es crítico; la resistencia puede llevar al fracaso|Simplificación de tareas, reducción de carga manual y herramientas fáciles de usar|
|**Intendente/ Gabinete**|Alto: alineación con la agenda política y metas de gobierno digital|Muy Alta: toman decisiones estratégicas y asignan presupuesto|Mejorar la percepción pública, optimizar costos y obtener datos para decidir|
|**Prensa Local**|Medio: interés en informar sobre la gestión de servicios públicos|Media: moldean la opinión pública sobre el éxito o fracaso del proyecto|Transparencia total y acceso a información sobre el impacto del sistema|

- Construya una matriz de impacto y explique 2 decisiones tomadas a partir de ella.
	- Cuadrante Alto Impacto/Alta Importancia: ciudadanos e Intendente.
	- Cuadrante Alto Impacto/Media Importancia: personal administrativo.
	- Cuadrante Bajo Impacto/Media Importancia: prensa.
	- Decisiones tomadas:
		- Priorizar la usabilidad para el ciudadano: dado que tienen alto impacto y son el foco del beneficio, se decide realizar pruebas de usabilidad intensivas para garantizar que cualquier vecino pueda usar el sistema sin asistencia técnica.
		- Plan de gestión del cambio para empleados: debido a que el proyecto impacta fuertemente en su rutina, se decide realizar workshops y capacitaciones tempranas para reducir la resistencia al cambio y asegurar que se apropien del sistema.

### 12. Identifique 3 beneficios concretos y medibles que se espera obtener con la implementación del proyecto anterior, y para cada uno:
- Describa el beneficio de manera específica.
- Defina cómo y en qué momento se podría evaluar.
- Especifique qué resultado se esperaría observar.

El objetivo es asegurar que los beneficios sean específicos, medibles y vinculados a resultados estratégicos.

- Beneficio 1: reducción del tiempo de respuesta.
	- Descripción: disminuir el tiempo promedio desde que un ciudadano registra un reclamo hasta que este recibe una resolución o respuesta final.
	- Evaluación: se evalúa mediante la comparación de métricas de desempeño del sistema vs. registros manuales históricos, 6 meses después del lanzamiento.
	- Resultado esperado: reducción del 30% en el tiempo promedio de resolución de reclamos de luminarias y bacheo. (**si puedo consultar si esta respuesta es la que quieren en el parcial**)
- Beneficio 2: incremento en la transparencia y trazabilidad.
	- Descripción: permitir que el 100% de los reclamos digitales tengan un número de seguimiento visible para el ciudadano en tiempo real.
	- Evaluación: encuestas de satisfacción del cliente (ciudadano) y auditoría de logs del sistema al finalizar el primer año de operación.
	- Resultado esperado: lograr una calificación superior a 4/5 en percepción de transparencia en las encuestas ciudadanas.
- Beneficio 3: eficiencia en la administración interna.
	- Descripción: eliminar la duplicación de tareas y el ingreso manual de datos en múltiples planillas de papel.
	- Evaluación: medición de la productividad operativa del personal administrativo comparando horas hombre dedicadas a la carga de datos antes y después del sistema.
	- Resultado esperado: eeducción del 20% en costos operativos relacionados con la gestión burocrática de reclamos.

### 13. Diseñe un plan de comunicación básico para el proyecto.

Un plan de comunicación es central para gestionar las expectativas de los interesados.

- Objetivo: concientizar sobre los beneficios, mantener informados a los interesados y asegurar la alineación de expectativas.
- Mensajes Clave: "La municipalidad está más cerca tuyo", "Tu reclamo tiene seguimiento real". (en la teoria decia Promover mensajes claves del programa asi que supongo que está bien esto (?)
- Canales y Audiencia:
	- Externo (Ciudadanos): redes sociales, gacetillas en prensa/medios locales y cartelería en oficinas públicas para un alcance amplio.
	- Interno (Empleados): boletines internos, correos electrónicos y seminarios/workshops para contacto directo y feedback.
- Responsables: el Líder de Proyecto y el área de Comunicación Institucional.
- Frecuencia: reportes de avance mensuales para las autoridades; campaña intensiva de uso 15 días antes del lanzamiento; y comunicación de resultados de beneficios cada semestre.
- Feedback: implementación de un canal de comunicación de doble vía para recibir sugerencias de los usuarios y actuar en consecuencia.

## Parte V: Ejercicios

### 14. Una universidad desea implementar un “Sistema Integral Académico” en 3 meses, el cual debe permitir: gestionar inscripciones a materias, administrar notas, permitir comunicación entre docentes y alumnos e integrarse con sistemas existentes. El proyecto aún no tiene un presupuesto definido, cuenta con un equipo de 5 integrantes, no hay claridad sobre los requerimientos, se aplica a distintas áreas (alumnos, docentes, administración) con expectativas diferentes y las autoridades esperan que el sistema “resuelva todos los problemas actuales”.

- Detecte al menos 5 problemas concretos del proyecto.
	- Expectativas poco realistas: la dirección espera que el sistema "resuelva todos los problemas actuales", lo cual es un objetivo vago, no medible y probablemente inalcanzable para un solo sistema de software.
	- Ausencia de presupuesto: un proyecto se define por tener que ser completado dentro de un costo específico, no tener un presupuesto definido impide la administración de recursos y el control financiero.
	- Plazo de entrega insuficiente (3 meses): implementar un sistema "integral" que incluye inscripciones, notas, comunicaciones e integraciones técnicas complejas en solo 3 meses representa una mala estimación de la duración.
	- Requerimientos ambiguos: no hay claridad sobre lo que el sistema debe hacer exactamente ("no hay claridad sobre los requerimientos"), lo que impide que el producto final cumpla con las especificaciones.
	- Conflicto de intereses entre stakeholders: existen múltiples áreas (alumnos, docentes, administración) con expectativas diferentes que no han sido alineadas, lo que genera un alto riesgo de rechazo del sistema
	- 
- Clasifique los problemas en categorías (planificación, alcance, recursos, …) y justifique brevemente cada clasificación.

|**Categoría**|**Problemas identificados**|**Justificación**|
|-|-|-|
|**Alcance**|Requerimientos ambiguos y el objetivo de "resolver todo"|El alcance debe definir los límites del proyecto (qué se hace y qué no). Al ser ambiguo, el equipo no sabe cuándo ha terminado o qué debe construir exactamente|
|**Planificación**|Plazo de 3 meses para un sistema integral complejo|La planificación requiere una estimación de tiempos realista. Un plazo arbitrario sin considerar la complejidad técnica ni las tareas de integración indica una planificación deficiente|
|**Recursos** (presupuesto)|Presupuesto no definido|El costo es el presupuesto disponible. Sin un límite financiero, es imposible gestionar la adquisición de herramientas, infraestructura o personal adicional necesario|
|**Gestión de interesados**|Expectativas contrapuestas de alumnos, docentes y autoridades|La falta de compromiso y participación de los interesados en una etapa temprana impide definir beneficios claros y genera metas poco realistas que llevan al fracaso del programa|
|**Recursos** (humanos)|Equipo de 5 integrantes para múltiples áreas y funciones|Las personas son el recurso más importante. Un equipo de 5 puede ser insuficiente para cubrir simultáneamente el análisis, desarrollo, pruebas e integración de un sistema que afecta a toda la universidad|

- Redefina el proyecto proponiendo un objetivo claro, un alcance acotado y restricciones realistas.
	- Objetivo: desarrollar e implementar el núcleo funcional del sistema académico (módulos de inscripción a materias y carga de notas) en un plazo de 3 meses, asegurando la integridad de los datos de los alumnos
	- Alcance:
		- Incluye: registro de alumnos, inscripción a cursadas del cuatrimestre vigente, validación de correlatividades básicas y panel de carga de notas para docentes.
		- Excluye: sistema de mensajería interna e integración automática con todos los sistemas legados (se reemplaza por una migración de datos única)
	- Restricciones:
		- Tiempo: 3 meses
		- Recursos: un equipo de 5 integrantes con roles definidos (por ejemplo 1 líder, 1 analista y 3 desarrolladores)
		- Calidad: el sistema debe cumplir la norma ISO/IEC 25010 en su característica de funcionalidad
		- Costo: presupuesto limitado a la infraestructura de servidores y licencias necesarias para la fase inicial
		
- Defina entre 5 y 10 tareas principales y realice un WBS de no más de 2 niveles.

Meta: Sistema Integral Académico 

1.  **Analizar Requerimientos y Diseño**
    -   1.1 Especificar requisitos detallados de inscripción y notas.
    -   1.2 Diseñar el modelo de datos y la arquitectura del sistema.
2.  **Desarrollar Módulos Críticos**
    -   2.1 Implementar el módulo de gestión de inscripciones.
    -   2.2 Implementar el módulo de administración de notas para docentes.
    -   2.3 Implementar el panel de autogestión para el alumno.
3.  **Integrar y Probar**
    -   3.1 Ejecutar pruebas funcionales y de seguridad.
    -   3.2 Realizar la migración inicial de datos existentes.
4.  **Implementar y Desplegar**
    -   4.1 Capacitar a los usuarios clave (docentes y administrativos).
    -   4.2 Desplegar el sistema en el entorno de producción.
