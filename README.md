# Portfolio Thinks

Repositorio personal de toma de decisiones de inversión. No es un sistema de señales ni una herramienta de recomendación — es un diario de convicción donde documento el **por qué** detrás de cada posición antes de operar, y reviso los resultados con honestidad.

## Archivos

| Archivo | Descripción |
|---------|-------------|
| [`think.md`](think.md) | Tesis de inversión por activo + resumen semanal con análisis de operaciones |
| [`dashboard.html`](dashboard.html) | Dashboard interactivo con widgets de TradingView en tiempo real |

## Portafolio actual

| Activo | Tipo | Rol | Semana |
|--------|------|-----|--------|
| **VOO** | ETF Long | Base — S&P 500, ancla del portafolio | S1 |
| **QQQ** | ETF Long | Base — Nasdaq 100, sobrepeso en tecnología | S1 |
| **NVDA** | Acción Long | Convicción — infraestructura de IA | S1 |
| **TSLA** | Acción Long | Momentum — EV + energía + FSD | S1 |
| **AMD** | Acción Long | Chips IA — competencia directa a NVDA | S2 |
| **CAT** | Acción Long | Industrial — infraestructura, diversificador sectorial | S2 |
| **LLY** | Acción Long | Pharma — GLP-1/obesidad, mercado $150B+ | S2 |
| **PLTR** | Acción Short | Cobertura anticíclica — defensa / gobierno | S1 |

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

### Semana 2 (11 mayo 2026 · en curso)

| Métrica | Valor |
|---------|-------|
| Net Worth | $10,135.34 |
| Retorno total | +1.35% (+$135.34) |
| Mejor posición | TSLA +9.00% |
| PLTR short | -2.61% (mejorando desde -3.30%) |
| Operaciones S2 | 3 — limpias, 1 entrada por posición |
| Margen activo | $7,116.03 (~41% del net worth) ⚠ |
| Rank | #5 (subió desde #7) |

---

*Uso personal. No constituye asesoría financiera.*
