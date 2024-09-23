# **Pikabu- A Pokemon identifier based on the image used**

Pikabu is a machine-learning model designed to identify the Pokemon based on the image provided. Currently limited to only three but most popular Pokemons -Pikachu , Bulbasaur, Charmander.

## **Getting Started**

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/AdityaAVG/Pikabu.git
    ```
2. **Navigate to the Project Directory**:
    ```bash
    cd Pikabu
    ```
3. **Set Up a Virtual Environment** (recommended to avoid dependency issues):
    #### **For Linux and macOS**:
```bash
python3 -m venv venv
source venv/bin/activate
```
### For windows
```bash
venv\Scripts\activate
```
4. **Install the Required Libraries**:
    ```bash
    pip install torch pandas numpy matplotlib tensorflow

    ```
5. **Run the Application**:

## **Running on Google Colab**

To run this project on Google Colab, follow these steps:

### **Step 1: Open Google Colab**
1. Go to [Google Colab](https://colab.research.google.com/).
2. Sign in with your Google account.

### **Step 2: Clone the GitHub Repository**
In a new Colab notebook, run the following command to clone the repository:

```python
!git clone https://github.com/AdityaAVG/Pikabu.git
```

### **Step 3: Navigate to repository**
```python
import os
os.chdir('/content/voice_doc')
```
#Install dependencies
```bash
!pip install torch pandas numpy matplotlib tensorflow
```

#Installing the dataset 
```bash
!wget https://www.dropbox.com/scl/fo/oi9huerppteppcz5t5b32/AJ_ykZC9n5AA0BJat_LlnYI?rlkey=uas4cay1272poo2jc6gf0n5rp&e=2&st=7v2lw3ud O -data
```


#Run



---

## **Tech Stack**

- **Python**: Core language for data processing and application building.
- **Pandas**: Handles data manipulation and feature storage.
- **Tensorflow**: For building Neural Network 

---

## **Dataset**

The dataset used for training is the [Pokemon Dataset](https://www.dropbox.com/scl/fo/oi9huerppteppcz5t5b32/AJ_ykZC9n5AA0BJat_LlnYI?rlkey=uas4cay1272poo2jc6gf0n5rp&e=2&st=7v2lw3ud), which contains biomedical voice measurements, including features representing fundamental frequencies, harmonics, and noise measurements.

---


## **Future Improvements**

Add a dataset of more Pokemons to help the model identify a large set of Pokemon.
---

## **References**

- **Pokemon Dataset**: [Link to Dataset](https://www.dropbox.com/scl/fo/oi9huerppteppcz5t5b32/AJ_ykZC9n5AA0BJat_LlnYI?rlkey=uas4cay1272poo2jc6gf0n5rp&e=2&st=7v2lw3ud)

---

## **Contributing**

Contributions are welcome! Please fork this repository and submit a pull request if you'd like to improve the project.

---
