# Entrega de Proyecto: Interfaces Web con Bootstrap 5
Este repositorio contiene el desarrollo de una solucion web completa para el centro deportivo GYM RUBENS. El proyecto demuestra el uso avanzado de Bootstrap para crear una experiencia de usuario (UX) moderna, rapida y totalmente adaptativa (responsive).

## Organizacion del Repositorio
Para mostrar la evolucion del trabajo, el repositorio se ha dividido en tres carpetas principales:

**Ejercicio 1:** 
Desarrollo inicial de la Home Publica.

**Ejercicio 2:**
Desarrollo inicial del Panel de Administracion (Dashboard).

**Proyecto Completo (Final):** 
Version unificada y corregida. En esta carpeta, index.html y admin.html estan interconectados, permitiendo navegar entre la zona publica y la privada de forma fluida.

## 1. Home Publica (index.html)
Se ha diseñado una pagina de aterrizaje enfocada en la captacion de clientes y presentacion de servicios.

**Caracteristicas tecnicas:**
- Navegacion: Menu superior fijo (sticky-top) con buscador integrado y selector de idiomas mediante desplegables.
- Impacto Visual: Titulo animado con la libreria Animate.css y un carrusel fotografico profesional configurado para mantener la proporcion de las imagenes (object-fit: cover).
- Estructura de Contenidos: * Bloques 50-50 para ofertas destacadas.
- Rejilla de 4 columnas para las disciplinas deportivas, que se apilan automaticamente en moviles.
- Sistema de pestañas interactivas para organizar informacion de tarifas y horarios sin recargar la pagina.
- Conversion: Formulario de acceso para socios y mapa de ubicacion.

## 2. Panel de Administracion (admin.html)
Interfaz diseñada para la gestion interna del gimnasio, permitiendo al administrador supervisar el negocio de un solo vistazo.

**Herramientas incluidas:**
- Layout Profesional: Menu lateral persistente (sidebar) y sistema de Breadcrumbs para facilitar la navegacion.
- Monitorizacin en Tiempo Real: * Barras de Progreso: Indicadores de color (verde, amarillo, rojo) para el control de aforo en las salas.
- Tablas Dinamicas: Gestion de inventario y tienda con diseño table-responsive.
- Interactividad avanzada: * Uso de Modales para visualizar el listado de Staff sin cambiar de vista.
- Implementacion de Popovers y Tooltips para mostrar especificaciones tecnicas y ayuda rapida al usuario.

## 3. Adaptabilidad (Responsive Design)
El proyecto ha sido testado bajo una metodologia Mobile First, garantizando que:
- En moviles, el menu se convierta en un boton de tipo hamburguesa.
- Las columnas se reorganicen verticalmente para evitar el scroll horizontal.
- Todos los elementos interactivos sean faciles de pulsar en pantallas tactiles.

## Tecnologias Utilizadas
- Bootstrap 5.3.3: Framework principal para el diseño y componentes.
- Bootstrap Icons: Libreria de iconos vectoriales.
- Animate.css: Para las transiciones y animaciones del sitio.
- JavaScript: Inicializacion de componentes interactivos (pestañas, modales y avisos).