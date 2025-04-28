Sakila Project Analysis

This project is an analysis of the Sakila codebase, focused on extracting relevant insights and knowledge using a Large Language Model (LLM). The analysis is performed on the SakilaProject GitHub repository, and the key features and steps involved are as follows:
Project Overview

The Sakila project is a sample database project often used for learning SQL, database management, and application development. In this analysis, we have examined the Java code in the project, extracting high-level insights, key methods, and functionality.
Steps Involved:

    Cloning the Repository: The SakilaProject repository was cloned from GitHub.

    Codebase Processing: The Java files within the repository were read and processed to analyze their content.

    LLM Integration: We used a Large Language Model (FLAN-T5 Small) for analyzing the Java code. The model was tasked with extracting:

        High-level purpose and functionality of the project.

        Key methods and their signatures.

        Complexity and any noteworthy code aspects.

    Chunking: Due to token limitations of the LLM, the Java code was divided into smaller chunks (1000 characters) to ensure smooth processing.

    Structured Output: The results of the analysis were saved in a structured JSON format for easy consumption and readability.

Output

The output of the project is a JSON file containing the structured analysis of the Java code. The file includes:

    The purpose of the project.

    Key methods and their descriptions.

    Complexity and other important insights.

Installation & Execution

To run this project:

    Clone the repository:

git clone https://github.com/kamminenibhanurekha/Sakila_project

Install the required libraries:

    pip install langchain langchain-community transformers accelerate tiktoken

    Execute the analysis in Google Colab or your local Python environment.

