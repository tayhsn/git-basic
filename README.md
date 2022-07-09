# <div align="center"> Comandos Básicos  :memo: ​ </div>

<div align="center"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/tayhsn/git-basic?logoColor=blue&style=social"> <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/tayhsn/git-basic?logoColor=yellow&style=social"> </div>

### Comandos básicos para iniciar com Git :octocat:

Você pode copiar esse repositório para o seu perfil com FORK ou salvá-lo com uma STAR. :sparkles:

<hr>

### Configurando o git

Se você acabou de instalar o Git, você precisará configurar o seu usuário para realizar os passos abaixos, e é bem simples:

- Configurando o e-mail:

  ​	```git config --global user.email "seu email do github aqui" ```

- Configurando o usuário:

  ```git config --global user.name "Nome ou Apelido"```

Pronto! Pode continuar..

<hr>

### Iniciando o versionamento

> Há 2 formas de iniciar esse processo. 
> A primeira forma é clonando um repositório já existente no Github, utilizando o comando ```git clone URL```, isso substitui os passos 1 e 4 desse passo-a-passo. 
> A segunda forma é como fazemos a seguir, iniciando o versionamento direto da máquina e posteriormente linkando a um repositório remoto. 
> As duas formas geram resultados iguais!


1. Inicia monitoramento da pasta de trabalho [working directory]

  ​		``` git init ```

2. Adiciona os arquivos da pasta na área de envio [staging área] 

  ​		```git add . ```
  
  > O ```.``` indica que está enviando todos os arquivos contidos na pasta atual, é uma forma prática de enviar muitos arquivos de uma vez.

3. Commita as alterações  

  ​		```git commit -m "initial commit"```

  > **Boas práticas: aprenda sobre commits semânticos: conventionalcommits.org**

4. Aponta o repositório remoto que o Git deve enviar seus arquivos

  ​		```	git remote add origin URL ```

  > Para apontar pra um novo repositório, ou atualizar o nome do repositório [porque voce trocou o nome no github, por exemplo], use ```git remote set-url origin novaURL```

5. Empurra os arquivos para o repositório indicado

  ​		```git push -u origin main```
  
  > -u é uma tag que linka o repositório indicado a pasta de trabalho, assim nos próximos envios pode-se usar apenas ```git push ```

 <hr>
 
### Colaborando em um projeto


1. Clone o repositório do github:

  ​		```git clone URL```

2. Crie a sua própria branch de desenvolvimento

  ​		```git checkout -b "minha-branch"```
  
  > ```git checkout -b``` é uma junção dos comandos git branch & git checkout, esse comando cria a branch e automaticamente se move pra ela. 

> Se você estiver fazendo um projeto com outras pessoas simultaneamente, antes de commitar as suas alterações é necessário atualizar o seu repo local com as alterações dos seus colegas, para isso, utilize o comando```git pull```

3. Commite suas alterações

  ​		```git commit -m "mensagem"```

4. Envie suas alterações para o repositório 

  ​		```git push -u origin "minha-branch" ```
  
5. Na página do repositório, irá aparecer uma mensagem sobre suas alterações, clique em "compare e pull request", informe o que se trata as suas alterações no campo indicado e submeta para review e merge.

  > Saiba mais sobre contribuir em projetos do GitHub aqui: https://github.com/firstcontributions/first-contributions/blob/master/translations/README.pt_br.md

<hr>

### Acompanhando o versionando


* Acompanhar o monitoramento da pasta

  ​		```git status```
  
* Ver todos os commits do repositório (aperte Q para sair do log)

  ​		```git log```
  
* Ver somente o último commit  

  ​		```git show```

<hr>

### Atualizando o git pela cli


* Atualiza a versão do seu git bash pela linha de comando (SOMENTE WINDOWS)

  ​		```GIT UPDATE-GIT-FOR-WINDOWS```

<hr>

Documentação oficial: https://git-scm.com/docs

Git Command Explorer: https://gitexplorer.com/
