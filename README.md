https://www.youtube.com/watch?v=UJCpzOeMDBA&ab_channel=BlackBoxTech

docker build -t flight-app-docker .

STEP 1: Build File App
-- docker run -p 8000:4200 flight-app-docker
-- http://localhost:8000/

STEP 2: Build File Live Reload
-- docker-compose up
-- http://localhost:4200/