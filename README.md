# 🎬 Proyecto ScreenMatch v3 - API RESTful y Front End

Este proyecto es la tercera versión del ScreenMatch, desarrollado como parte del programa de formación en Java de Alura Latam en colaboración con Oracle. En esta versión, se ha ampliado la funcionalidad para incluir una API RESTful y se ha conectado con un frontend, mejorando la experiencia del usuario y la gestión de datos de series y episodios.

## 📝 Descripción

ScreenMatch v3 es una aplicación Java que utiliza Spring Boot para crear una API RESTful que interactúa con una base de datos mediante JPA y Hibernate. La aplicación permite gestionar datos de series y episodios, conectándose a la API OMDb para obtener información en línea. Se ha desarrollado un frontend que interactúa con esta API, proporcionando una interfaz de usuario amigable. El proyecto también incluye consultas JPQL avanzadas para búsquedas específicas en la base de datos.

## 🚀 Funcionalidades

- **API RESTful:** Proporciona endpoints para gestionar series y episodios.
- **Integración con OMDb API:** Permite buscar información de series en línea.
- **Persistencia de datos:** Utiliza Spring Data JPA y Hibernate para interactuar con la base de datos.
- **Consultas avanzadas:** Realiza búsquedas y filtrados específicos mediante JPQL.
- **Interfaz de usuario:** Un frontend conectado a la API para facilitar la interacción con la aplicación.

## 📂 Estructura del Proyecto

El proyecto está organizado en varios paquetes, cada uno con responsabilidades específicas:

- `com.aluracursos.screenmatch.controller`: Contiene los controladores REST.
- `com.aluracursos.screenmatch.model`: Define las entidades de la base de datos.
- `com.aluracursos.screenmatch.repository`: Contiene las interfaces de repositorio JPA.
- `com.aluracursos.screenmatch.service`: Incluye servicios para la lógica de negocio.
- `com.aluracursos.screenmatch.principal`: Contiene la clase principal para la aplicación de consola (comentada).
- `com.aluracursos.screenmatch`: Clase principal para ejecutar la aplicación Spring Boot.

## 📑 Clases y Funcionalidades

### 📡 ScreenmatchApplication

- **Funcionalidad:** Clase principal para ejecutar la aplicación Spring Boot.
- **Método:**
  - `main`: Inicia la aplicación y se hace visible en el Front End.

### 🚀 ScreenmatchApplicationConsola

- **Funcionalidad:** Clase principal para ejecutar la aplicación de consola.
- **Métodos:**
  - `main`: Inicia la aplicación de consola.
  - `run`: Ejecuta el menú interactivo que hace consultas en la API de OMDB y guarda los registros en PostgreSQL.

## 🛠 Tecnologías Utilizadas

- **Java:** Lenguaje de programación principal.
- **Spring Boot:** Framework para crear aplicaciones Java.
- **Spring Data JPA:** Abstracción de persistencia.
- **Hibernate:** Framework de ORM.
- **OMDb API:** API para obtener información sobre series y películas.
- **PostgreSQL:** Base de datos utilizada.
- **HTML:** Lenguaje de marcado para la estructura de páginas web.
- **CSS:** Lenguaje de estilos para el diseño y presentación de páginas web.
- **JavaScript:** Lenguaje de programación para la interactividad en páginas web.
- **JPQL:** Lenguaje de consulta específico de Java Persistence Query Language utilizado para consultas avanzadas en bases de datos.
- **Maven:** Herramienta de gestión de proyectos.
- **IntelliJ IDEA:** Entorno de desarrollo.

## ▶️ Ejecución del Proyecto

Para ejecutar la aplicación:
1.- Puedes utilizar la clase `ScreenmatchApplicationConsola` para iniciar la aplicación de consola, en la que se te mostrarán una serie de opciones para hacer consultas en la BD o buscar nuevos datos en la API de OMDB y registrarlos en la BD.
2.- Puedes utilizar la clase `ScreenmatchApplication` para iniciar el servidor Spring Boot. La API RESTful estará disponible para interactuar con el frontend.

## 👨‍💻 Desarrollado por

David Velasco Fierros

## 📝 Notas Finales

Este proyecto es una evolución del ScreenMatch, integrando una API RESTful y un frontend para mejorar la gestión de datos de series y episodios. Se recomienda explorar y personalizar el código para adaptarlo a tus necesidades específicas.

## 📷 Capturas de Pantalla

![Captura app fullstack 1](https://github.com/DavidVF7/Screenmatch-FullStack-API-RESTful/assets/103916971/aaf1495d-0948-4604-93b9-42ef8cf07402)
![Captura app fullstack 2](https://github.com/DavidVF7/Screenmatch-FullStack-API-RESTful/assets/103916971/132e6d62-09c7-4225-9e4f-9917a9773d1f)
![Captura app fullstack 3](https://github.com/DavidVF7/Screenmatch-FullStack-API-RESTful/assets/103916971/a77ed3d4-f701-48b8-a69c-759931eaf7eb)
![Captura app fullstack 4](https://github.com/DavidVF7/Screenmatch-FullStack-API-RESTful/assets/103916971/8b19633e-61e9-489b-b281-9b6e7c5cafd9)
![Captura app fullstack 5](https://github.com/DavidVF7/Screenmatch-FullStack-API-RESTful/assets/103916971/0126b3a1-6907-41a6-a003-7d2be9187880)
![Captura app fullstack 6](https://github.com/DavidVF7/Screenmatch-FullStack-API-RESTful/assets/103916971/3701dded-ef75-4986-b94c-dd8f0a56f30c)
![Captura app fullstack 7](https://github.com/DavidVF7/Screenmatch-FullStack-API-RESTful/assets/103916971/72b0d22e-222f-48d7-9ef9-4892da359c33)
