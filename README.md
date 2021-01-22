## command to create docker image 
docker build --tag loadbalancerordersales .
## command to create docker container
docker run --name loadbalancerordersales -d -p 8070:80 loadbalancerordersales