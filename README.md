# PROYECTO AREP 2019 -2
- Realizado por : Oscar Ricardo Pinto Benavides - Andres Martin Cantor Urrego
- Arquitectura Empresarial – AREP

## INTRODUCCION:
- En este documento en primera parte se busca entender y analizar el estado actual de la empresa, lo que permitirá establecer un diagnóstico de la situación presente y un abordaje de alguna problemática actual. Para realizar este estudio es necesario dividir el estudio en 4 partes centrales para abordar todos los componentes de la organización, en primer lugar, se presentará a nivel de perspectiva de Negocio donde se presentará el modelo CANVAS, el diagrama de procesos y el organigrama de la organización.
En segundo lugar, se toma la perspectiva a nivel de Aplicaciones, donde se presentará un Inventario de aplicaciones y un diagrama lógico de arquitectura de aplicaciones.
En tercer lugar, se toma la perspectiva de Datos y de Infraestructura de TI, donde se presentará un diagrama de identificación de las entidades principales, Un diccionario de datos, Un inventario de base de datos, un diagrama de infraestructura de Red y servidores, y para finalizar un inventario de servidores y servicios presente en la organización.
- En última instancia se realiza un análisis con todos los artefactos indicados anteriormente sobre la problematica escogida, mostrando la situacion actual de la empresa y el impacto actual (con cifras numericas), despues se planteara los cambios e impactos que se tendra en el negocio en indicadores internos de la organizacion, asi como el modelamiento de la solucion presentando el diagrama de clases y el modelo de arquitectura de la misma, un estimado en costos de la implementacion con los servicios de AWS y los costos de la operacion por parte de ingenieria sumados a la Reserva Gerencial establecida y el horizonte de proyeccion para este proyecto.
Se mostrara tambien el cambio a nivel de gobierno que tiene que realizarse par la implementacion asi, como una descripcion del prototipo y demostraciones del experimento.
POr ultimo se mostrara el trabajo Futuro por realizar y las conclusiones respectivas de este proyecto.

## Analisis Preliminar de la Empresa Francisco Rocha
- Noviembre 8 de 2019

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

![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.48.19%20AM.png)

![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.48.38%20AM.png)

![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.49.18%20AM.png)

3. Organigrama de la organización

![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.49.32%20AM.png)
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.49.43%20AM.png)
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.49.53%20AM.png)
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.50.04%20AM.png)
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.50.17%20AM.png)
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.57.48%20AM.png)
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.57.58%20AM.png)


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
1. Diagrama de identificación de las entidades principales:

![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.58.17%20AM.png)

El diagrama de clases para la Empresa FRANCISCO ROCHA  esta formado por 15 clases y las relaciones que se establecen entre las diferentes clases, tienen en cuenta el tipo de relaciones si es de asociación, generalización, o agregación además de la respectiva multiplicidad.
La empresa maneja su inventario manteniendo el control y actualizando la información de sus ventas y pedidos para así realizar la solicitud de compra de productos a sus proveedores. En relación a los clientes que llegan a la tienda estos compran sus productos y los cancelan quedando como videncia la respectiva factura y si el producto esta agotado se pasa a la clase pedidos para que desde la clase inventario se proceda a solicitarlo al proveedor.
  
2. Diccionario de datos:

#### B:
- Botones: Elemento pequeño utilizado para abrochar o ajustar vestimentas

#### C:
- Cliente: Persona que utiliza los servicios de un profesional o de una empresa, especialmente la que lo hace regularmente.
- Cliente Nacional: Cliente cuya residencia de operacion es en el mismo pais de operacion de la empresa que presta el servicio
- Cliente Internacional: Cliente cuya residencia de operacion es en un pais diferente al de operacion de la empresa que presta el servicio
- Colección:Es un conjunto de prendas creadas por un diseñador con una coherencia interna en términos de estilo y destinada a una temporada del año en concreto
- Compra: Orden generada cuando se realiza la compra de material a un proveedor

#### F:
- Factura: Cuenta en la que se detallan las mercancías recibidas por un cliente, junto con su cantidad y su importe, y que se entrega a quien debe pagarla.

#### H:
- Hilo: Es una hebra larga y delgada de un material textil, especialmente la que se usa para coser

#### I:
- Inventario: Lista ordenada de bienes y demás cosas valorables (Materiales y Colecciones) que pertenecen a la empresa o institución.

#### M:
- Material:Materia prima destinada a la elaboracion de trajes a la medida para hombres

#### P:
- Pedido:Es el documento que realiza quien ha tomado la decisión en firme de comprar un bien o servicio
- Proveedor: Un proveedor es una persona o una empresa que abastece a otras empresas con existencias (artículos), los cuales serán vendidos directamente o transformados para su posterior venta.

#### T:
- Tela: Es un material textil. Un tejido es el género obtenido en forma de lámina más o menos resistente, elástica y flexible, mediante el cruzamiento y enlace de series de hilos o fibras de manera coherente al entrelazarlos o al unirlos por otros medios.
- Traje: Es un atuendo en el que consta de chaqueta y pantalón, los cuales han sido cortados de la misma tela

#### V:
- Ventas: Es una acción que se genera de vender un bien o servicio a cambio de dinero.

3. Inventario de base de datos

- Dbeaver: Es un cliente SQL y una herramienta de administración de bases de datos.
- MySQL: Es un sistema de gestión de bases de datos relacionales de código abierto (RDBMS, por sus siglas en inglés) con un modelo cliente-servidor. RDBMS es un software o servicio utilizado para crear y administrar bases de datos basadas en un modelo relacional. 
- Apache Cassandra: Cassandra es probablemente uno de los proyectos NoSQL más conocidos del mercado. Se trata de una base de datos distribuida de segunda generación con alta escalabilidad. El objetivo es ofrecer un entorno consistente, tolerante a fallos y de alta disponibilidad a la hora de almacenar datos.
- MariaDB: Es una rama compatible hacia atrás de MySQL® Database Server. Incluye soporte para la mayoría de los motores de almacenamiento Open Source, y además para el propio motor de almacenamiento Maria.

4. Diagrama de infraestructura de Red y servidores
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/Screen%20Shot%202019-11-08%20at%2010.58.29%20AM.png)

5. Inventario de servidores y servicios
- Web Service, Permite a los usuarios tener un contacto con la compañia por medio de la seccion contactenos, al igual que los datos para un contacto telefonico
- Nubox, como ERP usado para pago de nóminas.
- Servidor de base de datos : Un equipo informático especializado en servir consultas a clientes remotos o locales que solicitan información o realizan modificaciones a los registros y tablas que existen dentro de las bases de datos del sistema.
- 2 Sysracks 42u It Servidor De Datos De Red Gabinete
- XAMPP: Incorpora un servidor Apache, un sistema gestor de bases de datos MySQL y lenguajes como PHP y Perl. Además, ofrece soporte para gestionar cuentas FTP, acceso a bases de datos mediante PHPMyAdmin, bases de datos SQLite y varias otras características. También incluye un servidor de correos Mercury para el envío de emails, un servidor Tomcat para servlets JSP, y un servidor FTP FileZilla.

## Analisis Final de la Empresa Francisco Rocha
- Diciembre 10 de 2019

### Problematica
- Se ha identificado como problematica que la empresa Francisco rocha presenta una falencia en la organizacion de la materia prima a la hora de realizar el procedimiento de confeccion y costura, debido a que mucha materia prima es malgastada, y se sospecha que tambien se podria estar perdiendo materia prima, debido a que no hay un orden en la sacada y entrega de material en la bodega por parte de los empleados del area de costura, la materia prima es encargada acto seguido almacenada en las bodegas y fábricas de Francisco Rocha, al momento de manufactura se extrae por porciones de esta misma, sin embargo no hay un buen control con respecto a esto, simplemente cuando se va acabando se encarga más material, lo que ha incurrido en un incremento del presupuesto para materia prima, se presume un inminente malgasto de esta misma o incluso maluso o desaparición de la misma, se busca instaurar un sistema que permita llevar un control de los retiros y disposición de los materiales, de esta manera poder estar al tanto completamente del inventario así saber, y preveer el siguiente encargo que se va a hacer, que al por mayor se obtienen beneficios, también tener un seguimiento/auditoria sobre la persona que hizo el restiro y llevar el control sobre la materia prima usada y lo producido.

### Estado Actual e Impacto:
- Francisco Rocha Actualmente tiene perdidas de Material calculadas en $25'000.000 en lo que va del 2019 y $45'768.000 en el periodo de 2018, Desperdicio de Material en el proceso de manufacturacion, transporte, por defectos y de movimientos innecesarios calculados en $90'000.000 en lo que va del 2019 y $137'567.000 en el periodo de 2018.
Se ha producido un Aumento de los costos de materiales directos en un 10%, en los precios de las unidades vendidas en un 5%, en la cantidad de pedidos a proveedores en un 15% y un aumento del valor de los pedidos en $4'000.000.
- Por la misma situacion se ha incurrido en sanciones a mas de 67 trabajadores en lo corrido de 2019 y a 180 en 2018.
- Toda esta situacion ha provocado una disminucion en el Reveneu Anual de la empresa en un 8.9%

## Arquitectura de la solucion:

### Modelo de la solucion Propuesta:
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/entities.PNG)
  
  Nos muestra las entidades principales relacionadas al proceso que manejamos, los trabajadores hacen un retiro de x cantidad en una 
  unidad específica de uno o muchos materiales y a este retiro se le asocia uno o más producidos que nos especifica en qué se usaron
  los materiales y cuanto fue producido, el restante puede ingresarlo de nuevo, como también se registra un ingreso por parte de un 
  proveedor.
  
### Modelo de la Arquitectura:
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/arquitectura.png)

### Costo de la Implementacion y Operacion (AWS):
- En la siguiente imagen se presenta los costos estimados deacuerdo a la calculadora de costos de AWS:
![](https://github.com/Martin9958/ProyectoAREP-III/blob/master/Imagenes/AWS.png)

### Costos de Implementacion (Ingenieria):
Se Estima que el personal de Ingenieria son:
- 4 Ingenieros (2 para Back, 1 para Front)
- 2 Ingenieros de Seguridad
- Sueldo X Ingeniero ($2’500.000)
Por un Total de $ 15’000.000

Costos de la implementación con AWS:  USD (375.43) $ 1’314.000
Costos de contratación: $ 15’000.000
-------------------------------------------------------------
TOTAL Costos de Implementación: $16’314.000 Mensual
Reserva gerencial: $500.000
Total mensual:  $16’314.000

HORIZONTE DE PROYECCIÓN : 3 meses y 15 días
TOTAL DEL PROYECTO: $58.849.000

### Cambios en Gobierno
Algunos cambios a nivel de Gobierno que toca implementar para la respectiva solucion son:
- Implementacion de una cultura del uso de la T.I como herramienta organizacional
- Implementacion de politicas frente al tratamiento de materiales
- Capacitaciones sobre el uso de la aplicación y las ventajas corporativas que trae para las áreas de Costura, transporte y Administrativa de Bodegas con el módulo de manejo de inventario
- Participación activa de los trabajadores sobre funcionalidades y sugerencias para la aplicación

### Prototipo

#### Descripcion del Prototipo:

- Link del repositorio del prototipo experimental: https://github.com/AREP-Proyecto-ROCHA 

#### Imagenes demostrativas de la solucion:



### Trabajo Futuro
Algunas consideraciones a futuro para posteriores proyectos relacionados son:
- Desarrollo del Módulo Administrativo, Módulo de Transporte y Módulo de costura
- Escalamiento Vertical para soportar los diferentes módulos
- Planeación de pedidos en base de estadísticas obtenidas a partir de los reportes de las entradas y salidas de material, con un sistema de Machine learning

### Conclusiones
- La arquitectura empresarial es una disciplina de la informática que permite establecer cómo los sistemas pueden proponer formas de organizar los procesos para una optimización de los recursos y así lograr los objetivos que una organización se propone; todo esto gracias a la visión integral de las organizaciones, permitiendo observar los procesos, datos, aplicaciones e infraestructura tecnológica centrado desde el área de negocio.

- Todo este análisis permite que se establezca el estado actual de la organización de estudio y asi poder tener en cuenta los puntos claves y criticos que se estan presentando dentro de la misma, por supuesto este estudio podria estar acompañado de una serie de otras medidas, como estudios de riesgos, costos, su impacto en el mercado y la viabilidad que esta compañia presenta.

- Concluímos que la implementación de soluciones T.I, ayuda a la reducción de costos, mitigación de errores humanos o malintencionados.

- El análisis de arquitectura permite tener una visión más panorámica de todos los frentes organizacionales y de esta manera encontrar puntos débiles que pueden ser tratados para mejorar los procesos de la organización. 

- Haciendo proyectos con un enfoque en T.I aumenta el revenue de la organización al presentar alternativas de mejora frente a la ejecución de procesos.

- Tener en consideración Gastos, Costos y Presupuesto frente a un proyecto y realizar el análisis respectivo de utilización permite un mejor manejo del cronograma así como visualización del rendimiento del proyecto.

- Hay que tener en cuenta que la mejor solución a implementar no siempre recae en el desarrollo propio de una solución, ya que en el mercado se presentan situaciones similares con soluciones ya implementadas que facilitan la mitigación del problema.

- No siempre son soluciones de TI, las soluciones pueden recaer en la optimización de procesos en componentes críticos en la trazabilidad.


### Bibliografia y fuentes
- http://www.franciscorocha.com/web/
- https://es.wikipedia.org/wiki/XAMPP
- Carlos Eduardo Martin (Gerente Amezquita & Cia)


