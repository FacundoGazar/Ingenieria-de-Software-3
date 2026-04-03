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
