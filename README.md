CRUD Repaso – Proyecto JavaScript
📖 Descripción

Este proyecto es un CRUD básico en JavaScript que permite gestionar usuarios y explorar conceptos de programación asíncrona y manejo de objetos. Está diseñado como un repaso de conceptos clave de JavaScript moderno:

Callbacks
Promises
Async/Await
Destructuring de objetos

El proyecto combina JavaScript puro, HTML, CSS personalizado y Bootstrap 5 para crear una interfaz responsiva y moderna.

🗂 Estructura del proyecto
/proyecto-crud/
│
├─ index.html             # CRUD principal de usuarios
├─ callback.html          # Ejemplo de callbacks
├─ promise.html           # Ejemplo de Promises
├─ async.html             # Ejemplo de Async/Await
├─ objects.html           # Ejemplo de Destructuring de objetos
│
├─ css/
│  └─ styles.css          # Estilos personalizados
│
├─ js/
│  ├─ crud.js             # Lógica CRUD principal
│  ├─ callback.js         # Ejemplo de callback
│  ├─ promise.js          # Ejemplo de Promises
│  ├─ async.js            # Ejemplo Async/Await
│  └─ objects.js          # Ejemplo Destructuring
│
└─ README.md              # Documentación del proyecto
⚙ Funcionalidades
CRUD Principal (index.html)
Agregar, editar y eliminar usuarios (nombre, correo, documento)
Manejo de arrays en memoria usando promises y async/await para simular operaciones asíncronas
Validaciones básicas de campos
Tabla responsiva y estilizada con Bootstrap
Mensajes de error y confirmación visuales
Callback (callback.html)
Entrada de datos para un país
Demuestra el uso de callbacks para manejar la respuesta después de ejecutar una función asíncrona
Promises (promise.html)
Entrada de texto para verificar condiciones
Uso de Promises para controlar operaciones asíncronas
Resultados mostrados dinámicamente con estilos de Bootstrap
Async/Await (async.html)
Entrada de número para cálculos simulados
Uso de async/await para escribir código asíncrono de manera más legible
Resultados mostrados en un contenedor estilizado
Destructuring (objects.html)
Demostración de destructuring de objetos para extraer propiedades de manera simple
Resultados mostrados en un contenedor con estilo Bootstrap
🎨 Tecnologías utilizadas
JavaScript (ES6+): callbacks, promises, async/await, destructuring
HTML5 y CSS3
Bootstrap 5: diseño responsivo y componentes estilizados
🖥️ Cómo usar el proyecto
Clona o descarga el repositorio.
Abre index.html en tu navegador para usar el CRUD principal.
Navega por las demás páginas (callback.html, promise.html, async.html, objects.html) para ver los ejemplos de JavaScript.
Edita los archivos JS para experimentar con la lógica y mejorar el proyecto.
📌 Notas
El proyecto no utiliza base de datos, los datos se almacenan temporalmente en memoria.
Bootstrap se carga desde CDN para simplificar el despliegue.
El CSS personalizado (styles.css) se usa para pequeños ajustes visuales adicionales.
