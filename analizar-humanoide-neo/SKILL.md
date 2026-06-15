---
name: analizar-humanoide-neo
description: Analizar, comparar o decidir sobre robots humanoides comerciales usando NEO de 1X como referencia base. Usar cuando Codex deba evaluar humanoides para Integrarobot, comparar robots domesticos o de servicios, preparar due diligence, detectar riesgos de adopcion, estimar madurez tecnica/comercial, o convertir noticias, fichas tecnicas, demos, papers o propuestas de humanoides en una recomendacion operativa.
---

# Analizar humanoides con NEO como baseline

## Principio

Usar NEO de 1X como robot de referencia, no como ganador por defecto. NEO sirve para fijar el liston de comparacion en humanoides orientados a hogar y servicios: utilidad real, seguridad en contacto humano, autonomia, teleoperacion, coste total, datos, privacidad, mantenimiento y disponibilidad comercial.

No convertir claims comerciales en hechos. Separar siempre:

- **Hechos**: afirmaciones verificadas en fuentes primarias o documentacion tecnica.
- **Inferencias**: conclusiones razonadas a partir de varios hechos.
- **Hipotesis**: posibilidades plausibles sin evidencia suficiente.
- **Dudas operativas**: puntos que bloquearian una recomendacion seria.

## Flujo

1. Leer primero la fuente o pregunta del usuario.
2. Si se mencionan modelos, precios, capacidades, disponibilidad, seguridad, normativa o noticias recientes, verificar en internet con fuentes primarias cuando sea posible.
3. Leer `references/neo-baseline.md` para recordar el baseline NEO y sus limites.
4. Leer `references/evaluation-matrix.md` cuando haya que comparar, priorizar, recomendar o rechazar un humanoide.
5. Responder con juicio operativo para Integrarobot: que significa para clientes, pilotos, formacion, integracion, compras o estrategia.
6. Si el analisis aporta conocimiento reutilizable para la wiki de Integrarobot, proponer guardarlo o actualizar la wiki si el usuario lo pide.

## Salida recomendada

Usar esta estructura salvo que el usuario pida otra cosa:

1. **Resumen ejecutivo**: decision o lectura principal en 3-5 frases.
2. **Hechos verificados**: solo datos con fuente clara.
3. **Comparacion contra NEO**: donde supera, iguala o queda por debajo.
4. **Riesgos y limites**: autonomia real, seguridad, teleoperacion, privacidad, mantenimiento, coste, dependencia del proveedor.
5. **Inferencias**: consecuencias razonadas para Integrarobot.
6. **Preguntas criticas**: informacion que falta antes de recomendar compra, piloto o comunicacion publica.
7. **Recomendacion**: comprar, observar, entrevistar proveedor, pilotar con alcance limitado, descartar o incorporar a vigilancia.

## Criterios de rigor

- Penalizar demos sin tareas completas, sin entorno no controlado o sin metricas.
- Diferenciar autonomia fisica real de teleoperacion, asistencia humana o scripting.
- Tratar la manipulacion domestica como problema de alta dificultad: objetos deformables, variabilidad, seguridad, recuperacion de errores y confianza del usuario.
- No confundir forma humanoide con utilidad economica. Preguntar que tarea concreta justifica piernas, brazos, manos y presencia humana.
- Para clientes, priorizar escenarios donde el robot reduzca riesgo, escasez laboral, desplazamientos o tareas repetitivas, no donde solo sea llamativo.
- Identificar dependencia de datos del hogar/empresa, conectividad, servicios cloud y operadores remotos.

## Referencias

- `references/neo-baseline.md`: baseline NEO de 1X y advertencias de verificacion.
- `references/evaluation-matrix.md`: matriz para analizar humanoides frente a NEO.
