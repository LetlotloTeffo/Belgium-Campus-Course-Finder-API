The Belgium Campus Course Finder API is an AI-powered backend built with Node.js, Ollama, and Llama 3.2. 
It allows users to ask questions and get information about Belgium Campus
This includes courses, fees, accommodation, accommodation fees, campus locations, and other college-related information.

This project runs locally on the developers machine
and exposes an API at http://localhost:11434. 
The Node.js backend sends requests to Ollama, which processes the request using the locally installed Llama 3.2 model and returns the generated response.

This approach allows the application to experiment with AI inference locally without sending prompts to an external hosted LLM provider.

My Contribution

This project was completed as a group assignment, with each member responsible for different areas of the application. I, Letlotlo Teffo, was responsible for the complete backend and AI implementation. My responsibilities included:

Designing and developing the Node.js backend API
Implementing the API logic for processing user requests
Integrating Ollama with the Llama 3.2 large language model
Connecting the backend to the Belgium Campus information stored in data.json
Implementing the processing of queries about courses, fees, campus locations, accommodation, accommodation fees, and other school information
Developing AI prompt/request handling between the API and local Llama 3.2 model
Implementing guardrails and input validation to control user interactions with the AI
Managing backend configuration and environment variables
Testing and troubleshooting the API and AI integration
Managing the backend's npm dependencies and project configuration
