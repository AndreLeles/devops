## Portfolio SRE/DevOps - Andre Leles


### 1. Conhecimentos, habilidades e tecnologias necessárias

* _**Linux**_
* _**Shell Script**_
* _**NodeJS**_
* _**SpringBoot**_
* _**Docker**_
* _**Kubernetes**_
* _**Git**_
* _**GitFlow**_

### 2. Premissas do ambiente

* Utileza o script que esta na pasta _**vagrant**_  para criação da VMs. 
* subir o jenkins server que esta na pasta _**jenkin-server**_  utilizando o docker-compose
* Pode ser utilizado o minishift no virtualBox  [minishift](https://blog.4linux.com.br/minishift-openshift-origin-como-ambiente-de-desenvolvimento/)
*  Elabore uma esteira utilizando o jenkins e pipeline com jenkinsfile para construção das aplicação

### 3. Descrição do ambiente

<b>Etapa 1:</b>
* Criar um contêiner com a aplicação nodeJS disponivel em "fontes/frontend"; 
* Criar um contêiner com a aplicação SpringBoot disponivel em "fontes/backend"; 


<b>Etapa 2:</b>
* Criar um pipeline utilizando jenkins que irá construir e registrar os contêineres na sua conta pessoal no Docker Hub a cada _**push**_ 

<b>Etapa 3:</b>
* Crie o ambiente utilizando o minishift

<b>Etapa 4:<b>
* Colocar a aplicação para funcionar no minishift, com namespace chamado "challenge";

_**Entrega:**_ Os objetos - deployment, service, volume, volumeclaim, ingress, Dockerfile, jenkinsfile

