# Detección de somnolencia al volante por visión computacional

Modelo que analiza los gestos faciales del conductor en tiempo real y emite una alerta
cuando aparecen signos de fatiga, usando una cámara común.

| | |
|---|---|
| **Integrante** | Tirza Buendía González |
| **Rol en el proyecto** | Proyecto individual: definición del problema, construcción del conjunto de entrenamiento, modelado, evaluación y prototipo funcional |
| **Contexto** | Proyecto de investigación aplicada |
| **Naturaleza de los datos** | Dataset con imágenes reales de conductores alertas y con somnolencia |
| **Material del proyecto** | [Carpeta con el video de demostración y capturas](https://drive.google.com/drive/folders/1uiERyUe1m4T0LvR-3WR8qGOtvRlHc_g6?usp=drive_link) |

---

## 1. El problema

En el Perú, la somnolencia del conductor explica el **31,8 % de los accidentes de
tránsito**. Entre los conductores de autobús, el **45 %** ha tenido o ha estado a punto de
tener un accidente por quedarse dormido, y el **56 %** admite sentirse cansado mientras
maneja.

Es un riesgo distinto de los demás porque **no da aviso**. El exceso de velocidad se mide,
el alcohol se detecta, la falta de mantenimiento se inspecciona. Un parpadeo involuntario
no deja rastro hasta que ya ocurrió: no hay frenos que detengan un cabeceo.

El transporte interprovincial concentra los factores —jornadas largas, conducción nocturna,
descanso insuficiente—, pero la fatiga no es exclusiva del conductor profesional.
Cualquiera que maneje tras una mala noche o una jornada extensa está expuesto.

**Por qué no está resuelto.** Los sistemas de monitoreo existentes exigen cámaras
infrarrojas de alta gama y equipos de cómputo potentes, o fueron diseñados para entornos
controlados de laboratorio. El costo y la rigidez los dejan fuera del alcance de la flota
promedio, que es justamente donde el riesgo se concentra.

---

## 2. El análisis

La decisión que define el proyecto es la restricción de costo, asumida desde el inicio:
**el sistema debe funcionar con una cámara común**. No es una limitación técnica aceptada
a regañadientes, es el requisito que determina si alguien lo va a usar. Una solución
precisa que exige hardware de miles de dólares no reduce accidentes en una flota pequeña;
una solución razonable que corre con lo que ya hay instalado, sí.

De ahí se derivan las demás decisiones:

- **Qué observar.** Estado del conductor.
- **Qué exigirle al modelo.** La alerta sirve si llega antes del incidente, así que la
  latencia es un requisito, no una métrica secundaria.

**Herramientas y metodologías aplicadas**

| Herramienta / método | Para qué se usó |
|---|---|
| Visión por computadora | Extraer indicadores faciales de video en tiempo real |
| Algoritmos de IA | Clasificar el estado del conductor |
| Pruebas en escenarios variados | Comprobar el comportamiento con y sin lentes |

---

## 3. La solución

**Propuesta de valor:** para un transportista que no puede costear monitoreo
especializado, esto detecta fatiga en el conductor con una cámara común y avisa en menos
de un segundo — a diferencia de los sistemas existentes, que exigen cámaras infrarrojas y
cómputo de alta gama.

El sistema observa el rostro del conductor de forma continua para alertar de manera inmediata al detectar somnolencia. Sin sensores adicionales,
sin instrumentar el vehículo.

---

## 4. Resultados

| Indicador | Resultado |
|---|---|
| Precisión | Alta sobre el conjunto de evaluación |
| Latencia de detección | Menos de 1 segundo |
| Validación con lentes | La alerta se mantiene con los mismos tres indicadores |

La prueba con lentes es la más relevante de la demostración. Es la condición que rompe a
muchos detectores basados en seguimiento ocular, y es común entre conductores reales. Que
el sistema siga respondiendo en ese escenario dice más sobre su utilidad práctica que la
métrica de precisión agregada.

La demostración recorre tres escenarios: conductor alerta sin alarma, signos simulados de
somnolencia con alarma activada, y el mismo caso con lentes.

---

## 5. Limitaciones

- **Probado en demostración, no en carretera.** Los escenarios son simulados. La validación
  real exige recorridos nocturnos, vibración, cambios de luz y conductores que no saben
  que están siendo evaluados.
- **La precisión declarada es sobre el conjunto de evaluación.** No hay medición de falsos
  positivos en operación continua, que es lo que determina si un conductor termina
  desactivando el sistema.
- **La alerta avisa, no interviene.** Depende de que el conductor reaccione. No está
  integrado con el vehículo ni con una central de monitoreo de flota.
- **Condiciones de luz no caracterizadas.** La conducción nocturna, que es el escenario de
  mayor riesgo, es también el más exigente para una cámara convencional.

---

## 6. Material del proyecto

**[Carpeta con el video de demostración y las capturas de los tres escenarios](https://drive.google.com/drive/folders/1uiERyUe1m4T0LvR-3WR8qGOtvRlHc_g6?usp=drive_link)**

El video recorre la detección en funcionamiento: conductor alerta sin alarma, signos
simulados de somnolencia con la alarma activada, y el mismo caso con un conductor que usa
lentes.
