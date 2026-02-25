# Análisis de la Crispación Parlamentaria en España (1979-2026)

### Minería de Textos, NLP y LLMs aplicados al Diario de Sesiones del Congreso de los Diputados

## Estado del proyecto

El objetivo del trabajo es un estudio cuantitativo de la crispación lingüística en el Congreso de los Diputados desde la Transición hasta la actualidad.

El repo no se encuentra en su versión definitiva.

Incluye:
- Construcción y limpieza del corpus (PDF/OCR/TXT).
- Parsing de intervenciones parlamentarias.
- Filtrado y emparejamiento de entidades.
- Métricas de polarización y crispación.
- Benchmark de etiquetado con LLM.
- Visualización y análisis final.

> **Reconocimientos:** Premio especial del Congreso Jóvenes Investigadores 2025 (INJUVE).

## Estructura actual del repositorio

```text
.
├── README.md
├── notebooks/
│   ├── 01_scraping_downloads.ipynb
│   ├── 02_OCR_normalization.ipynb
│   ├── 03_intervention_parsing.ipynb
│   ├── 04_entity_matching_filtering.ipynb
│   ├── 05_word_frequency.ipynb
│   ├── 06_LLM_tagging_benchmark.ipynb
│   ├── 07_metric_computation.ipynb
│   └── 08_analysis_and_viz.ipynb
└── data/
	├── external/
	├── raw/
	├── processed/
	├── outputs/
	└── src/
```

## Notas de publicación

- Este repositorio se publica antes del cierre definitivo para compartir metodología y datos principales.
- Hay disponible un manuscrito en PDF en el que se desarrolla la investigación en detalle.


