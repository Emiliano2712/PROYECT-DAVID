# PROYECT-DAVID [![build](https://img.shields.io/badge/Build-0.0.1-green.svg)](https://semver.org) [![](https://img.shields.io/badge/Develop-ON-yellow.svg)](https://semver.org)
PROYECT-DAVID es una aplicación web progresiva ([PWA](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)) que busca simplificar la manera en que se gestionan los equipos de servidores en las áreas de la iglesia, así como poder tener información en tiempo real de dichos equipos.

> **Nota:**  **PROYECT-DAVID** no es el nombre final de la plataforma solo el nombre en clave del proyecto.

## Informacion general
Trabajaremos en implementar funcionalidades de planeación de equipos tales como:

 - Creación de equipos de trabajo
 - Perfiles de usuario
 - Asignación de roles
 - Control de acceso
 - Invitaciones a un equipo
 - Notificaciones y mensajes
 - Estadísticas en tiempo real

Estas son características inspiradas de otros proyectos tales como [Planning Center](https://www.planningcenter.com/) (de pago).

> **Véase también:**  [StackEdit](https://stackedit.io/) o [Flipboard](https://flipboard.com) como ejemplos de PWA's bien ejecutadas.

## Tecnologías
Las tecnologías propuestas idealmente para este proyecto son en su mayoría basadas en Javascript como lenguaje de programación principal.

 - [React JS](https://es.reactjs.org/) v17.0.2 (componentes funcionales)
 - [Node JS](https://nodejs.org/es/) v16.13.0 LTS 
 - [Express JS](https://expressjs.com/es/) v4.x
 - [Mysql](https://dev.mysql.com/) (Community)
 - [Git](https://git-scm.com/) v2.33

Los frameworks derivados de dichas tecnologías serán evaluados con  el equipo involucrado en desarrollar el feature correspondiente de la aplicación.

## Estructura del proyecto
La estructura básica del proyecto propuesta es la siguiente

 - Frontend
	 - Container
	 - Modules
		 - Module 1
			 - Components
			 - Hooks
			 - Css
		 - Module 2
			 - Components
			 - Hooks
			 - Css
		 - Module ...

 - Backend
	 - Middleware
		 - Module 1
		 - Module 2
		 - Module ...
	 - Services
		 - Module 1
		 - Module 2
		 - Module ...
	 - Utils

>**Importante:** Con la estructura propuesta intento expresar una arquitectura modular intentando evitar lo máximo posible tener un monolito de código o código "spaghetti", no es mi intención limitar sus capacidades técnicas para desarrollar arquitecturas.