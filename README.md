# Sistema de Gestión Suelotest

Proyecto web desarrollado para la gestión de clientes e informes, orientado a un entorno empresarial, con control de acceso, roles de usuario y administración de datos.

---

## 📌 Descripción general

El sistema permite a usuarios **administradores** y **clientes** interactuar con una plataforma segura para:

* Autenticación de usuarios
* Administración de clientes
* Gestión y descarga de informes en PDF
* Control de roles y permisos

El desarrollo sigue una arquitectura **MVC**, utilizando **Laravel** como framework principal y **MySQL** como motor de base de datos.

---

## 👥 Actores del sistema

* **Administrador**: Control total del sistema (usuarios, clientes, informes).
* **Cliente**: Acceso limitado para visualización y descarga de informes.

---

## 📚 Casos de uso

### C01 – Iniciar sesión

* **Actor:** Administrador
* **Descripción:** El administrador ingresa sus credenciales para acceder al panel de control.

### C02 – Cerrar sesión

* **Actor:** Administrador / Sistema
* **Descripción:** El administrador cierra sesión y el sistema bloquea accesos no autorizados.

### C03 – Administrar cliente

* **Actor:** Administrador
* **Descripción:** Permite agregar, editar y eliminar clientes.

### C04 – Listar clientes

* **Actor:** Sistema
* **Descripción:** Despliega los clientes registrados en la base de datos en formato tabla.

### C05 – Agregar cliente

* **Actor:** Sistema
* **Descripción:** Registra un nuevo cliente bajo acción del administrador.

### C06 – Editar cliente

* **Actor:** Sistema
* **Descripción:** Modifica los datos de un cliente existente.

### C07 – Eliminar cliente

* **Actor:** Sistema
* **Descripción:** Elimina un cliente del sistema.

---

## ⚙️ Requerimientos funcionales

### RF01 – Iniciar sesión

* **Descripción:** Acceso al sistema mediante credenciales válidas.
* **Prioridad:** Alta

### RF02 – Cerrar sesión

* **Descripción:** Opción para cerrar sesión y volver al login.
* **Prioridad:** Alta

### RF03 – Administrar cliente

* **Descripción:** CRUD completo de clientes usando Laravel y MySQL.
* **Prioridad:** Alta

### RF04 – Roles de usuario

* **Descripción:** Diferenciación entre administrador y cliente.
* **Prioridad:** Alta

### RF05 – Subir informes

* **Descripción:** Carga de informes en formato PDF para descarga.
* **Prioridad:** Alta

### RF06 – Deshabilitar usuario

* **Descripción:** Control de estado de usuario (habilitado/deshabilitado).
* **Prioridad:** Alta

### RF07 – Relaciones de tablas

* **Descripción:** Definición de relaciones entre usuarios, clientes e informes.
* **Prioridad:** Alta

---

## 🔒 Requerimientos no funcionales

### RNF01 – Diseño acorde al negocio

* UI basada en HTML5, CSS3 y Bootstrap.
* **Prioridad:** Alta

### RNF02 – Diseño responsive

* Adaptable a móviles, tablets y escritorio.
* **Prioridad:** Alta

### RNF03 – Seguridad

* Encriptación de contraseñas usando **Bcrypt**.
* **Prioridad:** Alta

### RNF04 – Uso de Laravel

* Framework PHP para seguridad y mantenibilidad.
* **Prioridad:** Alta

### RNF05 – Identidad corporativa

* Inclusión del logo de la empresa en login y panel.
* **Prioridad:** Alta

---

## 🎨 Interfaces de usuario

* Login como pantalla inicial.
* Panel de administrador.
* Panel de cliente.

El diseño se basa en la landing page de **Suelotest.cl**, manteniendo:

* Tipografía: Arial
* Colores: Blanco (#FFFFFF) y Verde (#2D9F87)

El objetivo es una interfaz intuitiva, con baja carga cognitiva y navegación clara.

---

## 💻 Requisitos de hardware

* Procesador: Pentium 4 Dual Core 1.66 GHz o superior
* RAM: 2 GB mínimo
* Conectividad a internet (>2 Mbps)
* Mouse y teclado

---

## 🧑‍💻 Requisitos de software

* **Sistema operativo:**

  * Windows 7 o superior
  * Android 6.0 o superior
  * iOS 10.1 o superior

* **Navegadores:**

  * Chrome
  * Firefox
  * Opera
  * Edge

---

## 🌐 Interfaces de comunicación

El sistema utiliza protocolos estándar de internet para la comunicación entre clientes, servidores y transferencia de archivos (HTTP/FTP u otros).

---

## 🗂️ Modelo de datos

El sistema maneja relaciones entre:

* Usuarios
* Clientes
* Informes

Las relaciones están diseñadas para mantener integridad y escalabilidad.

---

## 🔄 Funcionalidad y diagramas

Se implementaron diagramas de flujo para:

* Inicio de sesión
* Administración de clientes
* Administración de usuarios
* Ingreso y eliminación de informes

Estos diagramas permiten comprender el sistema sin necesidad de revisar el código fuente.

---
## 🖼️ Capturas del sistema

### Pantalla de inicio de sesión
![Login](docs/screenshots/login.png)


---

## ✅ Conclusión

Durante el desarrollo se aplicaron metodologías ágiles (Scrum), levantamiento de requerimientos mediante entrevistas y documentación constante.

El sistema fue diseñado para ser:

* Seguro
* Intuitivo
* Escalable
* Fácil de mantener

La documentación permite que usuarios finales y técnicos comprendan el funcionamiento del sistema sin fricción, cumpliendo con los objetivos del negocio Suelotest.

---

📌 *Este proyecto forma parte de un portafolio profesional y representa un desarrollo orientado a entornos reales de trabajo.*
