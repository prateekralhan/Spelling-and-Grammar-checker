# Spelling and Grammar checker
A simple UI based spelling and grammar checker built with :heart: powered by gingerit which is a wrapper around the gingersoftware.com API.

<kbd>
<img src="https://user-images.githubusercontent.com/29462447/110236764-ac0ab100-7f5d-11eb-96db-3d014b8d12ea.gif" data-canonical-src="https://user-images.githubusercontent.com/29462447/110236764-ac0ab100-7f5d-11eb-96db-3d014b8d12ea.gif"/> 
</kbd>

## Installation:
***pip install -r requirements.txt*** does the needful as usual :wink:

## Usage:
* Open the terminal in the same directory as this cloned repo and run the command ***streamlit run main.py***
* The default browser will pop up and load the UI in front of you on **http://localhost:8501**.

<kbd>
<img src="https://user-images.githubusercontent.com/29462447/110236115-1c173800-7f5a-11eb-88ab-3d50d3b54e68.png" data-canonical-src="https://user-images.githubusercontent.com/29462447/110236115-1c173800-7f5a-11eb-88ab-3d50d3b54e68.png"/> 
</kbd>

&nbsp;
### Running the Dockerized App
1. Ensure you have Docker Installed and Setup in your OS (Windows/Mac/Linux). For detailed Instructions, please refer [this.](https://docs.docker.com/engine/install/)
2. Navigate to the folder where you have cloned this repository ( where the ***Dockerfile*** is present ).
3. Build the Docker Image (don't forget the dot!! :smile: ): 
```
docker build -f Dockerfile -t app:latest .
```
4. Run the docker:
```
docker run -p 8501:8501 app:latest
```

This will launch the dockerized app. Navigate to ***http://localhost:8501/*** in your browser to have a look at your application. You can check the status of your all available running dockers by:
```
docker ps
```
