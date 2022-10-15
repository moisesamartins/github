<html>
<h1> Como usar o GitHub na prática</h1></br>
1 - Criar uma conta no github (https://github.com/)</br> 
2 - Criar um repositório no github</br>
- …or create a new repository on the command line</br>
Link: https://github.com/moisesamartins/github.git</br></br>

Configurações global</br>
 git config --global user.name "Moisés Martins"</br>
 git config --global user.email "moisesam@gmail.com"</br>

#Criar os diretórios no repositorio remoto</br>
git init

#Conectar com o repositório remoto</br>
git remote add origin https://github.com/moisesamartins/github.git</br>

#Verificar o estatus</br>
git status</br>

#Criar um arquivo</br> 
README.md
#Adicionar o arquivo para o commit
git add .\README.md

#Especificar a nossa breanch
git branch -M main

#Fazer o commit para nosso repossitório remoto
git commit -m "Primeiro commit"

#Enviar para repositório remoto
git push -u origin main

git add README.md
git commit -m "first commit"
git branch -M main

git push -u origin main

- …or push an existing repository from the command line
git remote add origin https://github.com/moisesamartins/github.git
git branch -M main
git push -u origin main

- …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

3 - 

</html>