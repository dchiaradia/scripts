# DESCRICAO
Exemplos de scripts para devops na AWS


### CRIAR SERVIÇO ECS EM UM CLUSTER

1. Realizar upload do arquivo ecs-service-template.json no terminal da AWS e executar o comando abaixo. 

```bash
aws ecs create-service --cli-input-json file://ecs-service-template.json
```
