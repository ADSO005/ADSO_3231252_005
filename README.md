🏥 SIGCMI
Sistema Integral de Gestión de Citas Médicas Inteligentes
4
🚀 Descripción

SIGCMI es una plataforma web diseñada para optimizar la gestión de citas médicas en centros de salud mediante una arquitectura escalable y segura.

El sistema permite:

Registro y autenticación de usuarios

Gestión de pacientes y médicos

Administración de especialidades

Agenda médica con control de disponibilidad

Agendamiento, cancelación y reprogramación de citas

Historial clínico básico

Dashboard administrativo con métricas

Notificaciones automáticas (simuladas)

🏗️ Arquitectura

El sistema implementa una arquitectura Cliente-Servidor en Modelo N-Capas:

🎨 Frontend: React / Angular

⚙️ Backend: Node.js / Python (API REST)

🗄️ Base de Datos: PostgreSQL

🔐 Autenticación: JWT + bcrypt

🔔 Notificaciones: Servicio SMTP simulado

🐳 Docker (opcional)

Capas del Sistema

Capa de Presentación

Capa de Negocio

Capa de Persistencia

🔐 Seguridad

Encriptación de contraseñas con bcrypt

Autenticación basada en JWT

Control de acceso por roles

Protección contra inyección SQL

Manejo de datos sensibles

👥 Roles del Sistema

👤 Paciente

👨‍⚕️ Médico

🛠️ Administrador

📊 Funcionalidades Principales

Registro de pacientes y médicos

Login seguro con JWT

Gestión de disponibilidad médica

Reserva de citas

Cancelación y reprogramación

Notificaciones automáticas

Dashboard administrativo

🧠 Modelo de Datos

Entidades principales:

Usuario

Rol

Paciente

Médico

Especialidad

Cita

HistorialClinico

Todas las entidades utilizan UUID como clave primaria.

🌿 Metodología

🌀 Scrum

🌱 Git Flow

📌 Sprints con estimación Fibonacci

🔄 Pull Requests obligatorios para merge a main

🌱 Estrategia de Ramas
main        → Producción
develop     → Desarrollo principal
release     → Versiones estables
feature/*   → Nuevas funcionalidades
📂 Estructura del Proyecto
SIGCMI/
│
├── frontend/
├── backend/
├── database/
├── docs/
└── README.md
🛠️ Instalación (Ejemplo Backend)
git clone https://github.com/tu-org/SIGCMI.git
cd backend
npm install
npm run dev
📚 Documentación Completa

La documentación técnica completa (diagramas UML, MER, arquitectura detallada y requisitos) se encuentra en la Wiki del proyecto.

🎓 Contexto Académico

Proyecto desarrollado para el programa ADSO – SENA.

Cumple con:

Diagrama de Arquitectura

Diagrama de Componentes

Diagrama de Despliegue

Diagrama de Clases

Modelo Entidad-Relación

Diagramas de Secuencia

Requisitos Funcionales y No Funcionales

📜 Licencia

Proyecto académico – Uso educativo.
