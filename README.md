# End to end Text-Summarizer-Project

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. update the conponents
6. update the pipeline
7. update the main.py
8. update the app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/entbappy/End-to-end-Text-Summarization
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n summary python=3.8 -y
```

```bash
conda activate summary
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```


```bash
Author: Sai Kiran
Email: ksaikiran247@gmail.com

```
##Process of data flow and prediction of the user input

1. **Data Ingestion**: This is the process of gathering the data that will be used for training and testing your text summarization model. It involves acquiring the raw text data from various sources such as files, databases, or APIs.

2. **Data Transformation**: Once you have the raw data, you need to preprocess and transform it into a format suitable for your model. This includes tasks like tokenization (breaking text into words or phrases), cleaning (removing unnecessary characters or formatting), and possibly feature extraction (converting text into numerical representations).

3. **Data Validation**: This step ensures that your data is clean, accurate, and ready for training. It may involve checking for missing values, handling outliers, and splitting the data into training and testing sets to assess model performance.

4. **Model Evaluation**: Before deploying your model, it's crucial to evaluate its performance. This involves using metrics like accuracy, precision, recall, or specific metrics tailored to text summarization, such as ROUGE scores (Recall-Oriented Understudy for Gisting Evaluation).

5. **Model Training**: This step involves feeding your preprocessed data into a chosen machine learning or deep learning model. The model learns patterns from the data to create summaries of text inputs.

6. **Prediction and FastAPI**: After training, your model can make predictions on new text inputs. FastAPI, a Python web framework, facilitates serving your model predictions as an API. This allows other applications or users to send text inputs and receive summaries in response.

Each step plays a critical role in developing and deploying a text summarizer, ensuring that the model is accurate, efficient, and ready for real-world applications.
