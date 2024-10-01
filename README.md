# Heroes Marvel & DC - Single Page Application (SPA)

[![Netlify Status](https://api.netlify.com/api/v1/badges/1318b01e-b9b9-47d3-b74c-ae8c3ebf070e/deploy-status)](https://app.netlify.com/sites/heroesmarvelanddc-spa-react/deploys)(https://heroesmarvelanddc-spa-react.netlify.app/)

Este proyecto es una Single Page Application (SPA) desarrollada en React, utilizando Vite como herramienta de construcción y Yarn como gestor de dependencias. La aplicación permite a los usuarios explorar información de héroes de Marvel y DC Comics, con rutas públicas y privadas, y características como autenticación (sin backend), filtrado de héroes por query params, y recordatorio de la última ruta visitada.

Puedes ver la aplicación en vivo [aquí](https://heroesmarvelanddc-spa-react.netlify.app/).

## Características

- 📜 **SPA (Single Page Application)**: Navegación fluida sin recarga de página.
- 🔓 **Rutas públicas** y 🔐 **Rutas privadas**.
- 🔄 **Login y Logout** (sin backend aún).
- 📍 **Recordar última ruta visitada** para mejorar la experiencia del usuario.
- 🔄 **Manejo de rutas**: Implementación de múltiples routers.
- 🔍 **QueryParams & QueryStrings**: Lectura de parámetros por URL y aplicación de filtros.
- 🛠️ **Context y Reducer**: Gestión del estado de la aplicación.
- ⚡ **Vite**: Para un entorno de desarrollo rápido.

## Requisitos

- Node.js >= 18.0.0
- Yarn

## Instalación

Sigue estos pasos para clonar e instalar el proyecto en tu máquina local.

1. Clona el repositorio:

```bash
git clone https://github.com/manuelherreram/heroes-spa.git
```

2. Entra en el directorio del proyecto:

```bash
cd heroes-spa
```

3. Instala las dependencias usando Yarn:

```bash
yarn install
```

## Ejecución en Desarrollo

Para iniciar el servidor de desarrollo, usa el siguiente comando:

```bash
yarn dev
```

Esto ejecutará la aplicación en modo desarrollo. La aplicación estará disponible en [http://localhost:5173](http://localhost:5173).

## Compilación para Producción

Para construir la aplicación para producción, utiliza el comando:

```bash
yarn build
```

Los archivos compilados estarán en la carpeta `dist/`.

## Despliegue

La aplicación está desplegada en [Netlify](https://heroesmarvelanddc-spa-react.netlify.app/). Para hacer el despliegue en un servicio como Netlify o Vercel, sigue sus respectivas guías para proyectos basados en Vite.

## Dependencias Principales

- **React**: ^18.3.1
- **React Router DOM**: ^6.0.0
- **Vite**: ^5.4.1

## Contribuciones

Si deseas contribuir a este proyecto, por favor haz un fork del repositorio y crea una nueva rama para tus cambios. Luego envía un pull request y lo revisaré a la brevedad.

## Licencia

Este proyecto está bajo la licencia MIT.

---

Desarrollado por [Manuel Herrera](https://www.linkedin.com/in/manuelherreramontoya/).
