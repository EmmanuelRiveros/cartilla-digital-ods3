# Cartilla Digital · Prototipo navegable (ODS 3)

Prototipo académico de una cartilla de vacunación digital familiar, desarrollado para el proyecto final de Diseño de sistemas interactivos (ITSON) sobre el ODS 3, Salud y bienestar.

> **Aviso:** todos los datos (personas, vacunas, campañas, lugares y existencias) son ficticios. No es un servicio oficial y no está vinculado con IMSS, Secretaría de Salud ni clínicas. Los esquemas de vacunación son ilustrativos y están por validar con una fuente institucional.

## Cómo correrlo

No requiere instalación ni dependencias: es un solo archivo HTML.

1. Descarga o clona el repositorio.
2. Abre `index.html` en cualquier navegador moderno.

Con Git:

```bash
git clone <URL-DEL-REPOSITORIO>
cd <carpeta>
# abre index.html en tu navegador, o sirve la carpeta:
python3 -m http.server 8000   # luego visita http://localhost:8000
```

También puede publicarse con GitHub Pages (Settings → Pages → rama `main`, carpeta `/ (root)`).

## Qué puedes probar

- Acceso con PIN de demostración **1234** (o el botón de huella simulada).
- Cambiar entre cuatro perfiles familiares y agregar un familiar nuevo.
- Historial con semáforo (color, símbolo y texto) y barra de avance.
- Detalle de vacuna con explicación sencilla, **marcar como aplicada** (queda como "declarada por ti, sin verificar") y deshacer.
- Recordatorios (7 días antes y mañana de la cita) y botón **Simular aviso**.
- Solicitud de revisión con foto simulada y folio.
- Campañas con fuente y vigencia, comprobante PDF y QR de demostración (marcados como no oficiales).
- Modo **Sin conexión** (panel izquierdo).

En pantallas anchas se muestra una guía lateral con los pasos del flujo principal; en teléfono ocupa toda la pantalla.

## Documentación

- `docs/wireframes/`: wireframes Lo-Fi (mapa de flujo, 3 hojas de pantallas y 1 de estados).
- `docs/capturas/`: capturas del prototipo y comparación storyboard → Lo-Fi → Hi-Fi.

## Límites conocidos

- Sin respaldo de datos: el estado vive en memoria y se reinicia al recargar.
- No se ha probado con usuarios reales ni en un teléfono físico.
- No está construido en Figma.
