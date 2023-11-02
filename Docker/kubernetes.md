# What is Kubernetes (K8)

Allows you to create a group of containers that allows you to automatically scale, load balance and deploy among other functions. Essentially automates container management and simulates an ASG using containers.

![Alt text](image-6.png)

### Why k8

K8 is used to build cloud microservice based apps. It's use of many containers at once with autoscaling functionality allows you to simulate an application if it was deployed on the cloud. Also, as it automates the creation of an ASG this has practical uses in actual app deployments as it allows you to automatically create an ASG for your application.

### Benefits of K8

- **Saves time**: As you're automating the creation of an ASG, you save time you would usually be spending creating it manually.
- **Open source**: This means K8 has a lot of community support and allows you to tweak K8 code for whatever purpose you need it for.
- **Multi-cloud compatible**: K8 allows you to deploy containers on multiple different cloud platforms, giving you flexibility for what cloud providers you want to use for what deployments, potentially saving you money as services vary in price between providers.
- **Enables easy scaling**: As K8 automates the creation of what is functionally similar to an ASG, it means K8 can be used to scale your applicaiton to meet demands.
- **Cheap**: K8 is cheaper than many of it's alternatives, and also provides the base software for free.

### K8 architecture

![Alt text](image-7.png)

K8 works by essentially deploying 'pods' which contain copies of your contiainer.

### When not to use K8

K8 is designed for microservice based applications, and isn't appropriate for all cases. You shouldn't use K8 if...
- Your application is monolithic
- Your application is small enough that the components can be hosted on a couple of containers 
- You know you won't be recieving high amounts of traffic.

