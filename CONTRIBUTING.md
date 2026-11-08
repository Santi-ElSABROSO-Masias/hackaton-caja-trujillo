# Guía interna del equipo

Este documento es para los integrantes. El `README.md` es la cara pública: lo lee el
jurado, así que ahí no van instrucciones.

---

## Qué evalúa el formulario

El paso 4 (*Habilidades*) es **individual**. Cada quien escribe sus propios textos. Este
repositorio es el enlace de validación que se adjunta en *"Enlace a un proyecto, demo o
portafolio"*, y la fuente de la que cada uno redacta sus respuestas.

Los textos se califican contra tres habilidades. Toda evidencia debe hablar de estas tres,
no del stack técnico:

| Habilidad | Qué quieren ver |
|---|---|
| Análisis de problemas y procesos de negocio | Que entendiste el problema antes de construir |
| Diseño de soluciones y propuestas de valor | Que la solución responde al problema y a quién sirve |
| Definición de indicadores y evaluación de resultados | Que mediste si funcionó, y con qué |

La plantilla de evidencia está ordenada en ese mismo orden. Quien la llena bien tiene los
tres campos del formulario casi redactados.

---

## Cómo subir tu evidencia

1. Copia `evidencias/_PLANTILLA/` y renómbrala `evidencias/<tu-nombre>-<proyecto>/`.
   Ejemplo: `evidencias/step-dashboard-bi/`.
2. Llena el `README.md` de tu carpeta. No borres secciones: si algo no aplica, escríbelo.
3. Pon las capturas en `capturas/` y enlázalas desde tu README.
4. Agrega tu fila a la tabla de integrantes del `README.md` principal, y tu proyecto a la
   sección de evidencias.
5. Commit y push a `main`.

```bash
git clone https://github.com/Santi-ElSABROSO-Masias/hackaton-caja-trujillo.git
cd hackaton-caja-trujillo

cp -r evidencias/_PLANTILLA evidencias/<tu-nombre>-<proyecto>

git add evidencias/<tu-nombre>-<proyecto>
git commit -m "Agrega evidencia: <proyecto> (<tu nombre>)"
git push
```

No borres ni edites `evidencias/_PLANTILLA/`. Es el molde para los demás.

---

## Antes de subir cualquier cosa

Este repositorio es **público**. Lo ve el jurado y cualquier otro postulante. Revisa tu
material contra esta lista:

- [ ] No hay nombres, DNI, correos, teléfonos ni datos de clientes reales.
- [ ] No hay credenciales, tokens, cadenas de conexión ni archivos `.env`.
- [ ] No hay documentos internos, contratos ni material bajo acuerdo de confidencialidad
      de ninguna empresa o institución.
- [ ] Las capturas no dejan ver correos, rutas locales con tu usuario, ni pestañas del
      navegador con información personal.

Si un proyecto no puede pasar esta lista, descríbelo en texto sin capturas, o usa otro.

---

## Datos sintéticos

Son válidos. Declararlos es obligatorio, en tu ficha y en la sección "Sobre los datos" del
README principal. Un análisis bien hecho sobre datos sintéticos vale más que un resultado
real sin método, y el jurado distingue la diferencia. Declararlo suma; que lo descubran,
resta.

---

## Capturas

- PNG, ancho mínimo 1280 px.
- Nombres descriptivos: `dashboard-rotacion-clientes.png`, no `Captura1.png`.
- Recorta el navegador y la barra de tareas. Deja solo el producto.
- Verifica que se vean renderizadas en GitHub, no solo en tu editor.

---

## Criterio de redacción

Resultados antes que herramientas. Nadie evalúa un stack: evalúan qué cambió y cómo lo
sabes.
