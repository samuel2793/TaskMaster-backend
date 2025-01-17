# TaskMaster Backend

## Descripción del Proyecto
TaskMaster Backend es una aplicación basada en **Spring Boot** que ofrece servicios backend para gestionar tareas de manera eficiente. Incluye características como persistencia de datos, validación, seguridad y una experiencia optimizada para el desarrollo.

---

## Tecnologías y Dependencias

### **Web**
- **Spring Web**: Construcción de aplicaciones web, incluyendo servicios RESTful, utilizando el modelo MVC de Spring. Usa Apache Tomcat como contenedor embebido predeterminado.

### **Base de Datos**
- **Spring Data JPA**: Persistencia de datos en bases de datos SQL mediante Java Persistence API (JPA), con el soporte de Hibernate.
- **H2 Database**: Base de datos en memoria, rápida y ligera (2 MB), con soporte JDBC y acceso R2DBC. Incluye modos embebidos y servidor, además de una consola basada en navegador.
- **MySQL Driver**: Controlador JDBC para conexión con bases de datos MySQL.

### **Herramientas de Desarrollo**
- **Spring Boot DevTools**: Herramientas para reinicio rápido de aplicaciones, soporte LiveReload y configuraciones para mejorar la experiencia de desarrollo.
- **Lombok**: Biblioteca de anotaciones para reducir el código repetitivo en Java.

### **Validación**
- **Hibernate Validator**: Implementación de Bean Validation para garantizar la consistencia de los datos.

### **Seguridad**
- **Spring Security**: Marco altamente personalizable para la autenticación y el control de acceso.
- **OAuth2 Client**: Integración con Spring Security para las funcionalidades de cliente OAuth2/OpenID Connect.
