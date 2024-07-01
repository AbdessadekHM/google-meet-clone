# Google Meet Clone

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Getting Started](#getting-started)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Project Structure](#project-structure)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

## Introduction
This is a clone of Google Meet, a video conferencing application. It allows users to join video calls, share their screens, and chat in real-time.

## Features
- User authentication and authorization
- Create and join video calls
- Real-time chat during calls
- Screen sharing
- Mute/unmute audio and video
- Responsive UI

## Technologies Used
### Frontend
- Next.js

### Backend
- Django
- Django REST Framework
- Channels (for WebSocket support)

### Database
- MongoDB

### DevOps
- Docker

## Getting Started
To get a local copy up and running follow these simple steps.

### Prerequisites
- Python 3.8+
- Node.js 14+
- MongoDB
- Docker

## Installation

### Backend Setup
1. Clone the repository
    ```sh
    git clone https://github.com/yourusername/google-meet-clone.git
    cd google-meet-clone/backend
    ```

2. Create a virtual environment and activate it
    ```sh
    python -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages
    ```sh
    pip install -r requirements.txt
    ```

4. Set up environment variables
    Create a `.env` file in the `backend` directory and add the following:
    ```
    SECRET_KEY=your_secret_key
    DEBUG=True
    DATABASE_URL=mongodb://user:password@localhost:27017/dbname
    ```

5. Apply migrations
    ```sh
    python manage.py migrate
    ```

6. Run the development server
    ```sh
    python manage.py runserver
    ```

### Frontend Setup
1. Navigate to the `frontend` directory
    ```sh
    cd ../frontend
    ```

2. Install NPM packages
    ```sh
    npm install
    ```

3. Set up environment variables
    Create a `.env.local` file in the `frontend` directory and add the necessary environment variables.

4. Run the development server
    ```sh
    npm run dev
    ```

## Usage
- Open your browser and navigate to `http://localhost:3000` for the frontend and `http://localhost:8000` for the backend API.

## Project Structure

google-meet-clone/
│
├── backend/
│ ├── manage.py
│ ├── requirements.txt
│ ├── .env
│ └── <django project files>
│
├── frontend/
│ ├── package.json
│ ├── .env.local
│ └── <next.js project files>
│
└── README.md



## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.


