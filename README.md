# TA-IND-04 — Informe Técnico Individual

**Universidad:** Universidad Técnica Estatal de Quevedo
**Facultad:** Ciencias de la Computación
**Carrera:** Ingeniería de Software
**Asignatura:** Aplicaciones Distribuidas (ISR-701)
**Unidad:** Unidad 4 — Cómputo Paralelo y Distribuido
**Período académico:** 2026–2027 PPA

**Estudiante:** Cristhian Daniel Pacheco Cárdenas
**Equipo de PE-U4:** Equipo A (Cristhian Daniel Pacheco Cárdenas, Robinson Rodrigo
Cando Moreno, Ernesto Gregory Luna Mora)
**PFC de referencia:** ACC — Sistema de Gestión de Soporte Técnico ISP
**Transformación declarada como foco individual:** T3 (Join, tickets ⋈ agentes)

## Origen de los datos (trazabilidad, criterio 1.1)

- **Repositorio de PE-U4:** https://github.com/CristhianP03/pe-u4-spark-equipoA
- **Commit exacto:** `aac987686e1d8dd0559b3ea6ed07af3335570ced`
- **Archivo origen:** `resultados/tiempos_resumen.csv`
- **Plataforma:** Google Colab, PySpark 3.5.3, pandas 2.2.3
- El archivo `datos/tiempos_base.csv` de este repositorio es una copia
  verificada byte a byte del original citado arriba (ver `docs/TA_IND_04_Informe.tex`,
  Sección 2, para la declaración completa de trazabilidad).

## Estructura

```
ta-ind-04-pacheco/
├── README.md
├── LICENSE
├── docs/
│   ├── TA_IND_04_Informe.tex
│   ├── TA_IND_04_Informe.pdf
│   └── references.bib
├── datos/
│   └── tiempos_base.csv
└── figuras/
    ├── fig_speedup.png
    └── fig_arquitectura_integracion.png
```

## Instrucciones exactas de compilación

Requisitos: distribución TeX con `pdflatex` y `biber` (TeX Live 2023+ o
MiKTeX actualizado), paquete `biblatex-ieee`.

Desde la raíz del repositorio:

```bash
cd docs
pdflatex TA_IND_04_Informe.tex
biber TA_IND_04_Informe
pdflatex TA_IND_04_Informe.tex
pdflatex TA_IND_04_Informe.tex
```

Es obligatorio ejecutar la secuencia completa (`pdflatex → biber → pdflatex
→ pdflatex`); una sola pasada de `pdflatex` deja las citas bibliográficas
sin resolver (aparecerán como `[?]`).

El PDF resultante debe coincidir con `docs/TA_IND_04_Informe.pdf`, que ya
se entrega compilado y versionado en este repositorio.

## Declaración de uso de inteligencia artificial generativa

Ver la sección final de `docs/TA_IND_04_Informe.pdf` / `.tex` para la
declaración completa (herramienta, propósito y secciones asistidas).
