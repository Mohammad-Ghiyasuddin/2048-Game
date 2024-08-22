# 2048-Game
![UI](https://drive.google.com/uc?export=view&id=1XW0X_olGbta7Ft0sWifZ0zBOLgP9VdcS)

# 2048 Game

**How to play:** Use your arrow keys to move the tiles. Tiles with the same number merge into one when they touch. Add them up to reach 2048!

This game project is originally made by Gabriele Cirulli and updated by me (Mohammad Gayasuddin).

## Steps

1. Created Dockerfile.

![Dockerfile](https://drive.google.com/uc?export=view&id=1caN8vEyLRgZZGlUUmV-ifUb8HjjuBnHQ)


2. Built Docker image from Dockerfile.
3. Pushed Docker image to Google Cloud Container Registry:
   ```bash
   docker build -t gcr.io/project_id/appname:version .
   docker push gcr.io/project_id/2048-game:v01
![Container Registry](https://drive.google.com/uc?export=view&id=1xJ1MmfkhEaR0qORss3W-mwLEuWrdVATs)

4. Created Google Cloud run service
![Cloud Run Service](https://drive.google.com/uc?export=view&id=1VYDmdWBi-i32EICZkQjyGR2CkmGt9B_O)


5. Successfully deploy on google cloud run a serverless environment.
![UI](https://drive.google.com/uc?export=view&id=1XW0X_olGbta7Ft0sWifZ0zBOLgP9VdcS)
