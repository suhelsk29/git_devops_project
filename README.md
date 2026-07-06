# Docker Flask application

- This application is written on python 
- It shall be deployed on GKE


##Cloud Build
- It is cicd tool in GCP which is used to build software quickly
- Can run multiple cuncurrent build at a same time
- Also integrate it to deploy accross environments such as vm , k8s, firebase, 
- Done in a private network in gcp account
- Serverless
- we can trigger cloud build 
   connect github repo to our cloud build using component cqlled cloud build trigger
   once connected we will configure a trigger(which is a event that is going to start cloud build job)
   event can be push to master brance or mail branch
- what a cloud build willl do that is specified in cloudbuild.yaml code
