# Matriz de evaluacion de humanoides frente a NEO

Usar esta matriz para comparar robots humanoides, priorizar pilotos o preparar recomendaciones para Integrarobot.

## Escala

Puntuar de 0 a 5 solo cuando haya evidencia suficiente.

- 0: no demostrado o irrelevante.
- 1: claim comercial sin prueba robusta.
- 2: demo limitada o entorno muy controlado.
- 3: capacidad plausible con algunas pruebas reales.
- 4: capacidad demostrada repetidamente en condiciones relevantes.
- 5: capacidad madura, medible, soportada y desplegable.

Si falta evidencia, escribir "ND" en lugar de inventar puntuacion.

## Dimensiones

### 1. Caso de uso y encaje

- Tareas concretas que resuelve.
- Usuario objetivo: hogar, cuidado, hotel, fabrica, retail, logistica, educacion, investigacion.
- Dolor economico u operativo que justifica un humanoide.
- Motivo por el que no basta un robot no humanoide.

### 2. Autonomia real

- Tareas end-to-end sin ayuda humana.
- Necesidad de teleoperacion, copiloto, scripting o supervision.
- Recuperacion de errores.
- Generalizacion a objetos, casas, empresas y usuarios distintos.
- Evidencia: videos completos, benchmarks, despliegues, clientes, papers, logs.

### 3. Manipulacion

- Manos, DOF, payload, fuerza, precision, velocidad y sensibilidad.
- Manipulacion de objetos deformables, fragiles, sucios o no estructurados.
- Bimanualidad.
- Seguridad de contacto accidental.
- Cambio de herramientas o accesorios.

### 4. Movilidad

- Bipedismo, ruedas u otra base.
- Velocidad, estabilidad, escaleras, suelos irregulares, puertas, umbrales y espacios estrechos.
- Consumo energetico y autonomia.
- Riesgo de caida y recuperacion.

### 5. Seguridad

- Diseno fisico: baja inercia, compliance, pinch points, materiales, bordes, cuerpo blando.
- Ensayos, certificaciones o metricas publicadas.
- Seguridad cerca de ninos, mayores, mascotas, clientes o trabajadores.
- Parada de emergencia, limites de fuerza, supervision y fallbacks.

### 6. IA, datos y privacidad

- Percepcion visual, audio, memoria, LLM/VLM, planificacion y control.
- Procesamiento local vs cloud.
- Politicas de datos, retencion, entrenamiento y acceso humano.
- Riesgos de operadores remotos.
- Ciberseguridad y actualizaciones.

### 7. Producto y operacion

- Precio de compra, alquiler o suscripcion.
- Disponibilidad real, plazos y paises.
- Mantenimiento, repuestos, garantia y soporte.
- Tiempo de instalacion y entrenamiento.
- Integracion con sistemas del cliente.
- Escalabilidad de flota.

### 8. Proveedor

- Solvencia tecnica.
- Capital, fabricacion, cadena de suministro.
- Historial de entregas reales.
- Ecosistema de partners.
- Transparencia ante fallos y limites.

## Comparacion contra NEO

Para cada dimension, clasificar el robot como:

- **Supera a NEO**: evidencia clara en una dimension relevante.
- **Comparable a NEO**: prestaciones similares o trade-off razonable.
- **Por debajo de NEO**: menor madurez, peor seguridad, menos producto o menos evidencia.
- **No comparable**: otro segmento o falta informacion.

## Recomendacion final

Usar una de estas categorias:

- **Comprar**: solo si hay necesidad inmediata, soporte claro y riesgo aceptable.
- **Piloto acotado**: hay promesa, pero debe probarse en tarea limitada, metrica clara y entorno controlado.
- **Vigilar**: interesante, pero inmaduro, caro, incierto o sin disponibilidad.
- **Entrevistar proveedor**: faltan datos criticos que pueden cambiar la decision.
- **Descartar**: no hay encaje operativo, evidencia insuficiente o riesgo excesivo.

## Preguntas minimas para proveedor

- Que tareas hace hoy sin teleoperacion?
- Cual es la tasa de exito por tarea y en que condiciones?
- Que parte del sistema depende de cloud?
- Quien puede ver audio/video y bajo que permisos?
- Que ocurre ante perdida de conectividad?
- Cuales son precio, suscripcion, garantia, mantenimiento y SLA?
- Hay clientes reales usando el robot? En que volumen?
- Que certificaciones de seguridad tiene o esta buscando?
