 

Identificación del caso de uso 
	

C01 

Nombre caso 
	

Iniciar sesión 

Actor 
	

Administrador 

Descripción 
	

El usuario administrador ingresa los datos solicitados por el sistema en los campos correspondientes para el inicio de sesión. 

 

 

Identificación del caso de uso 
	

C02 

Nombre caso 
	

Cerrar sesión 

Actor 
	

Administrador y sistema 

Descripción 
	

El usuario administrador cierra la sesión en caso de salir en caso de requerirlo, y el sistema realiza el proceso de cerra la sesión, bloqueando aperturas en URL en caso de usuarios maliciosos intenten entrar al sistema. 

 

Identificación del caso de uso 
	

C03 

Nombre caso 
	

Administrar cliente 

Actor 
	

Administrador 

Descripción 
	

El usuario administrador administra los datos del cliente, agregando, editando y eliminando al cliente. 

 

Identificación del caso de uso 
	

C04 

Nombre caso 
	

Listar cliente 

Actor 
	

Sistema 

Descripción 
	

El sistema despliega los datos que están en la base de datos, mostrando en una tabla. 

 

Identificación del caso de uso 
	

C05 

Nombre caso 
	

Agregar cliente 

Actor 
	

Sistema 

Descripción 
	

El sistema agrega los datos del cliente, dependiendo del actor administrador. 

 

Identificación del caso de uso 
	

C06 

Nombre caso 
	

Editar cliente 

Actor 
	

Sistema 

Descripción 
	

El sistema edita los datos del cliente, dependiendo del actor administrador. 

 

Identificación del caso de uso 
	

C07 

Nombre caso 
	

Eliminar cliente 

Actor 
	

Sistema 

Descripción 
	

El sistema elimina los datos del cliente, dependiendo del actor administrador. 

 

    Requerimientos funcionales. 

 

Identificación 
	

RF01 

Nombre 
	

Iniciar sesión 

Características 
	

El usuario administrador puede ingresar los datos para iniciar la sesión e ingresar al panel de control. 

Descripción  
	

El sistema despliega en un formulario con diseños acordes a las necesidades del negocio con colores, logo e imágenes, el usuario ingresa los datos correspondientes en los campos. 

Identificación de los requerimientos no funcionales 
	

RNF01 

RNF02 

RNF03 

RNF04 

Prioridad del requerimiento 
	

Alta 

 

Identificación 
	

RF02 

Nombre 
	

Cerrar la sesión 

Características 
	

El usuario administrador tiene la opción de cerrar la sesión y volver al formulario de inicio de sesión. 

Descripción  
	

El sistema tiene un botón con una indicación de salir de la cuenta, redireccionando al formulario de Inicio de sesión. 

Identificación de los requerimientos no funcionales 
	

RNF01 

RNF02 

RNF03 

RNF04 

Prioridad del requerimiento 
	

Alta 

 

Identificación 
	

RF03 

Nombre 
	

Administrar cliente 

Características 
	

El sistema debe tener la funcionalidad de administrar al cliente, donde el usuario administrador, tiene distintas opciones (agregar, buscar, editar y eliminar). 

Descripción  
	

El sistema realiza consulta mediante el framework Laravel, utilizando el motor de base de datos MySQL, con la funcionalidad de listar, agregar, editar y eliminar al cliente, realizando las consultas desde el controlador. 

Identificación de los requerimientos no funcionales 
	

RNF01 

RNF02 

RNF03 

RNF04 

Prioridad del requerimiento 
	

Alta 

 

Identificación 
	

RF04 

Nombre 
	

Roles de usuario administrador y cliente. 

Características 
	

Los roles y permisos están divididos en tipos de usuarios administrador y cliente, donde el administrador controla todo lo del sistema, a diferencia que el cliente tiene funcionalidades limitadas. 

Descripción  
	

El sistema realiza una validación de usuario administrador y cliente. 

Identificación de los requerimientos no funcionales 
	

RNF01 

RNF02 

RNF03 

RNF04 

Prioridad del requerimiento 
	

Alta 

 

Identificación 
	

RF05 

Nombre 
	

Subir informes  

Características 
	

El administrador sube informes a la plataforma para luego ser descargados. 

Descripción  
	

El sistema debe tener la funcionalidad de subir informes con la extensión PDF, para quedar disponible para ser descargado por el usuario cliente. 

Identificación de los requerimientos no funcionales 
	

RNF01 

RNF02 

RNF03 

RNF04 

Prioridad del requerimiento 
	

Alta 

 

Identificación 
	

RF06 

Nombre 
	

Deshabilitar usuario. 

Características 
	

Un usuario en caso de salir de vacaciones o tener algún tipo de inconveniente, se debe deshabilitar de la base de datos, para no acceder al sistema. 

Descripción  
	

En la base de datos en la tabla de usuario se debe tener un campo de estado, donde es tipo de dato en booleano, false o true, en caso de ser true está habilitado para usar el sistema, y lo contrario false usuario deshabilitado. 

Identificación de los requerimientos no funcionales 
	

RNF01 

RNF02 

RNF03 

RNF04 

Prioridad del requerimiento 
	

Alta 

 

Identificación 
	

RF07 

Nombre 
	

Relaciones de tablas. 

Características 
	

Un usuario en caso de salir de vacaciones o tener algún tipo de inconveniente, se debe deshabilitar de la base de datos, para no acceder al sistema. 

Descripción  
	

 

Identificación de los requerimientos no funcionales 
	

RNF01 

RNF02 

RNF03 

RNF04 

Prioridad del requerimiento 
	

Alta 

 

    Requerimientos no funcionales. 

 

Identificación 
	

RNF01 

Nombre 
	

Diseño acorde a las necesidades del negocio. 

Características 
	

El sitio completo se comprende de colores, logos entregados por el diseñador, fotos sacadas por la empresa e iconos y interfaz de usuario fácil de entender. 

Descripción 
	

El diseño de la interfaz del usuario como son todas las páginas web tiene el esqueleto con el lenguaje de HTML5 y para el diseño estético CSS3 con librería de Bootstrap para mayor facilidad y para la programación Front-End de JavaScript y JQuery. 

Prioridad del requerimiento 
	

Alta. 

[Salto de ajuste de texto] 

Identificación 
	

RNF02 

Nombre 
	

Diseños adaptables a distintos dispositivos. 

Características 
	

El diseño del software debe estar adaptado a distintos dispositivos como; smartphone, Tablet, notebook y monitores de varias pulgadas. 

Descripción 
	

El sistema debe estar adaptado en los diseños a distintos dispositivos, está solución la entrega Bootstrap, los CSS ya están configurado para no tener problemas. 

Prioridad del requerimiento 
	

Alta. 

 

Identificación 
	

RNF03 

Nombre 
	

Encriptación de contraseñas del usuario. 

Características 
	

Al agregar la contraseña de usuario este mismo se guarda en la base de datos como código que no se puede identificar. 

Descripción 
	

El usuario al iniciar la sesión ingresa correo y contraseña, al ingresar la contraseña el sistema lo procesa como un hash, específicamente utiliza Bcrypt para la encriptación. 

Prioridad del requerimiento 
	

Alta. 

 

Identificación 
	

RNF04 

Nombre 
	

Utilizar el framework de Laravel. 

Características 
	

El desarrollo de la codificación debe ser con el framework de laravel. 

Descripción 
	

El framework laravel es utilizado por el lenguaje de PHP mantenido por terceros, para mayor seguridad y mantenibilidad por otros programadores. 

Prioridad del requerimiento 
	

Alta. 

 

Identificación 
	

RNF05 

Nombre 
	

Utilizar el logo de la empresa desarrollo. 

Características 
	

El logo debe estar en el sistema. 

Descripción 
	

El sistema debe desplegar el logo de la empresa en la cual está en el inicio de sesión y en el panel de control. 

Prioridad del requerimiento 
	

Alta. 

 

    Interfaces de usuario. 

 

La interfaz del usuario está diseñada con un inicio de sesión, como pantalla inicial del sistema, donde el usuario ingresas sus datos correspondientes y redirecciona al panel del administrador acorde a diseños y colores y logos solicitados.  

Se define las interfaces de usuario, hardware, software y comunicación, para los requisitos mínimos para poder usar el software. 

El prototipado fue realizado por el diseñador, aplicando los diseños correspondientes para el desarrollo del sistema, focalizándose en disminuir los niveles de navegación y hacer más intuitiva la interfaz, para así lograr una buena experiencia de usuario. 

La interfaz se basó en la landing page actual de la empresa Suelotest (suelotest.cl), conservando elementos como; alto de la barra de navegación, tipografía (Arial) y colores (Blanco; #FFFFFF y Green; #2D9F87). 

El color, tanto de la barra de navegación como del menú lateral fueron asignados con la finalidad de tener una mejor visualización de los documentos visualizables y descargables dentro de la misma interfaz, la tipografía y espaciados se definieron con la intención de tener una mayor legibilidad y una navegación intuitiva, para así enfocar la atención a los elementos más importantes del proyecto (informes y administración de clientes). 

 

    Interfaces de hardware. 

 

Será necesario tener algún dispositivo que tenga conectividad a internet, con los requisitos mínimos a considerar:   

 

    Procesador Pentium 4 Dual Core de 1.66 GHz o superior. 

    Memoria RAM mínima de 2 Gb o superior.  

    Adaptador de red.  

    Un ancho de banda idealmente superior a 2 Mb/s, tanto de subida como de bajada (la velocidad de carga del sistema va a depender tanto de la velocidad de internet local como la disponibilidad y carga del servidor en el cual esté alojado)  

    Mouse.   

    Teclado.   

    Router.   

 

*La correcta navegación del software solo se asegura cumpliendo los requisitos anteriormente mencionados. 

 

 

    Interfaces de software. 

 

    Sistema Operativo: Windows® 7 (32/64-bit) / Vista / XP o superior, Android 6.0 o superior, iOS 10.1 o superior.   

     Explorador: Mozilla, Opera, Chrome, Microsoft Edge.   

 

*La correcta navegación del software solo se asegura cumpliendo los requisitos anteriormente mencionados. 

 

    Interfaces de comunicación. 

Los servidores, clientes y aplicaciones se comunicarán entre sí, mediante protocolos estándares en internet, siempre que sea posible. Por ejemplo, para transferir archivos o documentos deberán utilizarse protocolos existentes (FTP u otros convenientes). 

    Requisitos funcionales. 

    Funcional 1. 

    Autentificar usuarios administradores: Los usuarios registrados en la base de datos, deben acceder al sistema mediante un inicio de sesión, ingresando su correo electrónico y contraseña. 

    Funcional 2 

    Cerrar la sesión: El sistema debe tener la opción de cerrar la sesión redireccionando al inicio de sesión. 

    Funcional 3. 

    Administración de clientes:  El sistema debe tener la funcionalidad de administración de datos del cliente, realizando consultas, lista, agregar, edita y elimina la fila de datos. 

    Funcional 4. 

    Roles de usuario administrador y cliente: El sistema debe tener la funcionalidad de roles y permisos de usuarios, el administrador es que tiene todo el control del sistema, sube informes en cambio del usuario cliente que solo descarga los informes desde su cuenta de tipo cliente.  

    Funcional 5. 

    Subir informes: El usuario de tipo administrativo debe tener el requisito de subir informes a la base de datos, para luego ser desplegado en este mismo en otra vista. 

    Funcional 6. 

    Deshabilitar usuario: En la base de datos en la tabla de usuario debe tener un campo de estado, donde true es habilitado y false es deshabilitado. 

    Requisitos no funcionales. 

    No funcional 1. 

    Diseño acorde a las necesidades del negocio: Este unos del requisito más importante del sistema, porque es lo primero que se aprecia por el usuario a primera vista. 

    No funcional 2. 

    Diseños adaptables a distintos dispositivos: Requisito no funcional donde el sistema sea adaptable a distintos dispositivos, Tablet, smartphones y monitores con varias pulgadas. 

    No funcional 3. 

    Encriptación de contraseñas del usuario: Este requisito es necesario para la seguridad y evitar usuarios maliciosos entren al sistema. 

    No funcional 4. 

    Utilizar el framework de Laravel: Para codificación del proyecto es con el lenguaje de programación PHP, usando el framework laravel, para reutilizar código de terceros y tener una estructura más ordenada en el proyecto MVC (Modelo, Vista y Controlador). 

    No funcional 5. 

    Utilizar el logo de la empresa desarrollo: Este requisito es para promocionar la empresa de desarrollo. 

 

 

    Prototipo diseño gráfico. 

 

A continuación, se presentan las propuestas realizadas por el diseñador junto a una breve explicación de cada interfaz; 

 

Login. 

 

Sección “Informes”, sin informes a mostrar. 

 

Menú lateral desplegado en la sección “Informes”, sin informes a mostrar. 

 

Sección “Informes”, el cual muestra la totalidad de los informes solicitados, marcando con un botón gris los documentos ya visualizados. 

 

Sección “Clientes”, en la cual se administraría los usuarios que han pedido informes. 

 

 

 

 

 

 

    Modelo de datos. 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

    Funcionalidad del software. 

 

    Diagrama de flujo (Inicio de sesión-administrador). 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

    Diagrama de flujo (Administrar-cliente) 

 

 

 

 

    Diagrama de flujo (Administrar usuario) 

 

 

    Diagrama de flujo (Ingreso de informe) 

 

 

 

 

 

 

 

 

 

 

    Diagrama de flujo (Eliminar-informe) 

 

 

 

 

 

 

 

    Conclusión 

Durante toda la codificación del sistema web, se fue documentando las acciones, metodología ágil como el scrum dan mayor facilidad de desarrollo y tener un programa adaptado a las necesidades de cliente, analizando las historias de caso de uso, identificando los actores que utilizan el sistema (administrador y cliente) durante la interacción con del código se modificó el diagrama con su cambio o agregación de este mismo, la utilización de herramientas case facilita la mayor compresión del sistema para no necesitar ver el código fuente y no tener confusiones. 

Para la toma de requerimiento se realizó la técnica de entrevista con el cliente preguntando como desea el sistema, para un programa personalizado, fácil de comprender y utilizar por el usuario. Definiendo los requerimientos funcionales y no funcionales. Definición de requisito del sistema como lo mínimos componentes de hardware, de comunicación para el tráfico de internet y compatibilidad con diferentes navegadores web. 

En el diseño de la interfaz de usuario fue creada por un diseñador gráfico, creando bosquejos para el desarrollo del proyecto basado en los bosquejos, el diseño gráfico fue traspasado a código, HTML, CSS y el Framework de Bootstrap para mayor facilidad de codificación, diseñando el inicio de sesión con colores y logotipos de la empresa que solicita el desarrollo, el panel de administrador y panel del usuario cliente. 

Para el mayor entendimiento de la funcionalidad del sistema se dibujaron diagramas de flujos (dfd), creando el inicio de sesión, administración de cliente, administración de usuario, ingresar un informe y eliminar el informe. Utilizando programas (case) para crear los diagramas correspondientes para el desarrollo, con un mayor entendimiento de este mismo. 

Este documento está toda la información fácil de comprender del sistema de Suelotest, utilizando metodologías de desarrollo para mayor rápides, el sistema comprende de otros dos documentos, diferenciados por tipos de usuarios (Administrador-cliente), esto es importante para que los usuarios que no entiendan como utilizar el sistema consulte a la documentación de usuario, en caso de no entender la utilidad consulte con alguien que sepa o el mismo programador del sistema le brinda soporte, puede ser por video llamada. 
