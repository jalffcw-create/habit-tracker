# 🌱 Habit Tracker — Mis Hábitos

App sencilla para seguir tus hábitos diarios. Un solo archivo HTML, sin dependencias ni instalación: ábrela en cualquier navegador y empieza.

## Características

- ✅ Marca hábitos como completados cada día con un clic
- 🔥 Rachas automáticas (días consecutivos)
- 🗓️ Mapa de calor de los últimos 30 días por hábito
- 📊 Estadísticas del día: completados, progreso y mejor racha
- 💾 Tus datos se guardan **localmente** en el navegador (`localStorage`) — 100% privado, sin servidores
- 🌙 Interfaz oscura y responsiva (funciona en móvil y escritorio)

## Uso

Abre `index.html` en tu navegador:

```bash
open index.html        # macOS
```

O simplemente haz doble clic en el archivo.

Para agregar un hábito, escribe su nombre y pulsa **Agregar** (o Enter). Pulsa el círculo para marcarlo como hecho hoy.

## Datos

Toda la información vive en el `localStorage` de tu navegador bajo la clave `habit-tracker.v1`. Si limpias los datos del navegador, se borrará el historial. No se envía nada a internet.

## Licencia

MIT
