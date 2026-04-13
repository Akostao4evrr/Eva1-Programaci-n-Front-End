# PNK Inmobiliaria - Gestión Inmobiliaria Profesional

## Descripción

PNK Inmobiliaria es una plataforma web profesional para la gestión inmobiliaria en la Región de Coquimbo, diseñada con un enfoque en eficiencia, calidad y accesibilidad. Combina herramientas avanzadas con un diseño limpio en blanco, grises y azules oscuros para una experiencia confiable.

## Características

- **Página Principal**: Encabezado con logo y botones de registro, sección hero con banner, sidebar de login, buscador por Provincia/Comuna/Sector, grilla de propiedades con detalles al "Ver Más".
- **Registro de Gestor Inmobiliario**: Formulario con RUT, nombre, fecha nacimiento, email, contraseña, sexo, teléfono, registro bienes raíces, y subida de certificado de antecedentes.
- **Registro de Propietario**: Formulario con RUT, nombre, fecha nacimiento, email, contraseña, sexo, teléfono, registro bienes raíces.
- **Login y Recuperación de Contraseña**: Autenticación con enlace a recuperación.
- **Dashboard Administrativo**: Panel con métricas, mantenedor de usuarios (CRUD) y mantenedor de propiedades (CRUD).
- **Registro de Usuarios**: Gestión de usuarios por administradores.
- **Registro de Propiedades**: Agregar nuevas propiedades al sistema.

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica con elementos como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<form>`, `<fieldset>`, `<legend>`, `<table>`.
- **CSS3**: Diseño profesional con paleta sobria (blancos, grises, azules oscuros), grid, flexbox, animaciones sutiles, responsividad.
- **JavaScript Básico**: Para modales de detalles de propiedades.
- **Accesibilidad**: ARIA labels, roles, contrastes adecuados, navegación por teclado.

## Diseño Profesional

- Paleta de colores corporativa: Blancos, grises, azules oscuros.
- Layout limpio y moderno con grids y flexbox.
- Transiciones suaves y efectos minimalistas.
- Interfaz intuitiva enfocada en usabilidad y accesibilidad.
- Enfoque regional: Buscador específico para Provincias de Elqui y Limarí.

## Detalles de Propiedad

Al hacer clic en "Ver Más" en una tarjeta de propiedad, se muestra un modal con:
- Área Construida
- Cantidad de baños y dormitorios
- Precio en UF
- Si cuenta con piscina, bodega o estacionamiento

## Estructura de Archivos

- `index.html`: Página principal completa con todas las secciones.
- `registro-gestor.html`: Registro de gestores.
- `registro-propietario.html`: Registro de propietarios.
- `login.html`: Login y recuperación.
- `dashboard.html`: Panel administrativo con mantenedores.
- `registro-usuarios.html`: Gestión de usuarios.
- `registro-propiedades.html`: Registro de propiedades.
- `styles.css`: Estilos globales organizados por secciones.
- `README.md`: Esta documentación.

## Cómo Ejecutar

Abre `index.html` en un navegador web moderno para explorar la plataforma. Las imágenes de propiedades son placeholders (casa1.jpg, etc.) y deben ser reemplazadas con archivos reales.

## Accesibilidad

La aplicación incluye:
- Atributos `aria-label`, `aria-labelledby`, `role`.
- Navegación por teclado.
- Contraste de colores WCAG compliant.
- Texto alternativo para imágenes.
- Estructura semántica clara.
- Tablas con roles apropiados.

## Futuro

Esta es la primera entrega estática. En futuras iteraciones, se integrará con backend para funcionalidad completa, base de datos y autenticación real.
