# CloudsDL

Proyecto de práctica orientado a optimización de modelos de Deep Learning y Computer Vision para despliegue en hardware Edge (NVIDIA Jetson y similares). Cubre el pipeline completo: entrenamiento, exportación/optimización y (más adelante) inferencia en tiempo real.

## Dataset

[Cloud Dataset (UCI)](https://archive.ics.uci.edu/dataset/155/cloud) — usado para clasificación de nubes.

## Etapa actual: clasificación de nubes con TensorFlow → ONNX

El primer objetivo es entrenar un modelo de clasificación de nubes con **TensorFlow** y exportarlo a formato **ONNX**. El resto de los temas (abajo) se abordarán una vez esta etapa esté completa.

## Roadmap de temas

1. Optimizando modelos de Deep Learning
2. Optimizando modelos de Computer Vision
3. NVIDIA Jetson
4. TensorRT
5. ONNX
6. OpenCV
7. PyTorch/TensorFlow
8. Docker
9. Optimización de inferencia en hardware con restricciones reales
