# Code for Application of Natural Language Processing and Deep Learning Models for the Detection of Mental Health Disorders in Social Networks

Kristell Urueta and José Márquez


#### Abstract— This study shows the use of Artificial Intelligence (AI) techniques and advanced trained models to analyze emotions expressed in social network texts, focusing on their relationship with mental health disorders. Using the NLTK library and algorithms such as VADER in Python, a natural language processing model is implemented to classify messages into specific emotional categories: positive, negative and neutral. Messages classified as negative are filtered for a more detailed study of the concerns and adverse emotions expressed. Additionally, the Latent Dirichlet Allocation (LDA) model is employed for thematic segmentation of the data, identifying patterns and themes prevalent in negative messages. This combined methodology provides a comprehensive understanding of the emotions and concerns manifested in the texts, facilitating the inference of possible underlying mental states. To enrich the analysis, it integrates with OpenAI's GPT-3.5 and GPT-4.0 API, offering advanced and contextualized interpretations of the connection between identified themes and associated emotions. This approach presents itself as a valuable tool for psychology and psychiatry, particularly for monitoring and analyzing mental health indicators in digital communications.

#### Index Terms— Bidirectional Encoder Representations from Transformers (BERT), Latent Dirichlet Allocation (LDA), TF-IDF, Natural Language Processing (NLP), Topic Modeling, VADER Sentiment Analysis.


![paper_resumen (1)](https://github.com/user-attachments/assets/984e7106-ab78-4a84-8e0f-dde8b451dabf)

<!-- Resources and extra documentation for the manuscript "Application of Natural Language Processing and Deep Learning Models for the Detection of Mental Health Disorders in Social Networks" published in IEEE Latin America Transactions. -->


## Instructions for running

**Environment Setup:**

It is recommended to use Google Colab for running this notebook to avoid environment conflicts and simplify access to Google Drive storage.
If using Google Colab, mount your Google Drive:


```python
from google.colab import drive
drive.mount('/content/drive')
```

**Data Setup:**
Place your dataset in the appropriate Google Drive directory (e.g., /MyDrive/Maestria2024/TESIS_AVANCES/paper).
Ensure that the dataset is accessible from the notebook.

**Execution:**

Navigate to the directory where the dataset is stored:

```bash
%cd /content/drive/MyDrive/...
```

Run the notebook cells sequentially to perform data loading, cleaning, and analysis.


## Requirements

* **Python 3.8+:** The code uses features and libraries that are compatible with Python 3.8 and above.

* **Libraries:** Ensure the following libraries are installed:

  - pandas
  - nltk
  - scikit-learn
  - matplotlib
  - seaborn
  - xlrd
  - openpyxl
  - cohere
  - tiktoken
  - gensim
  - openai
  - transformers
  - torch
  - vaderSentiment

You can install all required libraries with the following command:

```bash
pip install pandas nltk scikit-learn matplotlib seaborn xlrd openpyxl cohere tiktoken gensim openai transformers torch vaderSentiment
```

## Screenshots
<img width="492" alt="cake-clasification" src="https://github.com/user-attachments/assets/78bf612b-a270-4d8b-8b95-f17ad178ab8f">

![download](https://github.com/user-attachments/assets/b3efb150-034a-4b57-a13d-86ec4e47e08f)

![results](https://github.com/user-attachments/assets/951cab9f-03f8-46c6-913e-11a170ad3d02)

