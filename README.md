# GSI-Primark
🛍️ Sistema RRHH Primark - Portal del Empleado (Intranet)

📖 Sobre el Proyecto

Este proyecto consiste en el diseño, desarrollo e implantación de un Portal del Empleado (Intranet) corporativo para la gestión de Recursos Humanos de Primark.

El objetivo principal es la digitalización y centralización de los procesos administrativos internos de las tiendas, sustituyendo la gestión tradicional basada en cuadrantes de papel y correos electrónicos desestructurados por un entorno digital seguro, interactivo y eficiente.

Proyecto desarrollado en el ámbito académico de la Universidad de Sevilla.

✨ Funcionalidades Principales

El sistema está diseñado para cubrir las necesidades tanto del personal base como de la gerencia:

📅 Gestión Interactiva de Turnos: Visualización de horarios actualizados y alertas de solapamiento.

📄 Descarga de Nóminas: Acceso confidencial e historial retributivo en PDF.

🏖️ Gestión de Vacaciones: Formulario de solicitudes con validación de reglas de negocio (preaviso mínimo de 15 días y límite anual de 22 días).

📊 Dashboard de Analítica (HR): Cuadro de mando para la gerencia con KPIs de costes laborales y métricas de personal.

🔒 Seguridad y Enrutamiento: Sistema de login seguro con prevención de fuerza bruta y redirección basada en roles.

👥 Roles de Usuario

El portal diferencia el acceso y las vistas según el nivel de privilegios del usuario:

Empleado: Usuario base que interactúa con el sistema para consultar sus nóminas, ver sus turnos asignados y solicitar vacaciones.

Gerente de Tienda: Encargado de asignar turnos, revisar la disponibilidad mediante cuadrantes interactivos y gestionar las ausencias de su sucursal.

Técnico de RRHH: Administrador global con permisos para altas/bajas de trabajadores, gestión de contratos y monitorización analítica.

🛠️ Stack Tecnológico y Entorno

La plataforma está construida sobre el CMS WordPress para facilitar la gestión de contenidos, complementado con desarrollos a medida inyectados en el frontend.

Frontend y Diseño

Tema Base: Astra (Seleccionado por su carga ultraligera <0.5s y ausencia de dependencias de jQuery).

Estilos y Lógica: HTML5, Tailwind CSS y JavaScript (Vanilla JS).

Almacenamiento Local: LocalStorage para el control lógico de enrutamiento en vistas a medida.

Plugins Core

🛡️ Wordfence Security: Firewall (WAF) en tiempo real para proteger datos sensibles (DNI, nóminas) contra ataques de fuerza bruta e inyecciones SQL.

⚡ LiteSpeed Cache: Optimización de caché para garantizar la estabilidad del servidor ante picos de accesos concurrentes (ej. días de cobro).

📈 MonsterInsights: Panel de analítica integrado para la monitorización de uso por parte de RRHH.

🔍 Rank Math SEO: Estructuración e indexación interna de manuales corporativos y normativas.

Gestión y Herramientas Ágiles

Metodología: SCRUM gestionado a través de Jira (Sprints, Product Backlog, Burndown Charts).

Control de Versiones: GitHub para la preservación de código (HTML/CSS/JS) inyectado.

Comunicación: Servidor de Discord integrado mediante Webhooks para notificaciones automáticas de pushes en GitHub y transiciones en Jira.

Servidor Local: XAMPP (Apache, MariaDB/MySQL, PHP).

🚀 Despliegue Local (XAMPP)

Para levantar este entorno en un servidor local:

Instalar XAMPP y arrancar los módulos de Apache y MySQL.

Clonar el repositorio en la carpeta htdocs de XAMPP.

Importar la base de datos MySQL (archivo .sql proporcionado en el repositorio) a través de phpMyAdmin.

Asegurarse de tener instalado WordPress y el tema Astra activado.

Instalar y activar los 4 plugins requeridos (Wordfence, LiteSpeed Cache, MonsterInsights, Rank Math).

👨‍💻 Equipo de Desarrollo (Scrum Team)

Aimar García Borrego - Desarrollador Frontend

David Ávalos Moya - Scrum Master

Pablo Seco Amores - Desarrollador Backend

Antonio Pulido Barba - Analista de Requisitos

Juan Manuel Martínez Librero - DBA y Gestor de Repositorio

Documentación técnica completa disponible en los archivos REMUS (Requisitos) y Memoria de Proyecto adjuntos en este repositorio.
