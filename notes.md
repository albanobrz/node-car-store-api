# Learning notes

## General
- as classes ISpec e Spec por exemplo, são interface e a classe mesmo
- dentro do Spec, a classe ISpec é chamada, como forma de implement, ou seja, Spec implements ISpec, que vai ter que conter tudo que está dentro da ISpec (interface)
- tudo que começa com maiusculo é classe ou interface. o que começa com minúsculo é variável mesmo, ou objeto
- repositories é como se fosse o banco de dados, onde arquiva os dados

## Flow

- primeiro cria as classes e serviços, depois que cria as rotas, é por último
- service (camada mais acima, é chamado um repository para ele)
- o serviço é chamado na rota. A rota chama o Controller. Dentro do Controller, é chamado o UseCase. Dentro do UseCase é chamado o Repository.

## Node

- Existe o fs, recurso nativo do próprio node, para ler por partes arquivos (streaming) 

## Docker

- comandos:
    docker ps -a : lista todos os containers
    docker rm (id do container) : remove o container
    docker start (id do container) : começa o container
    docker stop (id do container) : para de rodar o container
    