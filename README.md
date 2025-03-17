# CRUD Web Application con Servicios REST

## Objetivo
Este proyecto tiene como objetivo aplicar los fundamentos del desarrollo web en Java utilizando tecnologías como JEE, Servlets y REST para la gestión de una aplicación CRUD (Create, Read, Update, Delete). Se busca demostrar el manejo de la base de datos, la exposición de servicios REST y la implementación de una interfaz web funcional.

## Presentación
El desarrollo se basa en una aplicación web que permite a los usuarios realizar operaciones básicas de CRUD sobre una base de datos utilizando Servicios REST. La aplicación está estructurada en capas para mantener un código limpio y modular.

## Desarrollo
### Aspectos Clave Trabajados

#### Diseño de la Interfaz de Usuario:
- Uso de JSP y HTML para la creación de vistas dinámicas.
- Implementación de formularios para la inserción y modificación de datos.

#### Manejo de Base de Datos:
- Configuración de Apache Derby como sistema de gestión de base de datos.
- Creación de tablas y definición de esquemas necesarios para almacenar información.
- Uso de consultas SQL para la manipulación de datos.

#### Lógica de Negocio:
- Implementación de Servlets y Servicios REST para manejar las solicitudes HTTP y procesar la lógica de la aplicación.
- Uso de JPA y JDBC para la conexión y ejecución de consultas en la base de datos.
- Implementación de controladores para la gestión de operaciones CRUD.

#### Servicios REST:
- Implementación de servicios RESTful usando JAX-RS y Jersey.
- Métodos GET, POST, PUT y DELETE para gestionar los recursos.
- Uso de JSON como formato de intercambio de datos.

#### Conexión entre la Interfaz y la Lógica:
- Integración de JSP con Servlets y REST para gestionar las interacciones del usuario.
- Uso de session attributes para mantener el estado de usuario.
- Implementación de redirecciones y respuestas dinámicas según la acción del usuario.

## Ejemplo de Funcionamiento
1. El usuario accede a la página principal y ve una lista de registros.
2. Puede agregar un nuevo registro completando un formulario y enviándolo.
3. Puede actualizar información de un registro existente desde la interfaz.
4. Tiene la opción de eliminar un registro con un solo clic.
5. Se utilizan servicios REST para la comunicación entre el frontend y el backend.

## Imágenes de Funcionamiento
![image](https://github.com/user-attachments/assets/fe25ee89-a8ce-44bc-8110-995649f5083a)
![image](https://github.com/user-attachments/assets/ef46d9d4-8737-49c8-b38d-5144c30c75c5)

## Conclusión
Este proyecto demostró la aplicación de conceptos fundamentales del desarrollo web en Java, incluyendo el uso de Servlets, JSP y Servicios REST. Se logró una aplicación funcional que permite gestionar registros de manera eficiente a través de una interfaz web dinámica y una API REST.

## Referencias
- Documentación oficial de Apache Derby.
- Guía de desarrollo web en Java con Servlets y JSP.
- Introducción a los Servicios RESTful con JAX-RS.

