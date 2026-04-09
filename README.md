# Análisis de Comportamiento de Clientes - ConnectaTel 📊

## 🎯 Objetivo del Proyecto
El propósito de este análisis es identificar patrones de uso de los servicios de telecomunicaciones, detectar comportamientos atípicos (outliers) y comprender las necesidades de los diferentes segmentos de clientes. El fin último es proporcionar información estratégica para optimizar la oferta comercial y mejorar la experiencia del usuario.

## 📂 Datasets Utilizados
El proyecto se basa en tres fuentes de datos principales:
*   **`plans.csv`**: Detalles de los planes actuales (precios, límites de minutos/GB e importes por consumos excedentes).
*   **`users_latam.csv`**: Información demográfica de clientes (edad, ciudad, fecha de registro y plan contratado).
*   **`usage.csv`**: Detalle del uso real de servicios, incluyendo duración de llamadas y longitud de mensajes de texto.

## 🛠️ Etapas del Análisis
El flujo de trabajo se dividió en 8 etapas críticas:
1.  **Carga y Exploración:** Inspección inicial de la estructura y tipos de datos.
2.  **Identificación de Problemas:** Detección de nulos, duplicados y valores atípicos.
3.  **Limpieza de Datos:** Tratamiento de valores *sentinel*, corrección de fechas y manejo de nulos.
4.  **Agregación de Datos:** Resumen de estadísticas de uso por cada identificador de usuario.
5.  **Análisis Exploratorio (EDA):** Visualización de distribuciones y detección de *outliers*.
6.  **Segmentación:** Clasificación de clientes según su nivel de uso y grupo de edad.
7.  **Análisis Ejecutivo:** Redacción de hallazgos clave y recomendaciones de negocio.
8.  **Documentación:** Carga del proyecto y control de versiones en GitHub.

## 🚀 Ejecución del Notebook
Puedes ejecutar este análisis de dos formas:
*   **Google Colab:** Sube el archivo `.ipynb` y asegúrate de cargar los archivos `.csv` en la carpeta lateral o actualizar las rutas para conectar con tu Google Drive.
*   **Localmente:** Descarga el repositorio completo y asegúrate de que los datasets estén en la misma carpeta que el notebook para que las rutas relativas funcionen correctamente.

## 🔧 Guía de Reproducción
Para garantizar el funcionamiento del código, asegúrate de cumplir con los siguientes requisitos:

1.  **Librerías Necesarias:**
    Instala las siguientes dependencias:
    ```bash
    pandas numpy seaborn matplotlib
    ```
2.  **Configuración:**
    Importa las librerías al inicio del script y carga los archivos CSV.
3.  **Orden de Ejecución:**
    Ejecuta el código de forma **secuencial** (de arriba hacia abajo) para asegurar que las variables y transformaciones se mantengan consistentes a lo largo del análisis.
