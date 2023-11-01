# ChatBedrock Streamlit App

ChatBedrock is a Streamlit-based chatbot application powered by AWS services. This README provides an overview of the app.
This project was inspired by an AWS tutorial, which served as the foundation for building this chatbot application.

## Overview

ChatBedrock is a conversational chatbot that leverages an AWS language model to engage in text-based conversations with users using Amazon Bedrock, Amazon S3, LangChain, and Streamlit. The app features the following functionalities:

- User interaction through a chat interface.
- Integration with Amazon Bedrock and Claude model from Anthropic
- Storage of conversation history in an Amazon S3 bucket


1. **Prerequisites**:
   - Python 3.x installed.
   - AWS account and appropriate IAM permissions.
   - An AWS S3 bucket for storing conversation history. If you haven't created one, follow AWS documentation to create an S3 bucket.

2. **Installation**:
   - Clone the repository or download the source code.
   - Navigate to the project directory and install the necessary Python packages using the following command:

   ```shell
   pip install -r requirements.txt

   
