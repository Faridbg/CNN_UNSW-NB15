# CNN_UNSW-NB15
 DISEÑO Y EVALUACIÓN DE REDES NEURONALES CONVOLUCIONALES PARA UN SISTEMA DE DETECCIÓN DE INTRUSIONES.
## Descripción 🚀
Año a año, las comunicaciones entre equipos, personas, corporaciones, gobiernos o todo aquello que use cualquier mecanismo moderno para comunicarse con otra entidad ha crecido de manera exponencial. Vivir comunicados en un mundo globalizado es indispensable. Debido a ello, cada vez es más notorio la importancia de salvaguardar la seguridad de las comunicaciones frente al continuo crecimiento de los ataques cibernéticos. Estos ataques, día a día mejoran, se fortalecen y se hacen más difícilmente detectables frente a los equipos de ciberseguridad. Entre esos equipos, el IDS es materia de nuestro interés, siendo una herramienta fundamental para la detección de intrusiones en la red. Dicho equipo, a pesar de sus diversos beneficios, presenta ciertas carencias en algunos aspectos, entre la que destaca el alto ratio de falsos positivos que genera. Por ello, se vio necesario la utilización de otros mecanismos para paliar dicha carencia. Como resultado, este estudio pretende utilizar como IDS una red neuronal convolucional que mejore el resultado de los falsos positivos que vienen arrastrando los IDS tradicionales. Además, se evalúa nuestra red con otras dos redes neuronales: una red MLP y otra LSTM. Adicionalmente, se usan diferentes técnicas para procesar el set de datos que utilizamos (UNSW-NB15) para entrenar la red neuronal convolucional. Los resultados de este estudio reflejan una mejora notable en la tasa de falsos positivos con respecto a otras redes y estudios realizados, una mejora en la clasificación multiclase y una buena eficiencia de entrenamiento por parte de la red.

### Pre-requisitos 📋

Tener descargado en el Google Drive los ficheros:

* [UNSW_NB15_training-set.csv](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/) 
* [UNSW_NB15_testing-set.csv](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/) 

### Instalación 🔧

_Se requiere vincular la cuenta de Google Drive a Google Colab_

```
from google.colab import drive
drive.mount('/content/drive')
```

## Construido con 🛠️

* [Google Colab](https://colab.research.google.com/) - Entorno de ejecución y programación en Python en el navegador.



