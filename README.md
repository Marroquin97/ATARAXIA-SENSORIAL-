# ATARAXIA

## Project Description
ATARAXIA is a full-stack web application designed to provide a harmonious user experience. The project leverages modern technologies to ensure scalability, performance, and responsiveness. It aims to deliver a seamless integration of front-end and back-end functionalities.

## Installation Instructions
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/Marroquin97/ATARAXIA-SENSORIAL-
   cd ATARAXIA-SENSORIAL-
   ```  
2. **Navigate to the front-end directory:**  
   ```bash
   cd frontend
   ```  
3. **Install dependencies for React:**  
   ```bash
   npm install
   ```  
4. **Navigate to the back-end directory:**  
   ```bash
   cd ../backend
   ```  
5. **Install dependencies for FastAPI:**  
   ```bash
   pip install -r requirements.txt
   ```  
6. **Set up your MongoDB database and update the connection string.**  
7. **Run the application:**  
   - Start the backend server:  
   ```bash
   uvicorn main:app --reload
   ```  
   - Start the frontend server:  
   ```bash
   npm start
   ```

## API Endpoints
- **GET /api/items**: Retrieve a list of items.
- **POST /api/items**: Create a new item.
- **GET /api/items/{id}**: Retrieve a specific item by ID.
- **PUT /api/items/{id}**: Update an item by ID.
- **DELETE /api/items/{id}**: Delete an item by ID.

## Database Structure
The application utilizes MongoDB for data storage. The primary collections include:
- `users`: Stores user information.
- `items`: Stores items and their details.
- `transactions`: Logs user transactions.

## Stack Technology
- **Front-end**: React 19, Tailwind CSS  
- **Back-end**: FastAPI  
- **Database**: MongoDB

## Features
- User authentication and authorization  
- Responsive design with Tailwind CSS  
- Dynamic item creation and management  
- Smooth API integrations  
- Error handling and logging

## Contribution Guidelines
1. Fork the repo  
2. Create a new branch (`git checkout -b feature-branch`)  
3. Make your changes  
4. Commit your changes (`git commit -m 'Add new feature'`)  
5. Push to the branch (`git push origin feature-branch`)  
6. Open a Pull Request

## Troubleshooting
- Ensure MongoDB is running before starting the application.
- Check for errors in the terminal and dashboard logs for any issues.

## Roadmap
- Version 1.0: Initial release with core features.
- Version 2.0: Enhance UI/UX and add new functionalities.
- Version 3.0: Scaling the application to support more users and data.

Feel free to contribute or open issues for any bugs or enhancement requests!