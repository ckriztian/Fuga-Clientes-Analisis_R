
## Predicción de Fuga de Clientes – Dashboard Interactivo

![Dashboard Fuga de Clientes](/img/dashboard.png)

### 🚀 Descripción

Este proyecto implementa un sistema de **predicción y visualización de fuga de clientes** ("customer churn"). Permite a las organizaciones anticipar la pérdida de clientes, segmentar su base y simular escenarios de retención de manera interactiva.


### 🎯 Funcionalidades principales

- **Visualización de métricas clave**: Proporción de clientes fugados, análisis de variables relevantes.
- **Modelos predictivos**: Árbol de decisión y regresión logística para estimar el riesgo de fuga.
- **Segmentación de clientes**: Agrupamiento (clustering) para analizar perfiles de clientes.
- **Simulación Monte Carlo**: Permite modelar el impacto de estrategias de retención en la tasa de fuga.
- **Dashboard Shiny**: Interfaz amigable e interactiva para analizar resultados y simular escenarios.


### 💡 ¿Por qué este proyecto?

La retención de clientes es un desafío crítico para empresas de servicios, banca, telecomunicaciones, streaming, entre otros. Anticipar la fuga de clientes permite implementar acciones proactivas y personalizadas para mejorar la rentabilidad del negocio.


### 🏦 Ejemplo de aplicación en otras industrias

- Bancos (churn en productos financieros)
- Empresas de streaming (cancelación de suscripciones)
- Seguros (baja de pólizas)
- Servicios de suscripción SaaS (abandono de usuarios)


### 🛠️ ¿Qué resuelvo con este proyecto?
-	Detectar patrones y variables asociadas a la fuga.
-	Segmentar clientes según riesgo de fuga.
-	Permitir simulaciones (por ejemplo, cómo bajaría la fuga si aplico una campaña de retención).
-	Visualizar los resultados de forma clara para la toma de decisiones.

---

### 📂 Descripción del dataset

El proyecto utiliza el dataset “Telco Customer Churn” (Kaggle), que contiene información de clientes de una empresa de telecomunicaciones: datos demográficos, servicios contratados, historial de facturación y si el cliente abandonó o no el servicio.

---
### [Link del Video-Presentación del Proyecto](https://youtu.be/eLrBgtpBp4A) 
---
### 📁 Estructura del proyecto

```
├── data/                                 # Carpeta sugerida para agregar documentación
├── img/                                  # Imágenes ilustrativas del dashboard y resultados
├── Proyecto_Fuga-de-clientes.Rmd         # Análisis completo y desarrollo del proyecto
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset de Kaggle
```

---

### ⚙️ Instrucciones de uso

1. **Cloná el repositorio:**
   ```bash
   git clone https://github.com/ckriztian/Fuga-Clientes-Analisis_R.git
   ```
2. **Instalá las dependencias necesarias en R:**
   ```r
   install.packages(c("shiny", "shinydashboard", "caret", "rpart", "rpart.plot", "DT", "factoextra", "plotly"))
   ```
3. **Ejecutá la app Shiny:**
   - Abrí el archivo `Proyecto_Fuga-de-clientes.Rmd` en RStudio y hacé click en “Run All”.

---

## 👤 Créditos

*Desarrollado por Cristian Vera*  
*Para la Diplomatura en Business Intelligence – UTN BA*

