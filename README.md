<!--
**avoytkiv/avoytkiv** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Andrii Voitkiv - portfolio
## About
> This is a repository to showcase skills, share projects and track my progress in Data Science / Machine Learning related topics. 

## Table of contents
- [About](#About)
- [Study projects](#Study-projects)
  - [Master of Data Sciene and Analytics](#Master-of-Data-Sciene-and-Analytics)
  - [Pytorch fundamentals](#Pytorch-fundamentals)
  - [NLP Cook Dishes Project](#NLP-Cook-Dishes-Project)
- [Portfolio end-to-end projects](#Portfolio-end-to-end-projects) 
  - [[MLOps] - Client Segmentation for targeted marketing in a credit union - Internship project](#Client-Segmentation-for-targeted-marketing-in-a-credit-union)
  - [[NLP] - Predicting job salary using Neural Network model on Azure ML](#Predicting-job-salary)
  - [[MLOps] - End-to-end ML project predicting diabetes on Azure Machine Learning and GitHub Actions](#Predicting-diabetes-on-Azure-ML-with-GitHub-Actions)
  - [[LLM] - Fine-Tuning LLM with SkyPilot and DVC](#Fine-Tuning-LLM-with-SkyPilot-and-DVC)
- [Previous work](#Previous-work)
  - [Workflow automation](https://github.com/avoytkiv/automating-workflow)
  - [A Market-on-the-Close Approach: Research and Strategy Development](https://github.com/avoytkiv/moc_imbalance_flip)
<!--
- [Certificates](#Certificates)
-->


## Study projects
> In this section I will provide links to my github repositories containing code and jupyter notebooks I created while passing courses.

### Master of Data Sciene and Analytics
This is 12 months master program at the University of Calgary, Canada. 
For more details ---> [go to repo...](https://github.com/avoytkiv/MDSA-UofC)   
List of courses:
- [DATA601 - Working with Data and Visualization](DATA601/README.md)
- [DATA602 - Statistical Data Analysis](DATA602/README.md)
- [DATA603 - Statistical Modelling with Data](DATA603/README.md)
- [DATA604 - Working with Data at Scale](DATA604/README.md)
- [DATA605 - Actionable Visualization and Analytics](DATA605/README.md)
- [DATA606 - Statistical Methods in Data Science](DATA606/README.md)
- [DATA607 - Machine Learning](DATA607/README.md)
- [DATA608 - Developing Big Data Applications](DATA608/README.md)  


### Pytorch fundamentals
`Code:` [go to repo...](https://github.com/avoytkiv/pytorch_fundamentals)   
`Status:` In progress  

### NLP Cook Dishes Project 
`Code:` [go to repo...](https://github.com/avoytkiv/nlp_cook_dishes)   
`Description`: This project is an in-depth exploration of various NLP models with the purpose of generating text based on a dataset of recipes.    
`Skills in focus`: N-gram Language Model, Neural Language Models (RNN-LSTM, Convolutional), Sampling strategies, Evaluating language model   
`Status:` Completed in November 2023  

## Portfolio end-to-end projects
> In this section I will list projects briefly describing the technology stack used to solve cases.

### Client Segmentation for targeted marketing in a credit union 

<img width="31%" alt="Screenshot 2023-10-21 at 23 46 11" src="https://github.com/avoytkiv/avoytkiv/assets/74664634/6b75e82f-16da-4611-b81c-3c0a2d03e1f1">  


`Code`: [go to repo...](https://github.com/avoytkiv/credit-mlops)  
`Presentation`: [go to google slides...](https://docs.google.com/presentation/d/1pDSZ51ej2VtzNydxAlhoLrQY95iydV-mELwKtUmL1QI/edit?usp=sharing)  
`Industry`: Banking and Finance   
`Description`: The focus of the project was to build a highly flexible and automated ML pipeline to run experiments. Then, the best model is deployed to an app by a series of automated workflows.   
`Skills in focus`: Clustering, Model selection, Data and model versioning, Experimentations, CI/CD pipelines   
`Tools`:
 - *Environment*: GitHub Codespaces, devcontainer, Docker, venv, Hydra
 - *Data Management*: DVC (Data Version Control), AWS S3
 - *DS and ML*: scikit-kearn (PCA, clustering algorithms), keras (autoencoder)
 - *Continuous Integration*: GitHub Actions, CML, AWS EC2
 - *Continuous Deployment*: Fast API, Heroku  

`Results`: This helps the credit union make better decisions about how to reach out to different groups of clients.     
`Status`: Completed in August 2023.

### Predicting job salary

<img width="31%" alt="Screenshot 2023-09-28 at 11 02 13" src="https://github.com/avoytkiv/avoytkiv/assets/74664634/ca106b31-01c9-4f44-9893-6baa3421a202">   


`Code`: [go to repo...](https://github.com/avoytkiv/azml_predict_salary_nlp)   
`Description`: This is from Kaggle competition: "Adzuna wants to build a prediction engine for the salary of any UK job ad, so they can make huge improvements in the experience of users searching for jobs, and help employers and jobseekers figure out the market worth of different positions."   
`Data`: large dataset (hundreds of thousands of records), which is mostly unstructured text, with a few structured data fields.   
`Skills in focus`: Regression, Tokenization, Categorical Vectorization, Neural Networks, OOP, ML Pipeline (Azure CLI), Components (Azure CLI), Deployment       
`Tools`:
 - *Environment*: GitHub Codespaces, devcontainer, conda, Azure CLI, Azure ML Studio
 - *DS and ML*: PyTorch, scikit-learn   

`Status`: Completed in September 2023.   

### Predicting diabetes on Azure ML with GitHub Actions

<img width="31%" alt="Screenshot 2023-10-21 at 23 47 36" src="https://github.com/avoytkiv/avoytkiv/assets/74664634/59a4c85d-03b3-4642-98bb-e2f58802bdbd">  


`Code`: [go to repo...](https://github.com/avoytkiv/azml-github_actions-cicd)  
`Industry`: Healthcare   
`Description`:   
`Skills in focus`:  Logistic Regression, CI/CD pipelines, Linting, Testing, Package and Register the Model   
`Tools`:
 - *Environment*: GitHub Codespaces, devcontainer, Docker, venv
 - *Data Management*: Azure ML Datastore
 - *DS and ML*: scikit-kearn (Logistic regression)
 - *Continuous Integration*: GitHub Actions, Azure ML Resources (Job, Compute, Environment), flake8, pytest
 - *Continuous Deployment*:  MLFlow

`Results`: An automated workflow that will be triggered when a new model is registered. Once the workflow is triggered, the new registered model will be deployed to the production environment.   
`Status`: Completed in October 2023.

### Fine-Tuning-LLM-with-SkyPilot-and-DVC
   
<img width="31%" alt="Screenshot 2023-10-21 at 23 48 21" src="https://github.com/avoytkiv/avoytkiv/assets/74664634/95335731-45d0-4031-bc2b-c013e3a34c8a">  


`Code`: [go to repo...](https://github.com/avoytkiv/azml_finetune_llm)     
`Description`: Fine-tune the foundational LLM for hotel reviews' sentiment classification in the cloud on GPUs.  
`Skills in focus`: Text classification, Fine-tune LLM, Provision infrastructure, Checkpointing    
`Tools`:
 - *Environment*: GitHub Codespaces, devcontainer, Docker, venv   
 - *Infrastructure Management*: SkyPilot   
 - *DS and ML*: Transformer, PyTorch   
 - *Continuous ML*: DVC, Weights and Biases   

`Results`: Cost-optimized setup to run in the cloud to fine-tune LLM with continuous machine learning.  
`Status`: Completed in October 2023.


## Contacts
- Linkedin: https://www.linkedin.com/in/avoytkiv/
- E-mail: avoytkiv@gmail.com

