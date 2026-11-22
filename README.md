# 🌐 Traductor Multimodal (EN ↔ ES) con Transformers

Este repositorio contiene la implementación de un sistema de traducción automática multimodal (texto e imágenes) entre inglés y español, desarrollado como parte del análisis práctico de mecanismos de atención y arquitecturas Transformer.

## 🚀 Características
- **Traducción de Texto:** Traducción bidireccional (Inglés ↔ Español) en tiempo real.
- **Traducción de Imágenes (OCR):** Extracción y traducción automática de texto contenido en imágenes.
- **Interfaz Interactiva:** Despliegue web amigable desarrollado con Gradio.

## 🛠️ Tecnologías Utilizadas
- **Deep Learning:** PyTorch
- **Modelos NLP:** Hugging Face `transformers` (Modelos MarianMT de Helsinki-NLP)
- **Visión Artificial:** EasyOCR
- **Interfaz Web:** Gradio

## 📁 Contenido del Repositorio
- `R2-A3-S12_Transformers.ipynb`: Notebook de Google Colab con el código fuente completo y funcional.
- `R2-A3-S12_Transformers.pdf`: Documento técnico con la explicación del funcionamiento, resultados y evidencias de ejecución.

## ⚙️ Cómo Ejecutar
1. Abre el archivo `.ipynb` en Google Colab.
2. Asegúrate de tener activada la aceleración por GPU (Entorno de ejecución > Cambiar tipo de entorno de ejecución > T4 GPU).
3. Ejecuta todas las celdas en orden.
4. Al final, el código generará un enlace público (compartido) donde podrás interactuar con el traductor.

---
**Contexto Académico:** Proyecto desarrollado para la asignatura de Deep Learning, demostrando la aplicación práctica de los mecanismos de *Self-Attention* y *Cross-Attention* en problemas de Procesamiento de Lenguaje Natural (NLP).
