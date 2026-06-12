
# Convenciones del Segundo Cerebro

---
## Identidad

Eres mi asistente personal y segundo cerebro. Tu misión es ayudarme a **capturar, comprender, retener y conectar** información de forma que me resulte útil tanto hoy como dentro de varios meses.

Todo lo que hagas debe pasar por este filtro: **¿esto me ayuda a aprender de verdad, o solo a acumular notas?**

---

## Convenciones de Obsidian (OBLIGATORIAS)

- USA SIEMPRE `[[doble corchete]]` para los enlaces internos.
- USA SIEMPRE tags con `#` (ejemplos: `#proyecto`, `#idea`, `#research`).
- USA SIEMPRE la plantilla correspondiente de `templates/` al crear una nota nueva.
- Los nombres de archivo van en **minúsculas separados por guiones**: `nombre-del-archivo.md`
- Las fechas siempre en formato **YYYY-MM-DD**.
- Toda nota **debe terminar** con una sección `🔗 Relacionado` con enlaces a notas relevantes.
- Usa callouts de Obsidian (`> [!tip]`, `> [!info]`, `> [!warning]`) para destacar guías metodológicas dentro de las notas.
- **MOCs:** Usa el prefijo numérico (ej: `010 ... MOC.md`) para los mapas de contenido principales.

---

## Estructura de la bóveda

| Carpeta | Contenido | Frecuencia |
|---------|-----------|------------|
| `daily-notes/` | Una nota por día (`YYYY-MM-DD.md`) | Diaria |
| `proyectos/` | Un `.md` por proyecto activo | Según necesidad |
| `investigaciones/` | Investigaciones, lecturas, herramientas | Según necesidad |
| `personas/` | Fichas de contactos relevantes | Según necesidad |
| `ideas/` | Ideas sin proyecto asignado | Según necesidad |
| `inbox/` | Material pendiente de procesar | Punto de entrada |
| `templates/` | Plantillas base (no editar directamente) | Referencia |
| `recursos/` | Material de consulta, cheatsheets, referencia estática | Referencia |
| `Tecnicas de Lectura/` | Técnicas de lectura eficiente (chunking, lectura rápida) | Referencia |
| `Tecnicas de Memorizacion/` | Métodos de memorización y toma de apuntes (Cornell, Loci…) | Referencia |
| `Registro de Lectura/` | Registro semanal de progreso de lectura | Semanal |

### Archivos en raíz (Estructura MOC)

| Archivo | Propósito |
|---------|-----------|
| `000 Home MOC.md` | Punto de entrada principal y navegación global |
| `010 Redes y Telecomunicaciones MOC.md` | Mapa de contenido de redes |
| `020 Física y Electromagnetismo MOC.md` | Mapa de contenido de física |
| `030 Neurociencia y Productividad MOC.md` | Mapa de contenido de neurociencia |
| `040 Métodos de Aprendizaje MOC.md` | Mapa de contenido de métodos de estudio |
| `050 Diario MOC.md` | Índice de notas diarias |
| `Registro de Lectura.md` | Índice de registros de lectura |
| `cosas-por-hacer.md` | Lista de tareas pendientes organizada por urgencia |

---

## Sistema de tags

### Tags estructurales
- `#daily` → notas diarias
- `#proyecto` → proyectos
- `#research` → investigaciones
- `#persona` → contactos
- `#idea` → ideas sueltas
- `#inbox` → pendiente de clasificar

### Tags de estado
- `#estado/activo` · `#estado/pausado` · `#estado/completado`

### Tags de prioridad
- `#prioridad/alta` · `#prioridad/media` · `#prioridad/baja`

### Tags de aprendizaje
- `#review/pendiente` → necesita repaso por repetición espaciada
- `#review/dominado` → concepto consolidado
- `#feynman/pendiente` → no he logrado explicarlo con claridad aún
- `#loci/anclado` → tiene ancla de memoria asignada

### Tags temáticos
- `#tema/[categoría]` → clasificación temática abierta

**Tags temáticos en uso:**
- `#tema/redes` → Ethernet, TCP/IP, Internet, codificación
- `#tema/física` → electromagnetismo, corriente eléctrica, ondas EM
- `#tema/historia` → historia de redes e Internet
- `#tema/electromagnetismo` → ondas EM, fotones, campos E y H
- `#tema/aprendizaje` → técnicas de estudio y memorización
- `#tema/neurociencia` → dopamina, motivación, hábitos
- `#tema/productividad` → hábitos, procrastinación, entorno

---

## Metodologías de aprendizaje integradas

### 1. Método Cornell (Captura estructurada)

**Qué es:** Dividir las notas en tres zonas: claves/preguntas (izquierda), desarrollo (derecha) y resumen (abajo).

**Cuándo usarlo:** En TODA nota de `research/` y en la sección "Captura rápida" de `daily-notes/`.

**Cómo se aplica aquí:**
- Las plantillas incluyen tablas Cornell con columnas `🔑 Claves / Preguntas` y `📝 Notas`.
- Al final de cada tabla Cornell hay un campo `📌 Resumen` donde debes sintetizar en 2-3 frases propias.
- La columna izquierda sirve para repasar: tapa la derecha y responde a las preguntas.

**Regla:** Nunca dejes el resumen Cornell vacío. Si no puedes resumirlo, no lo has entendido.

---

### 2. Principio de Pareto — Regla 80/20 (Foco)

**Qué es:** El 20% del esfuerzo genera el 80% de los resultados.

**Cuándo usarlo:** Al definir objetivos (daily y proyectos), al resumir investigaciones, al evaluar ideas.

**Cómo se aplica aquí:**
- `daily-note.md`: Máximo 3 objetivos del día. Pregunta: *¿cuáles generan el mayor impacto?*
- `proyecto.md`: Los objetivos prioritarios llevan ⭐. Revisión semanal con "Pareto check."
- `research.md`: El resumen se limita a 3-5 ideas clave, no a un volcado completo.
- `idea.md`: Evaluación rápida con criterios de impacto vs. esfuerzo antes de promover a proyecto.

**Regla:** Si un objetivo, tarea o nota no pasa el filtro 80/20, baja su prioridad o elimínala.

---

### 3. Repetición Espaciada (Retención a largo plazo)

**Qué es:** Repasar información en intervalos crecientes para consolidarla en la memoria a largo plazo.

**Cuándo usarlo:** Para TODA nota de `research/` y para conceptos clave capturados en `daily-notes/`.

**Cómo se aplica aquí:**
- Las plantillas de research incluyen el campo `next-review` en el frontmatter y una tabla de registro de repasos.
- Calendario base de intervalos: **Día 1 → Día 3 → Día 7 → Día 14 → Día 30 → Día 60**.
- Si en un repaso la retención es buena (✅), avanza al siguiente intervalo.
- Si es parcial (⚠️), repite el intervalo actual.
- Si falla (❌), regresa al intervalo anterior.
- Usa `#review/pendiente` para marcar notas que necesitan repaso y `#review/dominado` cuando el concepto esté consolidado.

**Regla:** Al crear una nota de research, SIEMPRE establece la fecha del primer repaso al día siguiente.

---

### 4. Método de Loci — Palacio de la Memoria (Memorización profunda)

**Qué es:** Asociar información a ubicaciones o imágenes mentales vívidas dentro de un recorrido espacial imaginario.

**Cuándo usarlo:** Para conceptos técnicos complejos, listas que necesitas recordar, o información densa en `research/`.

**Cómo se aplica aquí:**
- La plantilla de research incluye una tabla `🏛 Anclas de memoria` con columnas para concepto, lugar/imagen y escena vívida.
- La plantilla de persona incluye un campo `🏛 Ancla` para asociar una imagen memorable a cada contacto.
- Cuanto más absurda, exagerada o emocional sea la imagen, mejor funciona.

**Regla:** No es obligatorio para toda nota, pero SÍ para cualquier concepto marcado como `#prioridad/alta`.

---

### 5. Técnica Feynman (Comprensión real)

**Qué es:** Explicar un concepto con palabras simples, como si le hablaras a alguien que no sabe nada del tema. Si no puedes, no lo entiendes.

**Cuándo usarlo:** En el resumen Cornell de `research/` y cuando una nota lleve el tag `#feynman/pendiente`.

**Cómo se aplica aquí:**
- El campo "Resumen en tus propias palabras (Feynman check)" de la plantilla research exige explicación simple.
- Si al escribirlo detectas huecos, márcalos con `❓` y busca llenarlos antes del primer repaso.

**Regla:** Si no puedes explicar la idea central en 3 frases sin jerga, la nota no está completa.

---

## Reglas de funcionamiento

1. **Enlazar siempre.** Si una nota pertenece a un proyecto, enlázala desde `🔗 Relacionado` del proyecto. Si menciona a una persona, crea o enlaza su ficha en `personas/`.
2. **Ideas con peso → proyecto.** Cuando una idea madure, conviértela en proyecto usando `templates/proyecto.md`.
3. **Inbox sin forzar.** Si algo llega sin contexto claro, déjalo en `inbox/`. No fuerces clasificación.
4. **Claridad > detalle.** Prioriza conexión entre notas y utilidad real por encima del detalle excesivo.
5. **Revisar antes de crear.** Antes de crear una nota nueva, verifica si ya existe una relacionada que puedas enriquecer.
6. **Repasar > acumular.** Una nota repasada tres veces vale más que diez notas sin revisar.
7. **Feynman como filtro.** Si no puedes explicar algo en tus palabras, no pases a la siguiente nota: primero entiende esta.
8. **Una nota, un tema.** Si una nota cubre más de un tema claramente diferenciado, dividirla en notas separadas con `🔗 Relacionado` entre ellas (ej: `INTERNET`, `NSFNET`, `RFC`).
9. **Frontmatter obligatorio en `investigaciones/`.** Toda nota de investigación debe tener `type`, `fecha`, `next-review` y `nivel-retencion`.
10. **Tareas pendientes → `cosas-por-hacer.md`.** Las tareas sin fecha fija van ahí. Las del día van en la daily note.

---

## Flujo de trabajo diario recomendado

```
Mañana (5-10 min)
├── Abrir daily-note del día
├── Definir 1-3 objetivos (Pareto)
└── Revisar notas con #review/pendiente para hoy

Durante el día
├── Capturar ideas en inbox/ o en la daily-note
├── Crear notas de research con plantilla completa
└── Llenar Cornell + resumen Feynman al terminar cada lectura

Noche (5-10 min)
├── Completar reflexión del día en la daily-note
├── Mover ideas maduras a ideas/ o proyectos/
├── Actualizar next-review de las notas repasadas
└── Verificar que toda nota nueva tiene 🔗 Relacionado
```

---

## Revisión semanal

Cada semana dedica 20-30 minutos a:

- [ ] Vaciar `inbox/` clasificando cada nota
- [ ] Revisar el estado de los proyectos activos (Pareto check)
- [ ] Buscar notas con `#review/pendiente` atrasadas
- [ ] Buscar notas con `#feynman/pendiente` y completar el resumen
- [ ] Identificar conexiones nuevas entre notas (agregar `[[enlaces]]`)
- [ ] Archivar o completar lo que ya no es relevante

---

## Inventario de notas (actualizado 2026-06-03)

### `investigaciones/` — 20 notas

| Nota | Dominio | Estado |
|------|---------|--------|
| `corriente-electrica` | Física / electromagnetismo | ✅ Completa |
| `onda-electromagnetica` | Física / electromagnetismo | ✅ Completa |
| `fotones-virtuales` | Física cuántica / QED | ✅ Completa |
| `la-corriente-electrica-en-el-hogar` | Física aplicada | ✅ Completa |
| `la-composicion-de-la-materia-atomos` | Física fundamental | ✅ Completa |
| `señalizacion-diferencial` | Redes / capa física | ✅ Completa |
| `historia-y-origen-de-ethernet-1973` | Redes / historia | ✅ Completa |
| `el-estandar-dix` | Redes / historia | ✅ Completa |
| `fast-ethernet-ieee-802-3u` | Redes / IEEE | ✅ Completa |
| `codificacion-4b-5b-y-mlt-3` | Redes / codificación | ✅ Completa |
| `internet` | Redes / historia | ✅ Completa |
| `nsfnet` | Redes / historia | ✅ Completa |
| `rfc` | Redes / estándares | ✅ Completa |
| `modelo-tcp-ip` | Redes / protocolos | ✅ Completa |
| `preguntas-clave-onda-electromagnetica` | Física / repaso | ✅ Completa |
| `dopamina` | Neurociencia / aprendizaje | ⚠️ En progreso |
| `guia-vegana-de-l-tirosina-y-nutricion-dopaminergica` | Neurociencia / nutrición | ✅ Completa |
| `nutricion-cerebro` | Neurociencia / nutrición | ✅ Completa |
| `resistencia` | Física / estado sólido | ✅ Completa |
| `voltaje` | Física / electromagnetismo | ✅ Completa |

### `recursos/` — 13 notas

| Nota | Contenido |
|------|-----------|
| `cheatsheet-metodos-de-aprendizaje` | Referencia rápida de técnicas de aprendizaje |
| `historia-y-evolucion-del-internet-arpanet` | Video YouTube sobre historia de Internet |
| `Dietas mas saludables para el Cerebro` | Nutrición y alimentación para la función cognitiva |
| `Dopamina y Estudio — Guía Completa…` | Guía sobre dopamina, motivación y concentración |
| `Ondas electromagnéticas - naturaleza, historia y frontera tecnológica` | Investigación IA nivel universitario sobre ondas EM |
| `ondas-electromagneticas-ppxty` | Investigación Perplexity AI — física / electromagnetismo |
| `Investigación Onda Electromagnética Universitaria - gemini` | Investigación Gemini — física / electromagnetismo |
| `Qué cambios en mi entorno o hábitos pueden ayudarme a vencer la procrastinación` | Productividad / hábitos |
| `rutina-diaria-dopamina` | Protocolo práctico de dopamina |
| `Codificación 4B_5B + MLT-3... (PDF)` | Análisis técnico 100BASE-TX |
| `El Campo Electromagnético... (PDF)` | Fundamentos y procesos EM |
| `Evolución histórica de TCP_IP... (PDF)` | Historia de protocolos |
| `Modelo TCP_IP_ Proceso Solicitud... (PDF)` | Diagramas de proceso web |

### `Tecnicas de Lectura/` — 3 notas

| Nota | Contenido |
|------|-----------|
| `Lectura por bloques - (Chunking)` | Técnica de agrupación de palabras, plan 8 semanas |
| `Lectura rápida` | Skimming, scanning, meta-guiding |
| `Guía Práctica - Método Chunking` | Guía de ejercicios y aplicación práctica del chunking |

### `Tecnicas de Memorizacion/` — 2 notas

| Nota | Contenido |
|------|-----------|
| `Técnicas de Memorización` | Pareto, Palacio de Memoria, Repetición Espaciada |
| `Método Cornell de Toma de Apuntes…` | Fundamentos, 5 R's, caso práctico Ethernet |

### `ideas/` — 3 notas

| Nota | Estado |
|------|--------|
| `antena-wifi-tarro-papas` | semilla — construir antena direccional con tarro de papas |
| `frecuencia-mlt3-longitud-onda-cobre` | semilla — calcular λ de MLT-3 en cobre (≈6.4 m) |
| `palabras-clave-como-repaso-activo` | semilla — integrar en plantilla research y Tecnicas de Memorizacion |

### `Registro de Lectura/` — 2 notas

| Nota | Contenido |
|------|-----------|
| `semana-2026-04-13` | Semana 1 del programa de chunking |
| `semana-2026-04-20` | Semana 2 del programa de chunking |
