# Análisis del comportamiento y fidelización de usuarios en AprendiFy

## Descripción del proyecto

Este proyecto presenta un análisis exploratorio y estadístico del comportamiento de los usuarios en la plataforma de aprendizaje **AprendiFy**. El objetivo principal es identificar patrones de uso, niveles de compromiso con el aprendizaje y factores asociados con la fidelización de los usuarios.

Para ello se analizan variables relacionadas con la actividad en la plataforma, tales como la frecuencia de uso, la tasa de completitud de cursos, el número de cursos iniciados, la antigüedad de los usuarios y el tipo de suscripción.

El proyecto se desarrolla utilizando **Power BI** como herramienta de visualización y análisis de datos, aplicando conceptos de **estadística descriptiva** y **análisis exploratorio de datos (EDA)**.

---

## Objetivos del análisis

* Analizar el comportamiento de los usuarios dentro de la plataforma.
* Identificar patrones de uso y niveles de compromiso con los cursos.
* Evaluar la relación entre el tipo de suscripción y la fidelización.
* Extraer insights que permitan mejorar la retención de usuarios.

---

## Dataset

El dataset contiene información sobre el comportamiento de los usuarios en la plataforma AprendiFy. Entre las variables analizadas se encuentran:

* Antigüedad del usuario (meses en la plataforma)
* Frecuencia de uso semanal (horas)
* Número de cursos iniciados
* Tasa de completitud de cursos (%)
* Tipo de suscripción (Básica / Premium)
* Intención de renovación de la suscripción

Las variables permiten analizar tanto la **actividad de aprendizaje** como la **probabilidad de permanencia en la plataforma**.

---

## Metodología de análisis

El proyecto sigue un enfoque de **análisis exploratorio de datos (EDA)** y estadística descriptiva, utilizando las siguientes técnicas:

### Estadística descriptiva

* Media
* Mediana
* Moda
* Desviación estándar

### Análisis de distribución

* Histogramas
* Diagramas de dispersión

### Análisis de relaciones entre variables

* Correlación lineal
* Regresión lineal
* Coeficiente de determinación (R²)

### Análisis de fidelización

* Comparación de comportamiento entre usuarios **Básicos** y **Premium**
* Análisis de intención de renovación de suscripción

---

## Visualizaciones del dashboard

El dashboard desarrollado en Power BI incluye diferentes páginas de análisis:

### 1. Antigüedad de los usuarios

Analiza la distribución del tiempo que los usuarios permanecen en la plataforma.

### 2. Frecuencia de uso

Examina el número de horas semanales que los usuarios dedican al aprendizaje.

### 3. Completitud de cursos

Evalúa el porcentaje de cursos que los usuarios logran finalizar.

### 4. Cursos iniciados

Analiza el nivel de exploración del contenido disponible en la plataforma.

### 5. Perfil y fidelización de usuarios

Compara el comportamiento de usuarios **Básicos y Premium**, analizando:

* tasa de completitud
* frecuencia de uso
* intención de renovación

---

## Principales hallazgos

* Los usuarios **Premium presentan una mayor tasa de completitud de cursos** en comparación con los usuarios del plan Básico.
* La **frecuencia de uso semanal es similar** entre ambos tipos de suscripción.
* Los usuarios Premium muestran una **mayor intención de renovar la suscripción**, lo que sugiere un mayor nivel de fidelización.
* La fidelización parece estar asociada más con el **nivel de compromiso con los cursos** que con el tiempo total de uso de la plataforma.

---

## Recomendaciones basadas en datos

A partir del análisis se identifican algunas posibles estrategias:

* Incentivar la transición de usuarios Básicos hacia el plan Premium.
* Implementar mecanismos de seguimiento del progreso de los cursos para aumentar la completitud.
* Diseñar estrategias de retención enfocadas en usuarios con menor compromiso con la plataforma.

---

## Herramientas utilizadas

* **Power BI** – visualización de datos y creación de dashboards
* **Estadística descriptiva**
* **Análisis exploratorio de datos (EDA)**

---

## Estructura del repositorio

```
aprendify-user-analytics/
│
├── dataset/
│   └── aprendify_users.csv
│
├── dashboard/
│   └── AprendiFy_Analytics.pbix
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## Autor

Proyecto desarrollado por **Gilbert Ardila** como práctica de análisis de datos y visualización con Power BI.
