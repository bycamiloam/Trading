# Portfolio Thinks

Repositorio personal de toma de decisiones de inversión. No es un sistema de señales ni una herramienta de recomendación — es un diario de convicción donde documento el **por qué** detrás de cada posición antes de operar, y reviso los resultados con honestidad.

## Archivos

| Archivo | Descripción |
|---------|-------------|
| [`think.md`](think.md) | Tesis de inversión por activo + resumen semanal con análisis de operaciones |
| [`dashboard.html`](dashboard.html) | Dashboard interactivo con widgets de TradingView en tiempo real |

## Portafolio actual

| Activo | Tipo | Rol |
|--------|------|-----|
| **VOO** | ETF Long | Base — S&P 500, ancla del portafolio |
| **QQQ** | ETF Long | Base — Nasdaq 100, sobrepeso en tecnología |
| **NVDA** | Acción Long | Convicción — infraestructura de IA |
| **TSLA** | Acción Long | Momentum — EV + energía + FSD |
| **PLTR** | Acción Short | Cobertura anticíclica — defensa / gobierno |

## Dashboard

El archivo `dashboard.html` no requiere servidor ni dependencias. Abre directamente en el navegador:

```bash
# Linux
xdg-open dashboard.html

# macOS
open dashboard.html
```

Requiere conexión a internet para cargar los widgets de TradingView.

**Incluye:**
- Ticker tape en tiempo real de los 5 activos
- Panel de resumen de la semana con sparkline SVG, P&L por posición y log de transacciones
- Mini gráfico + análisis técnico (osciladores y medias móviles) por activo
- Panel de estado de la posición short de PLTR con stop sugerido

## Filosofía

> "El portafolio no necesita que lo toque cada semana. Necesita tiempo."

La tesis central de este repositorio es que **la disciplina de no operar** es tan importante como la selección de activos. Cada decisión documentada en `think.md` existe para evitar que el ruido del mercado reemplace la convicción de largo plazo.

## Semana 1 — Resultados

| Métrica | Valor |
|---------|-------|
| Net Worth | $10,019.38 |
| Retorno total | +0.19% (+$19.38) |
| Mejor posición | TSLA +4.90% |
| Peor posición | PLTR short -3.30% |
| Operaciones ejecutadas | 8 de 9 órdenes |
| Operaciones con ruido | 3 (QQQ intraday + fragmentación PLTR) |

---

*Uso personal. No constituye asesoría financiera.*
