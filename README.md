# HomeMatch: Personalized Real Estate Agent

## Project Overview

### Introduction
HomeMatch is an innovative application developed to personalize the real estate search experience. By leveraging large language models (LLMs) and vector databases, HomeMatch transforms standard property listings into tailored narratives that align with individual buyer preferences. The goal is to revolutionize property search by offering highly engaging and personalized experiences for each client.

### Key Features

#### Understanding Buyer Preferences
- Collect buyer preferences such as location, property type, budget, amenities, and lifestyle choices.
- Use LLMs to interpret these inputs in natural language, identifying nuanced requests beyond standard filters.

#### Vector Database Integration
- Store real estate listings in a vector database.
- Use vector embeddings to match properties with buyer preferences, focusing on factors like neighborhood vibe, architectural style, and amenities.

#### Personalized Listing Descriptions
- Rewrite property descriptions using LLMs to highlight features that resonate most with the buyer’s needs.
- Maintain factual accuracy while emphasizing relevant characteristics.

#### Listing Presentation
- Deliver personalized listing descriptions that make the search process more engaging and tailored to the client.

## Project Instructions

### Step 1: Setting Up the Python Application
1. Initialize a new Python project.
2. Set up a virtual environment and install the necessary packages, including:
   - LangChain
   - LLM library (OpenAI’s GPT)
   - Vector database library (ChromaDB).

### Step 2: Generating Real Estate Listings
1. Use a Large Language Model (LLM) to generate at least 10 realistic property listings.
2. Use these listings to populate the vector database for testing and development.

### Step 3: Storing Listings in a Vector Database
1. Configure and initialize a vector database.
2. Generate vector embeddings for the property listings and store them in the database.

### Step 4: Building the User Preference Interface
1. Collect buyer preferences.
2. Parse the preferences for querying the database.

### Step 5: Semantic Search Implementation
1. Perform a semantic search on the vector database using structured preferences.
2. Retrieve listings that best match the buyer’s requirements based on semantic similarity.

### Step 6: Personalizing Listing Descriptions
1. Use an LLM to augment the retrieved listing descriptions.
2. Highlight features that align with buyer preferences while maintaining factual accuracy.

## Dependencies
Include the following in `requirements.txt`:
```plaintext
langchain
chromadb
openai
jupyter
```
