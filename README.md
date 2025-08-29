# Proyecto_Sprint6

# Proyecto Integrado — Análisis de Ventas de Videojuegos

Este repositorio contiene el notebook **`notebook.ipynb`, en el que se realiza un **análisis exploratorio de datos (EDA)** sobre un conjunto de **ventas de videojuegos** por plataformas, géneros y regiones, así como algunas **pruebas estadísticas** y visualizaciones para responder preguntas de negocio.

> El notebook incluye secciones de limpieza, transformación, visualización y (en menor medida) contraste de hipótesis.

---

## 🧭 Estructura principal del notebook

- **2. Preparar los datos**
  - Conversión de **nombres de columnas a minúsculas**.
  - Conversión de **tipos de datos** adecuados (fechas, numéricos, categóricos).

- **3. Analizar los datos**
  - **Cálculo de ventas totales** y por segmento.
  - **Juegos lanzados por año** (tendencias temporales).
  - **Plataformas con mayores ventas** y **distribución por año** (incluye el “tiempo de vida” de cada plataforma y plataformas vigentes).
  - **Ventas globales** y por región.
  - **Efecto de reseñas de usuarios y críticos** sobre ventas en una plataforma específica (ej.: Wii).
  - **Distribución por género** y **perfiles por región**.
  - **Clasificación ESRB** por región.

- **Pruebas de hipótesis**
  - Diferencias en **calificaciones promedio** entre **Xbox One** y **PC**.
  - Diferencias en calificaciones de usuarios entre **Acción** y **Deportes**.

- **Conclusiones generales**

> El cuaderno utiliza ampliamente **Pandas**, **NumPy**, **Seaborn** y **Matplotlib** para el análisis y las visualizaciones (≈36 llamadas a funciones de trazado).

---

## 📦 Datos


`Name`, `Platform`, `Year_of_Release`, `Genre`, `Publisher`, `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`, `Global_Sales`, `Critic_Score`, `User_Score`, `Rating (ESRB)`, etc.  
Ajusta los nombres si difieren en tu archivo.


---

## 🧪 Librerías utilizadas

El notebook importa principalmente:
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **scipy** (para funciones estadísticas)


---

## 📊 Salidas y Visualizaciones

Incluye múltiples visualizaciones (histogramas, distribuciones temporales, comparativas por plataforma/género/región). Puedes adaptar el estilo de gráficos y temas de `seaborn` según tus preferencias.

---

## 🧠 Hipótesis de ejemplo (adaptar si cambiaste el dataset)

- **H1:** No hay diferencia significativa entre las **calificaciones promedio** de **Xbox One** y **PC**.  
- **H2:** Las **calificaciones de usuarios** para juegos de **Acción** difieren de las de **Deportes**.

---

## 🧹 Recomendaciones de limpieza / mejoras

- Estandarizar **nombres de plataformas y géneros**.
- Revisar **valores perdidos** y **outliers** (Winsorization o reglas de negocio).
- Documentar las reglas para **agregaciones por región** y **cálculo de global_sales**.
- Centralizar funciones de preparación (helpers) si planeas reutilizar código.

---

## 📝 Licencia

Este proyecto se distribuye bajo la licencia que tú definas (ej.: MIT).  
Incluye un archivo `LICENSE` si lo harás público.

---

## 🙌 Agradecimientos

- Dataset público de ventas de videojuegos (común en cursos y ejercicios de EDA).
- Bibliotecas de la comunidad científica de Python.

---

### ✍️ Notas del autor
Si deseas, agrega una sección breve con el contexto (curso/sprint/empresa), tus hallazgos clave y próximos pasos (p. ej., modelos de predicción de ventas o segmentación por comportamiento).
