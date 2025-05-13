# Descripción general del proyecto BC61

El sistema a desarrollar está planteado en el contexto del negocio bancario que a medida que se va avanzando en los proyectos, se irá ampliando en base a este mismo proyecto.
Tiene como objetivo aprender y mejorar las habilidades necesarias para el desarrollo de las funciones dentro de la organización.

- Desarrollo de microservicios con Java 8, 11 
- Utilizar Spring Boot Webflux como framework base. 
- El proyecto debe utilizar Maven como manejadores de dependencias. 
- Los microservicios proporcionados deben implementar controladores REST. 
- Usar el patrón database per service, por lo que un microservicio no puede tocar ninguna tabla o colección que utilice otro microservicio. 
- Utilizar inyección de dependencias. 
- Aplicación de diagramas UML.
- Utilizar propiedades de configuración externalizadas con un Config Server. 
- Los nombres de las clases, métodos y las URLs deberán estar en inglés. 
- La base de datos a utilizar será MongoDB. 
- Uso de Lombok para reducir código. 
- Manejo de trazas con Logback y utilizar el nivel del log adecuado.

----

En base al analisis de los requisitos funcionales y no funcionales se ha realizado los siguientes diagramas UML:

## Diagrama de casos de uso
![Diagrama de casos de uso](/assets/images/diagram-use-cases.jpg)


## Diagrama de componentes

![Diagrama de componentes](/assets/images/diagram-components.jpg)


## Repositorios adjuntos (componentes)
- [user-service](https://github.com/JuanEscurra/user-service)
- [product-service](https://github.com/JuanEscurra/product-service)
- [transaction-service](https://github.com/JuanEscurra/transaction-service)
- [config-server](https://github.com/JuanEscurra/config-server)
  

## Requisitos de los componentes:
- Java 11
- Maven
- MongoDB
- Postman (Hay una colección lista para importar y probar)