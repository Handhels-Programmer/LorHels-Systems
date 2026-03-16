# LorHels-Systems

1. La Cara Pública (Landing Page de Alta Conversión)
Tu index.html es la máquina de ventas. Está diseñada para impresionar y captar clientes:

Hero Section Moderno: Un inicio impactante con un monitor flotante en 3D (glassmorphism) que muestra una captura real de tu sistema, adornado con notificaciones animadas ("Proyecto Aprobado", "Nuevo Lead") que dan sensación de actividad y éxito.

Portafolio Interactivo: Una cuadrícula con 6 soluciones tecnológicas (ERP, E-Commerce, Citas Médicas, LMS, RRHH, Logística).

Visor de Demos Integrado: Al hacer clic en un proyecto, en lugar de sacar al cliente de tu página, se abre una ventana elegante (Iframe) donde el cliente puede probar el sistema real sin salir de lorhels.com.

Captura de Leads: Un formulario de contacto conectado directamente a tu base de datos.

2. El Motor Oculto (Backend y Seguridad)
Toda tu plataforma está respaldada por la infraestructura de Google (Firebase):

Autenticación Segura: Sistema de login y registro de usuarios.

Roles Inteligentes: El sistema sabe distinguir entre un "Administrador" (tú) y un "Cliente", bloqueando el acceso a quien no corresponda.

Magia en Tiempo Real (onSnapshot): La base de datos no es estática; está "viva". Los datos viajan entre tu panel y el del cliente al instante, sin necesidad de recargar la página.

3. Panel de Administrador (Tu Centro de Mando)
Un entorno de trabajo oscuro, elegante y estructurado como una Single Page Application (SPA), donde controlas todo tu negocio a través de 5 pestañas:

📊 Resumen: Tarjetas con estadísticas en vivo (clientes, proyectos, tickets) y una lista de los últimos usuarios registrados.

📁 Proyectos: Puedes crear proyectos, asignárselos a clientes, y actualizar su fase y porcentaje de progreso en tiempo real.

💬 Mensajes (Leads): Una bandeja de entrada en vivo donde caen los mensajes de tu landing page y las solicitudes de nuevos proyectos. Puedes marcarlos como leídos.

🛟 Soporte: Recibes y gestionas los tickets de ayuda de tus clientes, cambiando su estado a "Resuelto".

💰 Finanzas: Puedes generar cotizaciones formales con montos específicos y enviarlas al panel del cliente para su aprobación.

4. Portal del Cliente (Experiencia B2B Premium)
Tus clientes tienen su propia área privada (también SPA), diseñada para darles tranquilidad y transparencia:

🚀 Mi Proyecto: Ven una tarjeta con el nombre de su sistema, la fase actual y una barra de progreso que se mueve sola en tiempo real cuando tú actualizas los datos. También tienen un botón para solicitar nuevos proyectos.

💸 Mis Cotizaciones: Una tabla donde reciben tus presupuestos. Tienen un botón verde para "Aprobar" la cotización con un solo clic (lo que te notifica al instante).

🎫 Soporte Técnico: Pueden enviarte tickets de ayuda detallando la prioridad (alta, media, baja) y ver el historial de sus problemas resueltos.

👤 Mi Perfil: Pueden actualizar su nombre y teléfono, asegurando que siempre tengas sus datos de contacto al día para cerrar ventas.
