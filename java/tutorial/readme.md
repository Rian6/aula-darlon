# Aula Docker - Dev Containers

###### Vamos abrir um container e vincular a um repositorio do git 

* Baixar a extensão do vscode Dev Containers
* No diretorio do container criar um arquivo chamado de .devcontainer.json
    Esse arquivo serve para extensão reconhecer    
    ![Alt text](image.png)

* Fechar e abrir novamente o vscode
* Quando abrir essa mensagem no vscode, clique em reabrir no contêiner: 
![Alt text](image-1.png)

obs: Você precisa reabrir somente a pasta java no vscode, pois a extensão procura na raiz do projeto o arquivo de configuração

* criar arquivo java com qualquer coisa, compilar e executar dentro do vscode

* A ideia é sempre que executar um arquivo ali ele executa dentro do container e quando estiver la no git a ideia é a mesma

* Terminal do vscode vai ficar assim quando estiver dentro do container: 

![Alt text](image-2.png)

* No arquivo de configuração você consegue também instalar uma nova extensão somente para o container:

![Alt text](image-3.png)

para adicionar copie o id da extensão aqui:

![Alt text](image-4.png)

e cole na lista em formato de string assim:

![Alt text](image-5.png)

* Reinicie o vscode dentro do container para aplicar kas extensões no container