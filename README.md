
# Plantilla del curso programación para QA

Plantilla para el [curso de desarrollo para QA](https://jj.github.io/curso-tdd)


# Contribuyentes:

| Name                     | Github User Name  |
| ----                     | ---               |
| Sergio Quijano Rey       | SergioQuijanoRey  |
| Pilar Navarro Ramírez    | pilarnavarro      |
| Juan José Herrera Aranda | KieDie            |

# Descripción del problema

* Se quiere crear una API Rest para consultar distintos datos medioambientales con la intención de hacerlos más accesibles
* Estos datos incluyen temperatura, precipitaciones, contaminación del aire...
* Los datos corresponden a la ciudad de Granada, aunque en un futuro puede ampliarse a otras ciudades

# Tecnologías

La discusión sobre las tecnologías se desarrolla en el siguiente [issue](https://github.com/tdd-JSP/TDD-curso/issues/6). No dudes en participar en la conversación y comentar tus ideas! :smile:

* API REST: programada en `python` con `flask`
* Sistema de mensajería: `RabbitMQ`
* Gestión de configuración: `etcd`
* Sistema Cloud: `Google Cloud`
* Acceso a los datos: módulo escrito en `python` y ficheros `.csv`. En un futuro se puede utilizar una base de datos más clásica
* Microservicios y orquestación: `docker` y `docker-compose`

Estas tecnologías son una propuesta inicial que pueden variar con el paso del tiempo al detectar fallos o nuevas necesidades
