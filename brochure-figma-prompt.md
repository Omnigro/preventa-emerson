# Brochure Canopy Master PRO ES — Prompt de contenido para Figma

## Especificaciones del documento

- **Formato:** 2 páginas independientes
- **Dimensiones por página:** 1080 × 1620 px (relación 2:3, orientación vertical)
- **Resolución:** 96 dpi (digital, no imprimir)
- **Uso:** Compartir por WhatsApp — visualización en mobile

---

## Sistema de diseño

### Colores
| Variable | Hex | Uso |
|---|---|---|
| `--dark` | `#252617` | Fondos oscuros, texto principal |
| `--dark2` | `#1d1e12` | Fondos oscuros secundarios |
| `--cream` | `#f1f1ed` | Fondo general, secciones claras |
| `--white` | `#FFFFFF` | Fondos de cards, secciones blancas |
| `--olive` | `#74764a` | Acentos, CTAs, eyebrows, íconos |
| `--beige` | `#d4d3bd` | Bordes, texto secundario |
| `--whatsapp` | `#25D366` | Botón CTA final |

### Tipografía
- **Títulos:** Figtree (pesos: 300 italic, 800, 900)
- **Cuerpo y labels:** Inter (pesos: 300, 400, 500, 600)

### Border radius
- Cards principales: 20px
- Cards pequeñas / model cards: 12px
- Chips, items de grilla: 10px
- Pills / badges: 100px (full)
- Botones: 100px (full)

---

## PÁGINA 1

### Bloque 1 — Header
**Fondo:** `--dark`
**Contenido:**
- Izquierda: Logo Omnigro (archivo: `logo-blanco-transparente.png`)
- Derecha: Pill tag con borde `--olive` → texto: `FABRICACIÓN ARGENTINA`

---

### Bloque 2 — Hero
**Fondo:** `--dark`
**Contenido:**
- Imagen del producto (archivo: `producto-hero-transp.png`) — ancho completo, border-radius 12px, fondo `#1d1e12`
- Eyebrow (Inter 600, 8px, uppercase, letter-spacing 0.22em, color `--olive`):
  `CANOPY MASTER PRO ES SERIES`
- Título H1 (Figtree 900, ~42px, letter-spacing -0.02em, color `--white`, line-height 1.05):
  `El LED más eficiente` + salto de línea + `del país.` ← esta línea en Figtree 300 italic, color `--olive`
- Subtítulo (Inter 300, 14px, color beige 60% opacidad, line-height 1.5):
  `Espectro Emerson 660 nm + 730 nm para la máxima tasa fotosintética por julio consumido.`
- Pills (3 unidades, borde `--olive` 50% opacidad, texto `--beige`, Inter 500 8px uppercase):
  - `3.2 µmol/J`
  - `CICLO COMPLETO`
  - `DISIPACIÓN PASIVA`

---

### Bloque 3 — ¿Por qué es el más eficiente?
**Fondo:** `--cream`
**Eyebrow:** `¿POR QUÉ ES EL MÁS EFICIENTE?`
**Grilla 2×3** (cards con borde `--beige`, fondo `--white`, border-radius 10px):
- Dot acento `--olive` + texto Inter 400 10px por cada ítem:
  1. LEDs seleccionados
  2. Diseño eléctrico de placa
  3. Driver eficiente
  4. Gestión térmica
  5. Espectro útil
  6. Distribución uniforme

**Cuerpo** (Inter 300, 11px, color dark 65%):
`La eficiencia real no depende de un solo componente — se construye en el sistema completo. Canopy Master PRO fue diseñada desde ese criterio.`

**Nota global** (card con fondo olive 8%, borde olive 25%, border-radius 8px, ícono globo):
`3.2 µmol/J es un promedio altísimo a nivel global. Las marcas más top del mundo alcanzan como máximo 3.5 µmol/J en sus líneas de mayor eficiencia.`

---

### Bloque 4 — Espectro y Efecto Emerson
**Fondo:** `--cream`
**Eyebrow:** `ESPECTRO Y EFECTO EMERSON`

**Barra espectral** (gradiente horizontal):
`#3344dd → #4499ff → #44dd99 → #99dd44 → #ddcc00 → #ee6600 → #cc1100 → #770022`
Con dos marcadores verticales sobre la barra (color `--olive`):
- `660 nm` (posición ~78% del ancho)
- `730 nm` (posición ~88% del ancho)

**Cuerpo:**
`El 660 nm activa el fotosistema II y el 730 nm activa el fotosistema I. Actuando en simultáneo logran mayor tasa fotosintética que cada longitud de onda por separado — el **Efecto Emerson**: más producción, mismo consumo.`

**Callout ciclo único** (card con fondo olive 5%, borde olive 30%, border-radius 8px):
- Label (Inter 600, 8px, uppercase, color `--olive`): `¿EQUIPOS PARA UN ÚNICO CICLO?`
- Texto (Inter 300, 10px): `Si usás los equipos solo para vegetación o floración podemos optimizar el espectro para ese ciclo específico. Consultanos.`

---

### Bloque 5 — Especificaciones por modelo

**Fondo:** `--cream`
**Eyebrow:** `ESPECIFICACIONES POR MODELO`

**Nota compartida** (visible una sola vez, sobre las cards):
Figtree 700, 11px, color `--olive`:
`Todos los modelos: 3.2 µmol/J de eficiencia · 50.000 hs de vida útil`

**5 model cards** (fondo `--white`, borde `--beige`, border-radius 12px):
Cada card contiene:
- Header: nombre del modelo (Figtree 800, 13px, color `--dark`) + wattaje (Inter 600, 9px, color `--olive`, derecha)
- Grilla de métricas (3 columnas × 2 filas = 6 celdas visibles, aunque son 5 métricas — la última celda vacía o con driver):
  - Label (Inter 500, 8px, uppercase, color dark 40%)
  - Valor (Figtree 700, 11px, color `--dark`)

| Modelo | Consumo Real | Cobertura | PPFD | Tamaño | Peso |
|---|---|---|---|---|---|
| **CM ES PRO 200** | 200 W | 0.8 × 0.8 m | — µmol/m²/s | 80 × 60 cm | 8 kg |
| **CM ES PRO 300** | 300 W | 1 × 1 m | — µmol/m²/s | 80 × 60 cm | 8 kg |
| **CM ES PRO 400** | 400 W | 1.2 × 1.2 m | — µmol/m²/s | 90 × 90 cm | 10 kg |
| **CM ES PRO 600** | 600 W | 1.2 × 1.2 m | — µmol/m²/s | 110 × 110 cm | 11 kg |
| **CM ES PRO 800** | 800 W | 1.5 × 1.5 m | — µmol/m²/s | 110 × 110 cm | 11 kg |

> Los valores de PPFD se completan cuando esté disponible el mapa PAR.

**Mapa PAR** (al pie de las cards):
- Eyebrow: `MAPA PAR — CM ES PRO 400`
- Placeholder imagen: mapa de calor PPFD (µmol/m²/s) — grilla de valores por posición sobre el canopy.
- Nota (Inter 300, 10px): `Distribución real de fotones sobre el canopy. Uniformidad certificada.`

---

## PÁGINA 2

### Bloque 6 — Beneficios complementarios + Control y regulación
**Fondo:** `--white` (sección unificada)
**Eyebrow:** `BENEFICIOS COMPLEMENTARIOS`

**Grilla 3 íconos** (cards con borde `--beige`, border-radius 10px, ícono `--olive` 20px):
1. 🌡 `Gestión térmica pasiva — temperatura de operación estable`
2. ⚙️ `Drivers Meanwell — componentes de grado industrial`
3. 🔧 `Placa LED diseñada y fabricada en Argentina`

**Divisor sutil** (1px, color dark 6%)

**Control y regulación** (mismo fondo, sin eyebrow separado):
- Imagen/diagrama: esquema de conexión Daisy Chain RJ45 (placeholder)
- Título (Figtree 800, 13px): `Control y regulación`
- Cuerpo (Inter 300, 10px):
  `Regulación grupal por Daisy Chain RJ45. Ajustá potencia y PPFD según cada fase del cultivo. Compatible con los sistemas de control líderes de la industria.`

---

### Bloque 7 — Contexto competitivo
**Fondo:** `--cream`
**Eyebrow:** `CONTEXTO COMPETITIVO`

**Tabla** (4 columnas: Equipo / µmol/J / Emerson / Garantía):

| Equipo | µmol/J | Emerson | Garantía |
|---|---|---|---|
| **Canopy Master PRO** ← fila destacada (fondo olive 7%, texto bold) | 3.2 | ● (dot olive) | 2 años |
| Nacionales top | 2.7–2.9 | ○ (dot beige) | — |
| Importados premium | 2.5–2.8 | ○ (dot beige) | — |
| Importados genéricos | 2.0–2.4 | ○ (dot beige) | — |

**Nota** (Inter 300, 10px):
`Único con espectro Emerson completo ≥3.2 µmol/J ensamblado en Argentina.`

---

### Bloque 8 — Post-venta y garantía
**Fondo:** `--dark`
**Eyebrow:** `POST-VENTA Y GARANTÍA` (color `--olive`)

**Card garantía** (borde olive 40%, border-radius 12px):
- Badge circular (borde 2px `--olive`, 52×52px):
  - Número `2` (Figtree 900, 16px, `--white`)
  - Texto `AÑOS` (Inter 600, 7px, uppercase, `--olive`)
- Título (Figtree 800, 13px, `--white`): `Garantía 2 años`
- Cuerpo (Inter 300, 10px, beige 60%): `Cada equipo Omnigro está respaldado por garantía completa sobre componentes y funcionamiento.`

**Card soporte** (borde dark 10%, border-radius 10px):
- Ícono auricular (color `--olive`)
- Texto (Inter 300, 10px, beige 60%):
  `**Asistencia técnica directa** con el equipo Omnigro — cultivadores que conocen el producto y el cultivo.`

---

### Bloque 9 — Cierre y CTA
**Fondo:** `--cream`
**Eyebrow:** `CONSULTÁ POR TU SALA`

**Layout horizontal:**
- Izquierda: QR (64×64px, fondo `--white`, borde `--beige`) → link a WhatsApp / landing
- Derecha:
  - Título (Figtree 800, 14px): `¿Cuántos equipos necesitás?`
  - Subtítulo (Inter 300, 10px, dark 50%): `Te asesoramos sin compromiso según el tamaño de tu sala.`
  - Botón WhatsApp (fondo `#25D366`, texto `--white`, Inter 700, 9px, uppercase, border-radius 100px, ícono WhatsApp): `ESCRIBINOS POR WHATSAPP`

---

## Assets disponibles
| Archivo | Uso |
|---|---|
| `logo-blanco-transparente.png` | Header página 1 |
| `logo-negro-transparente.png` | Alternativa sobre fondo claro |
| `producto-hero-transp.png` | Imagen hero página 1 |
| `producto-cuadrado.png` | Alternativa cuadrada |
| `logo-o-blanco.svg` | Isotipo blanco |
| `logo-o-negro.svg` | Isotipo negro |

## Pendientes para completar el brochure
- [ ] Valores de PPFD por modelo (disponibles con el mapa PAR)
- [ ] Imagen mapa de calor PAR (CM ES PRO 400 como referencia)
- [ ] QR final (generar con link a WhatsApp o landing)
- [ ] Diagrama Daisy Chain RJ45 (ilustración o foto)
