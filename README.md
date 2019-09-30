# sam-framework-training
SAM Serverless Framework Training


## Required tools

```
sam --version
aws --version
docker --version
```

## Create Project

```
sam init --runtime python3.6 --name demo
```

## Run demo

```
virtualenv --python=/usr/bin/python3.6 env
source env/bin/activate
cd hello_world/
pip install -r requirements.txt 
cd ..
sam build
sam local invoke --no-event HelloWorldFunction
```
