# Admistrador-construccion-
Administración para una empresa de construcción 
AdminConstrucciónPro es una aplicación desarrollada en Java para facilitar la administración operativa y técnica de una empresa constructora. Permite registrar empleados, clientes, proyectos, asignar tareas y generar reportes de manera ordenada y centralizada.

Problema Identificado
Las pequeñas y medianas empresas constructoras suelen depender de registros manuales o múltiples hojas de cálculo, lo cual genera:

Pérdida de información.

Dificultad para llevar seguimiento de proyectos.

Falta de control sobre tareas y recursos.

Mala comunicación entre responsables.

Solución Propuesta
Diseñar un sistema modular que permita:

Registrar y consultar datos de empleados, clientes y proyectos.

Asignar tareas y generar reportes por proyecto.

Guardar y recuperar información desde archivos CSV (versión ligera) o base de datos (en futuras versiones).

Implementar versiones futuras con interfaz gráfica o acceso web.

Arquitectura del Proyecto
MVC – Modelo Vista Controlador
modelo/
Clases de datos (Empleado, Proyecto, Tarea...)
vista/
 Consola (versión actual), interfaz gráfica (futuro)
controlador/
Lógica de negocio y validación
utils/
Lectura y escritura de archivos CSV
Principal.java
Tabla de Contenidos
Descripción

Problema Identificado

Solución Propuesta

Arquitectura del Proyecto

Requerimientos

Instalación

Configuración

Uso

Contribución

Roadmap

Producto
Requerimientos
Versión de Java
Java SE 8 o superior

IDE
Apache NetBeans 12.5+

Servidores
No requiere servidor web en la versión actual

Futuras versiones podrían implementar:

Servidor GlassFish, Apache Tomcat (si se pasa a web)

Heroku o Railway (para implementación en la nube)

Librerías / Paquetes adicionales
Ninguna (versión base)

Para versión con GUI: javax.swing

Para versión web futura: Jakarta EE, JSP, Servlets, JDBC
