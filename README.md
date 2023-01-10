# K8s-wordpress-application
This repository contains yaml files to launch Wordpress application on Kubernetes.

You can use the code from this repository to launch multi-tier application on kubernetes. The frontend is Wordpress and the backend is mysql database.

To launch the applicatin run secret.yaml file using following command
`kubectl apply -f secret.yaml`

Then run the mysql.yaml file and wordpress.yaml
`kubectl apply -f mysql.yaml`
`kubectl apply -f wordpress.yaml`
