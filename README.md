# MedMate: Your Medicare & Medicaid Companion

## What is MedMate?
MedMate is a conversational chatbot designed to simplify the complexities of Medicare and Medicaid by providing precise, conversational, and user-friendly answers. This project focuses on leveraging advanced machine learning, fine-tuning techniques, and custom data engineering to create an accessible resource for users navigating healthcare systems. The initiative bridges the gap between static policy information and dynamic user needs by transforming data into actionable insights.

## What are the key features?
MedMate is a innovative solution for conversational AI in healthcare. It aims to provide clear and accurate responses to user Medicare and Medicaid questions. 

## How does it work?
The user would enter a question about Medicare or Medicaid. The chatbot will then prodess the query using a fine-tuned Gemma model. The relevant information in then retrieved from the dataset and a response is displayed for the end user.

## What tools did you use?
Programming Language: Python
Machine Learning Frameworks: TensorFlow/Keras, Hugging Face
Data Management: BigQueryVectorStore
Fine-Tuning: LoRA (Low-Rank Adaptation)
Platform: Kaggle, Vertex AI
Version Control: Git

## Can I view the dataset?
Yes! The dataset is a custom Q&A dataset curated from web scrapping health care websites like: US Department of Health and Human Services hhs.gov, Social Security ssa.gov, Medicaid.gov, Medicare.gov, and the current Med and You publication.
The dataset contains 3 fields: Question, Answer, & Category.

You can access the dataset here: https://bit.ly/3Zj3dOX

## What challenges were faced?
While converting the Gemma models to Hugging Face transformers to deploy to Vertex AI and vllm I faced challenges with model conversion. The Keras NLP conversion script was not responsive along with running in dependency conflicts.

## What I learned?
I gained valuable experience in curating my own dataset being mindful of what information can be included. Finetuning models with LoRA, and troubleshooting infastructure.
