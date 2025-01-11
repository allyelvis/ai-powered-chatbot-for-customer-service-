# AI-Powered Chatbot for Customer Service

This project is an AI-powered chatbot designed to assist with customer service tasks. It uses OpenAI's GPT model to provide natural and context-aware responses.

## Features
- AI-generated responses to customer queries
- Context-aware conversation handling
- Simple REST API for chatbot integration
- Easy-to-deploy Node.js server

## Prerequisites
- Node.js installed
- OpenAI API key

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/allyelvis/ai-powered-chatbot-for-customer-service-.git
   cd ai-powered-chatbot-for-customer-service-

2. Install dependencies:

npm install


3. Create a .env file in the project root and add your OpenAI API key:

OPENAI_API_KEY=your_openai_api_key


4. Start the server:

node main.js


5. The server will run at http://localhost:3000.



API Endpoints

Health Check

GET /

Returns a message confirming the server is running.


Chat Endpoint

POST /chat

Sends a user message to the chatbot and receives an AI-generated response.

Request Body:

{
  "message": "Your question here",
  "context": [
    { "role": "user", "content": "Previous message" },
    { "role": "assistant", "content": "Previous reply" }
  ]
}

Response:

{
  "reply": "AI-generated response here"
}


Author

Ally Elvis Nzeyimana

License

This project is licensed under the MIT License.

---


Instructions to Deploy

1. Follow the steps in README.md.


2. Customize the repository link in the README.md if necessary.


3. Run the following command to start:

npm start



