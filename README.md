# kinetrack_capstone_002
# KineTrack 🩹

**Gestión activa de tratamientos kinesiológicos con alertas inteligentes**

![Estado](https://img.shields.io/badge/Estado-En%20Desarrollo-yellow) ![Metodología](https://img.shields.io/badge/Metodología-Scrum-blue)

## 📌 Sobre el Proyecto

**KineTrack** es una plataforma web, con diseño responsive para uso móvil, orientada a la gestión activa del proceso de rehabilitación kinesiológica en centros con varios profesionales. Aborda el problema del seguimiento manual y disperso —fichas físicas, planillas y ejercicios entregados en papel— que impide detectar a tiempo molestias, complicaciones o abandono del tratamiento.

El sistema permite a los kinesiólogos registrar pacientes, asignar planes de ejercicios y programar sesiones de control, mientras que un sistema transaccional de alertas garantiza que ninguna molestia reportada ni período de inactividad quede sin atención, escalando automáticamente a Coordinación cuando corresponde.

## ✨ Características Principales

- 👥 **Cuatro Perfiles de Usuario:** Paciente, Kinesiólogo, Coordinación y Administrador, cada uno con su propio flujo dentro de la plataforma.
- 🚨 **Alertas de Seguimiento con Escalamiento:** Notificación inmediata al kinesiólogo ante molestias (escala EVA ≥7) o inactividad prolongada; si no se atiende a tiempo, escala automáticamente a Coordinación.
- 📷 **Visión Computacional On-Device:** Integración de MediaPipe (Edge AI) para generar una referencia visual del movimiento articular, sin almacenar ni transmitir video del paciente.
- 📊 **Dashboard Analítico:** Reportería diferenciada por perfil y analítica de tasa de abandono y adherencia promedio por tipo de diagnóstico.

## 🛠️ Stack Tecnológico (Proyectado)

- **Frontend:** React, para el desarrollo de la plataforma web responsive.
- **Backend & Base de Datos:** Supabase (Backend as a Service) para autenticación, base de datos y notificaciones en tiempo real.
- **Visión Computacional:** MediaPipe, procesado on-device para el análisis de movimiento articular.
- **Modelado de Datos:** MySQL Workbench / Draw.io para el diseño del modelo entidad-relación y la arquitectura del sistema.
- **Control de Versiones:** GitHub, para el trabajo colaborativo del equipo.

## 📂 Estructura de este Repositorio

Actualmente, este repositorio contiene la documentación correspondiente a la **Fase 1 (Definición y Planificación)** del proyecto.

