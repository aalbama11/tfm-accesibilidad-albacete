# Análisis de Accesibilidad Urbana de Albacete

**Trabajo Fin de Máster** | Universitat Oberta de Catalunya (UOC) | 2026

**Autor:** Adrián Alba  
**Tutor:** Antonio Pérez-Navarro  
**Programa:** Máster Universitario en Ciencia de Datos

---

## Descripción del Proyecto

Este trabajo analiza la **accesibilidad urbana** de la ciudad de Albacete mediante técnicas de **Machine Learning** y **visualización cartográfica interactiva**. Se utilizan datos del Plan de Accesibilidad Municipal que evalúan vías públicas y edificios según criterios normativos para cinco colectivos con discapacidad.

### Objetivos

- **O1:** Analizar descriptivamente el estado de la accesibilidad urbana
- **O2:** Aplicar técnicas de ML (PCA, clustering, Random Forest) para identificar patrones
- **O3:** Estudiar interacciones y trade-offs entre colectivos
- **O4:** Desarrollar mapas interactivos de accesibilidad
- **O5:** Implementar un sistema de rutas óptimas por perfil de usuario

---

## Mapas Interactivos

Accede a las visualizaciones en: **https://aalbama11.github.io/tfm-accesibilidad-albacete/**

Los mapas disponibles incluyen:
- Dashboard principal con capas por colectivo
- Accesibilidad global de vías públicas
- Edificios públicos evaluados
- Clusters K-Means de perfiles de accesibilidad
- Análisis LISA (autocorrelación espacial)
- Residuos espaciales del modelo de regresión

---

## Tecnologías Utilizadas

- **Python 3.9+**: pandas, numpy, scikit-learn, scipy
- **Visualización**: matplotlib, seaborn, folium
- **Análisis espacial**: libpysal, esda
- **Entorno**: Kaggle Notebooks, Jupyter

---

## Estructura del Repositorio

```
├── index.html                      # Página principal con índice de mapas
├── dashboard_accesibilidad.html    # Mapa interactivo principal
├── mapa_accesibilidad_global.html  # Mapa de puntuación global
├── mapa_edificios.html             # Mapa de edificios públicos
├── mapa_clusters_kmeans.html       # Visualización de clusters
├── mapa_lisa_clusters.html         # Análisis de autocorrelación espacial
└── mapa_residuos_espaciales.html   # Residuos del modelo de regresión
```

---

## Cómo Citar

```
Alba, A. (2026). Análisis de la accesibilidad urbana mediante técnicas de 
Machine Learning y visualización cartográfica interactiva: caso de estudio 
de Albacete [Trabajo Fin de Máster]. Universitat Oberta de Catalunya.
```

---

## Contacto

- **Email:** aalbama@uoc.edu

---

## Licencia

Este proyecto se distribuye bajo licencia **MIT** para fines académicos y de investigación.

*Última actualización: 16/05/2026*
