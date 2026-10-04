# ComfyUI Generative Workflows & Automation

Este repositorio contiene flujos de trabajo (*workflows*) basados en nodos diseñados y optimizados en **ComfyUI**, enfocados en la automatización y generación de contenido mediante Inteligencia Artificial Generativa.

## 🛠️ Tecnologías y Modelos Utilizados
- **Interfaz:** ComfyUI (Estructura de ejecución basada en grafos de nodos).
- **Modelos Base:** Stable Diffusion XL (SDXL Base).
- **Controladores:** ControlNet (Guía estructural avanzada para consistencia visual).
- **Procesamiento Técnico:** KSampler para el control de pasos (*steps*), reducción de ruido (*denoise*) y configuración de muestreadores (*samplers*).

## 📁 Estructura del Proyecto
- `Unsaved_Workflow.json`: Flujo de Texto a Imagen (Text-to-Image) integrado con ControlNet para el condicionamiento de imágenes latentes estables.

## 🚀 Enfoque de Desarrollo e Integración (Backend)
Como desarrolladora de software, este enfoque de nodos me permite abstraer la lógica interna de los modelos generativos para su posterior automatización. El archivo JSON exportado está estructurado en formato compatible con la **API de ComfyUI**, permitiendo que este pipeline pueda ser consumido e iterado dinámicamente mediante scripts de **Python**, automatizando la inyección de prompts y controlando los parámetros de renderizado sin necesidad de interactuar con la interfaz gráfica.
