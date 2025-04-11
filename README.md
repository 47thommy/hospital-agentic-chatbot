# Hospital Chatbot

A sophisticated healthcare chatbot system that provides intelligent responses to queries about hospitals, physicians, patients, and healthcare-related information. The system uses a combination of Neo4j graph database, OpenAI's GPT models, and a modern web interface to deliver accurate and contextual responses.

## Features

- Interactive chat interface for healthcare queries
- Graph-based data storage using Neo4j
- ETL pipeline for healthcare data processing
- RAG (Retrieval Augmented Generation) implementation
- Real-time data processing and querying

## Technology Stack

- **Backend**: Python-based API service
- **Frontend**: Streamlit web application
- **Database**: Neo4j Graph Database
- **AI/ML**: OpenAI GPT models (GPT-4, GPT-3.5)
- **Data Processing**: Custom ETL pipeline
- **Containerization**: Docker and Docker Compose

## Prerequisites

- Docker and Docker Compose installed on your system
- OpenAI API key
- Neo4j database credentials

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/47thommy/hospital-agentic-chatbot.git>

```

2. Create a `.env` file:
```bash
cp .env.example .env
```

3. Update the `.env` file with your credentials:
- Add your OpenAI API key
- Configure Neo4j database credentials
- Set up other environment variables as needed

4. Build and run the application:
```bash
docker-compose up --build
```

The application will be available at:
- Frontend: http://localhost:8501
- API: http://localhost:8000

## Project Structure

- `chatbot_api/`: Backend API service
- `chatbot_frontend/`: Streamlit-based frontend application
- `hospital_neo4j_etl/`: ETL pipeline for data processing
- `data/`: Sample and processed data files
- `tests/`: Test files for the application

## Environment Variables

See `.env.example` for all required environment variables and their descriptions.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
