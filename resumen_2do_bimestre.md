# Resumen de Contenidos – Programación II GR2SW
## 2do Bimestre

### Introducción
Durante el segundo bimestre de Programación II se trabajaron conceptos relacionados con el diseño de Software, la organización del código y el manejo de datos, el enfoque principal fue aprender a estructurar aplicaciones de forma ordenada, mantenible y escalable, aplicando buenas prácticas de programación.

---

### 1er Tema: Arquitectura del Sistema
Se estudió el uso de una arquitectura por capas que es la Arquitectura N-Layer, la cual permite separar responsabilidades dentro de una aplicación, esta arquitectura facilita el mantenimiento del sistema y evita la dependencia directa entre componentes.

Las principales capas trabajadas fueron:
- **Infrastructure**: Este package contiene utilitarios, configuraciones, logs y manejo de rutas.
- **Data Access**: se encarga de la conexión con la base de datos y la ejecución de consultas.
- **Business Logic**: maneja la lógica del negocio y procesa la información obtenida del Data Access.
- **UserInterface**: permite la interacción del usuario con el sistema, inicialmente mediante consola y luego con interfaz gráfica.

---

### 2do Tema: Diseño y Programación Orientada a Objetos
Se reforzó la importancia de "no programar sin diseño previo", utilizando diagramas de clases y diagramas de casos de uso antes de escribir código, las clases deben representar correctamente las tablas de la base de datos y cumplir con principios de encapsulamiento.

Se aplicaron las siguientes prácticas:
- Uso de atributos privados.
- Implementación obligatoria de getters y setters.
- Uso de constructores completos y uno vacío.
- Implementación del método toString() para visualizar el estado de los objetos durante la ejecución.

---

### 3er Tema: Manejo de Base de Datos
Se trabajó con bases de datos relacionales, enfocándose en la correcta creación de tablas y el uso de claves primarias que son las PK.  
Se aprendió a:
- Definir tablas mediante DDL.
- Usar claves primarias autoincrementales.
- Crear primero tablas independientes antes de aquellas que dependen de claves foráneas.
- Separar el código SQL del código Java mediante scripts.

Además, se analizó la importancia de no mezclar el código fuente con los datos y de mantener rutas dinámicas para evitar errores en producción.

---

### 4to Tema: Uso de DTO, DAO y Factory
Se introdujeron los conceptos de **DTO (Data Transfer Object)** y **DAO (Data Access Object)** para estructurar el acceso a los datos, la capa DAC representa la unión entre DAO y DTO, mientras que la BL actúa como intermediaria entre la base de datos y la interfaz, también se utilizó el patrón **Factory** para evitar la creación manual repetitiva de objetos y centralizar su gestión dentro de la lógica del negocio.

---

### 5to Tema: Interfaz Gráfica y UI
Se aprendieron conceptos como:
- Uso de paneles independientes para cada pantalla.
- Manejo de eventos mediante escuchadores.
- Organización de la interfaz con layouts como BorderLayout.
- Uso de pantallas de carga (Splash Screen).
- Separación clara entre la lógica y la interfaz.

---

### 6to Tema: Configuración y Manejo de Errores
Se implementaron clases de configuración global como **AppConfig**, encargadas de centralizar rutas y constantes del sistema, además se utilizó el manejo de excepciones y logs para registrar errores y facilitar la depuración del programa sin necesidad de adivinar el origen de los fallos.

---

### Conclusión de los temas de 2do Bimestre: 
Los contenidos del segundo bimestre me permitieron comprender la importancia del diseño, la organización del código y la separación de responsabilidades en una aplicación, estos conocimientos fortalecen las bases de la programación estructurada y orientada a objetos, preparandome para desarrollar sistemas más complejos y robustos en el futuro.