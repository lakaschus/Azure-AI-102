# Study resources for Azure AI-102 AI Engineering

Official overview of study resources: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102#study-resources

This repo contains a table of measured skills for the Azure AI-102 course and learning resources associated with each skill.

In addition to that, custom learning notebooks and labs are found in the `labs` directory. Each lab is supposed to related to at least one AI-102 skill measured in the exam. In the notebooks I will try to do as much as possible using the Python SDK, as I believe this is best approach for automation

Disclaimer: Many code snippets are taken from various MS Learn resources that are subject to the MIT license, such as 

- https://github.com/MicrosoftLearning/mslearn-ai-services
- https://github.com/MicrosoftLearning/mslearn-ai-vision
- https://github.com/MicrosoftLearning/mslearn-ai-language
- https://github.com/MicrosoftLearning/mslearn-ai-document-intelligence
- https://github.com/MicrosoftLearning/mslearn-knowledge-mining
- https://github.com/MicrosoftLearning/mslearn-openai

# Status

Incomplete, work in progress

# Table of measured skills

## Plan and Manage an Azure AI Solution (15-20%)

### Select the Appropriate Azure AI Service

| Skill | MS Labs / Exercises | Documentation |Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Select the appropriate service for a computer vision solution | https://learn.microsoft.com/en-us/training/paths/create-computer-vision-solutions-azure-ai/ | | |
| Select the appropriate service for a natural language processing solution | https://learn.microsoft.com/en-us/training/modules/analyze-text-ai-language/ | | |
| Select the appropriate service for a speech solution | | | |
| Select the appropriate service for a generative AI solution | | | |
| Select the appropriate service for a document intelligence solution | | | |
| Select the appropriate service for a knowledge mining solution | | | |

### Plan, Create and Deploy an Azure AI Service

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Plan for a solution that meets Responsible AI principles | | | |
| Create an Azure AI resource | https://microsoftlearning.github.io/mslearn-ai-services/Instructions/Exercises/01-use-azure-ai-services.html \| https://learn.microsoft.com/en-us/training/modules/create-manage-ai-services/5a-exercise-ai-services | https://learn.microsoft.com/en-us/azure/ai-services/ | [create_az_ai_resource_from_template.ipynb](labs/getting-started/azure_ai_resource_template/create_az_ai_resource_from_template.ipynb) |
| Determine a default endpoint for a service | | | |
| Integrate Azure AI services into a continuous integration and continuous delivery (CI/CD) pipeline | | | |
| Plan and implement a container deployment | https://learn.microsoft.com/en-us/training/modules/investigate-container-for-use-with-ai-services/ | https://learn.microsoft.com/en-us/azure/ai-services/cognitive-services-container-support | |

### Manage, Monitor, and Secure an Azure AI Service

| Skill | MS Labs / Exercises | Documentation | Custom Lab  |
| ----- | ----------------- | ------------- | ------ |
| Configure diagnostic logging | https://learn.microsoft.com/en-us/training/modules/monitor-ai-services | https://learn.microsoft.com/en-us/azure/ai-services/diagnostic-logging | |
| Monitor an Azure AI resource | https://learn.microsoft.com/en-us/training/modules/monitor-ai-services | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview \| https://learn.microsoft.com/en-us/azure/azure-portal/azure-portal-dashboards | |
| Manage costs for Azure AI services | https://learn.microsoft.com/en-us/training/modules/monitor-ai-services | https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview | |
| Manage account keys | https://learn.microsoft.com/en-us/training/modules/secure-ai-services/ | | |
| Protect account keys by using Azure Key Vault | https://learn.microsoft.com/en-us/training/modules/secure-ai-services/ | | |
| Manage authentication for an Azure AI Service resource | https://learn.microsoft.com/en-us/training/modules/secure-ai-services/ | | |
| Manage private communications | | | |

## Implement Content Moderation Solutions (10-15%)

### Create Solutions for Content Delivery

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Implement a text moderation solution with Azure AI Content Safety | | | |
| Implement an image moderation solution with Azure AI Content Safety | | | |

## Implement Computer Vision Solutions (15-20%)

### Analyze Images

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Select visual features to meet image processing requirements | https://learn.microsoft.com/en-us/training/paths/create-computer-vision-solutions-azure-ai/ | | labs\computer-vision\image-analysis\image_analysis.ipynb |
| Detect objects in images and generate image tags | https://learn.microsoft.com/en-us/training/paths/create-computer-vision-solutions-azure-ai/ \| https://learn.microsoft.com/en-us/training/modules/detect-analyze-recognize-faces/ | https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/concept-detecting-faces \| https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview-identity | |
| Include image analysis features in an image processing request | | | |
| Interpret image processing responses | https://learn.microsoft.com/en-us/training/paths/create-computer-vision-solutions-azure-ai/ | | |
| Extract text from images using Azure AI Vision | https://learn.microsoft.com/en-us/training/modules/read-text-images-documents-with-computer-vision-service/ | | |
| Convert handwritten text using Azure AI Vision | | | |

### Implement Custom Computer Vision Models by Using Azure AI Vision

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Choose between image classification and object detection models | https://learn.microsoft.com/en-us/training/modules/custom-model-ai-vision-image-classification/ | | |
| Label images | | | |
| Train a custom image model, including image classification and object detection | https://learn.microsoft.com/en-us/training/modules/custom-model-ai-vision-image-classification/ | | |
| Evaluate custom vision model metrics | | | |
| Publish a custom vision model | | | |
| Consume a custom vision model | | | |

### Analyze Videos

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Use Azure AI Video Indexer to extract insights from a video or live stream | | | |
| Use Azure AI Vision Spatial Analysis to detect presence and movement of people in video | | | |

## Implement Natural Language Processing Solutions (30-35%)

### Analyze Text by Using Azure AI Language

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Extract key phrases | https://learn.microsoft.com/en-us/training/modules/analyze-text-ai-language/ | | |
| Extract entities | https://learn.microsoft.com/en-us/training/modules/analyze-text-ai-language/ | https://learn.microsoft.com/en-us/azure/ai-services/language-service/named-entity-recognition/concepts/named-entity-categories?tabs=ga-api | |
| Determine sentiment of text | https://learn.microsoft.com/en-us/training/modules/analyze-text-ai-language/ | | |
| Detect the language used in text | https://learn.microsoft.com/en-us/training/modules/analyze-text-ai-language/ | | |
| Detect personally identifiable information (PII) in text | | | |

### Process Speech by Using Azure AI Speech

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Implement text-to-speech | | | |
| Implement speech-to-text | | | |
| Improve text-to-speech by using Speech Synthesis Markup Language (SSML) | | | |
| Implement custom speech solutions | | | |
| Implement intent recognition | | | |
| Implement keyword recognition | | | |

### Translate Language

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Translate text and documents by using the Azure AI Translator service | | | |
| Implement custom translation, including training, improving, and publishing a custom model | | | |
| Translate speech-to-speech by using the Azure AI Speech service | | | |
| Translate speech-to-text by using the Azure AI Speech service | | | |
| Translate to multiple languages simultaneously | | | |

### Implement and Manage a Language Understanding Model by Using Azure AI Language

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Create intents and add utterances | | | |
| Create entities | | | |
| Train, evaluate, deploy, and test a language understanding model | | | |
| Optimize a language understanding model | | | |
| Consume a language model from a client application | | | |
| Backup and recover language understanding models | | | |

### Create a Question Answering Solution by Using Azure AI Language

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Create a question answering project | | | |
| Add question-and-answer pairs manually | | | |
| Import sources | | | |
| Train and test a knowledge base | | | |
| Publish a knowledge base | | | |
| Create a multi-turn conversation | | | |
| Add alternate phrasing | | | |
| Add chit-chat to a knowledge base | | | |
| Export a knowledge base | | | |
| Create a multi-language question answering solution | | | |

## Implement Knowledge Mining and Document Intelligence Solutions (10-15%)

### Implement an Azure AI Search Solution

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Provision an Azure AI Search resource | | | |
| Create data sources | | | |
| Create an index | | | |
| Define a skillset | | | |
| Implement custom skills and include them in a skillset | | | |
| Create and run an indexer | | | |
| Query an index, including syntax, sorting, filtering, and wildcards | | | |
| Manage Knowledge Store projections, including file, object, and table projections | | | |

### Implement an Azure AI Document Intelligence Solution

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Provision a Document Intelligence resource | | | |
| Use prebuilt models to extract data from documents | | | |
| Implement a custom document intelligence model | | | |
| Train, test, and publish a custom document intelligence model | | | |
| Create a composed document intelligence model | | | |
| Implement a document intelligence model as a custom Azure AI Search skill | | | |

## Implement Generative AI Solutions (10-15%)

### Use Azure OpenAI Service to Generate Content

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Provision an Azure OpenAI Service resource | | | |
| Select and deploy an Azure OpenAI model | | | |
| Submit prompts to generate natural language | | | |
| Submit prompts to generate code | | | |
| Use the DALL-E model to generate images | | | |
| Use Azure OpenAI APIs to submit prompts and receive responses | | | |

### Optimize Generative AI

| Skill | MS Labs / Exercises | Documentation | Custom Lab |
| ----- | ----------------- | ------------- | ------ |
| Configure parameters to control generative behavior | | | |
| Apply prompt engineering techniques to improve responses | | | |
| Use your own data with an Azure OpenAI model | | | |
| Fine-tune an Azure OpenAI model | | | |