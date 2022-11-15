# Installation
## 1. Build the app with the fellowing command :
````
docker compose build --pull --no-cache
````
## 2. Launch the app :
````
docker compose up
````

## 3. Enter the php container :
````
docker compose exec php /bin/sh
````

## 4. Install setoolkit requirements :
````
cd ../social-engineer-toolkit/
pip3 install -r requirements.txt
python3 setup.py
````

## 5. Lauch setoolkit and accept the agrements :

````
setoolkit
y
````
