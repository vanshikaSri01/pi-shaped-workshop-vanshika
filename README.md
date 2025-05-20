# pi-shaped-workshop-vanshika

**1. Why is Docker useful in building and deploying microservices?**

Docker allows developers to:

-   Isolate each microservice in its own container.
-   Ensure consistent behavior across environments.
-   Package dependencies and runtime with the app for reproducibility.
-   Deploy and scale services independently (e.g., payment vs. order services).

**2. What's the difference between a Docker image and a container?**

 Docker Image: A read-only blueprint (includes code, libraries, config).
 
 Docker Container: A running instance of that image.

 When scaling, you run multiple containers from the same image to handle load.


**3. How does Kubernetes complement Docker when running at scale?**

 Docker runs single containers.

 Kubernetes manages thousands of containers with features like:

-   Auto-scaling
-   Load balancing
-   Self-healing (restarts failed containers)
-   Rolling deployments

    Ideal for complex systems (like banking or e-commerce) where high availability is crucial.

Link to Ducker Hub Image: https://hub.docker.com/repository/docker/vanshikasri01/hello-docker-app/general
