# Profile Card - 100daysofprojects

[Profile Card] construido con HTML, CSS y JavaScript, para mejorar nuestras habilidades de codificación. Este proyecto es parte del desafío #100daysofprojects promovido por [Frontend Club](https://www.facebook.com/frontendclubfb).

![Screenshot](./images/modelo.jpg)

### Tabla de contenidos

- [Descripcion](#descripcion)
  - [El desafio](#el-desafio)
  - [Capturas](#capturas)
  - [Enlaces](#enlaces)
- [Flujo de trabajo](#flujo-de-trabajo)
  - [Desarrollo](#desarrollo)
  - [Recursos](#recursos)
- [Agradecimientos](#agradecimientos)
- [Contacto](#contacto)

## Descripcion

### El desafio

Codificar una **tarjeta de perfil personal**, usando HTML, CSS y JavaScript, y lograr que se parezca lo más posible al diseño.

Los usuarios deberían poder:

- Ver el diseño óptimo en pantallas grandes.
- Ver un color (`hover`) de fondo diferente al pasar el mouse sobre el ícono.

### Capturas

Así se verá en la pantalla de móvil, tabletas y escritorio.

![Captura](./images/phone.png)
![Captura](./images/tablet.png)
![Captura](./images/pc.png)
![Captura](./images/image.png)

> 💡Firefox te permite hacer capturas de pantalla haciendo clic derecho `Hacer captura de pantalla`.

### Enlaces

- [Repositorio](https://github.com/gabrielaDF/FrontendClub/tree/main/Proy01%20Profile%20card)

## Flujo de trabajo

### Desarrollo

Agrega el flujo de trabajo y las tecnologías que has utilizado para completar el proyecto.

Ejemplo:

**Estructura del proyecto**

```txt
/
📂

│ ├── normalize.css
│ └── style.css
├── 📂images/
└── index.html
└── README.md
```

**Tecnologías**

1. HTML Semántico
2. Estilos CSS
3. Animaciones CSS
4. Metodología BEM
5. Responsively App

**Flujo de desarrollo**

1. Análisis del diseño
2. Configuración inicial
   - Instalación de módulos y dependencias
   - Vincular archivos y librerías
   - Iniciar proyecto con Git
3. Marcado HTML
   - Etiquetas `meta`
   - Etiquetas `OG`
4. Estilos CSS
   - De arriba hacia abajo
   - Definición de variables
   - Estilos reutilizables
   - Estilos personalizados
   - Media queries
5. Flujo de trabajo `mobile-first`

**Fragmentos de codigo**

Etiquetas `meta` para el SEO.

```html
<meta name="author" content="Nombre del autor" />
<meta name="title" content="Título del proyecto" />
<meta
  name="description"
  content="Breve descripción del contenido del proyecto"
/>
<title>Profile Card - Frontend Club</title>
```

Menú de navegación HTML usando BEM.

```html
<nav class="main-nav" aria-label="Main">
  <ul class="main-nav__list">
    <li class="main-nav__item">
      <a href="#" class="main-nav__link">Home</a>
    </li>
    <li class="main-nav__item">
      <a href="#" class="main-nav__link">Work</a>
    </li>
    <li class="main-nav__item">
      <a href="#" class="main-nav__link">About us</a>
    </li>
  </ul>
</nav>
```

Animaciones CSS.

```css
/* Estilos básicos del div */
.scaley-div {
  width: 200px;
  height: 50px;
  background-color: #3498db;
  color: #fff;
  text-align: center;
  line-height: 50px;
  cursor: pointer;
  transition: transform 0.3s ease;
}

/* Estilo al hacer hover */
.scaley-div:hover {
  transform: scaleY(1.5);
}
```

## Contacto

Agrega los medios de contacto para que cualquiera pueda encontrarte y hablar sobre tus siguientes grandes proyectos.

- [LinkedIn](https://www.linkedin.com/in/gabriela-de-freitas-90529b121/)
- [GitHub](https://github.com/gabrielaDF)

---

> _La mejor manera de aprender a programar es practicando todos los días._ — **Frontend Club**
