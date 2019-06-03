# DBD Mongo DB
All the code is contened at db.py

# Postman
1. Download and Install [Postman](https://www.getpostman.com/downloads/)
2. The Posman Collections URI are at [Postman-platzi-mongo](https://www.getpostman.com/collections/ffcbfb5c8d5cd2dc52d2)
3. Import the Collections [Instructions](https://learning.getpostman.com/docs/postman/collections/data_formats/#exporting-and-importing-postman-data)

## Install Anaconda 
The quick and easiest way to run the project is installing [Anaconda](https://www.anaconda.com/distribution/).

After install Anaconconda with success, go to the project directory and open command prompt of anaconda and run the next commands: 
```
# In the project directory
cd platzi-mongo
# Create a new environment
conda create --name platzi-mongo
# To enable the environment
conda activate platzi-mongo
# To disable the environment
conda deactivate
```
## Install dependencies of the project
With active environment, install the requirements with the command below:
```
pip install -r requirements.txt
```
## Environment variables necessary to execute the project
After install the requirements.txt run the comands below with your project details.
Make sure to complete the correct values in mongodb+srv://userMongoDB:passworMongoDB@clusterName-xxxx.mongodb.net 
```
The user, password and cluster URL can be found in the MongoDb Atlas Dashboard
```
```
MacOS/Linux
export FLASK_APP=platzi-api
export FLASK_ENV=development 
export PLATZI_DB_URI=mongodb+srv://userMongoDB:passworMongoDB@clusterName-xxxx.mongodb.net

Windows
set FLASK_APP=platzi-api
set FLASK_ENV=development 
set PLATZI_DB_URI=mongodb+srv://userMongoDB:passworMongoDB@clusterName-xxxx.mongodb.net
```

## Init the server for dbd-mongodb project
```
flask run
```
