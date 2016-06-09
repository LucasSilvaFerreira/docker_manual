# docker_manual
My personal docker manual



listando imagens

```docker images```

listando containers

```docker ps```

criando um volume para persitencia 

``` docker volume create --name dados_x ```

Inicializa dentro do container uma pasta persistente com o caminho `/arquivo/`

```docker run -v dados_x:/arquivos/ -it  continuumio/miniconda /bin/bash```

criando container docker `continuumio/miniconda` e inicializando o bash:

```docker run -v dados_x:/arquivos/ --name='teste_panicio' -it  continuumio/miniconda /bin/bash ```

Para deixa o container digite `exit`

Para inicializar um container já usado digite:
```
docker start meu_container  
docker attach meu_container

```



