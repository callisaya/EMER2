# EMER2

---
title: "PRACTICA 1"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## EMERGENTES II

**¿Que son los sistemas empresariales?**

Los sistemas empresariales, juegan un papel importante dentro de las empresas, ya que estos permiten que tanto los empleados, como los clientes y proveedores de una determinada organización estén conectados a un mismo sistema donde la información es igual para cada una de las personas; Esto es, debido a que los sistemas empresariales son un conjunto integrado de sistemas de información que son herramientas que unifican los procesos que se llevan a cabo dentro de una empresa por medio de un software y hardware.

Es conjunto de computadoras independientes, interconectados a través de una red y que son capaces de colaborar con el fin de realizar una tarea”. 

Debido a que el entorno esta cambiando rápidamente, es de mucha importancia que las empresas manejen un sistemas de información acorde a lo que a lo que la empresa se dedica, para que de esta forma la información este actualizada en tiempo real y se pueda llevar a cabo un mejoramiento continuo, de esta manera la empresa va a estar en capacidad de realizar cambios con mayor rapidez en su estrategia, estructuctura organizacional y en la forma como se lleva a cabo el negocio.
Los sistemas empresariales son programas costos pero que le brindan un gran beneficio a la compañía, para que estos sistemas funcionen bien dentro de una determinada compañía deben ser compatibles con la cultura empresarial de esta y además debe estar orientado a alcanzar los objetivos y las metas organizacionales. Los sistemas empresariales pueden usarse por medio de la intranet y la Internet.

En el entorno colombiano, pienso que son muy pocas las empresas que han implementado bien los sistemas empresariales, según mi percepción las empresas colombianas tienden mucho a tener diferentes sistemas de información para cada uno de sus departamento, haciendo esto que la información no sea la misma para toda la organización y esto hace que la empresa no sea tan productiva y eficiente, ya que no hay un flujo de información entre las diferentes áreas , lo que hace que cada área trabaje de manera independiente. Para que una empresa colombiana no pierda competitividad frente a otras empresas nacionales como internacionales, es necesario que se haga un estudió de profundidad sobre como llevar a cabo la implementación de un buen sistema empresarial; pienso que la mejor forma de implementar un buen sistema espresarial es por medio de la cultura dentro de las empresas que se podría comenzar con la implementación de algunos de los módulos de sistema de información que mas necesite la empresa.



**Características más importantes de una aplicación empresarial**

![Características más importantes](http://3.bp.blogspot.com/_GbVgv3VY5Po/S5UsVJBv92I/AAAAAAAAAQA/iVOOwA61Bdg/s1600/caracter%C3%ADsticasSistemaEmpresarial.png)

**Tipos de Aplicaciones Empresariales**
**Ejemplo 1:** Aplicación B2C de venta on-line

* Capaz de manejar un muy alto volumen de usuarios
* Solución razonablemente eficiente en términos de recursos utilizados
* Escalable, tal que se pueda incrementar la carga agregando más hw
* Lógica de dominio bastante directa
* Presentación web genérica tal que pueda ser accedida por la mayor cantidad de usuarios posibles, soportando el rango más amplio de browsers
* Base de datos para almacenar las órdenes de compra
* Comunicación con el sistema de inventario



**Ejemplo 2:** Proceso de automatización de acuerdos de leasing

*	No tendrá más de 100 usuarios a la vez
*	Lógica de negocio mucho más compleja
    **	Calcular montos mensuales del leasing
**	   Manejar eventos como retornos tempranos y pagos fuera de término
**	Validar datos de la operación de leasing
*	Reglas de negocio cambiantes y con muchas excepciones
*	Interfaces gráficas más complejas
*	Comportamiento transaccional más complejo, debido a la complejidad de interacción
*	Complejo esquema de base de datos 
 
**Ejemplo 3:** Sistema de tracking de gastos
*	Pocos usuarios
*	Lógica de negocio simple
*	Es accedido desde dentro de la compañía a través de una interfaz web
*	Construirlo rápidamente
*	Prever su crecimiento. Proveer más funcionalidad, integrarlo con otros	sistemas, etc.



**Aplicaciones de misión crítica**

Las aplicaciones de misión crítica se entienden como aquellas que apoyan las funcionalidades del núcleo del negocio y por lo tanto la operación de una compañía depende del correcto funcionamiento y estabilidad de éstas aplicaciones. Entre estas aplicaciones se tienen ERP (Enterprise Resource Planning por sus siglas en inglés) y CRM (Customer Relationship Management).

**Diferencias entre la escalabilidad horizontal y escalabilidad vertical**


En la práctica existen muchas formas de hacer que un software sea escalable ya que podemos combinar técnicas de software y hardware e incluso arquitecturas de RED (por qué no), pero en esta ocasión me quiere centrar en la escalabilidad horizontal y vertical, porque sin duda es una de las características más importantes para sistemas de alta demanda o uso crítico. 

Escalabilidad vertical

La escalabilidad vertical o hacia arriba, este es el más simple, pues significa crecer el hardware de uno de los nodos, es decir aumentar el hardware por uno más potente, como disco duro, memoria, procesador, etc. pero también puede ser la migración completa del hardware por uno más potente. El esfuerzo de este crecimiento es mínimo, pues no tiene repercusiones en el software, ya que solo será respaldar y migrar los sistemas al nuevo hardware.

![Escalabilidad vertical](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-vertical.png)

Ventajas:

*	No implica un gran problema para las aplicaciones, pues todo el cambio es sobre el hardware
*	Es mucho más fácil de implementar que el escalamiento horizontal.
*	Puede ser una solución rápida y económica (compara con modificar el software)
 
Desventajas:

*	El crecimiento está limitado por el hardware.
*	Una falla en el servidor implica que la aplicación se detenga.
*	No soporta la Alta disponibilidad.
*	Hacer un upgrade del hardware al máximo pues llegar a ser muy caro, ya que las partes más nuevas suelen ser caras con respecto al rendimiento de un modelo anterior.


**Escalabilidad horizontal**
 
El escalamiento horizontal es sin duda el más potente, pero también el más complicado. Este modelo implica tener varios servidores (conocidos como Nodos) trabajando como un todo. Se crea una red de servidores conocida como Cluster, con la finalidad de repartirse el trabajo entre todos nodos del cluster, cuando el performance del cluster se ve afectada con el incremento de usuarios, se añaden nuevos nodos al cluster, de esta forma a medida que es requeridos, más y más nodos son agregados al cluster.

![Escalabilidad Horizontal](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-horizontal.png)


Ventajas:

*	El crecimiento es prácticamente infinito, podríamos agregar cuantos servidores sean necesarios
*	Es posible combinarse con el escalamiento vertical.
*	Soporta la alta disponibilidad
*	Si un nodo falla, los demás sigue trabajando.
*	Soporta el balanceo de cargas.
 
Desventajas:

* Requiere de mucho mantenimiento
*	Es difícil de configurar
*	Requiere de grandes cambios en las aplicaciones (si no fueron diseñadas para trabajar en cluster)
*	Requiere de una infraestructura más grande.

**¿Que es un servidor Web y que es un servidor de aplicaciones?**

Servidor web

Un servidor web o servidor HTTP es un programa informático que procesa una aplicación del lado del servidor realizando conexiones bidireccionales y/o unidireccionales y síncronas o asíncronas con el cliente generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente. El código recibido por el cliente suele ser compilado y ejecutado por un navegador web. Para la transmisión de todos estos datos suele utilizarse algún protocolo. Generalmente se utiliza el protocolo HTTP para estas comunicaciones, perteneciente a la capa de aplicación del modelo OSI. El término también se emplea para referirse al ordenador que ejecuta el programa. 


Algunos servidores web importantes son:

* Apache
*	Tomcat
*	Cherokee

**Servidor de aplicaciones**

En informática, se denomina servidor de aplicaciones a un servidor en una red de computadores que ejecuta ciertas aplicaciones.

Usualmente se trata de un dispositivo de software que proporciona servicios de aplicación a las computadoras cliente. 

Un servidor de aplicaciones generalmente gestiona la mayor parte (o la totalidad) de las funciones de lógica de negocio y de acceso a los datos de la aplicación. Los principales beneficios de la aplicación de la tecnología de servidores de aplicación son la centralización y la disminución de la complejidad en el desarrollo de aplicaciones.



**Servidores de aplicaciones Java EE**

Como consecuencia del éxito del lenguaje de programación Java, el término servidor de aplicaciones usualmente hace referencia a un servidor de aplicaciones Java EE. Entre los servidores de aplicación Java EE privativos más conocidos se encuentran WebLogic de Oracle (antes BEA Systems) y WebSphere de IBM. 

EAServer de Sybase Inc. es también conocido por ofrecer soporte a otros lenguajes diferentes a Java, como PowerBuilder. Entre los servidores de aplicaciones libres se encuentran JOnAS del consorcio ObjectWeb, JBoss AS de JBoss (división de Red Hat), Geronimo de Apache, TomEE de Apache, Resin Java Application Server de Caucho Technology, Blazix de Desiderata Software, Enhydra Server de Enhydra.org y GlassFish de Oracle.

Mucha gente confunde Tomcat como un servidor de aplicaciones; sin embargo, es solamente un contenedor de servlets.

Java EE provee estándares que permiten a un servidor de aplicaciones servir como "contenedor" de los componentes que conforman dichas aplicaciones. Estos componentes, escritos en lenguaje Java, usualmente se conocen como Servlets, Java Server Pages (JSPs) y Enterprise JavaBeans (EJBs) y permiten implementar diferentes capas de la aplicación, como la interfaz de usuario, la lógica de negocio, la gestión de sesiones de usuario o el acceso a bases de datos remotas.

La portabilidad de Java también ha permitido que los servidores de aplicación Java EE se encuentren disponibles sobre una gran variedad de plataformas, como Unix, Microsoft Windowsy GNU/Linux.


**Con un gráfico explique cómo funciona el protocolo HTTP**

HTTP es un protocolo, para la transferencia de contenido HTML "HyperText Markup Language" en su mayoría, entre un cliente y un servidor, indicado mediante una cadena de caracteres o URL "Uniform Resource Locator".

¿Cómo se realiza la comunicación HTTP?

La comunicación se puede simplificar en estos dos pasos:

*	El navegador manda una petición HTTP y solicita un archivo
*	El servidor responde con la información, que es descifrado por el navegador


![](https://www.miguelra.com/content/images/2016/12/comunicacionHTTP-1.jpg)


**HTTP Resquest  (Solicitud HTTP)**

Elementos clave de una "solicitud"
corriente

*	Método HTTP (acción a realizar)
*	La página para acceder (una URL)
*	Parámetros de formulario


**HTTP Response (Respuesta HTTP)**

Elementos clave de una "solicitud"
corriente

*	Un código de estado (para saber si la solicitud fue exitosa)
*	Tipo de contenido (texto, imagen, html, etc.)
*	El contenido (el contenido real)

![](https://1.bp.blogspot.com/-1VqkNVdi_Xg/XUcQRQGDi2I/AAAAAAAAAqM/3fNzk13ZBsYaIZbSW8Td2_YzOpyU58brQCLcBGAs/s640/alfredo.png)




**CONTENEDORES JAVA EE**

Escribir aplicaciones empresariales seria muy complejo y difícil de codificar, ya que implicaría muchas lineas de código complejo para el manejo de transacciones y la gestión de estados, multihilos y otros detalles de bajo nivel,  la arquitectura Java EE hace que las aplicaciones sean fáciles de escribir porque la lógica de negocio se divide en componentes reutilizables y adicionalmente se cuenta con un servidor de aplicaciones que proporciona servicios en la forma de contenedor para los diferentes tipos de componentes, debido a esto no se tiene que desarrollar estos servicios, sino enfocarse en el desarrollo.



SERVICIOS DEL CONTENEDOR

 Los contenedores son la interface entre un componente y el bajo nivel, es especifico para la plataforma, antes de que se pueda ejecutar el componente web, el bean o la aplicación cliente deben ser cargados en un modulo java EE y desplegarlo en el contenedor. al momento de desplegarlo cada componente puede tener su propia configuración en cuanto a seguridad, gestión de transacciones JNDI etc.
 
TIPOS DE CONTENEDORES

En la siguiente figura se muestra los tipos de contenedores para los diferentes componentes:


![](http://2.bp.blogspot.com/-xtOAc9rZSpc/U9_4CLOvnRI/AAAAAAAAAPQ/vX2vnfJhcWk/s1600/Captura.PNG)

Java EE Server: La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.

Contenedor EJB: Maneja la ejecución de los enterprise beans.

Contenedor Web: Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.

Contenedor de aplicación cliente: Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.

Contenedor Applet: Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.  


**HttpServletRequest vs HttpServletResponse**


Tanto HttpServletRequest como HttpServletResponse son inevitables en cada Servlet, escribe el Programador. Ambos existen en el código de Servlet como parámetros para el método service (). Incluso un principiante debe conocer estas dos interfaces.
Lista de diferencias HttpServletRequest vs HttpServletResponse

1.	Ambas son interfaces del paquete javax.servlet.http .
2.	Se derivan de las interfaces ServletRequest y ServletResponse.
3.	Ambos objetos se crean y se pasan implícitamente al método service () de Servlet por contenedor.

A) Jerarquía de HttpServletRequest
![](https://way2java.com/wp-content/uploads/2014/02/image2.png)

B) Jerarquía de HttpServletResponse

![](https://way2java.com/wp-content/uploads/2014/02/image3.png)

1.	El trabajo de HttpServletRequest es recibir datos enviados por el cliente web, como el nombre de usuario y la contraseña.

2.	También viene con muchos métodos getXXX () para recuperar otra información del cliente, como la dirección IP del cliente, qué protocolo usó el cliente, etc., y también incluye métodos para conocer el navegador del cliente, como el nombre del navegador, su versión, etc.

1.	El trabajo de HttpServletResponse es enviar datos al cliente web.

2.	También viene con muchos métodos setXXX () para establecer propiedades en un Servlet.



![](https://slideplayer.es/slide/3414386/12/images/14/SERVLET%3A+Ejemplo+1+%28HolaFigura.class%29.jpg)



**Por: ALFREDO CALLISAYA HUANCA - MATERIA EMERGENTES II**

 <http://callisayainformatico.blogspot.com/>.

```{r cars}
summary(cars)
```



You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
