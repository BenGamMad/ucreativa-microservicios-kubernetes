# Kuberntes Microservice Application

## How to run it?


Execute the following command

```sh
kubectl create -f .
```

## How to access the application?

Use the port 30000 to access the application.

```sh
[IP_ADDRESS / localhost]:[30000]
```

If you want to check the nodePort, run this command:

```sh
kubectl get services
```

## Architecture Diagram

![Microservice Application](/architecture.png "Microservice Application")




