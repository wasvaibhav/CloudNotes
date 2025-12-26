🚀 FastAPI Notes App

FastAPI Tutorial | Build a Notes App using FastAPI, MongoDB & Bootstrap

A full-stack Notes Application built using FastAPI, MongoDB, and Bootstrap, explained step-by-step in Hindi.
This project is perfect for beginners who want to learn backend development with FastAPI and connect it with a database and frontend UI.

📌 Features

    ✅ Create new notes

    ✅ View all notes

    ✅ Update existing notes

    ✅ Delete notes

    ✅ RESTful API using FastAPI

    ✅ MongoDB integration

    ✅ Responsive UI using Bootstrap

    ✅ Beginner-friendly & well-structured code

🛠️ Tech Stack

    Technology                                            	Usage

    FastAPI	                                                Backend API

    Python	                                                Core programming

    MongoDB		                                            Database

    Pydantic		                                        Data validation

    Bootstrap		                                        Frontend styling

    HTML / Jinja2		                                    Templates

    Uvicorn			                                        ASGI server

📂 Project Structure
<img width="1120" height="566" alt="image" src="https://github.com/user-attachments/assets/e32b68ab-709b-4e1c-a096-8caca35f9f76" />


⚙️ Installation & Setup

1️⃣ Clone the repository

    git clone https://github.com/wasvaibhav/fastapi.git

    cd fastapi-notes-app

2️⃣ Create virtual environment

    python -m venv venv

    venv\Scripts\activate    # Windows

3️⃣ Install dependencies

    pip install -r requirements.txt

4️⃣ Setup MongoDB

    Install MongoDB locally OR

    `Use MongoDB Atlas

    Update connection string in .env

    MONGO_URI=mongodb://localhost:27017

5️⃣ Run the application

    uvicorn app.main:app --reload
