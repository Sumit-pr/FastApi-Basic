# FastApi-Basic
Basic FastAPi application with React JS

A simple item management application built with FastAPI for the backend and React for the frontend. This app allows users to create, read, update, and delete items.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)

## Features

- Add new items with details like name, description, price, and tax.
- View a list of all items.
- Update item details.
- Delete items from the list.
- Responsive design for better user experience on all devices.

## Technologies Used

- **Backend**: [FastAPI](https://fastapi.tiangolo.com/)
- **Frontend**: [React](https://reactjs.org/)
- **HTTP Client**: [Axios](https://axios-http.com/)
- **Middleware**: CORS for handling cross-origin requests

## Installation
### Backend (FastAPI)
-Need to install Python in system 
-Install FastApi
  pip install fastapi
****Run the FastAPI server: uvicorn main:app --reload
## Fronted (React JS)
-Need to install NodeJS in system
-Navigate to the frontend directory:
         create react-app: npx create-react-app my-app, cd my-app, npm start
install required module like axios
**##Usage
-Open your browser and navigate to http://localhost:3000 to access the React frontend.
-The FastAPI backend will be running on http://127.0.0.1:8000.

**API Endpoints**
-Get all items
-URL: /items/ , Method: GET , Description: Retrieve a list of all items.
         




