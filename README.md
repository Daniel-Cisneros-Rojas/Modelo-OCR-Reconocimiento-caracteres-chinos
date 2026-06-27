## OCR de Caracteres Chinos Manuscritos (50 clases)
# Descripción

Este proyecto implementa un sistema de Reconocimiento Óptico de Caracteres (OCR) para caracteres chinos simplificados escritos a mano, utilizando TensorFlow y Deep Learning con Transfer Learning.

El modelo es capaz de clasificar 50 caracteres chinos comunes pertenecientes a categorías como animales, profesiones, objetos cotidianos, naturaleza y más.

Incluye todo el pipeline completo:

Generación de dataset sintético
Aumento de datos (data augmentation)
Entrenamiento con EfficientNetV2B0 / MobileNetV3Small
Entrenamiento en dos fases (feature extraction + fine-tuning)
Exportación del modelo y etiquetas

## Colab (entrenamiento completo)

Puedes ver y ejecutar el proyecto completo en Google Colab:

# https://colab.research.google.com/drive/1ZEByeOQKmgCP3-OQg_UmRPAjIPt2322e?usp=sharing

## Modelo en carpeta export_model

model.keras → modelo entrenado listo para inferencia

labels.json → lista de 50 caracteres en orden correcto del modelo

metadata.json → información adicional (hanzi, pinyin, significado)

<img width="574" height="668" alt="image" src="https://github.com/user-attachments/assets/bbcf3d4d-0a78-45f6-a794-fa107bee7d66" />

<img width="485" height="648" alt="image" src="https://github.com/user-attachments/assets/05b1926d-9b5a-4cfb-a780-442cbf423210" />

<img width="482" height="645" alt="image" src="https://github.com/user-attachments/assets/fe66f884-9ca8-4ab9-9944-77873a1512ba" />




