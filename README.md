# docker_manual
My personal docker manual



listando imagens

```docker images````

listando containers

```docker ps``

criando um volume para persitencia 
```docker volume create --name dados_x```

Cria dentro do container uma pasta persistente com o caminho `/arquivo/`
```docker run -v panicio:/arquivos/ -it  continuumio/miniconda /bin/bash```

Entrando no docker `continuumio/miniconda` e inicializando o bash
```docker run -i -t continuumio/miniconda /bin/bash```


