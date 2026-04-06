
APLICACIONES Y TECNOLOGÍAS DE LA WEB - SOLEMNE 01 PRÁCTICO

Instrucciones y Condiciones de Evaluación
•	Se debe desarrollar en parejas, estas las deben decidir al momento de la evaluación
•	Los resultados deben ser subidos al recurso blackboard dispuesto para ello
•	Esta debe ser desarrollada durante la hora de clases, disponen de 120 minutos para desarrollar el presente enunciado
•	Puede usar su repositorio GIT, cualquier otra página o código que no se encuentre en GIT se considerará como copia, y hará que el equipo obtenga un 1.0
•	Este parte representa el 60% de la nota de solemne 01
•	Tecnologías permitidas: HTML5, CSS3, Git/GitHub,Dockers.
•	No se permite usar frameworks CSS (Tailwind, etc.) ni JavaScript, se acepta el uso de Bootstrap, en base a lo solicitado en el enunciado.
•	Se evaluarán tres ejes:
o	Dominio de HTML5/CSS3 y semántica.
o	Aplicación de buenas prácticas de código y TDD visual.
o	Uso básico de Git/GitHub y organización del trabajo.

Enunciado general
Como se ha indicado anteriormente, la parte práctica de la prueba solemne corresponde al 60% de la nota de la evaluación y se desarrollará en parejas. El trabajo consiste en diseñar, implementar, versionar y ejecutar un sitio web multipágina de al menos 7 páginas, usando HTML5, CSS3, Bootstrap en 2 páginas, Git/GitHub y Docker, manteniendo coherencia visual y estructural entre todas las páginas.
El proyecto debe demostrar dominio de estructura semántica HTML, estilos CSS organizados, componentes principales de interfaz, buenas prácticas de codificación, trabajo con repositorios Git y un entorno de ejecución reproducible apoyado en contenedores, coherente con los contenidos del curso.
Contexto del proyecto
La Escuela de Ingeniería desea disponer de un micrositio institucional para difundir un programa académico o servicio digital. Cada pareja deberá construir un sitio web para uno de estos contextos, o uno equivalente aprobado por el docente:

•	Feria tecnológica universitaria.

El sitio debe tener una identidad consistente y profesional, por lo que todas las páginas deben compartir layout general, sistema de navegación, tipografía, paleta de colores y estilo visual coherente. No se aceptará que cada página parezca un sitio distinto ni que unas páginas usen una lógica visual incompatible con otras.
Requerimientos obligatorios
El sitio debe contener mínimo 7 páginas HTML distintas. Cada página debe ser navegable desde un menú común o desde enlaces claramente visibles, deben incluir, como mínimo, estas 7 páginas o equivalentes funcionales:
1.	Inicio: portada del sitio, presentación general y llamada a la acción.
2.	Nosotros / Institución / Programa: descripción detallada del proyecto o institución.
3.	Oferta / Servicios / Módulos: detalle de cursos, servicios o funcionalidades.
4.	Equipo / Docentes / Organizadores: tarjetas o fichas de personas.
5.	Galería / Noticias / Recursos: contenido visual o informativo adicional.
6.	Formulario de contacto o inscripción: formulario HTML estructurado.
7.	Preguntas frecuentes o página de detalle: sección adicional útil al usuario.

Componentes principales de interfaz
El proyecto debe obligatoriamente incorporar componentes principales de interfaz, distribuidos adecuadamente entre las páginas. Deben estar presentes al menos estas categorías:
•	Navegación: navbar, menú principal, breadcrumbs o menú lateral.
•	Contenido: cards, tablas, listas, secciones informativas, acordeones o paneles.
•	Interacción: formularios, botones, selectores, inputs, enlaces de acción.
•	Feedback: alertas, badges, mensajes visuales, estados destacados o validaciones visuales.

Además, la pareja deberá agregar un README indicando qué componentes usó y a qué categoría pertenecen, siguiendo la clasificación trabajada en clases.
Uso obligatorio de Bootstrap
Al menos 2 de las 7 páginas deben estar desarrolladas con Bootstrap 5 mediante CDN, incorporando componentes reales del framework. En esas dos páginas deben usarse al menos 3 componentes Bootstrap correctamente implementados, por ejemplo:
•	.navbar
•	.card
•	.btn
•	.form-control
•	.alert
•	.accordion
•	.modal o equivalentes si la solución lo permite.
Las páginas con Bootstrap deben integrarse visualmente con el resto del sitio. Aunque algunas páginas usen CSS propio y otras Bootstrap, todo el proyecto debe mantener coherencia de layout, diseño y colores.
HTML5 y CSS3
Todo el sitio debe construirse con HTML5 semántico y CSS3. Se espera uso correcto de:
•	<!DOCTYPE html>
•	<html>, <head>, <body>
•	<header>, <main>, <section>, <article>, <footer>
•	encabezados jerárquicos
•	listas, tablas, imágenes, enlaces, formularios.

El CSS debe estar organizado principalmente en archivos externos. No se permiten estilos inline salvo casos muy justificados. El código debe ser legible, indentado y con nombres significativos para clases e identificadores.
Coherencia visual obligatoria
Todas las páginas deben compartir:
•	misma identidad visual general;
•	paleta de colores consistente;
•	tipografía coherente;
•	estructura de encabezado y pie similar;
•	mismo criterio de espaciado y distribución;
•	navegación consistente entre páginas.

Esto responde al principio de código mantenible y diseño consistente visto en buenas prácticas, evitando soluciones fragmentadas o improvisadas.
Docker obligatorio
El proyecto debe ejecutarse mediante Docker. Cada pareja debe preparar una solución mínima para levantar el sitio en el laboratorio usando contenedores a través de un Dockerfile. 
El objetivo es que el sitio pueda ejecutarse de manera reproducible en un entorno tipo Unix/Linux, coherente con la relevancia de Linux, despliegue y contenedores en desarrollo web.
La solución Docker debe permitir:
•	levantar el sitio localmente;
•	servir correctamente las 7 páginas;
•	exponer el sitio en un puerto local;
•	ejecutar la solución sin depender de configuraciones manuales complejas.


Git y GitHub obligatorios
El proyecto debe mantenerse en un repositorio GitHub público. La pareja debe evidenciar trabajo colaborativo mediante Git, usando al menos:
•	repositorio remoto en GitHub;
•	commits significativos;
•	al menos una rama de trabajo adicional a main;
•	integración final a la rama principal.

Git y GitHub se consideran parte esencial del trabajo en equipo y del versionado profesional del código.
TDD visual y verificación
Aunque no se exige automatización formal, la construcción del sitio debe inspirarse en la lógica Red–Green–Refactor, definiendo criterios visuales y validándolos progresivamente. Esto es especialmente importante para layout, responsividad y estilos compartidos, se recomienda que cada pareja documente al menos una checklist breve de verificación de interfaz, por ejemplo:
•	menú visible y consistente;
•	cards alineadas;
•	formulario legible;
•	diseño responsive;
•	coherencia de colores;
•	páginas Bootstrap integradas al diseño general.

Instrucciones 
1.	Formar una pareja de trabajo.
2.	Definir el tema del micrositio según el contexto dado.
3.	Diseñar la arquitectura del sitio considerando al menos 7 páginas.
4.	Implementar el sitio con HTML5 y CSS3.
5.	Incorporar Bootstrap en 2 páginas como mínimo.
6.	Usar componentes de navegación, contenido, interacción y feedback.
7.	Mantener coherencia global entre todas las páginas.
8.	Versionar el proyecto con Git y subirlo a GitHub.
9.	Preparar la ejecución del sitio mediante Docker.
10.	Probar el funcionamiento en laboratorio.







Restricciones
•	No se permite entregar una sola página extensa en lugar de 7 páginas.
•	No se permite usar JavaScript como eje principal si el objetivo es suplir carencias de estructura HTML/CSS; el foco evaluado está en estructura, estilos, componentes y organización.
•	No se aceptarán sitios con páginas inconexas visualmente.
•	No se aceptará un proyecto sin Docker ni entregado a través de un repositorio GitHub.

Entregables
Cada pareja debe entregar:
•	Carpeta del proyecto.
•	index.html y el resto de páginas HTML.
•	Carpeta de estilos y recursos.
•	Archivos Dockerfile.
•	URL del repositorio GitHub.
•	Archivo breve README.md con:
•	nombres de los integrantes;
•	descripción del proyecto;
•	listado de páginas;
•	componentes principales de interfaz utilizados;
•	instrucciones para ejecutar con Docker.






