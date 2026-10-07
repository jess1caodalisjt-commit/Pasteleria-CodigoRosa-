# Pasteleria- Aplicacion Web para Pasteleria

Bienvenido al repositorio oficial del proyecto **Aplicacion web para pasteleria**. Este es un prototipo web desarrollado como parte de las actividades academicas de la materia **Desarrollo de aplicaciones web**.

---

## Datos Escolares y Equipo de Trabajo

- **Universidad:** Universidad Tecnologica de Leon
- **Carrera:** Ingenieria en Tecnologias de la Informacion e Innovacion Digital
- **Grupo:** LDSM 404
- **Docente:** Maria de Jesus Sanchez Solis
- **Nombre del Equipo:** Codigo Rosa
- **Fecha:** 06-10-2026

### Integrantes y Tareas Realizadas

| Integrante | Rol en el Proyecto | Tareas Realizadas |
| :--- | :--- | :--- |
| **Rodriguez Torres Nadia Guadalupe** | Integrante / Front-End | Creacion y subida de archivos al repositorio de GitHub, maquetacion de la pagina principal y formularios de acceso (index.html, login.html, registro.html). |
| **Garcia Romero Naomi Yiree** | Integrante / Front-End y Estilos | Apoyo en la eleccion de colores y tipografias, creacion de la hoja de estilos general (estilos/style.css) y vista del catalogo (consulta.html). |
| **Jimenez Tejeda Jessica Odalis** | Integrante / Front-End | Organizacion de las carpetas del proyecto, maquetacion del panel interno de cocina/pedidos (dashboard.html) y apoyo en la estructura general. |
| **Ramirez Carranco Emmanuel Alejandro** | Integrante / Pruebas y Documentacion | Revision de que las paginas se vean bien en celulares y computadoras, organizacion de capturas de pantalla y redaccion del README.md. |

---

## Descripcion del Proyecto

En esta plataforma los usuarios pueden navegar por todo el catalogo de productos, consultar precios al instante y revisar detalles de cada postre para elegir el tamano ideal para sus reuniones. 

El sistema permite hacer pedidos directamente desde la web y recibir la actualizacion de la entrega en tiempo real en la misma pagina. Ademas, el menu se mantiene actualizado ya que el equipo de la pasteleria administra los productos y precios desde el panel interno.

---

## Requerimientos del Sistema

### Requerimientos Funcionales (RF)

| Clave | Requerimiento Funcional | Vista / Archivo HTML | Componentes e Implementacion |
| :--- | :--- | :--- | :--- |
| **RF-01** | **Registro de Clientes:** Permitir a nuevos usuarios crear una cuenta con sus datos personales. | `registro.html` | Formulario estructurado con etiquetas `<form>`, `<label>`, `<input>` para nombre, correo y contrasena con validaciones basicas. |
| **RF-02** | **Inicio de Sesion:** Autenticar usuarios registrados y personal de la pasteleria. | `login.html` | Formulario de acceso con credenciales de prueba y redireccionamiento segun el tipo de usuario. |
| **RF-03** | **Consulta de Catalogo:** Mostrar la lista de productos disponibles con precios y descripciones. | `consulta.html` | Layout en cuadricula (Grid/Flexbox) con tarjetas de productos, imagenes, precios y detalles de tamano. |
| **RF-04** | **Gestion de Pedidos (Cocina):** Mostrar el estado y recepcion de pedidos en tiempo real. | `dashboard.html` | Panel de control interno con tabla de pedidos entrantes, estados de preparacion y datos de entrega. |
| **RF-05** | **Navegacion Principal:** Presentar la marca y permitir el acceso a todas las secciones. | `index.html` | Encabezado principal, menu de navegacion semantico `<nav>`, promociones de temporada y pie de pagina. |

### Requerimientos No Funcionales (RNF)

| Clave | Requerimiento No Funcional | Criterio de Aceptacion | Implementacion Tecnica |
| :--- | :--- | :--- | :--- |
| **RNF-01** | **Diseno Responsivo:** La interfaz debe adaptarse a dispositivos moviles, tabletas y computadoras. | El contenido se ajusta sin desbordamiento ni necesidad de desplazamiento horizontal. | Implementacion de Media Queries (`@media`) y unidades relativas en `estilos/style.css`. Capturas en `/docs/responsividad/`. |
| **RNF-02** | **Estructura Semantica:** El codigo HTML debe cumplir con los estandares de accesibilidad W3C. | Uso de etiquetas semanticas explicitas. | Uso estructurado de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>` en todas las paginas. |
| **RNF-03** | **Cohesion Visual e Identidad:** Mantener una paleta de colores y tipografias uniforme en todo el sitio. | Aplicacion constante de los estilos de la marca Codigo Rosa. | Definicion de variables CSS (`:root`) para colores principales, margenes y fuentes en `estilos/style.css`. |
| **RNF-04** | **Disponibilidad en Linea:** El prototipo debe ser accesible publicamente mediante servidor estatico. | Acceso continuo a traves de URL publica sin requerir servidor local. | Despliegue estatico configurado mediante GitHub Pages desde la rama principal. |

---

## Tecnologias Utilizadas

- **HTML5:** Estructura basica de las paginas utilizando etiquetas semanticas (header, nav, main, section, footer).
- **CSS3:** Hoja de estilos compartida (`estilos/style.css`) para diseno, colores, tipos de letra y adaptacion a distintos dispositivos.
- **Git y GitHub:** Control de versiones y trabajo colaborativo para subir el proyecto a internet.
- **GitHub Pages:** Plataforma para publicar el sitio web en linea.

---

## Enlace al Sitio en Linea

Puedes ver y navegar nuestro proyecto publicado en el siguiente enlace:  
 **[Ver Proyecto en GitHub Pages](https://yireegar.github.io/Pasteleria/)**


## Estructura de Archivos

```text
Pasteleria-CodigoRosa-/
├── estilos/
│   └── style.css
├── imagenes/
├── docs/
│   ├── mapa-navegacion.pdf
│   └── responsividad/
├── consulta.html
├── dashboard.html
├── index.html
├── login.html
├── registro.html
└── README.md
