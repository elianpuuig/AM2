¡Ah, excelente aclaración! Si el repositorio AM2 va a ser tu portafolio para toda la cursada, entonces el README.md principal tiene que funcionar como un "índice" de la materia, donde vas a ir sumando cada trabajo práctico.

Acá tenés el nuevo README.md adaptado para que sea la portada de toda tu materia.

Copiá esto, pegalo en GitHub usando el botón "Add a README" (como vimos en el paso anterior para destrabar la rama) y dale a Commit.

🤖 AM2 - Aprendizaje Automático II
Autor: Elián Puig | Estudiante de Ciencia de Datos e Inteligencia Artificial
Repositorio: Trabajos Prácticos y Proyectos de la materia Aprendizaje Automático II.

Este repositorio contiene las implementaciones, análisis y modelos predictivos desarrollados durante la cursada, enfocados principalmente en el uso de Deep Learning y PyTorch.

📁 Índice de Trabajos Prácticos
📌 TP1: Predicción Inmobiliaria (Sindian City) con PyTorch
Estado: Completado ✅ | Archivo: TP1_Aprendizaje_Automatico_II.ipynb

Implementación de redes neuronales profundas (Perceptrón Multicapa) para predecir el valor de propiedades en Taiwán. El proyecto se centra en la demostración empírica de las zonas de ajuste de un modelo mediante distintas arquitecturas:

Underfitting (Subajuste): Arquitectura limitada de 6 -> 2 -> 1.

Overfitting (Sobreajuste): Red profunda sin regularización que memoriza el dataset.

Modelo Óptimo: Arquitectura balanceada (6 -> 64 -> 32 -> 1) controlada mediante Dropout, regularización L2 y un scheduler de aprendizaje dinámico (ReduceLROnPlateau).

Conclusión Clave de Negocio:
El modelo óptimo logró un MAE de 4.95, lo que se traduce (desescalando los datos originales) en un margen de error de ~49.500 NT$ por Ping (unidad de superficie taiwanesa). Al compararlo con modelos lineales de la materia anterior (AA1), se demostró empíricamente que para datasets tabulares pequeños (~400 registros), los modelos simples y lineales tienden a generalizar mejor que el Deep Learning.

(Los próximos trabajos prácticos de la materia se irán agregando a este índice)

🛠️ Stack Tecnológico de la Materia
Framework principal: PyTorch

Machine Learning Clásico: Scikit-Learn

Manipulación de Datos: Pandas, NumPy

Visualización: Plotly, Matplotlib
