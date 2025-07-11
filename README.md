# SWASTH---A-Healthcare-Chatbot
SWASTH is an AI-powered healthcare chatbot designed to provide 24/7 medical assistance. It leverages natural language processing (NLP) and machine learning (ML) algorithms, including decision trees, to analyze user-provided symptoms and accurately predict illnesses or diseases. The chatbot then offers appropriate healthcare recommendations and suggests relevant medications. This project aims to improve healthcare accessibility and empower individuals by offering an alternative platform for basic medical advice and support.
# Project Overview
SWASTH is an AI-powered healthcare chatbot designed to provide round-the-clock medical assistance to users. The primary objective is to create an intelligent conversational program that can offer medical support by analyzing symptoms and providing relevant health recommendations. 
# Technical Specifications
## Software Requirements
*	Operating System: Windows 
*	Programming Language: Python 
*	NLP Libraries: re 
*	Machine Learning Libraries: Pandas, sklearn, NumPy, csv 
*	IDE: PyCharm 
*	Frontend: Python-Streamlit 
*	TTS: pyttsx3 
## Hardware Requirements
*	Processor: Intel i5 or i7 
*	Memory (RAM): 2GB 
# Proposed System Architecture
The chatbot's architecture emphasizes efficient communication between a client-side user interface and server-side components. 
## Modules
The system is comprised of several key modules:
1.	User Interface Module: Provides an interactive and user-friendly platform for users to input inquiries and view responses. It handles input gathering, user guidance, and response display. 
2.	Natural Language Processing (NLP) Module: Processes and understands user inquiries by performing tasks like text pre-processing, tokenization, part-of-speech tagging, named entity recognition, sentiment analysis, and intent recognition. 
3.	Decision Tree Module: Forms the core of the chatbot's decision-making. It implements the CART (Classification and Regression Trees) algorithm to analyze processed data from the NLP module and generate appropriate responses, performing both classification and prediction tasks. 
4.	Knowledge Base Module: Serves as a repository for healthcare-related information, storing medical knowledge such as symptoms, diseases, treatments, and medications. It supports information storage and retrieval. 
5.	Personalization Module: Aims to tailor chatbot responses to individual users based on their specific needs and preferences by analyzing user data like medical history and previous interactions. 
6.	Integration and Deployment Module: Responsible for seamlessly integrating all modules and deploying the chatbot to a production environment for user accessibility. 
## Methodology
* The SWASTH chatbot utilizes natural language processing (NLP) and machine learning (ML) algorithms, specifically decision trees, to analyze user-provided symptoms and accurately detect specific illnesses or diseases.
* It subsequently offers appropriate healthcare recommendations and suggests relevant medications.
* The project is developed using Python and trained with diverse datasets, including the Disease Prediction Dataset.
# Testing
The project underwent various testing phases to ensure correctness and adherence to requirements:
*	Unit Testing: Each module was individually tested for correctness and validity. 
*	Integration Testing: Modules were clipped together and tested as a whole to identify issues arising from poor interfacing. 
*	Functional Testing: Systematic demonstrations ensured functions met specified business and technical requirements. 
*	System Testing: Verified that the entire integrated software system met all requirements. 
*	Acceptance Testing: Confirmed that the software functioned as expected by the user. 
All test cases passed successfully with no defects encountered.
