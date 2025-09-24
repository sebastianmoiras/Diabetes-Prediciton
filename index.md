## Project Description
This project implements a **neural network model** to predict whether a patient has diabetes based on medical attributes.  
The goal is to showcase the application of **deep learning in healthcare**, turning structured patient data into actionable predictions that can assist in **early detection and prevention**.  

In addition, the project compares the performance of two Keras modeling approaches:

- **Sequential API** – a straightforward, layer-by-layer model.  
- **Functional API** – a more flexible approach that allows complex architectures (e.g., skip connections, multi-input).  

This comparison highlights how **architecture choices** can affect model accuracy, generalization, and training efficiency.  

---

**Dataset Sample (Input Features)**  
![Dataset Sample](/assets/diabetes-sample.png)

---

## Result

---

### Sequential API Evaluation
Accuracy and loss curve for Sequential model training:

![Sequential Result](/assets/sequential_result.png)  
![Sequential Loss Curve](/assets/loss_sequential.png)

---

### Functional API Evaluation
Accuracy and loss curve for Functional model training:

![Functional Result](/assets/functional_result.png)  
![Functional Loss Curve](/assets/loss_functional.png)

---

## Analysis
From both models, only minor differences were observed:  

- **Precision** on the Functional API model is about **1% higher**.  
- **Recall and AUC** on the Sequential API model are about **0.5% higher**.  
- For other metrics such as **loss and accuracy**, there are no significant differences.  

From the visualization graphs and evaluation results, we can conclude that the model has successfully learned to predict diabetes cases with reasonable performance.  
The **train loss and validation loss are closely aligned**, which indicates a **good fit** (not overfitting).  

---

## Tech Stack
- **NumPy, Pandas, Scikit-learn**
- **TensorFlow / Keras** 
- **Matplotlib, Seaborn** 
