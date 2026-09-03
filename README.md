# Portafolio — Andrés Mendoza

Sitios, paneles de gestión y automatizaciones para negocios. HTML/CSS/JS estático, sin build ni dependencias.

**En vivo:** https://andresmendoza30.github.io/PORTAFOLIO/

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | Portafolio principal. Concepto "sala de proyección": cada proyecto se muestra en una pantalla con vista previa en vivo (iframe) que se recorre sola al pasar el cursor |
| `copal.html` | Proyecto 01 — mezcalería y cocina, sitio de una página con reservaciones |
| `consultorio.html` | Proyecto 03 — consultorio dental con agenda en línea funcional |
| `consultorio-panel.html` | Proyecto 03b — panel interno del consultorio (agenda, ocupación, cobros) |
| `inventario.html` | Proyecto 04 — panel de inventario para ferretería (stock, alertas, resurtido) |
| `boutique.html` | Proyecto 05 — tienda en línea con filtros, carrito y pedido por WhatsApp |
| `hotel.html` | Proyecto 02 — hotel boutique con buscador de disponibilidad y comparativa contra plataformas |
| `comedor.html` | Proyecto 06 — comida corrida con menú por día de la semana y pedido a domicilio |
| `404.html` | Página de error con la identidad del sitio |
| `favicon.svg` | Ícono de pestaña (monograma AM) |
| `robots.txt` / `sitemap.xml` | SEO básico |

## Configuración

- Formulario de contacto: Formspree `xoeqwndw`
- WhatsApp: `529514418403`
- Correo: `andresmendoza8403@gmail.com`

## Cómo agregar un proyecto nuevo

1. Crea el archivo del proyecto en la raíz (ej. `gimnasio.html`).
2. En `index.html`, dentro de `<div class="reel">`, duplica un bloque `<article class="film rise">`.
3. Cambia el `src` del `<iframe>`, el `href` de los botones, el número, el título y la ficha de créditos.
4. Agrega la URL a `sitemap.xml` y súmala al conteo del hero ("4 proyectos en cartelera").

## Convención de honestidad

Los proyectos sin cliente real llevan la etiqueta `PROYECTO CONCEPTUAL` y nunca muestran métricas inventadas.
Cuando un caso sea de un cliente real, se quita la etiqueta y ahí sí se puede poner el resultado medido.

## Publicar cambios

```bash
git add -A
git commit -m "Actualiza portafolio"
git push
```

GitHub Pages republica solo en un par de minutos (rama `main`, carpeta raíz).
