<h1 align="center">
  <br>
  <a href="#"><img src="https://raw.githubusercontent.com/minatku/.github/72f5e47ebef5eed3e8b62046d3078bf0b042623a/profile/img/minatku_logo.svg" alt="Markdownify" width="200"></a>
  <br>
  MinatKu
  <br>
  “Temukan Minat Jadilah Hebat!”
</h1>

<img src="https://raw.githubusercontent.com/minatku/.github/80263cc14216a3ede82c281c8fecc70995959434/profile/img/minatku_banner.svg"></img>

## About this project

MinatKu is an application created to fulfil the capstone project in the Bangkit programme. This project was composed by 7 participants from Bangkit 2023 Batch 2, with 3 from Machine Learning, 2 from Mobile Development, and 2 from Cloud Computing.

### Background
MinatKu addresses the issue of students in Indonesia often selecting college majors that do not align with their interests, as evidenced by the Indonesia Career Center Network (ICCN) reporting that 87% of students admitted to this misalignment in 2017. This mismatch between students and their chosen fields has significant adverse effects, including unfulfilled potential, financial burdens, motivation decline, increased stress, career delays, and job market incompatibility. Through a 5 whys analysis, we've identified that poor career guidance and a lack of self-evaluation resources are contributing factors. Additionally, limited facilities and resources hinder a comprehensive understanding of student interests, talents, and career goals.

### Purpose
Our team initiated this project in response to a pressing issue revealed by the Indonesia Career Center Network (ICCN), where 87% of students in Indonesia admitted to selecting college majors misaligned with their interests in 2017. Recognizing the significant impact this misalignment has on individuals and the country's economy. Through a 5 Whys analysis, we identified issues like poor career guidance, a lack of self-evaluation resources, and a misalignment of educational priorities favoring academic curricula over comprehensive career guidance. Our project stems from the desire to address these challenges and empower students to make informed choices for their future.

<h1 align="center">
  <br>
  Machine Learning Implementation
</h1>

# Table of Contents
* [General Info](#general-info)
* [Roadmap](#roadmap)
* [Python Libraries](#python-libraries)
* [Contact](#contact)
* [Documentation](#documentation)

# General Info
This is the machine learning part of CH2-PS229 capstone project called MinatKu. This application will help students to achieve improvement in the alignment between their majors and interests by creating an accessible online career guidance platform and personalized major recommendations from assessments test.

# Roadmap

# Python Libraries
We built the model in Google Colab using the following libraries
* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [TensorFlow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [Scikit Learn](https://scikit-learn.org/stable/)

# Contact
For further information, kindly contact to :
- fhazzami@gmail.com (Fadhil Hadrian/fidelhadrian)
- andininurul83@gmail.com (Nurul Andini/nurandin)
- chinarasiwinugrahani@gmail.com (Chinara Siwi Nugrahani/chinarasiwinugrahani)

# Documentation
## Data Cleaning and Preprocessing Documentation

### Setup

To run this notebook, we will need:

- Python environment
- Jupyter notebook or Google Colab

Install the necessary library using:

```bash
pip install pandas
```

### Usage
1. Open the notebook in a Jupyter environment.
2. Mount Google Drive to access the dataset.
3. Execute each cell in sequence for data cleaning and preprocessing.

### Steps
1. Loading the Dataset
2. Dropping Unnecessary Columns
3. Renaming Columns
4. Creating New Columns
5. Mapping
6. Dropping Original Question Columns
7. Saving to CSV

### Output
The resulting CSV file (RIASEC10Q.csv) can be downloaded using the link provided or through the last cell in the notebook.

## MinatKu Model Documentation

MinatKu is a model developed for predicting academic interests based on a dataset. It uses a neural network implemented with Keras and TensorFlow.

### Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Model Training](#model-training)

### Installation

To use the MinatKu model, follow these steps:

1. Clone the repository or download the `Model MinatKu.ipynb` file.

2. Open the notebook in a Jupyter environment or any compatible platform.

3. Run the notebook to load the required dependencies and train the model.

### Usage

The MinatKu model can be used to predict academic interests based on input features. Here's a brief overview:

- Load the notebook and execute the provided code cells.

- The model is trained on a dataset (`RIASEC12Q.csv`) containing academic interest labels.

- Example predictions are provided for three different academic interest categories: Science, Arts and Literature, and Technology.

### Model Training
The model is trained on the provided dataset with the following architecture:

- Input layer: Dense layer with 128 units and ReLU activation.
- Hidden layer: Dense layer with 64 units and ReLU activation.
- Dropout layer: Dropout with a rate of 0.6.
- Output layer: Dense layer with softmax activation.
- The model is compiled with categorical crossentropy loss and Adam optimizer.

<h1 align="center">
  <br>
  Cloud Computing Implementation
</h1>

![13](https://github.com/minatku/minatku-CC/assets/100481579/4088e023-208c-4fc9-97a8-3ac26f27b34c)


Hello guys!! this is backend from application Minatku
# Table of Contents
* [General Info](#general-info)
* [Roadmap](#roadmap)
* [Python Libraries](#python-libraries)
* Services Used in GCP(#services)
* Cloud Architecture(architecture)
* [Contact](#contact)
* [Documentation](#documentation)

# General Info
This is the Cloud Computing part of CH2-PS229 capstone project called MinatKu. This application will help students to achieve improvement in the alignment between their majors and interests by creating an accessible online career guidance platform and personalized major recommendations from assessments test.

# Roadmap

# Python Libraries
We built the model in Google Colab using the following libraries
* [Flask](https://flask.palletsprojects.com/)
* [SQLAlchemy](https://www.sqlalchemy.org/)
* [Flask-RESTx/Flask-RestPlus](https://flask-restx.readthedocs.io/)
* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [TensorFlow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [Scikit Learn](https://scikit-learn.org/stable/)

# Services Used in GCP
What Services that we use in GCP?
| Google Cloud Services | Platform             |
|------------------------|----------------------|
| Cloud App Engine       | NodeJS (Backend)     |
| Cloud Storage          | Images               |
| Cloud SQL              | Database (MySQL)     |
| Cloud Build            | CI/CD                |

# Cloud Architecture
![MinatKu - CH2-PS229](https://github.com/minatku/minatku-CC/assets/100481579/3da95893-8808-4b68-a81d-2acd887369d0)


# Contact
For further information, kindly contact to :
- mrizki135790@gmail.com (Muhammad Rizki)
- labibhusain147@gmail.com (Mohammad Labib Husain)

# Documentation
## Data Cleaning and Preprocessing Documentation
For the documentation you can visit 
> https://minatku-cp5rxjg6xa-et.a.run.app


<h1 align="center">
  <br>
  Mobile Development Implementation
</h1>

<h1 align="center">
  <br>
  Bangkit 2023 Batch 2 Capstone Team CH2-PS229
</h1>

- [Fadhil Hadrian Azzami](https://www.linkedin.com/in/fhazzami/) - M200BSY1584 - Universitas Diponegoro
- [Nurul Andini](https://www.linkedin.com/in/nurul-andini/) - M277BSX1256 -  Universitas Negeri Jakarta
- [Chinara Siwi Nugrahani](https://www.linkedin.com/in/chinarasiwinugrahani/) - M200BSX0115 - Universitas Diponegoro
- [Muhammad Rizki](https://www.linkedin.com/in/rizki-muhammad-32b4b4203/) - C299BSY3985 - Universitas Pendidikan Indonesia
- [Mohammad Labib Husain](https://www.linkedin.com/in/mohammad-labib-husain-065452281/) - C299BSY4160 - Universitas Pendidikan Indonesia
- [Novallino Hamid Kiapmajaya](https://www.linkedin.com/in/novallinohamidk/) - A277BSY2801 - Universitas Negeri Jakarta
- [Brian Yudhistira](https://www.linkedin.com/in/brian-yudhistira-95a62b221/) - A258BSY2836 -  Universitas Muhammadiyah Malang
