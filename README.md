# 📊 Análisis de Evasión de Clientes (Churn) – Telecom X

![Diccionario de Datos](./assets/diccionario_datos.png)

## 🧠 Descripción del Proyecto

Este proyecto tiene como objetivo **analizar y comprender las causas de la evasión de clientes (Churn)** en una empresa de telecomunicaciones, utilizando técnicas de **análisis exploratorio de datos (EDA)** y visualización.

A través del análisis de variables demográficas, contractuales, de consumo y facturación, se buscan **patrones y factores clave** que influyen en la cancelación de los servicios por parte de los clientes, con el fin de apoyar la **toma de decisiones estratégicas** orientadas a la retención.

El proyecto está desarrollado en **Python**, utilizando un **Jupyter Notebook** como medio principal de análisis.

---

## 📂 Estructura del Proyecto

```
├── 📓 Telecom_X_Análisis_de_Evasión_de_Clientes.ipynb
├── 📄 README.md
├── 📄 LICENSE
└── 📄 .gitignore
```

---

## 🗂️ Diccionario de Datos

A continuación se describen las columnas contenidas en el dataset analizado:

| Columna            | Descripción                                         |
| ------------------ | --------------------------------------------------- |
| `customerID`       | Identificador único del cliente                     |
| `Churn`            | Indica si el cliente canceló el servicio (Yes / No) |
| `gender`           | Género del cliente                                  |
| `SeniorCitizen`    | Cliente con edad ≥ 65 años                          |
| `Partner`          | Indica si el cliente tiene pareja                   |
| `Dependents`       | Indica si el cliente tiene dependientes             |
| `tenure`           | Meses de permanencia del cliente                    |
| `PhoneService`     | Suscripción al servicio telefónico                  |
| `MultipleLines`    | Más de una línea telefónica                         |
| `InternetService`  | Proveedor de internet                               |
| `OnlineSecurity`   | Servicio adicional de seguridad en línea            |
| `OnlineBackup`     | Servicio adicional de respaldo                      |
| `DeviceProtection` | Protección del dispositivo                          |
| `TechSupport`      | Soporte técnico prioritario                         |
| `StreamingTV`      | Servicio de TV                                      |
| `StreamingMovies`  | Servicio de películas                               |
| `Contract`         | Tipo de contrato                                    |
| `PaperlessBilling` | Facturación electrónica                             |
| `PaymentMethod`    | Método de pago                                      |
| `Charges.Monthly`  | Cargo mensual del cliente                           |
| `Charges.Total`    | Total gastado por el cliente                        |

---

## ⚙️ Instalación y Configuración

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/JharleCompres/Telecom-X---An-lisis-de-Evasi-n-de-Clientes.git
cd Telecom-X---An-lisis-de-Evasi-n-de-Clientes
```

### 2️⃣ Instalar dependencias

```
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `jupyter`
```

---

## 📦 Dependencias Principales

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `jupyter`

---

## ▶️ Ejecución del Proyecto

1. Inicia Jupyter Notebook:

```bash
jupyter notebook
```

2. Abre el archivo:

```Telecom-X---An-lisis-de-Evasi-n-de-Clientes.ipynb
```

3. Ejecuta las celdas en orden para reproducir el análisis completo.

---

## 📈 Contenido del Análisis

* Limpieza y preparación de datos
* Transformación de variables categóricas
* Análisis de evasión (Churn) por:

  * Variables númericas
  * Tipo de contrato
  * Servicios contratados
  * Facturación mensual y total
* Visualización de patrones clave
* Interpretación de resultados

---

## 🚨 Problemas Comunes y Soluciones

### ❌ Error al ejecutar el notebook

**Solución:** Verifica que todas las dependencias estén instaladas.

### ❌ Valores nulos o inconsistencias

**Solución:** El notebook incluye pasos de limpieza; asegúrate de ejecutar todas las celdas previas.

### ❌ Gráficos no se visualizan correctamente

**Solución:** Reinicia el kernel y ejecuta nuevamente todas las celdas (`Restart & Run All`).

---

## 🧩 Posibles Mejoras Futuras

* Implementación de modelos predictivos de Churn
* Segmentación de clientes
* Dashboard interactivo (Power BI / Streamlit)

---

## 👤 Autor

**Jharle Compres**
Estudiante de Ingeniería en Sistemas & Ciencia de Datos

📌 Proyecto académico / analítico

---

## ⭐ Agradecimientos

Si este proyecto te resulta útil, no olvides dejar una ⭐ en el repositorio.

---

