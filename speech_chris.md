# Presentación

Hola

Hola a todos, soy Christian Villarroel, me pueden decir Chris. Y me desempeñó como Expertos Senior Data Scientist en Entel, es un rol de subgerente técnico. Mis responsabilidades son definir la metodología y herramienta para la explotación de los datos en la compañía

# Educativo y Laboral

Como herramienta de educación entiendo la utilidad de los Notebooks. En los últimos cinco años, he liderado a docenas de científicos de datos con distintas formaciones académicas, desde ingeniero comercial, industriales, electrónicos, estadísticos, matemáticos a astrónomos. Y mi propia formación universitaria es de ingeniero comercial. No somos desarrollares de software y sé lo difícil y abstracto que es empezar a programar. Una herramienta como un notebook apoya a entender que hace cada línea de código porque uno lo puede observar directamente en la herramienta y sin preocuparme mucho de la infraestructura que existe por debajo.

Hablemos de 3 actividades importantes que hacen los científicos de datos en una empresa y analicemos cómo apoyan o perjudican los Jupyter Notebook a la ejecución efectiva de estas tareas.

- Análisis exploratorio
- Creación de reportes  
- Desarrollo de un aplicativo analítico

# Análisis exploratorio

El análisis exploratorio es una actividad importante al un comienzo de un proyecto. Tenemos que entender qué datos utilizaremos y asegurar su calidad. De lo contrario, podría materializarse la famosa frase 'garbage in, garbage out'. Éste es un proceso bastante iterativo donde es necesario observar tablas de datos, gráficos, métricas y documentar los resultados o hipótesis encontradas. Los notebooks son una buena herramienta para realizar estas actividades. Si contamos con un ambiente con esta herramienta, es fácil ejecutar celda por celda para observar las tablas y gráficos resultantes, documentando todo en un mismo ambiente.

Si lo notaron, mencione notebooks, que es un concepto que engloba herramientas como Jupyter Notebook y a las alternativas que vamos a mencionar más adelante.

## Linting e IntelliSense

- En una oportunidad, con un colega del equipo, estábamos revisando una nueva fuente de información y queríamos validar si tenían los datos que estábamos esperando. El tiempo para validar era acotado porque teníamos que comunicar los hallazgos a la contraparte dentro de la próxima hora. Una buena herramienta para avanzar rápido fue una IDE con funcionalidades de 'linting' e 'IntelliSense', los cuales facilitan la escritura de código más limpio, eficiente y libre de errores. Los Jupyter Notebooks cuentan con una forma limitada de estas funcionalidades.

## Multilenguaje

- En la empresa en donde trabajo hay personas que tienen favoritismo por Python, R incluso Julia. Cada lenguaje tiene sus pro y contras. Suelo programar los modelos en Python, pero me gusta graficar con ggplot de R, entonces contar con un ambiente de trabajo que permita ocupar multi-lenguaje para tener la opción de elegir el mejor lenguaje para cada ocasión es relevante para mi. Veremos que Jupyter Notebook no cuenta con esta opción.

# Creación de reportes 

Al generar un reporte, queremos obtener un documento para informar los  resultados que encontramos en nuestro análisis a nuestro cliente de negocio, jefatura, colegas, etc.

## Orden de ejecusión

- Es muy relevante que el código sea reproducible, es decir, que al ejecutar el código se obtenga siempre el mismo resultado. Jupyter Notebook se presta para malas prácticas, como ejecutar celdas en distinto órden, sin que quede evidencia de aquello.

## Seguridad

- Otro punto importante en el ámbito laboral, es tener cuidado y proteger los datos sensibles y privados de nuestros clientes. Jupyter Notebook es peligro en este ámbito porque guarda esta información en el archivo JSON que luego uno puede publicar en un repositorio de Git.

# Desarrollo de un aplicativo analítico

Por último, tenemos la que en mi opinión, es la actividad más importante para  un científico de datos. El desarrollo de un aplicativo analítico. Aquí hay que entender que no es un desarrollo individual, sino un desarrollo para la empresa, donde hay que seguir las metodologías y prácticas definidas en lugar trabajo. Estas prácticas promueven el buen uso de los recursos, herramientas e infraestructura y permiten trabajar en equipo y a la vez documentar el proyecto de forma orgánica.

Nombraré 2 tareas dentro de esta actividad donde los Jupyter notebooks presentan problemas para su ejecución y rodo presentara los detalla en vivo.

## Formato JSON

- La primera tarea que les quiero comentar, es poder trabajar con control de versión de código, porque nos permite ver los cambios incrementales que se van programando. Por ejemplo, me ha tocado trabajar en paralelo con otro colega que avanzó usando jupyter notebook. Cuando me metí a revisar sus cambios para entender lo que había hecho, me encontre con 700 líneas editadas. Esto es porque Júpiter es un JSON por debajo. Esto dificulta trabajar colaborativamente con esta herramienta.

## Ejecutar código exclusivamente en celdas

- Otro problema del desarrollo de un proyecto analítico es que no solo hay que asegurar que el código funcione de principio a fin, sino que tambien hay que asegurar que las transforamciones tengan logica de negocio. Para asegurar un buen resultado de las predicciones, hay que ejecutar de manera minuciosa cada sección de código, asegurando que cada transformación de datos u otras operaciones hacen lo que deberían hacer. Cuando he tenido que revisar esto en Jupyte Notebook, me ha costado, porque te obliga a ejecutar celda por celda. Esto hace que uno tenga que intervenir mucho el codigo para ir ejecuando cada detalle.
