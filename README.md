# 🧠 Auriculoterapia-AI

Proyecto personal para crear una **biblioteca digital de puntos de auriculoterapia** y un prototipo de diagnóstico con visión por computadora.

## 📌 Funcionalidad actual
- Detecta una oreja en una foto con OpenCV.
- Escala un **mapa estándar de puntos** (JSON) a la oreja detectada.
- Dibuja los puntos en la imagen y exporta sus coordenadas absolutas en `puntos_detectados.json`.

## 🚀 Próximos pasos
- Ampliar `mapa_puntos.json` con los 200+ puntos (OMS + Nogier + China).
- Soporte para orejas derecha/izquierda.
- Agregar OCR para leer anotaciones de atlas.
- Implementar red neuronal para sugerir diagnósticos basados en fotos reales.

## ⚠️ Nota
Este proyecto es **experimental y de uso personal/investigación**.  
No debe usarse como sustituto de diagnóstico médico profesional.
