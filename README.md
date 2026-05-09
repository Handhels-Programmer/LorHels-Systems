# **LorHels-Systems**

---

### 🌐 1. El Sitio Web Principal (El imán de ventas)

Es la cara pública de tu empresa. Está diseñada para captar la atención, mostrar tu trabajo y convertir visitantes en clientes.

* **Diseño Premium:** Interfaz oscura, moderna, con efectos "Glassmorphism" (cristalizado), animaciones suaves al hacer scroll y diseño 100% adaptable a celulares.
* **Catálogo de Demos en Vivo:** Un portafolio interactivo donde los clientes pueden probar tus sistemas (LorHels ERP, CV, Music, Barber, etc.) dentro de una ventana emergente sin salir de tu página.
* **Captación de Leads:** Un formulario de contacto inteligente que, al llenarse, envía el mensaje directamente a tu base de datos privada.
* **Autenticación Inteligente:** Una ventana flotante para iniciar sesión o crear cuenta. El sistema reconoce si el usuario ya está logueado y cambia el botón de "Iniciar Sesión" por "Ir al Panel".

---

### 🤝 2. El Portal del Cliente (La experiencia VIP)

Un espacio privado, seguro y exclusivo para que tus clientes gestionen su relación con tu agencia.

* **Seguridad:** Solo los usuarios registrados pueden entrar.
* **Seguimiento de Proyectos en Vivo:** Los clientes pueden ver la fase actual de su proyecto y una barra de progreso que se mueve en tiempo real.
* **Hilo de Comentarios (Chat):** Un chat bidireccional integrado en cada proyecto para hablar directamente contigo, eliminando el desorden de correos o WhatsApps.
* **Botón "Ver Sistema en Vivo":** Un botón mágico que solo aparece cuando tú les asignas un enlace, permitiéndoles probar su sistema mientras lo desarrollas.
* **Centro de Soporte:** Pueden abrir "Tickets" detallando problemas y ver el estado de los mismos (Abierto/Resuelto).
* **Cotizaciones y Finanzas:** Reciben presupuestos enviados por ti y pueden dar clic en "Aprobar", lo que cambia el estado al instante.
* **Navegación Móvil:** Un menú lateral deslizable que hace que usar el portal desde el celular se sienta como una app nativa.

---

### 👑 3. El Centro de Mando (Tu panel de Administrador)

Es el corazón de tu negocio. Una ruta súper protegida a la que **solo tú** (como Admin) tienes acceso para controlar toda la agencia.

* **Métricas en Vivo (Resumen):** Contadores automáticos que te muestran cuántos clientes tienes, proyectos activos y tickets por resolver, además de una lista de los últimos usuarios registrados.
* **Gestor de Proyectos (Punto de Control):**
* Puedes crear proyectos y asignárselos a un cliente específico.
* Botones de acción rápida para: **Cambiar el % de progreso**, **Editar la fase** (ej. "En diseño"), **Asignar la URL en vivo**, y **Abrir el Chat** para responderle al cliente.


* **Bandeja de Leads:** Todos los mensajes del formulario de tu página web caen aquí. Puedes leerlos y marcarlos como "Leídos" o "Atendidos".
* **Atención de Tickets:** Puedes leer los reportes de fallos de tus clientes y marcarlos como "Resueltos" con un solo clic.
* **Módulo de Cotizaciones:** Creas presupuestos con un concepto y monto en dólares, los asignas a un cliente y se los envías a su portal para que los aprueben.

---

### ⚙️ 4. El Motor Invisible (Backend & Seguridad)

La arquitectura que sostiene todo es la de una aplicación moderna sin servidor (*Serverless*).

* **Firebase Authentication:** Gestión segura de contraseñas y correos.
* **Cloud Firestore (Base de Datos en Tiempo Real):** Todo está conectado por "túneles en vivo" (`onSnapshot`). Si tú apruebas algo en tu panel, el cliente lo ve reflejado en su pantalla en milisegundos sin tener que recargar la página.
* **Reglas de Seguridad Estrictas:** Configuramos un muro en Firestore que garantiza que un cliente A jamás pueda leer los proyectos, tickets o chats del cliente B, y que nadie pueda escribir donde no debe.
* **Hosting Global:** Desplegado en los servidores CDN de Google, garantizando carga rápida y seguridad SSL en cualquier parte del mundo.

---
