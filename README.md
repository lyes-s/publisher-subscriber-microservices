# Publisher/Subscriber Microservices

## Wiki
* [lyes-s/publisher-subscriber-microservices/wiki/Event-Driven-Microservices](https://github.com/lyes-s/publisher-subscriber-microservices/wiki/Event-Driven-Microservices)

## Technology Stack
* [lyes-s/publisher-subscriber-microservices/wiki/Technology-Stack](https://github.com/lyes-s/publisher-subscriber-microservices/wiki/Technology-Stack)

## Requirements
```
1. Java 11.x.y

2. Maven 3.x.y

3. Docker 3.x.y
```

## Git Clone
```
https://github.com/lyes-s/publisher-subscriber-microservices.git
```

## Development Environment

* [lyes-s/publisher-subscriber-microservices/wiki/Development-Environment](https://github.com/lyes-s/publisher-subscriber-microservices/wiki/Development-Environment)

```
docker-compose --env-file .env up --build -d
```

![Image](https://raw.githubusercontent.com/wiki/lyes-s/publisher-subscriber-microservices/images/Dev-Mode.PNG)

## Developmental Test & Evaluation
* [lyes-s/publisher-subscriber-microservices/wiki/Developmental-Test-&-Evaluation](https://github.com/lyes-s/publisher-subscriber-microservices/wiki/Developmental-Test-&-Evaluation)

## Orchestration with Docker Swarm

* [lyes-s/publisher-subscriber-microservices/wiki/Docker-Swarm-Deployment](https://github.com/lyes-s/publisher-subscriber-microservices/wiki/Docker-Swarm-Deployment)

![Image](https://raw.githubusercontent.com/wiki/lyes-s/publisher-subscriber-microservices/images/Orchestration-Swarm.PNG)

![Image](https://raw.githubusercontent.com/wiki/lsefiane/publisher-subscriber-microservices/images/docker-swarm-visualizer.PNG)

### Deployment
```
docker stack deploy -c docker-stack.yml stack
```
## Orchestration with Kubernetes

![Image](https://raw.githubusercontent.com/wiki/lsefiane/publisher-subscriber-microservices/images/kubernetes-cluster.PNG)

![Image](https://raw.githubusercontent.com/wiki/lsefiane/publisher-subscriber-microservices/images/kubernetes-deployment.PNG)

### Deployment
```
kubectl apply -f k8s/
```

## Enhancements

* OpenApi Implementation 
* Error Handling Implementation 
* Database access/storage Implementation
* Security Implementation

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://github.com/lyes-s/publisher-subscriber-microservices/blob/master/LICENSE.md)
