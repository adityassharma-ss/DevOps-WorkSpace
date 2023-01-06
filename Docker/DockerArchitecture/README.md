<h1 align="center"> Architecture </h1>

Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package.

The Docker architecture consists of the Docker Engine, which is a client-server application. The Docker Engine consists of a server, a REST API, and a command-line interface (CLI). The Docker server is a daemon that does all the heavy lifting of building, running, and distributing Docker containers. The REST API is used to communicate with the Docker daemon and instruct it to build, run, and manage containers. The CLI is a tool that allows users to interact with the Docker daemon through commands and scripts.

Containers are a lightweight alternative to virtual machines. Whereas virtual machines emulate a whole operating system, containers allow applications to use the same Linux kernel as the host machine, but only include the libraries and dependencies required for the specific application. This makes containers much more lightweight and efficient than virtual machines.

Containers are created from Docker images, which are essentially templates for creating containers. Docker images are built from a series of layers, each of which represents a specific instruction or change made to the image. When a container is created from an image, it takes the form of a read-only layer on top of the image. Any changes made to the container, such as writing new files or installing software, are stored in a writable layer on top of the read-only layer. This allows multiple containers to share the same base image, while still allowing each container to have its own unique set of changes and modifications.

In summary, Docker is a tool that allows developers to package applications into lightweight containers, which can be easily deployed and run on any platform that supports Docker. The Docker architecture consists of the Docker Engine, which is a client-server application that manages the creation, deployment, and execution of Docker containers. Containers are created from Docker images, which are templates that define the contents and instructions for creating a container.