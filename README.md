# Flask-React-Docker-Video_chat_app
Flask-React-Video_chat_app + Docker container


# video-chat-app
VideoChat Application in FLASK and REACTJS.

_______________________________________________________
BACKEND:-


1. create virtual environment(venv) and activate it.
2. install requirements.txt in virtual environment(venv).

3. Create dotenv (.env) in Backend 
4. add secret_key in .env file like( SECRET_KEY='3cd37a111e044698a41fa6b9dfb74865'  )

5. run your server :- python app.py
   server is Running on http://127.0.0.1:5000/

________________________________________________________
FRONTEND:-

1. install node_modules command :- npm i

2. runserver command :- npm start
   server is Running on http://localhost:3000/
________________________________________________________

DOCKER_CONTAINER :-

step:1 create .env file in Backend DIR

step:2 Build Docker Container :- docker-compose up --build

step:3 run Docker Container :- docker-compose up
