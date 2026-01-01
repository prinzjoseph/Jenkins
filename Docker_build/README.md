Jenkins Task from Kodekloud Engineer

Create/configure a Jenkins pipeline job named nginx-container, configure it to run on server App Server 1.


The pipeline can have just one stage named Build. (name is case sensitive)


In the Build stage, build an image named stregi01.stratos.xfusioncorp.com:5000/nginx:latest using the Dockerfile present under the Git repository. stregi01.stratos.xfusioncorp.com:5000 is the image registry server. After building the image push the same to the image registry server.

Jenkins file Dependencies:

Need Plugins:
Git,
Docker Pipeline
