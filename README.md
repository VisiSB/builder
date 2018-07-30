# builder
Quay builder config for kubernetes cluster

1) Make a secret named "pull-secret" inside namespace quay-deployment
2) Change the server environment variable value with your quay instance IP/domain and you're good to go!

Note: 
Default number of replicas is 3. Change by your needs
