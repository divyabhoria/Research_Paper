# Research_Paper
 How Much Data Do Transformers Need? A Scaling Analysis of DistilBERT for Fake News Detection

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/divyabhoria/Research_Paper.git
cd Research_Paper
```

### 2. Install Required Dependencies

```bash
pip install numpy pandas scikit-learn tensorflow transformers matplotlib seaborn jupyter
```


### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```


### 4. Run the Notebooks (in the following order)

#### Step 1: Classical Machine Learning Models

Open and run:

```
Machine Learning .ipynb
```

This notebook performs preprocessing and trains Logistic Regression, SVM, and Random Forest.


#### Step 2: Deep Learning Model (LSTM)

Open and run:

```
Deep Learning LSTM.ipynb
```

This notebook handles tokenization, sequence padding, and trains the LSTM model.


#### Step 3: Model Comparison

Open and run:

```
comparison of models .ipynb
```

This notebook compares all models and generates evaluation graphs.


#### Step 4: DistilBERT Experiments

Run each notebook separately:

```
distilBERT trained at 1000 samples.ipynb
distilBERT trained at 3000 samples.ipynb
distilBERT trained at 5000 samples.ipynb
```

These notebooks fine-tune DistilBERT on different dataset sizes and analyze performance scaling.


### 5. Important Notes

* Ensure the WELFake dataset file is present in the project directory before running the notebooks.
* Execute cells sequentially from top to bottom in each notebook.
* All experiments are configured to run on CPU; training time may vary depending on system performance.
