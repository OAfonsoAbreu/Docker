# Docker
Projeto para reunir conhecimento e testes do Docker


## Comandos

__docker container run * <imagem> * * <comando> * __ : Baixa imagem, Cria container, executa container, executa o comando e finaliza container.
  
**docker container run -it *<imagem>* *<comando>* **: Baixa imagem, Cria container, executa container, executa o comando e mantém container ativo e permitindo interação via terminal.
  
**docker container start *<containerID>* **: Inicia container já criado.
  
**docker container exec *<containerID>* *<comando>* **: Executa comando em container em execução.
  
**docker container stop *<containerID>* **: Para um container em execução.
  
**docker container run --name *<nome>* *<imagem>* **: Cria um container com um nome especifico.
  
**docker container rm *<containerID>* **: Remove um container criado.
  
****:
