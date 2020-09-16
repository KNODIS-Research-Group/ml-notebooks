---
marp: true
theme: uncover   
paginate: true
---

# Introducción al *machine learning*

---

![bg](images/ml-everywhere.jpg)

---

## ¿Qué NO es el *machine learning*?

---

![bg](images/terminator.jpg) 
![bg](images/hal9000.jpg)

---

![bg vertical](images/robots.jpg) 

---

## ¿Qué es el *machine learning*?

---

El *machine learning* es estadística disfrazada

![w:500](images/ml-as-statistics.jpg)

---

*Machine learning* = algorítmica + matemáticas

![w:500](images/algorithms-join-maths.jpg)

---

¿*Machine learning*?

![w:450](images/stir-the-pile.png)

---

Una mejor denominación para *machine learning* es *learning from data*.

![w:500 bg right](images/butterfly-car.jpg)

---

1. Sin **datos** no hay **aprendizaje**
2. Sólo se **aprende** lo que está en los **datos**

![w:500 bg left](images/ml-bar.jpg)

---

## ¿Por qué ~~queremos~~ necesitamos el *machine learning*?

---

![bg contain](images/2019-in-1min.jpg)

---

![bg](images/a-day-in-data.jpg)

---

### ¿Por qué?

- Necesitamos obtener conocimiento de grandes volúmenes de datos
- Los ordenadores son muy buenos calculando:
  - Velocidad de ejecución
  - No incorporan sesgos
  - No se cansan, trabajando 24/7
  - Precisión en los cálculos

---

### Algunas aplicaciones

- Visión por computador
  - Conducción autónoma, detección de cáncer, ...

- Reconocimiento del habla
  - Siri, Alexa, OK Google, ...

- Procesamiento del lenguaje natural
  - Traducción automática, chat bots, ...

- Detección de patrones
  - Sistemas de recomendación, detección de fraude, análisis de comportamiento en webs, ...

---

El *machine learning* es una disciplina de la **inteligencia artificial**

![](images/ml-in-ai.png)

---

Dos enfoques:

![](images/supervised-vs-unsupervised.png)

---

![bg contain](images/supervised-learning.png)

---

![bg contain](images/unsupervised-learning.png)

---

![bg contain](images/classical-ml.jpg)

---

![bg contain](images/sklearn-flowchart.jpg)

---

## Proyectos *machine learning*

---

Nomenclatura de un *dataset*:

| Feature 1       | Feature 2       | ... | Feature N       | Label   |
| --------------- | --------------- | --- | --------------- | ------- |
| Observation 1,1 | Observation 1,2 | ... | Observation 1,N | Label 1 |
| Observation 2,1 | Observation 2,2 | ... | Observation 2,N | Label 2 |
| ...             | ...             | ... | ...             | ...     |
| Observation M,1 | Observation M,2 | ... | Observation M,N | Label M |

---

*Dataset* de ejemplo:

| Latitude   | Longitud   | Timestamp  | Temperature   |
| ---------- | ---------- | ---------- | ------------- |
| 40,3214873 | -3,8123123 | 1587980647 | 18,3          |
| 18,9230112 | 15,2394502 | 1587984567 | 6,4           |
| ...        | ...        | ...        | ...           |
| -7,2321231 | 10,7234433 | 1587968742 | 25,7          |

---

El proceso de la ciencia de datos

![](images/data-sciences-process.png)

---

*Machine learning* paso a paso:

![](images/ml-steps.png)

---

Proceso de evaluación:

![](images/train-test.png)

---

Conseguir el modelo perfecto:

![](images/overfitting-undefitting.png)