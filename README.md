<h1 align="center">Proyecto de Data Analytics — Fútbol Femenino Internacional (Tableau)</h1>

<p align="center">
  Bootcamp de Data Analytics — Adalab — Módulo 4
</p>

<p align="center">
  <img src="pictures/Logo.png" width="400" alt="Logo Futbol Femenino">
</p>

---

## Índice de Contenidos

- [Resumen y Alcance](#resumen-y-alcance)
- [Objetivos](#objetivos)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Flujo de Trabajo Analítico](#flujo-de-trabajo-analítico)
- [Características del Dashboard](#características-del-dashboard)
- [Resultados y Hallazgos](#resultados-y-hallazgos)
- [Herramientas](#herramientas)
- [Instalación y Uso](#instalación-y-uso)
- [Autoría](#autoría)

---

## Resumen y Alcance

Este proyecto presenta un análisis visual exhaustivo sobre la evolución del fútbol femenino internacional. Utilizando Tableau, hemos transformado datos históricos de partidos, goleadoras y resultados desde 1956 hasta la actualidad para identificar patrones de crecimiento, hegemonías deportivas y tendencias de rendimiento.

El proyecto abarca desde la limpieza de datos brutos hasta la creación de un *storytelling* visual interactivo que permite a los usuarios explorar la historia de este deporte.

---

## Objetivos

### Objetivos de Análisis 
* **Tendencias Históricas:** Identificar el crecimiento exponencial de partidos y torneos.
* **Rendimiento por Selección:** Analizar la hegemonía de potencias como EE. UU. y la paridad en torneos oficiales.
* **Hitos Individuales:** Destacar a las máximas goleadoras históricas y su impacto en las competiciones.
* **Análisis de Tensión:** Evaluar la frecuencia y desenlace de las tandas de penaltis en fases críticas.

### Objetivos de Aprendizaje
* **Tableau Desktop:** Dominio de dashboards interactivos, filtros cruzados y parámetros.
* **Campos Calculados:** Creación de métricas personalizadas y KPIs de rendimiento.
* **Data Storytelling:** Comunicación efectiva de hallazgos complejos mediante visualización.
* **Gestión de Datos:** Unión, limpieza y estructuración de múltiples fuentes CSV.

---

## Estructura del Proyecto

```text
📁 proyecto-da-promo-59-modulo-4-team-1
│
├── Datos/
│   ├── results.csv        # Histórico de partidos y resultados
│   ├── goalscorers.csv    # Registro detallado de goles y jugadoras
│   └── shootouts.csv      # Datos de tandas de penaltis
│
├── worldCupoW.twbx        # Libro de trabajo empaquetado de Tableau
└── README.md              # Documentación del proyecto
```
---

## Flujo de Trabajo Analítico

### 1. Comprensión y Preparación de Datos
* Revisión de estructuras de datos y tipos de variables.
* Estandarización de nombres de países y formatos de fecha.
* Tratamiento de valores nulos en registros históricos antiguos.

### 2. Análisis Exploratorio (EDA)
* Identificación de las selecciones con mayor volumen de victorias.
* Análisis de la correlación entre torneos y promedios de gol.
* Segmentación de datos por décadas para visualizar el crecimiento.

### 3. Diseño del Dashboard
* Creación de una jerarquía visual clara.
* Implementación de filtros dinámicos (Año, Torneo, Equipo).
* Desarrollo de KPIs interactivos para una consulta rápida de métricas clave.

---

## Características del Dashboard

El libro de trabajo de Tableau incluye:
* **Filtros Interactivos:** Permiten al usuario segmentar la información por fecha o competición.
* **Indicadores KPI:** Resumen visual de partidos totales, goles y jugadoras destacadas.
* **Mapas de Rendimiento:** Visualización geográfica del dominio futbolístico.
* **Gráficos Dinámicos:** Comparativas de goles por minuto y tendencias temporales.

---

## Resultados y Hallazgos

| Métrica | Resultado |
|---------|-----------|
| **Partidos Analizados** | 11,177 encuentros registrados. |
| **Goles Totales** | Más de 41,000 goles documentados. |
| **Máxima Goleadora** | **Birgit Prinz** (34 goles registrados). |
| **Tendencia** | Crecimiento masivo de la profesionalización desde 1990. |

**Insights Clave:**
* **Hegemonía:** Estados Unidos lidera las estadísticas históricas, pero la brecha técnica con Europa se ha reducido significativamente en la última década.
* **Evolución:** Los partidos amistosos han dado paso a una estructura sólida de ligas y copas internacionales.
* **Paridad:** El aumento de tandas de penaltis en fases finales refleja una mayor igualdad competitiva entre las selecciones élite.

---

## Herramientas
<p align="center">
  <img src="https://cdn.worldvectorlogo.com/logos/tableau-software.svg" width="70"/>
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" width="55"/>
  &nbsp;
  <img src="https://cdn.worldvectorlogo.com/logos/microsoft-excel-2013.svg" width="55"/>
</p>

* **Tableau Desktop:** Diseño de dashboards interactivos y visualización avanzada de datos.  
* **Tableau Calculated Fields:** Creación de KPIs y métricas personalizadas.  
* **Excel / CSV:** Preparación y estructuración de la fuente de datos.  
* **Data Cleaning:** Transformación, estandarización y validación de datos antes del análisis.

---

## Instalación y Uso

1. **Clonar el repositorio:**
   ``` bash
   git clone [https://github.com/TamDb22/proyecto-da-promo-59-modulo-4-team-1.git](https://github.com/TamDb22/proyecto-da-promo-59-modulo-4-team-1.git)
   ```
2. **Requisitos:**
  Asegúrate de tener instalado Tableau Desktop o Tableau Reader (versión gratuita).
3. **Ejecución:**
  Abre el archivo worldCupoW.twbx.
5. **Navegación:**
  Utiliza las pestañas inferiores para explorar las historias y dashboards interactivos.

---

## Autoría

Proyecto desarrollado por el **Equipo 1 del Módulo 4 – Tableau** del Bootcamp de Adalab:

<p align="center">
  <a href="https://github.com/TamDb22">
    <img src="https://github.com/TamDb22.png" width="80" style="border-radius:50%;" alt="Tamara Díaz"/><br>
    <b>Tamara Díaz</b>
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://github.com/cristinaragon">
    <img src="https://github.com/cristinaragon.png" width="80" style="border-radius:50%;" alt="Cristina Aragón"/><br>
    <b>Cristina Aragón</b>
  </a>
</p>
