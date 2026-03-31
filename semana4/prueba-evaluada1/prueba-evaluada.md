# PRUEBA EVALUADA 1 (14/2/2026)
## PRUEBA EVALUADA

Temas a vealuar:

* MVC
* MMS_1 y MMS_2

Tiempo estimado 75 minutos

**Calificación final: 8.96/10.00**

## Respuestas
### Pregunta 1
¿Cuál es el rol operativo del "Controlador" dentro de este ecosistema arquitectónico?

* a. Almacenar exclusivamente el contenido sin procesar como archivos de sonido, video y subtítulos
* b. Definir la jerarquía visual de los elementos en la pantalla sin intervenir en la lógica
* c. Actuar como intermediario, gestionando la entrada del usuario y actualizando tanto el Modelo como la Vista :white_check_mark:

>Su respuesta es correcta.
>
>La respuesta correcta es: Actuar como intermediario, gestionando la entrada del usuario y actualizando tanto el Modelo como la Vista

### Pregunta 2
Es un requisito obligatorio que la aplicación sea sometida a una fase formal de pruebas antes de proceder a su lanzamiento

* Verdadero :white_check_mark:
* Falso

>La respuesta apropiada es 'Verdadero

### Pregunta 3 - Parcialmente correcta
Según el texto, ¿por qué se recomienda realizar pruebas con 5 participantes en diferentes momentos en lugar de una sola prueba con 15 personas?

```plaintext
Es para mejorar iterativamente la usabilidad de la aplicación, aun si no se detectan los problemas en su totalidad debido a que cada prueba con 5 participantes nos proporcionará información suficiente para mejorar la solución de diseño.
```

### Pregunta 4
¿Cuál es el propósito fundamental de estructurar una aplicación bajo el patrón de arquitectura MVC?

* a. Priorizar el diseño de interfaces de usuario altamente sofisticadas y reactivas en tiempo real
* b. Facilitar la gestión y mantenimiento del código base, promoviendo la modularidad y reutilización :white_check_mark:
* c. Optimizar la velocidad de respuesta del hardware del dispositivo

>Su respuesta es correcta.
>
>La respuesta correcta es: Facilitar la gestión y mantenimiento del código base, promoviendo la modularidad y reutilización

### Pregunta 5
Defina el propósito de la herramienta FODA y especifique qué factores componen el análisis interno y cuáles el externo según el texto :white_check_mark:

```plaintext
La herramienta FODA, es una herramienta de planificación estratégica, diseñada para
realizar una análisis interno (Fortalezas y Debilidades) y externo (Oportunidades y
Amenazas) en la empresa.

- Fortalezas: Factores internos que la empresa puede utilizar para lograr sus objetivos.

- Oportunidades: Factores externos que la empresa puede utilizar para lograr sus metas.

- Debilidades: Factores que pueden poner a la empresa en una posición desfavorable y afectar el proyecto.

- Amenazas: Factores externos que pueden afectar negativamente la estabilidad del proyecto.
```

### Pregunta 6
En relación con el flujo de datos, ¿Cuál es una característica esencial de la "Vista"?

* a. Interactúa de forma directa y bidireccional con el Modelo para obtener datos
* b. Es un componente activo que procesa la lógica de persistencia de la aplicación
* c. Es un componente pasivo que muestra los datos del Modelo y envía las entradas al Controlador :white_check_mark:

>Su respuesta es correcta.
>
>La respuesta correcta es: Es un componente pasivo que muestra los datos del Modelo y envía las entradas al Controlador

### Pregunta 7
La calidad percibida de una aplicación móvil está intrínsecamente ligada a las especificaciones de hardware del terminal

* Verdadero :white_check_mark:
* Falso

>La respuesta apropiada es 'Verdadero

### Pregunta 8
Las métricas relativas al consumo de energía se consideran irrelevantes en la valoración final de calidad por parte del usuario

* Verdadero
* Falso :white_check_mark:

>La respuesta apropiada es 'Falso

### Pregunta 9
De acuerdo con la organización técnica del proyecto, ¿Qué elementos deben ubicarse en la carpeta o grupo "Modelo"?

* a. ViewControllers y cualquier otro código de tipo "pegamento"
* b. Objetos de datos, lógica empresarial y código de persistencia de datos :white_check_mark:
* c. Guiones gráficos (Storyboards) y subclases de UIView personalizadas

>Su respuesta es correcta.
>
>La respuesta correcta es: Objetos de datos, lógica empresarial y código de persistencia de datos

### Pregunta 10
El ciclo de vida de la metodología MMS está conformado por exactamente 5 fases numeradas en el texto descriptivo

* Verdadero :x:
* Falso

>La respuesta apropiada es 'Falso

### Pregunta 11
¿Cuál es la utilidad de los **diagramas de flujo** y las **"cartillas de especificación"** en la identificación de procesos? :white_check_mark:

```plaintext
Los diagramas de flujo representan los procesos, y estos procesos muestran la dirección de la información, roles, actividades y las relaciones existentes entre cada proceso.

La utilidad de las cartillas es complementar los diagramas de flujo, especificando cada una de las actividades. Esto con el fin de evitar cometer errores durante el desarrollo. Se deben especificar las actividades predecesoras (origen), quién realizará la actividad (actor o usuario) y las reglas de negocio que se deben seguir antes y después de la actividad.
```

### Pregunta 12
Durante la fase de diseño, el cliente no participa activamente mediante la validación de prototipos para evaluar la usabilidad

* Verdadero
* Falso :white_check_mark:

>La respuesta apropiada es 'Falso

### Pregunta 13
¿Quiénes son los dos únicos actores que intervienen en la fase de planificación? :white_check_mark:

```plaintext
El gerente del proyecto y el cliente.
```

### Pregunta 14
Defina brevemente la función del Sprint Backlog y qué estructura jerárquica sigue la EDT en el modelo *MMS*. :white_check_mark:

```plaintext
El sprint backlog es una planificación de los requerimientos a desarrollarse durante un sprint, se debe considerar el nivel de priorización y si estos pueden ser completados y demostrados al cliente al final de la iteración.

La estructura jerárquica del EDT es:

- Proyecto
    - Fase
        - Sprint
            - Actividad
```

### Pregunta 15
¿Qué elementos debe contener la descripción de una **historia de usuario** para facilitar la comprensión entre el cliente y el gerente? :x:

```plaintext
- Identificador: Debe ser un valor único e irrepetible, pero a su vez secuencial para identificar fácilmente la continuidad de las historias.
- Actor: Es aquel usuario que efectuará la funcionalidad descrita en la historia.
- Prioridad: Se puede medir mediante los identificadores, baja, media y alta. Dichos valores estarán ligados a las reglas de negocio o a su vez a las necesidades del cliente.
- Sprint: Hace referencia a la iteración del proyecto, recordemos que el Modelo Mobile Sprint tiene como
base el desarrollo en ciclos cortos denominados sprints.
- Responsable por lo general siempre pertenece al grupo de desarrolladores, ya sea este un programador, diseñador o Tester.
- Requerimiento funcional: Se debe referenciar uno de los registrados previamente que solucionar la historia de usuario mencionada.
- Descripción: Debe ser escrita evitando palabras técnicas para facilitar la comprensión del cliente y gerente, detallando el ¿qué se va a realizar? y ¿cómo se lo va a realizar?
- Observación: Permite redactar indicaciones adicionales para el equipo de desarrollo.
```

>Comentario:<br />
>La descripción debe ser escrita evitando palabras técnicas para facilitar la comprensión del cliente y gerente, detallando el ¿Qué se va a realizar? y ¿Cómo se lo va a realizar?

### Pregunta 16
Explique la diferencia fundamental entre un requerimiento funcional y uno no funcional según la metodología :white_check_mark:

```plaintext
Los requerimientos funcionales son aquellos servicios o funciones que proveerá el software a sus usuarios, y la vez limitan lo que se puede y no puede hacer.

Los requerimientos no funcionales hacen referencia a características generales, tipos de restricciones o atributos de calidad. Pueden ser éticos, legislativos, etc.
```

### Pregunta 17
¿Cuál de las siguientes actividades corresponde estrictamente a la fase de Planificación?

* a. Redacción del manual del programador
* b. Gestión de Stakeholders y definición del Alcance :white_check_mark:
* c. Pruebas de mantenibilidad

>Su respuesta es correcta.
>
>La respuesta correcta es: Gestión de Stakeholders y definición del Alcance

### Pregunta 18
El gerente de proyecto es el responsable máximo de la gestión de recursos materiales, tecnológicos y humanos

* Verdadero :white_check_mark:
* Falso

>La respuesta apropiada es 'Verdadero

### Pregunta 19
¿Por qué el patrón MVC se considera una opción destacada para el desarrollo de Productos Mínimos Viables (MVP)?

* a. Porque la separación de tareas permite iterar rápidamente y modificar partes sin afectar a otras. :white_check_mark:
* b. Porque elimina automáticamente la sobrecarga de responsabilidades en los controladores
* c. Debido a que permite el manejo nativo de interfaces de usuario sumamente complejas

>Su respuesta es correcta.
>
>La respuesta correcta es: Porque la separación de tareas permite iterar rápidamente y modificar partes sin afectar a otras.

### Pregunta 20
¿Cuál es el propósito fundamental de implementar un diseño modular en la interfaz?

* a. Limitar el acceso del cliente a las funciones críticas del sistema
* b. Facilitar el escalamiento y desarrollo tanto de aplicaciones simples como complejas. :white_check_mark:
* c. Reducir el consumo de batería del dispositivo móvil

>Su respuesta es correcta.
>
>La respuesta correcta es: Facilitar el escalamiento y desarrollo tanto de aplicaciones simples como complejas.

### Pregunta 21
La metodología *MMS* se clasifica técnicamente como un modelo de enfoque puramente tradicional o en cascada

* Verdadero
* Falso :white_check_mark:

>La respuesta apropiada es 'Falso

### Pregunta 22
¿Cuáles son los componentes esenciales de la documentación técnica generada en la fase de lanzamiento?

* a. Acta de constitución y diccionario de datos
* b. Manual de usuario y manual de programador :white_check_mark:
* c. Solo el historial de versiones del software

>Su respuesta es correcta.
>
>La respuesta correcta es: Manual de usuario y manual de programador

### Pregunta 23
¿Qué componentes deben residir habitualmente dentro del directorio destinado a la "Vista"?

* a. Archivos de sonido, música y hashtags sin procesar
* b. Lógica de negocio y objetos de transferencia de datos
* c. Guiones gráficos (Storyboards), archivos XIB y subclases UIView personalizadas :white_check_mark:

>Su respuesta es correcta.
>
>La respuesta correcta es: Guiones gráficos (Storyboards), archivos XIB y subclases UIView personalizadas

### Pregunta 24 - Parcialmente correcta
Identifique al menos tres módulos lógicos del diseño modular y explica brevemente la función de uno de ellos que no sea visible para el usuario final

```plaintext
- Módulo de autenticación: En el se gestiona e implementa procesos para validar el tipo de sesiones y control de acceso a la aplicación por medio de una cuenta de usuario.
- Módulo de gestión de datos: Tiene como objetivo principal gestionar la accesibilidad al consumo de información almacenados en la base de datos.
- Módulo de servicios: A nivel de clases, pueden representarse todas aquellas funcionalidades que provienen de aplicaciones externas o terceras que intervienen en el correcto funcionamiento de la aplicación. Por ejemplo: APIs externas.
```

>Comentario:<br />
>Los define todos, pero no especificó cuál es no visible para el usuario

### Pregunta 25 - Parcialmente correcta
¿Cuál es el objetivo principal de la fase de **planificación** en la metodología *MMS*?

```plaintext
Se encarga de gestionar eficientemente los recursos y establecer las actividades necesarias para lograr el proyecto. Una correcta planificación reduce costos y tiempo.
```

### Pregunta 26 - Parcialmente correcta
¿Qué transformación específica se busca lograr durante la fase de diseño respecto a los requisitos del cliente?

```plaintext
Transformar cada requisito en un módulo, esto para clarificar el flujo de información que pueden mantener entre dichos módulos por medio de sus conectores o enlaces.
```

### Pregunta 27
¿Qué herramientas se especifican en el modelo para la gestión de repositorios y relación de código en la ejecución?

* a. GitHub y Azure DevOps :white_check_mark:
* b. Docker y Kubernetes
* c. Slack y Trello

>Su respuesta es correcta.
>
>La respuesta correcta es: GitHub y Azure DevOps

### Pregunta 28
Proporcione un ejemplo de un beneficio tangible y uno intangible que una empresa espera obtener al automatizar procesos con *MMS*. :white_check_mark:

```plaintext
- Tangible: Reducción de recursos

- Intangible: Mejora toma de decisiones
```

### Pregunta 29
¿Qué factores resultan determinantes para asegurar una valoración positiva de la app por el usuario final?

* a. Únicamente la resolución de los activos gráficos
* b. Rendimiento, eficiencia, compatibilidad y usabilidad :white_check_mark:
* c. Costo de adquisición y marketing digital

>Su respuesta es correcta.
>
>La respuesta correcta es: Rendimiento, eficiencia, compatibilidad y usabilidad

### Pregunta 30 - Parcialmente correcta
Describa la utilidad de realizar "observaciones múltiples" desde diferentes perspectivas antes de generar un modelado robusto.

```plaintext
Permite contemplar la mayor cantidad de aspectos lo cual facilita la realización de unificar los diagramas y generar un modelo de mayor robustez para el desarrollo de soluciones que satisfagan los requerimientos del sistema.
```

### Pregunta 31
La metodología *MMS* promueve un desarrollo basado en módulos con un alto grado de independencia entre sí :white_check_mark:

* Verdadero :white_check_mark:
* Falso

>La respuesta apropiada es 'Verdadero

### Pregunta 32
Mencione y defina brevemente los tres tipos de **factibilidad** que deben analizarse antes de iniciar el proyecto :white_check_mark:

```plaintext
- Factibilidad operativa: Relacionada con los recursos internos de la empresa, en especial el humano, ya que es el que desarrollará todas las fases del proyecto. Por lo que hay que evaluar si están en capacidad de llevar a cabo el proyecto asignado

- Factibilidad técnica: Relacionada a la infraestructura de la empresa. Analiza si cuenta con los conocimientos suficientes, como el hardware y software necesarios para el proyecto.

- Factibilidad económica: Relacionada a evaluar si la empresa podrá asumir el coste de instalar y desarrollar el proyecto.
```

### Pregunta 33
Uno de los criterios de la refactorización en *MMS* es la omisión deliberada de sentencias y controles anidados

* Verdadero :white_check_mark:
* Falso

>La respuesta apropiada es 'Verdadero

### Pregunta 34
El control de procesos en segundo plano es una práctica recomendada para optimizar el consumo de datos y el almacenamiento

* Verdadero
* Falso :x:

>La respuesta apropiada es 'Verdadero

### Pregunta 35
¿En qué consiste la limitación técnica denominada "Massive View Controller" (Controlador de Vista Masiva)?

* a. En un controlador que asume demasiadas responsabilidades, dificultando la comprensión, prueba y depuración :white_check_mark:
* b. En un problema de acoplamiento donde la Vista intenta realizar funciones de persistencia
* c. En la saturación de archivos dentro del directorio del Modelo en aplicaciones pequeñas

>Su respuesta es correcta.
>
>La respuesta correcta es: En un controlador que asume demasiadas responsabilidades, dificultando la comprensión, prueba y depuración

### Pregunta 36 - Parcialmente correcta
Explique la relación secuencial entre el Modelo Entidad-Relación (MER) y el Modelo Relacional (MR) en esta metodología :white_check_mark:

```plaintext
Primero, se desarrolla el MER es donde se definen todos los atributos y relaciones que tendra una entidad de la base de datos.

Una vez obtenido el MER, se crea el MR, que transforma las entidades en conjuntos de tablas relacionadas entre sí, lo cual ayuda a ser más comprensible para personas no técnicas.
```

### Pregunta 37
Enumere los tres roles principales de los **interesados** definidos de forma similar a la metodología Scrum :white_check_mark:

* Gerente de Proyecto
* Analista de Requerimientos
* Equipo de desarrollo

### Pregunta 38
¿Qué modalidad de prueba de sistema se enfoca en evaluar la experiencia de navegación y facilidad de uso?

* a. Pruebas de Usabilidad :white_check_mark:
* b. Pruebas de Calidad
* c. Pruebas de Tendencia

>Su respuesta es correcta.
>
>La respuesta correcta es: Pruebas de Usabilidad

### Pregunta 39
¿A través de qué actividad específica se valida el enfoque centrado en el usuario durante la fase de Diseño?

* a. Mediante el análisis de factibilidad económica realizado por el gerente
* b. A través de la prueba de prototipos para ajustar aspectos de usabilidad antes de la codificación :white_check_mark:
* c. Mediante la codificación inmediata de los módulos de seguridad

>Su respuesta es correcta.
>
>La respuesta correcta es: A través de la prueba de prototipos para ajustar aspectos de usabilidad antes de la codificación

### Pregunta 40
¿Qué responsabilidades específicas corresponden al componente "Modelo"?

* a. Gestionar los datos, procesar las reglas de negocio y responder a solicitudes de información :white_check_mark:
* b. Presentar los datos al usuario final a través de elementos visuales intuitivos
* c. Capturar las entradas del usuario y enviarlas al controlador para su validación

>Su respuesta es correcta.
>
>La respuesta correcta es: Gestionar los datos, procesar las reglas de negocio y responder a solicitudes de información