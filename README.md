# 2048-Game

# 2048 Game

**How to play:** Use your arrow keys to move the tiles. Tiles with the same number merge into one when they touch. Add them up to reach 2048!

This game project is originally made by Gabriele Cirulli and updated by me (Mohammad Gayasuddin).

## Steps

1. Created Dockerfile.
![Dockerfile](https://drive.google.com/file/d/1caN8vEyLRgZZGlUUmV-ifUb8HjjuBnHQ/view?usp=sharing)


2. Built Docker image from Dockerfile.
3. Deployed Docker image to Google Cloud Container Registry:
   ```bash
   docker build -t gcr.io/project_id/appname:version .
   docker push gcr.io/project_id/2048-game:v01
4. Deployed dockerfile on google cloud run  a serverless environment.
