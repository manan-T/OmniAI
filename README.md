# OmniAI

OmniAI is an advanced AI agent designed to interact with a variety of tools, providing robust and versatile solutions. The project leverages Retrieval-Augmented Generation (RAG) to enhance its capabilities.

## Overview
OmniAI is designed to seamlessly integrate various tools and provide accurate and contextual responses to user queries. The system utilizes RAG to enhance its ability to retrieve and generate information, making it a powerful assistant for a wide range of tasks.

## Features
- **Multi-tool Integration:** OmniAI integrates with various tools to provide comprehensive responses.
- **Retrieval-Augmented Generation (RAG):** Enhances the AI's ability to generate accurate and relevant information.
- **Flexible Query Handling:** Can process and respond to diverse queries using different datasets and engines.

## Setup
Follow these steps to set up the project:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/omniai.git
    cd omniai
    ```

2. **Install dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

3. **Set up environment variables:**
    Create a `.env` file in the project root and add your OpenAI API key.
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

4. **Prepare the data:**
    Ensure the `data` directory contains the necessary datasets such as `population.csv`.

## Usage
Run the following command to start the OmniAI agent:
```sh
python main.py
