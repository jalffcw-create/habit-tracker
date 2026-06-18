# 🌅 Before Dawn — Daily Tracker

Tu registro de hábitos para una construcción de seis meses. Un anillo por hábito, una marca por día: la rueda se va llenando conforme avanza el mes. Todo en un solo archivo HTML, sin instalación ni dependencias (más allá de las fuentes de Google).

## Características

- ⭕ **Rueda de hábitos** — cada hábito es un anillo; cada día, un segmento que se enciende al marcarlo
- ✅ **Panel "Today"** — marca los hábitos de hoy con un toque
- 📊 **"This month"** — progreso vs. meta mensual y rachas 🔥 por hábito
- ⚠️ **"Needs attention"** — avisa cuando llevas 4+ días seguidos sin cumplir un hábito
- ✏️ **Editar hábitos** — cambia nombre, color y meta mensual; agrega o elimina hábitos
- 📋 **"Copy progress for Claude"** — genera un resumen en texto plano para pegar en el chat
- 💾 **Guardado local** — usa `localStorage` del navegador (datos por mes); 100% privado, sin servidores
- 🗓️ Marca el inicio de la construcción: **lunes 15 de junio de 2026**

## Uso

Abre `index.html` en tu navegador:

```bash
open index.html        # macOS
```

O haz doble clic en el archivo. Pulsa los hábitos del panel **Today** para marcarlos, o toca directamente los segmentos de la rueda.

## Datos

La información se guarda en el `localStorage` del navegador:
- `habit-config` — la lista de hábitos (nombre, color, meta)
- `habits:AAAA-MM` — las marcas de cada mes

Si limpias los datos del navegador, se borrará el historial. No se envía nada a internet.

## Personalización rápida

Los hábitos por defecto y la fecha de inicio están definidos cerca del inicio del `<script>` en `index.html`:
- `DEFAULT_HABITS` — hábitos iniciales
- `START` — fecha de inicio de la construcción

## Licencia

MIT
