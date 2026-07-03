# Portafolio — Sergio Luján García

Sitio de una sola página construido con HTML, CSS y JS puro (sin frameworks), listo para GitHub Pages.

## Estructura

```
portafolio/
├── index.html
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   └── img/          ← coloca aquí tu foto como profile.jpg
└── README.md
```

## Publicar en GitHub Pages

1. Copia estos archivos a la raíz de tu repositorio (o a una carpeta `docs/` si prefieres esa configuración).
2. Agrega tu foto en `assets/img/profile.jpg` (formato cuadrado se ve mejor).
3. En GitHub: **Settings → Pages → Source**, selecciona la rama (`main`) y la carpeta (`/root` o `/docs`).
4. Tu sitio quedará en `https://<tu-usuario>.github.io/<tu-repo>/`.

## Qué personalizar

- **Sección IA (`#ia` en index.html):** actualízala conforme avances en cursos, certificaciones o proyectos de inteligencia artificial. Ahora mismo tiene contenido placeholder honesto ("En curso" / "Explorando") — cámbialo por logros concretos según vayas avanzando.
- **Foto:** `assets/img/profile.jpg`.
- **Colores/tipografía:** variables al inicio de `assets/css/style.css` (bloque `:root`).
- **Contacto:** sección `#contacto` en `index.html` — ya tiene tu email, teléfono y LinkedIn del CV.
- **Ubicación:** por privacidad se usa solo "Querétaro, México" en vez de tu dirección completa. Si prefieres mostrar la dirección completa, edítala en `#contacto`.

## Notas de diseño

- Tema oscuro con acento cian/coral, tipografía Space Grotesk + Inter + JetBrains Mono.
- El cubo 3D en el hero es una referencia directa a "Cubexplorer" y a la transición control industrial → IA (sus caras dicen CONTROL, PLC, MOTION, VISION, DATA, AI).
- Sin dependencias externas más allá de Google Fonts — carga rápido y es fácil de mantener.
