🧩 Sistema de Gestión de Usuarios con Laravel y AngularJS — Guía Práctica
🎯 Descripción General
Este proyecto implementa una aplicación web completa para administrar usuarios, usando Laravel como framework del lado del servidor y AngularJS para la interfaz interactiva. Además, se integra MySQL como motor de base de datos y se mejora la experiencia de usuario con Bootstrap y DataTables.

🛠 Herramientas y Tecnologías
Componente	Tecnología Empleada
Backend	Laravel (PHP Framework)
Frontend	AngularJS + Bootstrap
Base de Datos	MySQL
Librerías Extra	Laravel Mail, DataTables
Integraciones	API de Pokémon, calculadora CURP

🔧 Funcionalidades Principales del Sistema
Inicio de Sesión y Registro

Gestión de usuarios autenticados usando las herramientas de autenticación nativas de Laravel.

Envío de notificación por correo electrónico al registrar una nueva cuenta.

Módulo CRUD de Usuarios

Alta de usuarios con validaciones.

Consulta de registros en una tabla con filtros, paginación y ordenamiento dinámico.

Actualización de datos del usuario mediante formularios editables.

Eliminación de registros con confirmación.

Interfaz Optimizada

Paginación y búsqueda instantánea con DataTables, permitiendo una navegación más ágil y profesional.

Conexión con API Pública

Permite al usuario seleccionar su Pokémon favorito, haciendo uso de la API oficial de Pokémon.

Edad a partir del CURP

Extrae la fecha de nacimiento del CURP para calcular la edad automáticamente, sin guardar ese dato en la base de datos.

Gestión de Archivos

Subida y previsualización de imágenes de perfil.

📋 Requisitos Previos
Antes de instalar la aplicación, necesitas tener configurado tu entorno con:

PHP versión 8 o superior

Composer (administrador de dependencias PHP)

MySQL o MariaDB

Node.js y npm para manejar los assets del frontend
