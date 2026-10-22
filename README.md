# HistoPráctica — video de introducción (HyperFrames)

1920×1080 · 30 fps · 27 s · 16:9 · en español · pensado para verse sin sonido (Reddit y redes).

## Estructura
- `index.html` — composición raíz (7 escenas + fondo continuo).
- `compositions/` — `hook`, `logo`, `quiz`, `tissues`, `progress`, `devices`, `cta` y `bg`.
- `assets/` — GSAP 3.15 y fuentes Poppins.

| Escena | Segundos |
| --- | --- |
| hook (¿Reconoces este tejido?) | 0–4.5 |
| logo (microscopio + wordmark) | 4.5–8.5 |
| quiz (cómo funciona) | 8.5–12.5 |
| tissues (8 tejidos + piel) | 12.5–16 |
| progress (errores, racha, ranking) | 16–19.5 |
| devices (cualquier dispositivo, sin conexión) | 19.5–22.5 |
| cta (histopractica.online) | 22.5–27 |

## Pasos
1. `npx skills add heygen-com/hyperframes`
2. `npx hyperframes check --json` (corrige lo que marque)
3. `npx hyperframes preview`, luego `npx hyperframes render`

## Pendientes conocidos
- **Tipografía:** la marca usa Nunito; aquí va Poppins como respaldo. Pon los archivos de Nunito en `assets/fonts/`, añade su `@font-face` y antepón `"Nunito"` en la pila de fuentes de cada escena (ya está primera en la pila).
- **Imagen de tejido:** es una ilustración H&E generada en SVG. Sustitúyela por una captura real de tu banco.
- **Sin audio.** Añade música como `<audio id="...">` en `index.html` si la quieres.
