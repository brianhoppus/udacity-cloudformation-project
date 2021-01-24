# Udacity CloudFormation Project

## Diagram
![diagram](network-diagram.png)

## Usage
### Create Infrastructure
```
./create.sh udacity-project-networking networking.yml networking-params.json
./create.sh udacity-project-servers servers.yml server-params.json
```

### Delete Infrastructure
```
./delete.sh udacity-project-servers
./delete.sh udacity-project-networking
```

