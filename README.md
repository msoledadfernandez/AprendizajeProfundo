# AprendizajeProfundo

### Integrantes:

#### BORNANCINI, Veronica
#### FERNANDEZ, Maria Soledad
#### LOTO, Patricia
#### OLARIAGA, Sandra

**Este repositorio contiene:**

* el [código](https://github.com/msoledadfernandez/AprendizajeProfundo/tree/main/experiment) en donde se han analizado y modelado Redes Neuronales de tipo **Perceptrón Multicapa** (**MLP**) y **Convulsionales** (**CNN**). 
* [documento pdf](https://drive.google.com/file/d/1z2Jyl6WJHwiw0J6o0E4loYz6O28IZBt3/view) con los experimentos realizados con cada tipo de red neuronal junto con sus hiperpárametros y resultados correspondientes.

Los resultados de los experimentos utilizando MLP se encuentran en [mlrunsMLP](https://drive.google.com/file/d/13wxlh7DO11PZBOKDP0--OMsrs8sApoU3/view?usp=sharing)
y los resultados utilizando CNN se encuentran en [mlrunsCNN](https://drive.google.com/file/d/1oZNxKjFs0E7u9NMMHJffwV9DB444xVWT/view?usp=sharing).

### **Conclusiones**
Podemos observar como comportamiento general que cuando la métrica balance accuracy aumenta, la pérdida de validation y train disminuyen. Si validation loss es mayor que training loss podemos decir que es posible que existe algún tipo de sobreajuste, en cambio si validation loss es menor que training loss puede que exista desajuste en el modelo. Por lo tanto, el objetivo es hacer que la validation loss sea lo más pequeña posible.
Una pérdida o loss es un valor que indica cuán mala fue la predicción del modelo en un solo ejemplo. Una pérdida o loss alto hace referencia a una mala predicción para cualquier modelo. La pérdida se calcula sobre la base del entrenamiento y la validación y su interpretación es cuán bien está funcionando el modelo para estos dos conjuntos. A diferencia de la precisión, una pérdida no es un porcentaje.
El train loss es el error en el conjunto de datos de entrenamiento. Validation loss es el error después de ejecutar el conjunto de datos de validación a través de la red entrenada. Train / valid es la relación entre los dos. Si bien no pudimos utilizar muchas épocas por la limitación de recursos podemos concluir que a medida que aumentan las épocas, disminuyen tanto el error en la validación como en el entrenamiento.

