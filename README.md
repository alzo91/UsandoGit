# UsandoGit
* Aprendendo a usar o github

### Comando de configurações Globais

1. git config --global user.name "Seu Nome"
2. git config --global user.email "seuemail@dominio.com.br"

### Alguns Comandos para ser usados no terminal** na pasta do projeto

###### 1. *Iniciando projeto*
- git init

###### 2.*Vendo o status do projeto*
- git status

###### 3. **Incluindo as modificações e arquivos**
- git add -A

###### 4. *Após a inclusão de arquivos ou modificações*
- git commit -m "inclusão dos arquivos"

###### 5. *Apenas configuramos o git remote quando iniciamos o projeto uma unica vez*
- git remote add origin https://github.com/alzo91/UsandoGit.git
- Token
- [x] git remote set-url origin https://TOKEN@github.com/LOGIN/app.git

###### 6. *Realizando consulta de status de arquivos e modificações*
- git status

###### 7. **Comando abaixo serve para enviarmos as alterações e inclusões para o git**
- git push -u origin master 
- [x] **observação:** podemos adicionar o parametro **--force**

###### 8. *Visualizando a estrutura dos arquivos gerados pelo git*
- tree .git

###### 9. *Recebendo as modificações efetuadas e/ou pegando o codigo mais atualizado do repositorio*
- git pull origin master 
- [x] Observação: **Não é aconselhado, pois faz merge automáticamente**
  
###### 10. *Visualizando qual git remoto esta configurado*
- git remote -v

###### 11. *Recebendo as modificações efetuadas e/ou pegando o codigo mais atualizado do repositorio*
- git fetch 
- [x] Observação **Apenas faz o download do conteudo para ser atualizado, não inclui o merge**

###### 12. *Vendo o que foi feito de modificações*
- git diff master origin/master

###### 13.*Realizando merge do conteudo que foi feito download pelo* _git fetch_
- git merge origin/master

### Comando de Log

#### git log --oneline --decorate --all --graph

## Configurando terminal com usuário e senha
#### git config credential.helper store


