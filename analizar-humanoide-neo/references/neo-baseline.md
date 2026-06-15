# Baseline NEO de 1X

Fecha de captura inicial: 2026-06-15.
Fuente primaria inicial: https://www.1x.tech/neo

## Uso correcto

Usar esta pagina como baseline operativo, no como ficha congelada. Antes de afirmar datos actuales de NEO, abrir la fuente primaria de 1X u otra fuente primaria relevante. Si no se puede verificar, marcar como "segun captura inicial de 2026-06-15" o "pendiente de verificacion".

## Posicionamiento declarado

NEO se presenta como un robot humanoide domestico: "Home Robot". Su propuesta declarada combina tareas del hogar, compania, inteligencia conversacional, app movil, control por voz, teleoperacion/Expert Mode y aprendizaje progresivo.

## Claims funcionales de referencia

Segun la pagina oficial consultada el 2026-06-15, 1X declara:

- Tareas domesticas programables y asistencia cotidiana.
- Autonomia por defecto, con "Expert Mode" para tareas que el robot no sabe hacer.
- Expertos humanos de 1X que pueden guiar remotamente al robot en horarios programados.
- Control remoto desde app movil y dispositivo VR.
- Auto-carga.
- Interfaz de voz y app movil.
- Memoria, inteligencia visual, audio y LLM integrado.
- Modelo Redwood AI para aprender y repetir tareas.

## Baseline tecnico declarado

Segun la pagina oficial consultada el 2026-06-15:

- Altura: 5'6".
- Peso: 66 lb.
- Capacidad declarada de lift: 154 lb.
- Carry: 55 lb.
- Arm payload: 18 lb.
- DOF: manos 22x2, brazos 7x2, cuello 3, columna 2, piernas 6x2.
- Velocidad de marcha: 1.4 m/s.
- Velocidad maxima de carrera: 6.2 m/s.
- Bateria: 842 Wh.
- Runtime: 4 h.
- Carga rapida: 6 min por hora de autonomia.
- Cuerpo blando con lattice polymer.
- Joints sin pinchpoints.
- HIC declarado: <250.
- Actuacion: low inertia tendon drives.
- Manos IP68; cuerpo IP44.
- Chipset: 1X NEO Cortex, Nvidia Jetson Thor.
- AI compute: hasta 2070 FP4 TFLOPS.
- Camara: dual 8.85 MP 90 Hz stereo fisheye.
- Comunicacion: Wi-Fi, Bluetooth, 5G.

## Lectura operativa

NEO es un baseline exigente por tres razones:

- Integra robot fisico, IA, interfaz domestica, teleoperacion y experiencia de usuario en una narrativa coherente.
- Pone la seguridad fisica en el centro: cuerpo blando, actuacion por tendones, baja inercia, joints cubiertos.
- Reconoce implicitamente que la autonomia completa todavia no basta: incorpora Expert Mode y aprendizaje asistido.

## Riesgos que NEO hace visibles

- La teleoperacion puede ser valor operativo, pero tambien evidencia de autonomia incompleta.
- La privacidad es critica si hay camaras, microfonos, memoria y operadores remotos en viviendas.
- Las tareas domesticas reales son heterogeneas; los claims deben contrastarse con demos completas, tasas de exito, recuperacion de errores y condiciones del entorno.
- El coste total no es solo precio: incluye suscripcion, mantenimiento, reemplazos, conectividad, soporte, datos y dependencia del proveedor.
- La disponibilidad comercial puede no equivaler a madurez de producto.

## Preguntas base frente a NEO

- Que tareas realiza de extremo a extremo sin operador humano?
- Que tareas requieren teleoperacion o supervision?
- Que ocurre cuando falla una tarea?
- Que datos captura, donde se procesan y quien puede acceder?
- Cual es el coste total durante 3 anos?
- Que mantenimiento requiere y quien lo ejecuta?
- Que certificaciones o ensayos de seguridad tiene?
- En que entornos esta probado fuera de demos controladas?
