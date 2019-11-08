# Analisis de la Empresa Francisco Rocha
- Realizado por : Oscar Ricardo Pinto Benavides - Andres Martin Cantor Urrego
- Arquitectura Empresarial – AREP
- Noviembre 8 de 2019

## Introduccion
- En el siguiente documento se busca entender y analizar el estado actual de la empresa, lo que permitirá establecer un diagnóstico de la situación presente y un abordaje de alguna problemática actual. Para realizar este estudio es necesario dividir el estudio en 4 partes centrales para abordar todos los componentes de la organización, en primer lugar, se presentará a nivel de perspectiva de Negocio donde se presentará el modelo CANVAS, el diagrama de procesos, el organigrama de la organización y un diagrama único de arquitectura empresarial.
En segundo lugar, se toma la perspectiva a nivel de Aplicaciones, donde se presentará un Inventario de aplicaciones, un diagrama lógico de arquitectura de aplicaciones, un diagrama de base de datos, Un Inventario de Interfaces.
En tercer lugar, se toma la perspectiva de Datos y de Infraestructura de TI, donde se presentará un diagrama de identificación de las entidades principales, Un diccionario de datos, Un inventario de base de datos, un diagrama de infraestructura de Red y servidores, y para finalizar un inventario de servidores y servicios presente en la organización.
En última instancia se realiza un análisis con todos los artefactos indicados anteriormente y una serie de conclusiones frente a la identificación del problema presente.

## Contexto De La Organizacion
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/rocha.png)

- Francisco Rocha & Cia Ltda es una compañia especializada en el diseño, corte y manofactura de ropa a medida para hombres, lleva 27 años en el mercado, ubicado en la ciudad de Bogota con plantas en Buenaventura, Cartagena y Barranquilla, cuenta con socios ubicados en Estados Unidos y actualmente es un gran exportador para la costa Este y para Miami.
- Cada prenda producida por Francisco Rocha tiene el ajuste perfecto y la consistencia requerida por un cliente. Gracias al equipo más preparado de diseñadores, técnicos e ingenieros que trabajan con maquinaria de última tecnología, tienen un control especial en cada paso del proceso de fabricación que les permite reaccionar a tiempo a las actualizaciones en modelos y tejidos, sin causar ningún impacto en el producto terminado.
- Cuentan con Politicas de seguridad y salud en el trabajo con un enfoque hacia la proteccion integral del bienestar fisico, mental y social y la prevencion y control de riesgos profesionales para sus trabajadores.
- Las unidades exportadas, incluyendo las que están en producción, hasta el 25 de septiembre de 2019, ascienden a 807.250; de estas, más de 60.000 hacen parte del acuerdo Atpa. Los 200.000 vestidos a que se hace referencia corresponden no solo a las unidades que serán exportadas a Emanuel Ungaro según el presupuesto al 31 de diciembre de 2019, sino que también incluyen las unidades vendidas a la organización Arturo Calle para ventas nacionales. La empresa ha generado 510 empleos más desde octubre de 2018 para abastecer la demanda nacional y la de exportaciones de prendas de vestir, gracias al acuerdo Atpdea y a la ampliación de la jornada ordinaria.

#### Mision
- "Conformar una empresa única en su organización y modelo, dentro del sector de la confección, tanto por los resultados de la producción y calidad, como para el recurso humano y tecnológico con que cuenta."

#### Vision
- "C.I. FRANCISCO A. ROCHA ALVARADO Y CIA. LTDA., será una empresa con reconocimiento internacional en la confección de prendas de vestir masculina, caracterizada por la calidad de sus productos, la exigencia en el profesionalismo de su equipo de trabajo y la contribución positiva que realiza a la sociedad en general."

#### Politica Ambiental
- "C.I. FRANCISCO A. ROCHA ALVARADO & CIA. LTDA. Como empresa manufacturera dedicada a la confección de prendas de vestir y comprometida con la conservación del medio ambiente, a través de su Sistema de Gestión Ambiental, fortalece la búsqueda del mejoramiento continuo por medio del logro de los objetivos ambientales y el cumplimiento de la legislación y normatividad ambiental vigente. Adicionalmente, nuestro compromiso ambiental incluye la prevención y disminución de la contaminación, coadyuvar con el desarrollo sostenible de la sociedad y el control de los impactos en los seres humanos y el medio ambiente."

Ya teniendo un contexto de la empresa escogida, se procede al análisis respectivo tomando en cuenta de los siguientes puntos:

### Negocio

1. Modelo CANVAS
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/CANVAS.png)

- Este modelo permite observar la estructura del negocio de una manera organizada y simple dejando ver la forma en la que se crea valor para los clientes y logra competitividad, al permitir analizar las diferentes alternativas dentro del modelo de negocio y tantear la viabilidad y la forma en la que el sistema responde.

2. Diagrama de Procesos

3. Organigrama de la organización


### Aplicaciones
1. Inventario de aplicaciones

- Whatsapp: Es una aplicación de mensajería para teléfonos inteligentes, en la que se envían y reciben mensajes mediante
Internet, complementando servicios de mensajería instantánea, servicio de mensajes cortos o sistema de mensajería multimedia.
- Skype: Software que permite la comunicación de texto, audio y video.
- Outlook: Es el servicio de correo electrónico basado en la web de Microsoft, por medio de este se envian correos entre los diferentes sectores de la empresa,tambien se utiliza la funcion de calendario para agendar reuniones.
- Paqueteria Office: Herramientas utilizadas para la elaboracion de Informes, presentaciones, monitoreo de costos, balances y estados de resultados general. 
- Google Drive: Es un servicio de alojamiento de archivos en la nube de Google. 
- Gmail: es un servicio de correo electrónico gratuito proporcionado por la empresa estadounidense Google
- Scheduler: Software de la compañia que sirve para agendar reservas en las oficinas de reuniones

2. Diagrama Lógico de arquitectura de aplicaciones


### Datos e Infraestructura TI
1. Diagrama de identificación de las entidades principales
  
2. Diccionario de datos

3. Inventario de base de datos

- Dbeaver: Es un cliente SQL y una herramienta de administración de bases de datos.
- MySQL: Es un sistema de gestión de bases de datos relacionales de código abierto (RDBMS, por sus siglas en inglés) con un modelo cliente-servidor. RDBMS es un software o servicio utilizado para crear y administrar bases de datos basadas en un modelo relacional. 
- Apache Cassandra: Cassandra es probablemente uno de los proyectos NoSQL más conocidos del mercado. Se trata de una base de datos distribuida de segunda generación con alta escalabilidad. El objetivo es ofrecer un entorno consistente, tolerante a fallos y de alta disponibilidad a la hora de almacenar datos.
- MariaDB: Es una rama compatible hacia atrás de MySQL® Database Server. Incluye soporte para la mayoría de los motores de almacenamiento Open Source, y además para el propio motor de almacenamiento Maria.

4. Diagrama de infraestructura de Red y servidores

5. Inventario de servidores y servicios
- Web Service, Permite a los usuarios tener un contacto con la compañia por medio de la seccion contactenos, al igual que los datos para un contacto telefonico
- Nubox, como ERP usado para pago de nóminas.
- Servidor de base de datos : Un equipo informático especializado en servir consultas a clientes remotos o locales que solicitan información o realizan modificaciones a los registros y tablas que existen dentro de las bases de datos del sistema.
- 2 Sysracks 42u It Servidor De Datos De Red Gabinete
- XAMPP: Incorpora un servidor Apache, un sistema gestor de bases de datos MySQL y lenguajes como PHP y Perl. Además, ofrece soporte para gestionar cuentas FTP, acceso a bases de datos mediante PHPMyAdmin, bases de datos SQLite y varias otras características. También incluye un servidor de correos Mercury para el envío de emails, un servidor Tomcat para servlets JSP, y un servidor FTP FileZilla.

### Problematica
- Se ha identificado como problematica que la empresa Francisco rocha presenta una falencia en la organizacion de la materia prima a la hora de realizar el procedimiento de confeccion y costura, debido a que mucha materia prima es malgastada, y se sospecha que tambien se podria estar perdiendo materia prima, debido a que no hay un orden en la sacada y entrega de material en la bodega por parte de los empleados del area de costura, la materia prima es encargada acto seguido almacenada en las bodegas y fábricas de Francisco Rocha, al momento de manufactura se extrae por porciones de esta misma, sin embargo no hay un buen control con respecto a esto, simplemente cuando se va acabando se encarga más material, lo que ha incurrido en un incremento del presupuesto para materia prima, se presume un inminente malgasto de esta misma o incluso maluso o desaparición de la misma, se busca instaurar un sistema que permita llevar un control de los retiros y disposición de los materiales, de esta manera poder estar al tanto completamente del inventario así saber, y preveer el siguiente encargo que se va a hacer, que al por mayor se obtienen beneficios, también tener un seguimiento/auditoria sobre la persona que hizo el restiro y llevar el control sobre la materia prima usada y lo producido.

- Modelo de la solucion Propuesta:
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/entities.PNG)
  
  Nos muestra las entidades principales relacionadas al proceso que manejamos, los trabajadores hacen un retiro de x cantidad en una 
  unidad específica de uno o muchos materiales y a este retiro se le asocia uno o más producidos que nos especifica en qué se usaron
  los materiales y cuanto fue producido, el restante puede ingresarlo de nuevo, como también se registra un ingreso por parte de un 
  proveedor.

### Conclusiones
- La arquitectura empresarial es una disciplina de la informática que permite establecer cómo los sistemas pueden proponer formas de organizar los procesos para una optimización de los recursos y así lograr los objetivos que una organización se propone; todo esto gracias a la visión integral de las organizaciones, permitiendo observar los procesos, datos, aplicaciones e infraestructura tecnológica centrado desde el área de negocio.

- Todo este análisis permite que se establezca el estado actual de la organización de estudio y asi poder tener en cuenta los puntos claves y criticos que se estan presentando dentro de la misma, por supuesto este estudio podria estar acompañado de una serie de otras medidas, como estudios de riesgos, costos, su impacto en el mercado y la viabilidad que esta compañia presenta.

- Para nosotros como equipo fue muy importante conocer desde adentro a una compañia tan grande como esta, ya que nos da perspectiva sobre las compañias locales que manejan la tecnologia como un aliado, y como se ve el mercado para uno de ingeniero.

- En conclusion la empresa FRANCISCO ROCHA es una empresa que cuenta con una cantidad de informacion muy grande, con oportunidades de crecimiento y con un buen escalamiento,pero con una deficiencia grande en la organizacion de la materia prima, por lo que al hablar con ellos se sugiere la opcion de un aplicativo movil (una PWA) que les permita llevar un control sobre el tipo de materia prima que se va a utilizar y si esta en uso, que cantidad y por cuanto tiempo, y si esta fue devuelta a bodega para que otro usuario la utilice, o bien el uso de algún ERP que se ajuste a las necesidades, lo que solucionaria un punto critico a la hora del proceso de manufacturacion.

### Bibliografia y fuentes
- http://www.franciscorocha.com/web/
- https://es.wikipedia.org/wiki/XAMPP
- Carlos Eduardo Martin (Gerente Amezquita & Cia)


