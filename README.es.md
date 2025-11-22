# Frontend Mentor – Solución al desafío *Profile Card Component*

Esta es mi solución al desafío **Profile Card Component** de [Frontend Mentor](https://www.frontendmentor.io/).  
El desafío me ayudó a mejorar mis **habilidades en HTML y CSS**, construyendo una tarjeta de perfil responsiva con jerarquía visual, accesibilidad y un diseño limpio.

## Tabla de Contenidos
- [Descripción General](#descripción-general)  
- [El Desafío](#el-desafío)  
- [Diseño](#diseño)  
- [Enlaces](#enlaces)  
- [Mi Proceso](#mi-proceso)  
- [Tecnologías Utilizadas](#tecnologías-utilizadas)  
- [Lo Que Aprendí](#lo-que-aprendí)

## Descripción General
Este proyecto es un **componente UI de tarjeta de perfil** que muestra información del usuario como foto de perfil, nombre, edad, ubicación y estadísticas sociales (seguidores, likes y fotos).

La interfaz incluye:
- Un diseño limpio y minimalista  
- Una tarjeta centrada y responsiva que se adapta al tamaño de pantalla  
- Un avatar superpuesto sobre un fondo con patrón  
- Consistencia visual mediante variables de CSS y tipografía importada desde Google Fonts  

## El Desafío
Los usuarios deben poder:

- Ver el diseño óptimo de la tarjeta dependiendo del tamaño de su dispositivo  
- Identificar una jerarquía visual clara entre la información del perfil y las estadísticas.  

## Diseño
### Diseño Desktop
![Desktop Design](./design/desktop-design.jpg)

### Diseño Mobile
<img src="./design/mobile-design.jpg" width="200px" alt="Diseño para móviles">

## Enlaces
- [GitHub Repository](https://github.com/mlopezl/my-version-of-profile-card-component-challenge)  
- [Live Demo](https://mlopezl.github.io/my-version-of-profile-card-component-challenge/)

## Mi Proceso
1. Analicé el diseño original e identifiqué las secciones principales del layout: encabezado, imagen de perfil, información del usuario y estadísticas.  
2. Construí una estructura semántica y escalable usando `<article>`, `<header>` y `<footer>`.  
3. Importé la tipografía desde Google Fonts y apliqué tamaños y pesos de fuente consistentes.  
4. Definí variables CSS en `:root` para mantener un sistema de colores cohesivo.  
5. Apliqué imágenes de fondo ubicadas con `position: fixed` para reproducir el diseño abstracto.  
6. Utilicé **Flexbox** y **CSS Grid** para alinear y distribuir los componentes internos de forma limpia.  
7. Implementé una adaptación responsiva mediante una media query para pantallas pequeñas.

## Tecnologías Utilizadas
- HTML5  
- CSS3  
- Flexbox  
- CSS Grid  
- Google Fonts  
- Variables de CSS  

## Lo Que Aprendí
- Cómo estructurar un componente UI reutilizable usando **HTML semántico**.  
- Cómo centrar contenido usando **Grid layout** y combinarlo con Flexbox en secciones internas.  
- Cómo usar **propiedades personalizadas de CSS (variables)** para lograr consistencia visual y facilitar el mantenimiento.  
- Cómo superponer elementos visualmente mediante **márgenes negativos** y estilos de borde.  
- Cómo escalar un diseño para pantallas móviles con pequeños ajustes visuales sin rediseñar por completo.
