# Twenty 4 - CAJATHON

Evidencias de los proyectos que respaldan la postulación de este equipo.

**Desafío al que postulamos:** Riesgos

---

## El equipo

| Integrante | Aporte | Evidencias | GitHub |
|---|---|---|---|
| Daniel Stip Sarmiento Valdez | Arquitectura y backend | [Cortex](evidencias/daniel-cortex/) · [Agrovicman](evidencias/daniel-agrovicman-whatsapp/) · [ArsaTours](evidencias/daniel-arsatours/) | [@Santi-ElSABROSO-Masias](https://github.com/Santi-ElSABROSO-Masias) |
| Bryan Kevin Quispe Puma | Product manager · Project manager | [Cortex](evidencias/daniel-cortex/) · [Agrovicman](evidencias/daniel-agrovicman-whatsapp/) · [BI Ferretería Salas](evidencias/tirza-bi-ferreteria/) | [@BryankqpDev](https://github.com/BryankqpDev) |
| Lua Almendra Castro Salas | Diseño UX/UI | [Agrovicman](evidencias/daniel-agrovicman-whatsapp/) · [SUSALUD](evidencias/lua-susalud/) | [@luxy-h](https://github.com/luxy-h) |
| Tirza Nicol Buendía González | Ciencia de datos · Aprendizaje automático | [BI Ferretería Salas](evidencias/tirza-bi-ferreteria/) · [Detección de somnolencia](evidencias/tirza-deteccion-somnolencia/) | [@azritB](https://github.com/azritB) |

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

**Segundo puesto** en hackathon Transforma + Mipyme. Construido y funcional.

→ [Ver documentación](evidencias/daniel-agrovicman-whatsapp/) · [Ver demo en video](https://youtu.be/N10_jb003mM)

### Cortex — La Secuencia
¿Cómo podemos anticiparnos a accidentes en minería de conductores que generar miles de gastos millonarios y pérdidas humanas con
accidentes trágicos?. Ahí nace Cortex, un aplicativo que estudia el cansancio físico, corporal, resacas y somnolencias en conductores
con simples test, probados por neurólogos internacionales en estudios de universidades del extranjero. Creamos un ambiente seguro, sin trampas
para que los usuarios puedan rendir evaluaciones en tiempo real, con identificación facial y modelos de ML. Hacemos de la minería
un entorno seguro, para que todos podamos llegar a casa para ver a nuestras familias. El test es tan riguroso, que solo 1 pasada es 
la única oportunidad que tiene un operador. Somos justos, con las vidas humanas no se juegan.

**En producción**: 505 evaluaciones en los últimos 30 días, 33 operadores activos en dos
turnos, 14,7 % de resultados no aptos detectados. 305 pruebas automatizadas cubren las
reglas de decisión de seguridad.

→ [Ver documentación](evidencias/daniel-cortex/) · [Ver demo en video](https://youtu.be/5cQqVPp6WrM)

### Análisis Preescriptivo — Ferretería Salas
Una ferretería decide qué reponer por costumbre y por disponibilidad del proveedor, sin
medir rotación ni estacionalidad: el costo no se ve en la caja diaria sino en el capital
inmovilizado en stock que no se mueve. El proyecto construye el modelo de datos que falta
—ocho tablas— define cuatro KPIs de abastecimiento y los lleva a un tablero de tres hojas
que termina en recomendaciones de compra concretas. Eh incluye SCRAPPING para un estudio
estacional de climas, eventos, proyectos, ferias y demás, para anticiparnos al movimiento
del stock, pedidos y proveedores de la Ferretería. 

→ [Ver documentación](evidencias/tirza-bi-ferreteria/) ·

### Detección de somnolencia al volante
La somnolencia del conductor explica el 31,8 % de los accidentes de tránsito en el Perú y
no da aviso: no hay frenos que detengan un cabeceo. Los sistemas de monitoreo existentes
exigen cámaras infrarrojas y cómputo de alta gama, lo que los deja fuera del alcance de la
flota promedio. Este modelo detecta fatiga con una cámara común analizando cierre de ojos,
bostezos e inclinación de cuello.

Entrenado sobre más de 4.000 imágenes reales con XGBoost y Random Forest. Alerta en menos
de un segundo, incluso con conductores que usan lentes.

→ [Ver documentación](evidencias/tirza-deteccion-somnolencia/) · [Ver demo en video](https://drive.google.com/drive/folders/1uiERyUe1m4T0LvR-3WR8qGOtvRlHc_g6?usp=drive_link)

### SUSALUD — Gestión de atención médica
En un establecimiento de salud pequeño, la información del paciente queda repartida entre
cuadernos y formatos impresos, y el historial no está a la vista en la siguiente consulta.
SUSALUD centraliza pacientes, historias clínicas y atenciones en una base consultable, con
un panel de indicadores calculados desde los propios registros.

→ [Ver documentación](evidencias/lua-susalud/)

### Plataforma de tours — ArsaTours
Una agencia de turismo receptivo en Cusco vende a viajeros que no hablan español y compran
antes de llegar: el contenido debe existir en varios idiomas y mantenerse, y las salidas grupales
se venden sobre un cupo finito. La plataforma resuelve ambas: traducción asistida a tres
idiomas revisable antes de publicar, y una restricción en la base de datos que hace
imposible vender una plaza que no existe. Agregamos modelos de predicciones y scraping para realizar
un estudio de dónde enfocar la financiación de los proyectos turísticos, por fechas, estacionalidad,
clima. Un plus innovador, frente a otras webs estáticas.

→ [Ver documentación](evidencias/daniel-arsatours/) · [Visitar el sitio](https://www.arsatourscusco.com/)


```
evidencias/
  <integrante>-<proyecto>/
    README.md      ficha del proyecto
    capturas/      evidencia visual
```
