# End to End Medical Chatbot Generative AI


## Medical chatbot using OpenAI LLM model
### Project Description
Developing a medical chatbot by leveraging the Retrieval-Augmented Generation (RAG) process to fine-tune OpenAI's LLM responses for improved accuracy and relevance. Additionally, designing a user-friendly interface to facilitate seamless interaction

### Methodology
- Pinecone Vector database API
- Langchain
- embedding model from hugging face
- Open AI LLM model API
- AWS Free Tier Service to store
- Frontend using html 

### Interface

<img width="709" alt="Screenshot 2025-02-07 at 11 35 52 AM" src="https://github.com/user-attachments/assets/cdb5de93-5251-4184-9e39-809c7f4802d5" />

### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone


# AWS-CICD-Deployment-with-Github-Actions

## 1. Login to AWS console.

## 2. Create IAM user for deployment

	#with specific access

	1. EC2 access : It is virtual machine

	2. ECR: Elastic Container registry to save your docker image in aws


	#Description: About the deployment

	1. Build docker image of the source code

	2. Push your docker image to ECR

	3. Launch Your EC2 

	4. Pull Your image from ECR in EC2

	5. Lauch your docker image in EC2

	#Policy:

	1. AmazonEC2ContainerRegistryFullAccess

	2. AmazonEC2FullAccess

	

    
