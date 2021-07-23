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


* Inicia monitoramento da pasta de trabalho/working directory

  ​		``` git init ```

* Adiciona os arquivos da pasta na área de envio/staging área/index

  ​		```git add * ```

* Commita as alterações  

  ​		```git commit -m "initial commit"```

  > **Boas práticas: aprenda sobre commits semânticos em: conventionalcommits.org**

* Aponta o repositório remoto que o Git deve enviar seus arquivos

  ​		```	Git remote add origin URL ```

  > Para apontar pra outro repositório, por exemplo, mudou o nome do repositório no github, use:
  >
  > ```git remote set-url origin novaURL```

* Empurra os arquivos para o repositório indicado

  ​		```git push -u origin main/master```
  
  > -u é uma tag que linka o repositório indicado a pasta de trabalho, assim nos próximos envios use oapenas ```git push ```

 <hr>
 
### Colaborando em um projeto


* Clone o repositório do github:

  ​		```git clone URL```

* Trazendo as alterações do repositório clonado para o seu local em tempo de desenvolvimento

  ​		```git pull```

* Commitando

  ​		```git commit -m "mensagem"```

* Enviando suas alterações para o repositório

  ​		```git push -u origin main ```

  > Saiba mais sobre contribuir em projetos do GitHub aqui: https://github.com/firstcontributions/first-contributions/blob/master/translations/README.pt_br.md

<hr>

### Acompanhando o versionando


* Acompanhar o monitoramento da pasta

  ​		```git status```
  
* Ver todos os commits do repositório (aperte Q para sair do log)

  ​		```git log```
  
* Ver o último commit  

  ​		```git show```

<hr>

### Atualizando o git pela cli


* Atualiza a versão do seu git bash pela linha de comando (WINDOWS)

  ​		```GIT UPDATE-GIT-FOR-WINDOWS```

<hr>

Documentação oficial: https://git-scm.com/docs

Git Command Explorer: https://gitexplorer.com/
