Create Kubernetes config to launch Clickhouse & Superset pods in Minikube & connect them

Prerequisites:

Minikube: Local Kubernetes cluster management tool.
kubectl: Kubernetes command-line tool for interacting with clusters.
Docker: Containerization platform knowledge for building and managing images.

Steps : 

Create statefulset clickhouse deployment with persistent storage of 10gb (expose 9000 native port as superset only connect to it)
Create deployment of superset superset ( keep this while doing it Doc)
Open superset url in the browser
Connect clickhouse to superset. 
Go to superset url
Go to Data > Databases > (+Database button) > Choose clickhouse from list > add clickhouse url like Doc )
Click connect
