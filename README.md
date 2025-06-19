# Animal Recogniser

Animal Recogniser es un proyecto de clasificación de imágenes de animales utilizando machine learning y deep learning en Jupyter Notebooks. El sistema es capaz de identificar animales en 10 clases diferentes. Este repositorio contiene cuatro notebooks, cada uno explorando diferentes técnicas para mejorar la precisión del clasificador.

## Estructura del Proyecto

El repositorio incluye los siguientes archivos:

1. **Clasificador básico**  
   - Implementa un modelo de clasificación estándar.
   - Precisión alcanzada: **86.25%**.

2. **Clasificador con búsqueda automática de hiperparámetros**  
   - Añade un tuner para optimizar los hiperparámetros del modelo automáticamente, buscando la mejor configuración posible.

3. **Clasificador con Data Augmentation**  
   - Incluye técnicas de aumento de datos para mejorar la robustez y generalización del modelo.

4. **Clasificador con modelo preentrenado de TensorFlow**  
   - Utiliza un modelo preentrenado de TensorFlow (transfer learning) para aprovechar características previamente aprendidas y mejorar la precisión.

## Requisitos

- Python 3.x
- Jupyter Notebook
- TensorFlow
- Keras
- NumPy, Matplotlib, y otras dependencias estándar para machine learning

Instala las dependencias ejecutando:

```bash
pip install tensorflow keras numpy matplotlib
```

## Cómo usar

1. Clona este repositorio:
    ```bash
    git clone https://github.com/<usuario>/Animal-Recogniser.git
    cd Animal-Recogniser
    ```

2. Abre los notebooks en Jupyter:
    ```bash
    jupyter notebook
    ```
    y selecciona uno de los archivos `.ipynb` para comenzar.

3. Sigue las instrucciones dentro de cada notebook para ejecutar el clasificador correspondiente.

## Descripción de las clases

El modelo está preparado para reconocer 10 clases diferentes de animales. Puedes modificar las clases o el dataset según tus necesidades.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o pull request para sugerencias o mejoras.

## Licencia

Este proyecto está bajo una licencia MIT. Consulta el archivo `LICENSE` para más detalles.
