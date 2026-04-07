# 📊 Proyecto End-to-End: Pipeline de Análisis de Datos (ADSO)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## 🎯 Resumen del Proyecto
Este ecosistema de datos fue desarrollado íntegramente el **5 de abril**, como resultado de un proceso de **aprendizaje autónomo intensivo iniciado el 12 de marzo**. En menos de un mes, logré integrar herramientas de programación, bases de datos y visualización para resolver un problema real de infraestructura local.

---

## 📂 Fase 1: Datos Crudos (Dataset)
Iniciamos con un archivo plano que contiene la información sin procesar. Este es el punto de partida de nuestra ingesta.

> **Visualización del archivo CSV:**
> ![Captura del CSV](Captura_del_CSV.png)

---

## 🐍 Fase 2: Procesamiento y ETL (VS Code + Python)
Para este paso, utilicé **Desarrollo asistido por IA** para optimizar la escritura de los scripts de limpieza en Python, garantizando una carga eficiente de los registros hacia el motor de base de datos.

> **Terminal de VS Code (Confirmación de envío a SQL):**
> ![Captura de la Terminal](Terminal_Load.png)
> *Aquí se observa el log de ejecución del 5 de abril, confirmando la inserción de datos.*

---

## 🗄️ Fase 3: Persistencia en SQL Server
Una vez procesados, los datos se alojan en una instancia local de **SQL Server Express**. Esta etapa garantiza la integridad de los datos y permite un modelado relacional profesional.

> **Ubicación de los datos en SQL Server:**
> ![Captura de SQL Server Management Studio](SQL_EXPRESS.png)
> *Consulta de verificación de los registros importados exitosamente.*

---

## 📊 Fase 4: Business Intelligence (Power BI)
**Proceso 100% Manual:** La conexión entre SQL Server y Power BI, el modelado de medidas DAX y el diseño de la interfaz fueron realizados con mis propios conocimientos técnicos adquiridos desde marzo.

> **Resultado Final - Dashboard Estratégico:**
> ![Resultado Power BI](GIF_POWERBI.gif)
> *Dashboard con diseño moderno (Arial Black / Sombras), filtros dinámicos y métricas clave de negocio.*
> ## 📊 Análisis Detallado del Dashboard (Insights & UX)

El tablero fue diseñado bajo una arquitectura de **User Experience (UX)** que permite transformar los datos crudos de SQL en decisiones estratégicas. A continuación, el desglose de los componentes visuales:

### 🗂️ Panel de Navegación (Slicers)
* **Segmentación por Departamento:** Ubicado a la izquierda como un menú lateral dinámico. Permite filtrar instantáneamente toda la metadata por áreas clave (Ciberseguridad, Finanzas, Logística, etc.), facilitando el análisis comparativo entre equipos.

### 📈 Indicadores de Rendimiento y Seguridad (KPIs)
* **Gráfico de Indicador (Gauge Chart):** Muestra el acumulado de `login_attempts`. Funciona como un termómetro de actividad que permite visualizar rápidamente si los accesos están dentro de los rangos normales de operación.
* **Distribución de Seguridad (Donut Chart):** Clasifica la suma de intentos de inicio de sesión por **Categoría de Salario**. Este visual es crítico para identificar si existe una correlación entre el nivel jerárquico y la actividad en el sistema.

### 🧪 Correlación y Tendencias
* **Análisis de Dispersión (Scatter Plot):** Relaciona la **Antigüedad (meses)** con el monitoreo (`mon`). Este visual permite identificar *outliers* (datos atípicos) y observar la estabilidad de los colaboradores veteranos vs. los nuevos ingresos.
* **Promedio por Departamento (Bar Chart):** Una comparativa clara de las métricas de monitoreo promedio, permitiendo identificar qué áreas requieren mayor atención o recursos.

### 📑 Detalle Transaccional
* **Tabla Dinámica de Registros:** Proporciona el nivel de detalle más bajo (*Granularidad*). Incluye nombre, email y departamento, permitiendo realizar auditorías directas sobre los datos que fueron procesados previamente en el script de Python.

---
> **Nota técnica:** El diseño utiliza una paleta de colores minimalista con **Sombras (Shadows)** aplicadas a cada contenedor para mejorar la jerarquía visual y reducir la fatiga cognitiva del usuario.

---

## 🛠️ Desafíos y Logros
Este proyecto es el testimonio de mi capacidad de **autoaprendizaje y resolución de problemas**. Ante la limitación de cuentas empresariales, diseñé este puente técnico que hoy funciona como un sistema de BI profesional.

---
**Desarrollado por:** DAVID SANTIAGO VELASQUEZ LASPRILLA
