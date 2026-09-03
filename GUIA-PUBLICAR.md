# Guía para publicar — pasos exactos

Tiempo estimado: 10-15 minutos.

---

## YA ESTÁ CONFIGURADO

- Formspree: `xoeqwndw` ✅
- WhatsApp: `529514418403` (con mensaje prellenado) ✅
- Usuario GitHub: `AndresMendoza30` ✅

No hay nada que reemplazar. Directo al paso de subir.

---

## PASO 1 — Subir a GitHub

**Opción fácil (por la web, sin comandos):**

1. Entra a **github.com** → botón verde **New** (repositorio nuevo)
2. Nombre: `portafolio`
3. Márcalo como **Public**
4. NO marques "Add a README" (ya tenemos uno)
5. Dale **Create repository**
6. En la pantalla que sigue, dale a **uploading an existing file**
7. Arrastra TODOS los archivos de esta carpeta
8. Abajo dale a **Commit changes**

**Opción por terminal** (si prefieres):
```bash
cd carpeta-del-portafolio
git init
git add .
git commit -m "Portafolio v1"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/portafolio.git
git push -u origin main
```

---

## PASO 2 — Activar GitHub Pages

1. En tu repo, ve a **Settings** (arriba a la derecha)
2. En el menú izquierdo, busca **Pages**
3. En "Source", elige **Deploy from a branch**
4. Branch: **main**, carpeta: **/ (root)**
5. Dale **Save**
6. Espera 1-2 minutos y refresca — te va a aparecer tu link:
   `https://TU_USUARIO.github.io/portafolio/`

---

## PASO 3 — Pruébalo antes de mandarlo a nadie

Checklist rápido:

- [ ] El formulario manda correo de verdad (mándate una prueba)
- [ ] El botón de WhatsApp abre tu chat con el número correcto
- [ ] Los dos casos de estudio abren bien
- [ ] Se ve bien en celular (no solo en compu)
- [ ] El ícono aparece en la pestaña del navegador

---

## Después: dominio propio (opcional, cuando ya tengas clientes)

`tuusuario.github.io/portafolio` funciona perfecto para empezar. Cuando quieras algo tipo `andresmendoza.mx`:

1. Compra el dominio (Namecheap, GoDaddy, o el que uses)
2. En Settings → Pages → Custom domain, pon tu dominio
3. En tu proveedor de dominio, apunta los DNS a GitHub Pages

No lo hagas todavía — primero consigue el primer cliente, luego inviertes.
