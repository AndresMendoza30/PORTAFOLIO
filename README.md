# Portafolio — Andrés Mendoza

Sitio personal: diseño y desarrollo digital. HTML/CSS/JS estático, sin dependencias ni build.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | Portafolio principal (hero, servicios, casos, proceso, sobre, contacto) |
| `copal.html` | Caso de estudio 01 — mezcalería/restaurante |
| `consultorio.html` | Caso de estudio 02 — consultorio dental |
| `404.html` | Página de error con la identidad del sitio |
| `favicon.svg` | Ícono de pestaña (monograma AM) |
| `robots.txt` / `sitemap.xml` | SEO básico |

## Configuración

- Formulario: Formspree `xoeqwndw`
- WhatsApp: `529514418403`
- URL: https://AndresMendoza30.github.io/portafolio/

## Cómo agregar un caso de estudio nuevo

1. Crea el archivo (ej. `tienda.html`) en la raíz
2. En `index.html`, busca `<section class="casos"` y duplica un bloque `<div class="case-row reveal">`
3. Cambia el `href` y el `src` del iframe al archivo nuevo
4. Actualiza el texto de problema / solución / resultado esperado
5. Agrega la URL a `sitemap.xml`

## Convención

- Los proyectos conceptuales SIEMPRE llevan la etiqueta `PROYECTO CONCEPTUAL` y dicen "Resultado esperado", nunca métricas inventadas.
- Cuando un caso sea de un cliente real, se quita la etiqueta y se puede poner el resultado real.
