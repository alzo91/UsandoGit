# UsandoGit
* Aprendendo a usar o github

### Comando de configurações Globais

1. git config --global user.name "Seu Nome"
2. git config --global user.email "seuemail@dominio.com.br"

### Alguns Comandos para ser usados no terminal** na pasta do projeto

1. git init 

2. git status

3. git add -A

4. git commit -m "inclusão dos arquivos"

5. git remote add origin https://github.com/alzo91/UsandoGit.git

6. git status

7. git push -u origin master **podemos adicionar o parametro --force**

8. tree .git **Permite visualizar a estrutura dos arquivos gerados pelo gi**

9. git pull origin master **Não é aconselhado, pois faz merge automáticamente**

10. git remote -v **vendo para qual git remoto esta configurado**

11. git fetch **Faz download do conteudo para ser atualizado**

12. git diff master origin/master

13. git merge origin/master

### Comando de Log

#### git log --oneline --decorate --all --graph

## Configurando terminal com usuário e senha
#### git config credential.helper store
