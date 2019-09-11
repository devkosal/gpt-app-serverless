You need to use the contents from these files to follow along the instructions here
My set up took 2GB memory to work properly. 

https://medium.com/swlh/deploying-pytorch-models-to-serverless-environments-8fcd25dc7b5c


Once your model is deployed, you can use the following command to test the function:

`curl -XPOST https://us-central1-URL-FROM-GCP_UNDER_TRIGGER -H 'Content-Type: application/json' -d @test.json`
