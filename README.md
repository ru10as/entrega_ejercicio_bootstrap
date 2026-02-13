# entrega_ejercicio_bootstrap
Este proyecto consiste en el desarrollo de una interfaz web completa utilizando Bootstrap 5, enfocada en la creacion de sitios rapidos, responsivos y modernos. Se divide en dos ejercicios: una landing page publica y un panel de administracion (Dashboard).

# EJERCICIO 1
## Proyecto RuMbo - Agencia de Viajes
Este proyecto consiste en el desarrollo de una pagina de agencia de viajes, utilizando Bootstrap 5 como framework principal para garantizar un diseño responsivo, moderno y funcional.

## Objetivos del Proyecto
Crear una home pública con: 
- a. Logo 
- b. Idiomas 
- c. Input para buscador 
- d. Menú desplegable y responsivo 
- e. Carrusel fotográfico 
- f. Título o eslogan animado con anímate.css 
- g. Dos bloques 50-50 texto e imagen 
- h. 4 bloques responsivos 
- i. Bloque con pestañas o acordeones 
- j. Dos bloques responsivos con formulario de login y mapa (como imagen) 
- k. Pie diferenciado con tres bloques

## Procedimiento de Implementacion
Para lograr los objetivos propuestos, se ha seguido el siguiente flujo de trabajo tecnico:

**1. Estructura de Navegacion y Cabecera**
- Se ha implementado una navbar de Bootstrap con la clase sticky-top para mantener la navegacion siempre visible. 
- Se incluyo un Logo personalizado y un menu Dropdown para la gestion de idiomas y exploracion de destinos.
- Se integro un fomato de busqueda directamente en la barra de navegacion para mejorar la usabilidad.

**2. Elementos Visuales y Animaciones**
**Titulo Animado:** Se utilizo la libreria Animate.css aplicando la clase animate__fadeInDown al encabezado principal para captar la atencion del usuario.

**Carrusel:** Se configuro un componente carousel con indicadores y controles de navegacion para mostrar imagenes de alta calidad de destinos paradisiacos.

**3. Organizacion de Contenidos (Grid System)**
**Bloques 50-50:** Se diseñaron secciones utilizando filas (row) y columnas (col-md-6) para equilibrar texto e imagenes de ofertas de cruceros.

**Bloques Responsivos (4 columnas):** Para la seccion de "Destinos TOP", se utilizo una rejilla de col-md-3, que permite visualizar 4 tarjetas en escritorio y se apila verticalmente en moviles.

**4. Componentes de Informacion y Registro**
**Pestañas (Tabs):** Se implemento un sistema de navegacion por pestañas (nav-tabs) para organizar de forma limpia la informacion de viajes, itinerarios, precios y una galeria interna sin recargar la pagina.

**Seccion de Acceso y Mapa:** Se dividio un contenedor en dos columnas; la izquierda contiene el Formulario de Login con validacion visual basica de Bootstrap, y la derecha muestra la ubicacion de la agencia mediante una imagen de mapa optimizada con la clase img-fluid.

**5. Pie de Pagina (Footer)**
Se estructuro un pie de pagina diferenciado en tres bloques principales:
- Informacion de marca.
- Enlaces legales y corporativos.
- Datos de contacto y ubicacion fisica.

**6. Optimizacion y Estilos Personalizados**
Se añadieron reglas de CSS especificas para el control de altura de imagenes (object-fit: cover) asegurando que el diseño no se rompa independientemente de la resolucion de las fotos utilizadas.


____________________________________________________________________________________________


# EJERCICIO 2
## Descripcion del Proyecto
Este ejercicio consiste en el desarrollo de una interfaz de administracion para un gimnasio utilizando el framework Bootstrap. El objetivo es crear un panel funcional que permita gestionar activos, personal y aforo de forma centralizada y adaptable a cualquier dispositivo.

## Requisitos Cumplidos
**Columna izquierda y menu:** Se ha implementado una estructura de rejilla donde la navegacion ocupa una columna lateral persistente en escritorio y se reposiciona en dispositivos moviles.

**Breadcrumb:** Se incluye una ruta de navegacion jerarquica para mejorar la ubicacion del usuario dentro de la aplicacion.

**Tablas:** Uso de tablas dinamicas para las secciones de Tienda e Inventario, optimizadas para lectura rapida.

**Botones y Modal:** Integracion de una ventana emergente para la gestion del Staff, permitiendo visualizar datos sin cambiar de pantalla.

**Barras de progreso:** Sistema de monitorizacion de aforo por salas con indicadores de color segun el nivel de ocupacion.

**Popovers y Tooltips:** Incorporacion de mensajes flotantes para acciones rapidas y especificaciones tecnicas de maquinaria.

## Tecnologias Utilizadas
- HTML5 y CSS para la estructura y estilos base.
- Bootstrap para los componentes y el sistema responsive.
- Iconos de Bootstrap para los botones y menus.
- JavaScript para la inicializacion de los componentes interactivos.

## Adaptabilidad
- La pagina utiliza el sistema de columnas de Bootstrap para reordenar los elementos segun el ancho de pantalla:
    - En ordenadores se muestra el menu lateral y contenido en paralelo.
    - En moviles el menu se situa en la parte superior y las tablas activan un desplazamiento horizontal para no romper el diseño.