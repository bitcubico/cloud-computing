# Conceptos de la nube

 ## Computo en la nube
***Es la prestación de servicios informáticos a través de internet***, lo que permite una innovación más rápida, recursos flexibles y costos regulables. Posibilita el acceso bajo demanda a un grupo de recursos *(servidores, componentes de red, componentes de almacenamiento, aplicaciones, servicios o una combinación entre estos recursos)*,  que son configurables.

### Ventajas de la nube

 1. Se puede acceder desde cualquier parte del mundo a través de internet
 2. La creación y puesta en marcha de los recursos es con un mínimo esfuerzo de administración y con muy poca interacción con el proveedor de servicios

## Nube privada
En este tipo de nube las organizaciones crean un entorno de nube en su centro de datos, esta, es responsable de operar los servicios que brinda incluyendo la seguridad en las comunicaciones entre los diferentes componentes que la conforman, incluyendo el acceso a esta misma desde el exterior.

### Ventajas

 1. Se debe comprar el hardware por adelantado
 2. Las organizaciones tienen control total sobre los recursos y la seguridad
 3. Las organizaciones tienen la responsabilidad del mantenimiento y la actualización del hardware

## Nube pública
Este tipo de nube ofrece los componentes que los usuarios requieren sin que estos pertenezcan a la organización ya que son propiedad del proveedor de hosting y seguramente estos son compartidos con otros clientes del mismo. Se accede a través de una conexión segura en internet por lo general

### Ventajas

 1. No hay costo de capital para escalar
 2. Los recursos se pueden aprovisionar y quitar rápidamente
 3. Las organizaciones solo pagan por lo que consumen

## Nube híbrida
Esta permite combinar la nube pública con la nube privada y facilita que las aplicaciones se ejecuten en la ubicación más adecuada.

### Ventajas

 1. Brinda mayor flexibilidad
 2. Las organizaciones determinan dónde ejecutar sus aplicaciones
 3. Las organizaciones controlan la seguridad, el cumplimiento o los requisitos legales

## Beneficios de la nube

### Alta disponibilidad
Es la capacidad que tienen las infraestructuras de mantenerse funcionando la mayor cantidad de tiempo posible sin perjudicar la operación.

### Tolerancia a fallos
Es la capacidad que tienen las infraestructuras de responder a una falla sin generar la caída completa de los sistemas.

### Escalabilidad
Es la capacidad de agregar instancias o crecer verticalmente, por ejemplo en la cantidad de máquinas virtuales que se tienen operando para un determinado sistema.

### Elasticidad
Es la capacidad de crecer horizontalmente y que permite agregar más recursos de computo a un servicio o sistema que se está ejecutando en la nube sin la necesidad de crecer en máquinas.

### Alcance global y capacidad de latencia
Esta relacionado con las regiones donde están ubicados los centros de computo y que permiten mantener la latencia baja con respecto al acceso a datos por parte de los clientes.

### Agilidad
Es la capacidad de gestionar recursos de manera rápida y eficiente en el momento en que el cliente lo necesite.

### Consideraciones de costos predictivo
Le posibilita a los clientes poder predecir sus costos

#### CapEx (Costo de capital)
Es el gasto inicial que la organización debe realizar para adquirir infraestructura física si se esta trabajando en un modelo on-premise. Los costes derivados de CapEx tienen un valor que se reduce con el tiempo ya que a medida que avanza este, la compañía debe obtener menos de estos recursos y entra en una operación de mantenimiento de los mismos.

### OpEx (Gastos Operativos)
Estos son gastos de operación de servicios en la nube. En este la facturación se da de acuerdo a la cantidad de computo que he necesitado en la nube y se deducen el mismo año de consumo.

## Servicios en la nube

### IaaS (Infraestructura como servicio)
Es la categoría más básica dentro de los servicios de nube, este servicio le permite al cliente usar una infraestructura de TI de pago por uso alquilando servidores, máquinas virtuales, almacenamiento, licencias, redes y sistemas operativos de un proveedor de nube.

### PaaS (Plataforma como servicio)
Este servicio le proporciona al cliente un entorno para desarrollar, probar e implementar aplicaciones de software, sin centrarse en la administración de la infraestructura subyacente.

### SaaS (Software como servicio)
Este servicio le permite a los usuarios usar aplicaciones basadas en la nube y se conectan a ellas a través de internet. Algunos ejemplos de estas aplicaciones son el correo electrónico, calendarios, Microsoft 365, etc.

> **Se debe tener en cuenta que los modelos de negocios se pueden combinar entre ellos**

## Modelo de responsabilidad compartida
Habla sobre la responsabilidad que tiene cada uno de los actores que intervienen en el funcionamiento de la nube:

Responsabilidad | Nube privada | IaaS | PaaS | SaaS
--- | --- | --- | --- | ---
Datos de acceso | User | User | User | User
Solicitudes | User | User | User | Prov
Tiempo de ejecución | User | Prov | Prov | Prov
Sistema operativo | User | Prov | Prov | Prov
Máquina virtual | User | Prov | Prov | Prov
Proceso | Prov | Prov | Prov | Prov
Redes | Prov | Prov | Prov | Prov
Almacenamiento | Prov | Prov | Prov | Prov

## Computo sin servidor
Con las aplicaciones de computo sin servidor, ***el proveedor de servicios en la nube aprovisiona, escala y administra de manera automática la infraestructura necesaria para ejecutar el código***. Esta automatización de acciones sin la intervención del cliente se hacen a través de:

### Azure Functions
Es el código que ejecuta su servicio y no la plataforma o infraestructura subyacente. ***Crea una infraestructura basada en un evento*** y la destruye después que el evento halla pasado, esto es muy ventajoso porque solo se cobra por el computo generado en ese evento.

### Azure Logic Apps
Es un servicio en la nube que ***ayuda a automatizar y organizar tareas***, pone a disposición procesos de negocios y flujos de trabajo para cuando se necesiten integrar aplicaciones, datos, sistemas y servicios. ***Es similar a un orquestador de procesos de negocios***.
