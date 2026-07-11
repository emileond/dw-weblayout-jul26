# Design Tokens & System Configuration

This document contains the consolidated design tokens extracted from the system specification sheets, structured for seamless integration with Google Stitch / design token pipelines.

---

## 1. Typography

* **Font Family:** `Inter` (regular, medium, semibold)
* **Base Size:** `16px`
* **Scale Multiplier:** `1.125`

### Typographic Scale

| Token / Element | Rem Value | Pixel Value | Font Weight |
| :--- | :--- | :--- | :--- |
| `h1` | `1.8rem` | `28.8px` | Semibold |
| `h2` | `1.6rem` | `25.62px` | Semibold |
| `h3` | `1.42rem` | `22.78px` | Semibold |
| `h4` | `1.27rem` | `18.0px` | Medium |
| `body1` | `1.0rem` | `16.0px` | Regular |
| `body2` | `0.88rem` | `14.08px` | Regular |
| `caption` | `0.75rem` | `12.0px` | Regular |

---

## 2. Color System

### Semantic Roles & Component Mapping

#### Base Roles
* **Primary:** Azul 500 (`#006FEE`)
* **Secondary:** Morado 500 (`#7828C8`)
* **Default:** Gris 100 (`#F4F4F5`)
* **Success:** Verde 500 (`#17C964`)
* **Warning:** Amarillo 500 (`#F5A524`)
* **Danger:** Rojo 500 (Mapped to 500 block token context)

#### Layout Mapping
* **Card Background:** White (`#FFFFFF`)
* **Layout Background:** Gris 50 (`#FAFAFA`)
* **Border:** Gris 300 (`#D4D4D8`)
* **Input Background:** Gris 200 (`#E4E4E7`)

#### Text Mapping
* **Text Primary:** Gris 900 (`#18181B`)
* **Text Secondary:** Gris 700 (`#3F3F46`)
* **Text Muted:** Gris 500 (`#71717A`)

### Full Color Palettes

| Scale | Azul | Morado | Verde | Rojo | Amarillo | Gris |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **50** | `#E6F1FE` | `#F2EAFA` | `#E8FAF0` | `#FEE7EF` | `#FEFCE8` | `#FAFAFA` |
| **100** | `#CCE3FD` | `#E4D4F4` | `#D1F4E0` | `#FDD0DF` | `#FDEDD3` | `#F4F4F5` |
| **200** | `#99C7FB` | `#C9A9E9` | `#A2E9C1` | `#FAA0BF` | `#FBDBA7` | `#E4E4E7` |
| **300** | `#66AAF9` | `#AE7EDE` | `#74DFA2` | `#F871A0` | `#F9C97C` | `#D4D4D8` |
| **400** | `#338EF7` | `#9353D3` | `#45D483` | `#F54180` | `#F7B750` | `#A1A1AA` |
| **500** | `#006FEE` | `#7828C8` | `#17C964` | *[Base Color]* | `#F5A524` | `#71717A` |
| **600** | `#005BC4` | `#6020A0` | `#12A150` | `#C20E4D` | `#C4841D` | `#52525B` |
| **700** | `#004493` | `#481878` | `#0E793C` | `#920B3A` | `#936316` | `#3F3F46` |
| **800** | `#002E62` | `#301050` | `#095028` | `#610726` | `#62420E` | `#27272A` |
| **900** | `#001731` | `#180828` | `#052814` | `#310413` | `#312107` | `#18181B` |

---

## 3. Spacing & Layout Constraints

### Spacing Scale
The system uses a highly structured base-8 pixel layout grid.

* **1:** `4px`
* **2 (Base):** `8px`
* **3:** `16px`
* **4:** `24px`
* **5:** `32px`
* **6:** `48px`
* **7:** `64px`

### Breakpoints

* **sm:** `600px`
* **md:** `900px`
* **lg:** `1200px`
* **xl:** `1536px`
