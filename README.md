# Twenty 4 — Cajathon Caja Trujillo

Evidencias de los proyectos que respaldan la postulación de este equipo.

**Desafío al que postulamos:** Riesgos

Las evidencias de este repositorio se presentan desde esa perspectiva: control
preventivo, trazabilidad para auditoría y diseño frente a un usuario con incentivo
para evadir el control.

---

## El equipo

| Integrante | Aporte | Evidencias | GitHub |
|---|---|---|---|
| Daniel Stip Sarmiento Valdez | Arquitectura, reglas antifraude, app móvil y backend en Cortex · Automatización, reglas de negocio e integración en Agrovicman | [Cortex](evidencias/daniel-cortex/) · [Agrovicman](evidencias/daniel-agrovicman-whatsapp/) | [@Santi-ElSABROSO-Masias](https://github.com/Santi-ElSABROSO-Masias) |
| Bryan Quispe Puma | Desarrollo en Cortex · Diseño UX/UI en Agrovicman | [Cortex](evidencias/daniel-cortex/) · [Agrovicman](evidencias/daniel-agrovicman-whatsapp/) | [@BryankqpDev](https://github.com/BryankqpDev) |
| Lua Almendra Castro Salas | Diseño UX/UI en Agrovicman | [Agrovicman](evidencias/daniel-agrovicman-whatsapp/) | [@luxy-h](https://github.com/luxy-h) |
| Tirza Buendía González |  | [BI Ferretería Salas](evidencias/tirza-bi-ferreteria/) | [@azritB](https://github.com/azritB) |

---

## Evidencias

Cada carpeta documenta un proyecto con la misma estructura: el problema de negocio, el
análisis que lo precedió, la solución, los indicadores con que se evaluó y sus
limitaciones.

### Asistente comercial de WhatsApp — Agrovicman
Un productor de café de especialidad vendía por WhatsApp atendido por una sola persona:
respuestas fuera de horario perdidas, precios inconsistentes entre clientes y stock
repartido en dos ciudades. El asistente responde al instante con el precio correcto
tomado del inventario, respeta un piso de negociación y devuelve la conversación a la
dueña cuando hace falta.

**Segundo puesto** en hackathon. Construido y funcional.

→ [Ver documentación](evidencias/daniel-agrovicman-whatsapp/) · [Ver demo en video](https://youtu.be/N10_jb003mM)

### Cortex — La Secuencia
En faena minera, el control de ingreso se apoyaba en listas en papel e inspección visual
del supervisor: ni objetivo ni reproducible ante una auditoría tras un incidente. Cortex
mide el estado psicomotriz del operador antes de que tome el control de maquinaria
pesada, con registro inalterable y trazabilidad por contratista.

**En producción**: 505 evaluaciones en los últimos 30 días, 33 operadores activos en dos
turnos, 14,7 % de resultados no aptos detectados. 305 pruebas automatizadas cubren las
reglas de decisión de seguridad.

→ [Ver documentación](evidencias/daniel-cortex/) · [Ver demo en video](https://youtu.be/5cQqVPp6WrM)

### Dashboard de inteligencia de negocios — Ferretería Salas
Una ferretería decide qué reponer por costumbre y por disponibilidad del proveedor, sin
medir rotación ni estacionalidad: el costo no se ve en la caja diaria sino en el capital
inmovilizado en stock que no se mueve. El proyecto construye el modelo de datos que falta
—ocho tablas— define cuatro KPIs de abastecimiento y los lleva a un tablero de tres hojas
que termina en recomendaciones de compra concretas.

Proyecto de tesis, trabajo individual. Datos **sintéticos**: demuestra el método completo,
del esquema a la recomendación, no un diagnóstico de un negocio real.

→ [Ver documentación](evidencias/tirza-bi-ferreteria/) ·

---

## Sobre los datos

Los proyectos aquí documentados describen arquitectura y decisiones de diseño. Ninguno
publica credenciales, endpoints, identificadores de bases de datos, datos de contacto ni
información comercial de los clientes involucrados.

Las evidencias que usan datos sintéticos lo declaran en su propia ficha y en el resumen
de esta portada.

---

## Cómo está organizado

```
evidencias/
  <integrante>-<proyecto>/
    README.md      ficha del proyecto
    capturas/      evidencia visual
```

Integrantes del equipo: ver [CONTRIBUTING.md](CONTRIBUTING.md).
