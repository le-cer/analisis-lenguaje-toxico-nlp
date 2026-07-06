# Análisis del Lenguaje Tóxico en Español con BERT 🚀

### 📝 Descripción del Proyecto
Este proyecto resuelve la necesidad de detectar, moderar y clasificar contenido tóxico o abusivo en plataformas digitales e internacionales en español. La solución aborda un desafío crítico en la lingüística computacional: la **desambiguación semántica** y el tratamiento de la **variación lingüística** regional.

### 🛠️ Stack Tecnológico
* **Lenguaje:** Python
* **Modelos:** BERT (Fine-tuning de modelo preentrenado para español / Beto)
* **Librerías Core:** Transformers (Hugging Face), scikit-learn, Pandas, NumPy, Core NLP.

### 📊 Características Técnicas & Enfoque Lingüístico
* **Tratamiento de Corpus:** Preprocesamiento avanzado de texto, normalización de modismos y manejo de sesgos contextuales.
* **Métricas Logradas:** **87% de precisión** en la clasificación de comentarios complejos en entornos UGC (User Generated Content).
* **Desambiguación:** Reducción drástica de falsos positivos en textos donde el lenguaje coloquial o la ironía suelen confundir a los clasificadores estadísticos tradicionales.

### 📁 Estructura del Repositorio
* `/data`: Muestras o especificaciones del corpus (respetando privacidad).
* `/notebooks`: Jupyter Notebooks con la exploración de datos (EDA) y el entrenamiento del modelo.
* `/src`: Scripts de producción para tokenización y predicción en tiempo real.

---
*Proyecto desarrollado como parte de la especialización práctica en Inteligencia Artificial y NLP.*