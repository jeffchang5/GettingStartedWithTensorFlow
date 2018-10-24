# Data Science Environment

The objective of this repo is to provide consistentcy between many environments and ensures the same tooling is being used.

## Getting Started

1. Follow the installation [instructions](https://www.docker.com/get-started) for Docker.

2. Install Docker container

   * **Install from Docker Hub**

     ```bash
     docker pull jeffchang32/jupyter-docker-env
     ```

   * **Install from GitHub**

     ```git clone https://github.com/jeffchang5/jupyter-docker-env.git```

3. Change directory to project folder.

### Docker-Compose

1. Run `docker-compose up`

### Manually

1. Run `docker build -t <container name> .` in the directory that includes this project to start installing your container. `<container name>` is what you wish to name your container.
2. Run `docker run -p 8888:8888 <container_name>` to start Jupyter Notebook.

You should see output in your terminal that looks like this.

```
Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://(ed5a9f8dd10d or 127.0.0.1):8888/?token=de534daa0accdcf4d7560cc39af18fc0c155ea155c9fb7bd

```

Copy the URL into your browser to access Jupyter.

Store data into mounted data folder and notebooks into notebooks folder.# GettingStartedWithTensorFlow
