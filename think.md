# Portfolio Thinks

Repositorio personal de toma de decisiones de inversión. No es un sistema de señales ni una herramienta de recomendación — es un diario de convicción donde documento el **por qué** detrás de cada posición antes de operar, y reviso los resultados con honestidad.

## Archivos

| Archivo | Descripción |
|---------|-------------|
| [`tesis.md`](tesis.md) | Tesis de inversión completa del portafolio — macro, estructura por capas, tesis por posición, riesgos y métricas de éxito |
| [`think.md`](think.md) | Tesis por activo + resúmenes semanales con análisis de operaciones |
| [`dashboard.html`](dashboard.html) | Dashboard interactivo con widgets de TradingView en tiempo real |

## Portafolio actual

| Activo | Tipo | Rol | Semana |
|--------|------|-----|--------|
| **VOO** | ETF Long | Base — S&P 500, ancla del portafolio | S1 |
| **QQQ** | ETF Long | Base — Nasdaq 100, sobrepeso en tecnología | S1 |
| **NVDA** | Acción Long | Convicción — infraestructura de IA | S1 |
| **TSLA** | Acción Long | Momentum — EV + energía + FSD | S1 |
| **AMD** | Acción Long | Chips IA — competencia directa a NVDA | S2 |
| **CSCO** | Acción Long | Tech defensivo — networking para IA | S3 |
| **LLY** | Acción Long | Pharma — GLP-1/obesidad, mercado $150B+ | S2 |
| **PLTR** | Acción Short | Cobertura anticíclica — defensa / gobierno | S1 |
| ~~CAT~~ | ~~Long~~ | ~~Cerrada 5/13 con -$10.90~~ | ~~S2→S3~~ |

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
- Ticker tape en tiempo real de los 8 activos
- Panel de resumen con sparkline SVG acumulada (S1+S2), P&L por posición e historial de transacciones
- Mini gráfico + análisis técnico por activo, organizados por sección (ETF / Growth / S2 nuevas / Short)
- Panel de estado de la posición short de PLTR con seguimiento semana a semana

## Filosofía

> "El portafolio no necesita que lo toque cada semana. Necesita tiempo."

La tesis central de este repositorio es que **la disciplina de no operar** es tan importante como la selección de activos. Cada decisión documentada en `think.md` existe para evitar que el ruido del mercado reemplace la convicción de largo plazo.

## Resultados por semana

### Semana 1 (4–8 mayo 2026)

| Métrica | Valor |
|---------|-------|
| Net Worth cierre | $10,019.38 |
| Retorno | +0.19% (+$19.38) |
| Mejor posición | TSLA +4.90% |
| Peor posición | PLTR short -3.30% |
| Operaciones ejecutadas | 8 de 9 |
| Operaciones con ruido | 3 — QQQ intraday + PLTR fragmentado en 3 órdenes |

### Semana 2 (11–11 mayo 2026 · cerrada)

| Métrica | Valor |
|---------|-------|
| Net Worth cierre | $10,135.34 |
| Retorno total | +1.35% (+$135.34) |
| Mejor posición | TSLA +9.00% |
| PLTR short | -2.61% (mejorando desde -3.30%) |
| Operaciones S2 | 3 — limpias, 1 entrada por posición |
| Margen activo | $7,116.03 (~70% del net worth) ⚠ |
| Rank | #5 |

### Semana 3 (12–15 mayo 2026 · en curso)

| Métrica | Valor |
|---------|-------|
| Net Worth | $10,002.62 |
| Retorno total | +0.03% (+$2.62) |
| Pico alcanzado | $10,485.77 (+4.86%) el 5/14 |
| Caída hoy | -4.61% — borró 3 días de ganancias |
| Mejor posición | NVDA +6.15% |
| Peor posición | AMD -8.45% |
| PLTR short | -0.44% — casi en breakeven |
| Operaciones S3 | 2 — CAT vendida, CSCO comprada |
| Margen activo | $8,021.89 (~80% del net worth) 🚨 |
| Buying Power | **-$172.52** 🚨 SOBRE-APALANCADO |
| Rank | #4 |

---

*Uso personal. No constituye asesoría financiera.*
