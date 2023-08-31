# Google Cloud Function Course
## Starting a project
To start a new project in Google Cloud, we can go to the [Firebase 
Console](https://console.firebase.google.com/) or creat it from [Google 
Cloud Platform Console](https://console.cloud.google.com/)
## Creating a virtual environment
First we have to install `python3-venv` with the following command:

```
sudo apt install python3-venv
```

Then, we execute the following command:

```
pyton3 -m venv venv
```

To activated our virtual environment:

```
source venv/bin/activate
```

In order to add new packages to our virtual environment we create a file called `requirements.txt` and execute the following command:

```
pip install -r requirements.txt
```