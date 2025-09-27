# 🏞 Opiniones de TripAdvisor sobre Lugares Turísticos en Guanajuato  

Este proyecto analiza **cientos de opiniones de turistas en TripAdvisor** sobre los principales atractivos turísticos de Guanajuato, México.  
A través de técnicas de **ciencia de datos, procesamiento de lenguaje natural (NLP) y visualización estadística**, se identifican patrones en las calificaciones, diferencias entre visitantes nacionales e internacionales, y se descubren los temas más relevantes mencionados por los usuarios.  

---

## 🎯 Objetivos del proyecto
- Explorar cómo perciben los turistas los principales sitios de Guanajuato.  
- Comparar opiniones entre **grupos demográficos**: hombres vs. mujeres, jóvenes vs. adultos, nacionales vs. internacionales.  
- Detectar **lugares más polémicos** y **lugares mejor valorados**.  
- Extraer **tópicos y palabras clave** en reseñas positivas y negativas.  
- Analizar la **evolución temporal** de las opiniones.  

---

## 🛠 Técnicas y herramientas utilizadas
- **Preprocesamiento de texto** con `NLTK` (tokenización, eliminación de stopwords en español e inglés).  
- **Modelado de texto con TF-IDF** para representar las opiniones en bolsas de palabras.  
- **Selección de características con Chi-cuadrado** para identificar los términos más relevantes.  
- **Visualización de datos** con `matplotlib`: histogramas de edades, calificaciones y distribución por grupos.  
- **Nubes de palabras** para opiniones generales y negativas.  
- **Análisis de tópicos con LSA (Latent Semantic Analysis)** para descubrir temas latentes en subgrupos de turistas.  
- **Comparaciones demográficas**:  
  - Nacionales vs. Internacionales  
  - Hombres vs. Mujeres  
  - Jóvenes (<40 años) vs. Adultos (≥40 años)  
- **Análisis temporal**: cambios en las opiniones antes y después de 2015.  

---

## 📊 Principales hallazgos
- El **Museo de las Momias** es el sitio más polémico: combina opiniones muy positivas con reseñas negativas extremas.  
- El **Teatro Juárez** destaca como el lugar más valorado, especialmente por mujeres y jóvenes, alcanzando promedios cercanos a 4.7/5 sin opiniones negativas relevantes.  
- Las quejas más comunes incluyen percepciones de lugares “sobrevalorados” y problemas de “basura/suciedad”.  
- Los aspectos más apreciados fueron la **arquitectura histórica**, la **importancia cultural** y la **experiencia visual** de los sitios.  
