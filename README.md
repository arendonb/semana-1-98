# Proyecto final Sprint I

Desarrollar un sitio web que conste de 5 secciones, cada sección deberá ser realizada por un estudiante. Los diferentes elementos del sitio web contarán con estilos personalizados creados por los estudiantes y deberán estar condensados en una sola hoja de estilos.

Para iniciar con el desarrollo del sitio web, los estudiantes deberán definir previamente aspectos como ancho del sitio (mínimo 1200px), la información a presentar en el sitio web, diseñar un mockup, borrador o bosquejo, también descargar, diseñar o crear los recursos a utilizar como imágenes, iconos, logos, entre otros y finalmente asignar responsable a cada sección.

El proyecto, deberá manejarse versionado en un repositorio remoto en github, en el que los diferentes miembros del equipo deben tener acceso, no se permite el push directo a las ramas Dev o Master.

## Secciones

- Sección superior, cabecera o header: esta sección deberá contar con el menú de navegación a tres páginas internas del sitio web y su respectivo enlace al inicio. Debe contar con una imagen que ocupe el ancho del sitio.
  El menú debe de estar en un tag `<nav></nav>`.
- Sección de servicios: aquí los estudiantes deberán dividir en ancho del sitio en 3 partes y en cada parte se deberá incluir un servicio. Cada servicio debe contar con una breve descripción, un logo, ícono o imagen que lo identifique y un enlace al detalle de los servicios. El elemento donde están los servicios debe de tener un `id=”services”`
- Sección de noticias: El estudiante encargado de la sección de noticias, deberá dividir el ancho del sitio web en 2 filas y dos columnas para presentar 4 noticias. Cada noticia debe contar con un resumen, una imagen y un enlace a leer la noticia completa.
  El elemento donde están los servicios debe de tener un `id=”news”`

- Sección de equipo: El estudiante deberá dividir el ancho del sitio entre el número de participantes del equipo e incluir junto con cada uno una foto o imagen, el nombre y algún dato como la institución educativa, edad, pasatiempo, entre otros.
  El elemento donde están los servicios debe de tener un `id=”team”`

- Sección Footer o pie del sitio: el estudiante deberá crear el pie del sitio web en donde se incluye información de contacto, deberá estar dividido en dos partes, en una se tendrá la información del sitio web como el motivante del desarrollo y el enlace al repositorio de github, y en la otra los contacto de los miembros del equipo con sus nombres y roles. La sección debe de estar en un tag <footer></footer>

Este trabajo es realizado por:

Santiago Andrés Millan Pardo
Cristhian Daniel Diaz Salazar
Miguel Enrique Marquez Aldana
Alejandro Rendón Blandón

Inicialmente se crea el repositorio semana-1-98 en GitHub en blanco en la rama por defecto "main". En "main" se crea la rama "master" con el esqueleto
dado por la UTP para este trabajo.

Para probar el manejo de Git, se crea localmente la rama "iss1A" con los sigueintes cambios:
- Se actualiza todo el index.html con la plantilla esqueleto pagina sprint 1. Incluyendo el archivo style.css
- Se cambia el titulo de pagina y titulo principal a "semana-1-98"
- Se cambia la imagen del header por una mas bonita
- Se borra un integrante de los 5 previstos
- Se configura el perfil de Alejandro
- Luego se pasa a GitHub y se fusiona la rama "iss1A" con "master".

Lluego para probar la colaboración en Git, se crea la rama "iss2A" con los siguientes cambios:
- Se edita la noticia 4 (con el link respectivo) y el servicio 3 (sin el link)
- Luego se pasa a GitHub y se fusiona la rama "iss2A" con "master".

A partir de ahí se crea la rama "desarrollo" y se edita los campos personales de Cristian y se salva directamente.

Una vez estabilizado el contenido de "desarrollo" se asigna las tareas adicionales donde cada uno crea un issue resepctivo:
- issu3A se utilizó para crear la noticia 3 e integrarlo con desarrollo.
- issue-santiago se utilizó para crear los link del menu de inicio, noticia 1, servicio 1 y datos personal de Santiago
- issue1m se utilizó para crear la noticia 2, servicio 2 y datos personales de Miguel
- issue1c se utilizó para crear el footer y los id. 

Para los link de los servicios se decidió hacer una pagina plana donde se encuentre la descripción del servicio. Se ejecuto el issue y se integro a Desarrollo.

Al final se unen casa issue a desarrollo y finalmente se une con master.