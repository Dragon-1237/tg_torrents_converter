build:
  docker:
    web: Dockerfile
run:
  web: python3 -m bots.py
  worker: python3 -m bots.py
  heroku ps:scale web=1
