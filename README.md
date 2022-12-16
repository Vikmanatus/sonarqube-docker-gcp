# sonarqube-docker-gcp

A simple repository to demonstrate how to deploy a Sonarqube server to Google Cloud Compute Engine

To setup the server we will follow this [official documentation](https://docs.sonarqube.org/latest/setup-and-upgrade/install-the-server/)

## Run the project locally

To run the project locally, please open a terminal and run the following command:

```bash
docker-compose up -d
```
### 🗒 Information

The `docker-compose.yml` file use a custom image for M1 machines. If you're not running the project on a M1 machine, please change the following line:

```yml
image: davealdon/sonarqube-with-docker-and-m1-macs
To
image: sonarqube:community
```

## 🗒 Notes

- [Used to fix Sonarqube Docker image for Mac OS M1](https://hub.docker.com/r/davealdon/sonarqube-with-docker-and-m1-macs)
