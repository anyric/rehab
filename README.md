# REHAB
## Description
This repo contains a python flask Web Application for hosting a local NGO profile. The NGO is engaged in senzitizing the local community particularly the youths about the dangers of alcoholism, to rehabilitate and then empower the rehabilitated youths through  training on life skills and entreprenuership.

## Setup
### Dependencies
* [Python 3.8](https://www.python.org/) - popular general-purpose scripting language suited for web development
* [Flask 1.1.1](http://flask.palletsprojects.com/en/1.1.x/) - A web application framework for Python

### Getting Started
Setting up project in development environment
* Ensure Python 3.8 is installed by running:
```
python --version
```
* Ensure pipenv is installed or you can follow the intallation from [PIPENV](https://docs.pipenv.org/)
* Create a folder for the project by running:
```
mkdir myprojectfoldername
```
* cd in to `myprojectfoldername`
* Create a virtualenv using pipenv by running:
```
pipenv shell
```
* Clone the project repo by running:
```
git clone https://github.com/anyric/rehab.git
```

### Running the application
* Export the .env file by running 
```
. .env
```
* Inside the project root folder i.e rehab/, run the command below in your console
```
flask run
```
* Navigate to `http://127.0.0.1:5000/`

## Developer and Maintainer
* Anyama Richard