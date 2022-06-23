#Creating google cloud function - python


-> Installed Google cloud CLI using documentation

-> Opened Cloud code terminal from tools
#Deploy cloud function to GCP

-> gcloud auth login
#It triggers our browser and ask to pick an account to use for Google cloud SDK

-> gcloud config set project [my project id]
#to set the project 

-> gcloud functions deploy hello_aditi --region us-east1
-- allow-unauthenticated --memory 128 MB --runtime python39
--timeout 90 --min-instance 0 --max-instance 1 --trigger-http
--service-account hello-aditi-function-sa@[name].gserviceacccount.com

-> Saw my cloud function. It's deployed and active

- > Clicked URL
#to see the output
