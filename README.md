# Albor Solar — Landing page

Landing para anuncios de Meta (mobile first). Es un único archivo `index.html`, sin dependencias.

Estructura: Inicio → Calculadora de ahorro → Cómo trabajamos → Packs (sin precios) → Garantías → Preguntas frecuentes → Contacto por WhatsApp / llamada.

## Antes de publicar, editá:
1. **`CONFIG` (al final de `index.html`)**: número de WhatsApp, teléfono, email, zonas y supuestos de la calculadora.
2. **`ALBOR_PIXEL_ID`** (en el `<head>`): ID de tu píxel de Meta. Eventos: `PageView`, `Lead` (clic en cualquier botón de WhatsApp) y `Contact` (clic en llamar).
3. **Imagen para compartir** (`og-image.jpg`, 1200x630): la que se ve al pegar el link en WhatsApp/Facebook.
4. **Equipos de cada pack.**

## Publicar
Funciona en cualquier hosting estático (Netlify, Vercel, GitHub Pages, Cloudflare Pages): subí `index.html`.
