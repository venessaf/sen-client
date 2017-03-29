# docker-sensu-client

## Installation

Install from docker index or build from Dockerfile

```
docker pull venessaf/sensu-client1
```

or

```
git clone https://github.com/venessaf/sen-client.git
cd docker-sensu-client
docker build -t yourname/sensu-client .
```

## Run

```
docker run -d usman/sensu-client SERVER_IP RABIT_MQ_USER RABIT_MQ_PASSWORD CLIENT_NAME CLIENT_IP
```

