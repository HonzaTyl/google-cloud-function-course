# Google Cloud Functions Course
## starting a project
To start a new project in Google Cloud, we can go to the 
[Firebase Console](https://console.firebase.google.com) or create it from [Google Cloud Platform Console](https://console.cloud.google.com)
## Creating a virtual environment
First we have to install "python3-venv" with the following command:
```
sudo apt install python3-venv
pip  install python3-venv
```
Then, we execute the following command:
```
python -m venv venv
```
To activate the virtual environment we do:
```
source venv/bin/activate
```

Ok, so, unfortunately, there is no source  command in Windows. 
Also, the path of the activate  file changes in Windows. 
So in order to activate your new brand virtual environment in Windows, 
you should run the following command: venv\scripts\activate.bat


```
venv\scripts\activate.bat
```


```
pip install -r requirements.txt
```