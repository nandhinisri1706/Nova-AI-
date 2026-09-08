# Nova AI - AI-Powered Chatbot

Nova AI is an AI-powered chatbot developed using Python, Streamlit, Hugging Face Inference API, and Groq. The application provides a simple conversational interface for students and general users to interact with an AI assistant.

## Features

* AI-powered conversations
* AI concept explanations
* Python programming assistance
* Study assistance
* AI project idea generation
* Tamil and Tanglish language support
* Fast AI responses using Groq
* Chat history management
* Clear chat functionality
* Streamlit Community Cloud deployment support

## Tech Stack

* Python
* Streamlit
* Hugging Face Inference API
* Groq
* python-dotenv

## Project Structure

```text
nova-ai-chatbot/
│
├── app.py
├── requirements.txt
├── .gitignore
├── .env
└── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/nova-ai-chatbot.git
cd nova-ai-chatbot
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment on Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Hugging Face API Token

Create a `.env` file in the project directory:

```env
HF_TOKEN=hf_your_token_here
```

The Hugging Face token is required to access the AI inference service.

Do not share or upload your API token publicly.

### 5. Run the Application

```bash
streamlit run app.py
```

The application will be available at:

```text
http://localhost:8501
```

## AI Model

The application uses the following model:

```text
openai/gpt-oss-120b
```

The model is accessed through Hugging Face Inference Providers using Groq for fast inference.

## Deployment

Nova AI can be deployed using Streamlit Community Cloud.

Deployment steps:

1. Push the project to a GitHub repository.
2. Connect the GitHub repository with Streamlit Community Cloud.
3. Select the repository.
4. Select the main branch.
5. Select app.py as the main application file.
6. Add the HF_TOKEN through Streamlit Secrets.
7. Deploy the application.

## Environment Variables

For local development, create a `.env` file:

```env
HF_TOKEN=your_huggingface_token
```

For deployment, configure the token using Streamlit Secrets.

## Security

API keys and tokens must never be committed to the GitHub repository.

Add the following entries to `.gitignore`:

```text
.env
venv/
__pycache__/
```

## Use Cases

Nova AI can be used for:

* Student learning assistance
* Programming support
* AI concept explanations
* Study planning
* Project brainstorming
* General question answering
* Tamil and Tanglish conversations

## Future Enhancements

* Voice input and output
* PDF and document analysis
* Image understanding
* User authentication
* Persistent conversation history
* Multi-language support
* Personalized learning features

## Author

Nandhini Sri

B.Sc. Computer Science with Artificial Intelligence

## Project Objective

Nova AI aims to provide a simple, fast, and student-friendly AI assistant that helps users with learning, programming, project development, and general knowledge through natural language interaction.
