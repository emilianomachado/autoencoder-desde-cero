# Autoencoder desde Cero

Implementación de un **Autoencoder** utilizando Python en Google Colab.  
Este proyecto muestra cómo construir, entrenar y analizar un autoencoder básico sin utilizar frameworks de redes neuronales avanzados, con el objetivo de comprender profundamente su funcionamiento interno.

---

## 🧠 ¿Qué es un Autoencoder?

Un **Autoencoder** es una red neuronal que aprende a **comprimir (codificar)** los datos a un espacio de menor dimensión y luego **reconstruirlos (decodificar)**.  

Su objetivo principal es aprender representaciones internas útiles de los datos, por ejemplo:

- Reducción de dimensionalidad  
- Eliminación de ruido (Denoising Autoencoders)  
- Compresión  
- Extracción de características  
- Representaciones latentes

Un Autoencoder consta de:

- **Encoder** → reduce la dimensionalidad  
- **Latent space** → representación comprimida  
- **Decoder** → intenta reconstruir la entrada original  

El entrenamiento se basa en minimizar el error entre la entrada y la salida reconstruida.

---

## 📂 Contenido del proyecto

Este repositorio incluye:

- `Autoencoders.ipynb`  
  Notebook con:
  - Implementación del autoencoder
  - Definición del encoder y decoder
  - Función de costo y optimización
  - Entrenamiento paso a paso
  - Gráficos y visualización de resultados
  - Ejemplos de compresión y reconstrucción

---

## 🚀 ¿Cómo ejecutar el proyecto?

1. Abrí el notebook en Google Colab.  
2. Ejecutá todas las celdas en orden.  
3. Podés modificar parámetros como:
   - Dimensión de la capa latente
   - Funciones de activación
   - Épocas de entrenamiento
   - Dataset utilizado
   - Tasa de aprendizaje

Esto te permite experimentar con distintas arquitecturas y niveles de compresión.

---

## 🛠 Requisitos

Este notebook puede ejecutarse directamente en Google Colab, sin instalaciones adicionales.

Librerías utilizadas:

- NumPy  
- Matplotlib  
- (Opcional) Otros módulos estándar de Python para graficar o manipular datos.

---

## 📈 Resultados

El notebook permite visualizar:

- Diferencia entre entrada y salida reconstruida  
- Evolución de la función de costo  
- Representación latente comprimida  
- Efecto de diferentes arquitecturas en la calidad de reconstrucción  

---

## 🧪 Conceptos clave implementados

- Codificación y decodificación  
- Representación latente  
- Redes neuronales simétricas  
- Función de reconstrucción  
- Entrenamiento no supervisado  
- Compresión mediante aprendizaje automático  

---

## 📄 Licencia

Este proyecto es de uso libre para estudio y experimentación.

---

## ✨ Autor

Proyecto realizado por **Emiliano Machado** como parte del estudio de redes neuronales y modelos de representación.
