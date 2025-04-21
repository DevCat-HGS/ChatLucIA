# AI Chat Interface

A secure and scalable chat interface for interacting with Hugging Face's machine learning models.

## Features

- Secure authentication using JWT tokens
- Modern and responsive UI using Material-UI
- Real-time chat interface
- Integration with Hugging Face models
- Scalable backend architecture
- Error handling and loading states
- Protected routes

## Prerequisites

- Node.js (v14 or higher)
- Python (v3.8 or higher)
- pip (Python package manager)

## Installation

### Backend Setup

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the backend directory:
```
SECRET_KEY=your-secret-key-here
```

### Frontend Setup

1. Install dependencies:
```bash
cd frontend
npm install
```

## Running the Application

### Backend

1. Activate the virtual environment:
```bash
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Start the server:
```bash
cd backend
uvicorn main:app --reload
```

The backend will be available at `http://localhost:8000`

### Frontend

1. Start the development server:
```bash
cd frontend
npm start
```

The frontend will be available at `http://localhost:3000`

## Security Features

- JWT-based authentication
- Password hashing using bcrypt
- Protected API endpoints
- Secure token storage
- CORS configuration
- Environment variable management

## Scalability Considerations

- Modular architecture
- Separation of concerns
- Error handling
- Loading states
- Responsive design
- API rate limiting (to be implemented)
- Database integration (to be implemented)

## Default Credentials

For testing purposes, use:
- Username: testuser
- Password: testpassword

## API Documentation

The API documentation is available at `http://localhost:8000/docs` when the backend is running.

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 