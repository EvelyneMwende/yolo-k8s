# Yolomy Project Link
- http://35.194.225.167/

# Choice of the Kubernetes Objects used for deployment (Use of - or the lack of use - of StatefulSets for storage solutions).
Pod- Pods are the smallest deployable units of computing that you can create and manage in Kubernetes.Pods represent the processes running on a cluster

Persistent volume-  provide persistent storage for your containerized applications: even after restarting, the application pod will still have access to the previously stored data.

Persistent Volume Claim -A PersistentVolumeClaim (PVC) is a request for storage by a use
# Method used to expose your pods to internet traffic.
Service - services connect a set of pods to an abstracted service name and IP address.They provide discovery and routing between pods. For example, services connect an application front-end to its backend, each of which running in separate deployments in a cluster.

# Requirements
Make sure that you have the following installed:
- [node](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04) 
- npm 
- [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/) and start the mongodb service with `sudo service mongod start`

## Navigate to the Client Folder 
 `cd client`

## Run the folllowing command to install the dependencies 
 `npm install`

## Run the folllowing to start the app
 `npm start`

## Open a new terminal and run the same commands in the backend folder
 `cd ../backend`

 `npm install`

 `npm start`

 ### Go ahead a nd add a product (note that the price field only takes a numeric input)