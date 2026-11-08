# Cómo subir tu evidencia

## Antes de subir cualquier cosa

Este repositorio es **público**. Cualquiera con el enlace lo ve, incluido el jurado y
cualquier otro postulante. Revisa tu material contra esta lista:

- [ ] No hay nombres, DNI, correos, teléfonos ni datos de clientes o pacientes reales.
- [ ] No hay credenciales, tokens, cadenas de conexión ni archivos `.env`.
- [ ] No hay documentos internos, contratos ni material bajo acuerdo de confidencialidad
      de ninguna empresa o institución.
- [ ] Las capturas no dejan ver correos, rutas locales con tu usuario, ni pestañas del
      navegador con información personal.

Si un proyecto no puede pasar esta lista, no lo subas: descríbelo en texto sin capturas, o
usa otro proyecto.

## Datos sintéticos

Son válidos. Declararlos en la ficha es obligatorio. Un análisis bien hecho sobre datos
sintéticos vale más que un resultado real sin método, y el jurado distingue la diferencia.

## Capturas

- Formato PNG, ancho mínimo 1280 px.
- Nombres descriptivos: `dashboard-rotacion-clientes.png`, no `Captura1.png`.
- Si la herramienta tiene modo claro y oscuro, usa el que se lea mejor impreso.
- Recorta el navegador y la barra de tareas. Deja solo el producto.

## Flujo de trabajo

```bash
git clone https://github.com/Santi-ElSABROSO-Masias/hackaton-caja-trujillo.git
cd hackaton-caja-trujillo

cp -r evidencias/_PLANTILLA evidencias/<tu-nombre>-<proyecto>
# edita el README.md, agrega tus capturas en capturas/

git add evidencias/<tu-nombre>-<proyecto>
git commit -m "Agrega evidencia: <proyecto> (<tu nombre>)"
git push
```

No borres ni edites `evidencias/_PLANTILLA/`. Es el molde para los demás.

## Antes de cerrar

Agrega tu fila a la tabla de evidencias del `README.md` principal y marca tu estado como
`listo`. Revisa que tus imágenes se vean en GitHub, no solo en tu editor.
