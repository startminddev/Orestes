# Sitio web de Orestes Arnaldo (Manitas)

Una página sencilla y moderna para promocionar los servicios de manitas de Orestes Arnaldo. Incluye nombre, teléfono, foto y lista de servicios.

## Cómo usar

1. Abre el archivo `index.html` en tu navegador (doble clic) o ábrelo en VS Code y usa una extensión de server local (opcional).
2. Personaliza el contenido según se indica abajo.

## Personalización rápida

Edita el archivo `index.html` y revisa estos puntos:

- Teléfono:
  - Ya está configurado como `+34 685070242` y los enlaces usan `tel:+34685070242` y `https://wa.me/34685070242`.
  - Si cambia el número, actualiza ambos formatos (visible con espacios y enlaces sin espacios).
- Foto:
  - La página ya usa `assets/orestes.jpeg` en la imagen principal, en `og:image` y en el bloque JSON‑LD.
  - Para cambiar la foto, sustituye el archivo `assets/orestes.jpeg` por otro con el mismo nombre, o actualiza esas rutas si prefieres otro nombre.
- Servicios:
  - Modifica la lista bajo el título "Servicios" (`<ul class="service-list">`).
- (Opcional) Localidad:
  - En el bloque JSON-LD, puedes rellenar `areaServed.name` con la ciudad o zona donde trabaja Orestes.

## Estructura

- `index.html`: contenido principal (nombre, teléfono, foto, servicios y llamadas a la acción).
- `styles.css`: estilos responsivos y accesibles.
- `assets/orestes.jpeg`: foto actual mostrada en la web y usada para SEO.
- `assets/orestes-placeholder.svg`: imagen temporal (ya no se usa en la página, puedes eliminarla si no la necesitas).

## Consejos

- WhatsApp: ahora es el canal preferente de contacto. Los enlaces usan `https://wa.me/34685070242` (sin espacios ni `+`).
- Llamadas: los botones de llamada se han retirado a petición. Si quieres volver a activarlos, cambia los enlaces por `tel:+34...` en `index.html`.
- Accesibilidad: mantén el texto alternativo de la imagen con el nombre de Orestes.

## Servir localmente (opcional)

Si prefieres un servidor local y tienes Python instalado, en PowerShell puedes hacerlo desde la carpeta del proyecto:

```powershell
# Inicia un servidor en http://localhost:8000
python -m http.server 8000
```

Luego abre `http://localhost:8000` en tu navegador.

## Licencia

Este sitio es tuyo. Puedes modificarlo y distribuirlo libremente.
