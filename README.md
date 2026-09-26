# Equipo A

Repositorio del **Equipo A** para la entrega del pipeline de **Machine Learning (Proyectos 10, 11 y 12)**.

---

## Casos de Uso Adaptados

---

### Proyecto 10: Limpieza de datos de autos
* **Caso de Uso:** Preparacion de datos de vehiculos usados para analizar precios, kilometraje y caracteristicas.
* **Descripcion:** Limpieza de valores faltantes, normalizacion de texto, transformacion de columnas e identificacion de valores atipicos en precios.
* **Datos:** Dataset de autos incluido en `autos_para_limpieza.csv`.

---
### Proyecto 11: Optimización con GridSearchCV

* **Caso de Uso:** **Diagnóstico de Cáncer de Mama mediante Optimización de Hiperparámetros**
* **Descripción:** Implementación de escalado de datos (`StandardScaler`) y búsqueda exhaustiva con `GridSearchCV` (validación cruzada `cv=5`) sobre un clasificador `SVC` para encontrar la combinación óptima de hiperparámetros (`C`, `kernel` y `gamma`) aplicada al dataset *Breast Cancer Wisconsin*.
* **Resultados:** Comparativa del desempeño entre el modelo `SVC` base y el modelo optimizado, evaluando el incremento en *Accuracy* sobre el conjunto de prueba.


---

### Proyecto 12: Evaluación de Modelos y Métricas (NLP)
* **Caso de Uso:** **Detección Automática de SPAM en Mensajes SMS**
* **Descripción:** Implementación de Procesamiento de Lenguaje Natural (`TF-IDF`) y clasificación supervisada (`SVC`) para identificar mensajes en tiempo real como `spam` (fraude/promoción) o `ham` (legítimo).
* **Resultados:** 
  * **Accuracy:** **~98%** en el conjunto de prueba.
  * **Diagnóstico:** Evaluación detallada mediante Matriz de Confusión y `classification_report`.

---

##  Archivos en este Repositorio

* [`Proyecto 3 Adaptacion Autos.ipynb`](<Proyecto 3 Adaptacion Autos.ipynb>) — Notebook adaptado de limpieza de datos de autos.
* [`autos_para_limpieza.csv`](autos_para_limpieza.csv) — Dataset utilizado por el notebook.
* `Proyecto_10_Caso_Adaptado.ipynb` — *Notebook del Proyecto 10*
* `Proyecto11_GridSearchCV_Adaptado.ipynb` — *Notebook del Proyecto 11*
* `Proyecto12_ClasificacionDeTexto_Adaptado.ipynb` — *Notebook del Proyecto 12 (Filtro SMS)*

---
*Materia: Ciencia de Datos — Laboratorio Práctico*
