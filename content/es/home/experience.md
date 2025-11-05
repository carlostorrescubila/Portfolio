---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experiencia Laboral
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - company: Banco General
    company_url: 'https://www.bgeneral.com/'
    company_logo: banco-general
    location: Ciudad de Panamá, Panamá
    date_start: '2021-01-04'
    date_end: '2025-02-28'
    roles:
      - title: Científico de Datos Senior
        date_start: '2022-04-01'
        date_end: '2025-02-28'
        description: |2-
            * Lideré proyectos estratégicos de analítica avanzada en banca, como Delinquency Forecasting y Recovery Optimization, logrando mejoras sustanciales en la recuperación de cartera y reducción de morosidad.
            * Implementé modelos de machine learning (Scikit-learn, LightGBM, XGBoost) desplegados en producción con pipelines escalables en Databricks y seguimiento mediante MLflow.
            * Diseñé procesos ETL robustos en PySpark para alimentar tableros ejecutivos en AWS QuickSight, optimizando la toma de decisiones basada en datos para directivos de alto nivel.
            * Dirigí y mentoricé a un equipo de científicos e ingenieros de datos, impulsando estándares de modelado, ingeniería de datos y visualización alineados con mejores prácticas internacionales.      
      - title: Científico de Datos
        date_start: '2021-01-04'
        date_end: '2022-03-31'
        description: |2-
          * Participé en proyectos de analítica end-to-end como predicción de cancelaciones de tarjetas de crédito, ventas de seguros y next best producto to buy, integrando modelos predictivos directamente en procesos de negocio logrando aumentar la colocación de productos en la cartera de clientes.
          * Automatizé procesos ETL en PySpark y desarrollé modelos predictivos en Python, incrementando la escalabilidad y eficiencia de los flujos analíticos.
          * Elaboré reportes financieros con visualizaciones adaptadas a audiencias técnicas y no técnicas, facilitando la comunicación de hallazgos y recomendaciones.
        
  - title: Científico de datos en prácticas
    company: STAT-UP
    company_url: 'https://stat-up.com/es/'
    company_logo: stat-up
    location: Múnich, Alemania
    date_start: '2020-02-01'
    date_end: '2020-04-30'
    description: |2-
        * Implementé procesos ETL en R (Tidyverse) para consolidar y limpiar datos de diversas fuentes.
        * Desarrollé y desplegué una aplicación interactiva en Shiny para análisis estadístico multivariado, mejorando la exploración y visualización de datos.
        * Creé informes interactivos en HTML con visualizaciones dinámicas, optimizando la comunicación de resultados a clientes internacionales.

  - title: Estadístico en prácticas
    company: Departamento de Estadística de la Universidad de Salamanca
    company_url: 'http://biplot.dep.usal.es/'
    company_logo: universidad-de-salamanca
    location: Salamanca, España
    date_start: '2018-09-01'
    date_end: '2019-01-31'
    description: |2-
        * Asesoré a estudiantes en la aplicación de técnicas estadísticas avanzadas a proyectos académicos.
        * Apoyé la docencia en cursos de estadística aplicada,fomentando el uso de herramientas analíticas y software estadístico.

design:
  columns: '2'
---
