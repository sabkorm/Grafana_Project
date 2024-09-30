# Grafana Dashboard Project

In this project I've created a custom Grafana dashboard to monitor a kubernetes cluster hosted on Kind nodes, using a Prometheus datasource. 
The dashboard applies chained variables (The cluster is running a namespace, containers, and pods, on nodes), and monitors several parameters, including CPU usage, memory usage, network activity, etc.

## The Dashboard

### Chained Variables:

![](Screenshots/chainedvariables.PNG)

### Node:

![](Screenshots/node.PNG)


### Namespace:

![](Screenshots/namespace.PNG)


### Pod:

![](Screenshots/pod.PNG)


### Container:

![](Screenshots/container.PNG)
