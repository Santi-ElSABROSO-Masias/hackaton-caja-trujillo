# SUSALUD — Sistema de gestión de atención médica

Plataforma web para centralizar la información del paciente y dar seguimiento al proceso
de atención médica.

| | |
|---|---|
| **Integrante** | Lua Almendra Castro Salas |
| **Rol en el proyecto** | Proyecto personal, desarrollo individual |
| **Contexto** | Proyecto personal · en desarrollo |
| **Repositorio** | [luxy-h/SISTEMA-SUSALUD](https://github.com/luxy-h/SISTEMA-SUSALUD) |

---

## 1. El problema

En un establecimiento de salud pequeño, la información del paciente queda repartida entre
cuadernos de registro, formatos impresos y archivos sueltos. Cada atención genera datos
—diagnóstico, tratamiento, antecedentes— que no quedan vinculados al paciente de forma
consultable.

El costo aparece en la siguiente consulta: el profesional no tiene a la vista el historial
de quien atiende, y reconstruirlo depende de que alguien encuentre el papel correcto.
Tampoco hay forma de responder preguntas agregadas —cuántas atenciones hubo esta semana,
qué diagnósticos se repiten— porque los registros no están en una estructura que lo
permita.

---

## 2. La solución

Una aplicación web que centraliza pacientes, historias clínicas y atenciones en una sola
base, con acceso autenticado por usuario.

### Panel principal

Indicadores calculados directamente desde la base de datos:

- Pacientes registrados
- Atenciones médicas
- Diagnósticos registrados
- Tratamientos registrados
- Actividad de atenciones de los últimos siete días
- Listado de las atenciones más recientes
- Accesos rápidos a los procesos frecuentes

El panel no es un adorno: convierte el registro en información de gestión. La actividad de
los últimos siete días responde una pregunta que en papel no tiene respuesta rápida.

### Stack

| Capa | Tecnología |
|---|---|
| Backend | PHP |
| Base de datos | MySQL |
| Interfaz | HTML5 y CSS3 |

---

## 3. Estado

**En desarrollo.** El sistema cuenta con autenticación de usuarios y la interfaz de
gestión desde la que se accede a los procesos principales.

---

## 4. Capturas

<PENDIENTE: agregar capturas de la interfaz en `capturas/`>
