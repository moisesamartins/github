<!DOCTYPE html>
<html lang="pt-br">
<header>
<meta charset="UTF8" />
</header>

<h1> Como usar o GitHub na prática</h1>

<h2>História</h2>
<lo>
<h2>Criar conta no GitHub</h2>
<lu>Criar conta do GitHub</lu>
Para criar sua conta entre no site do  
<a href="https://github.com/">GitHub</a></br> 
<lu>Criar um repositório no github</lu></br>
<h3>…or create a new repository on the command line</h3></br>
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
README.md</br>
#Adicionar o arquivo para o commit</br>
git add .\README.md</br>

#Especificar a nossa breanch</br>
git branch -M main</br>

#Fazer o commit para nosso repossitório remoto</br>
git commit -m "Primeiro commit"</br>

#Enviar para repositório remoto</br>
git push -u origin main</br>

git add README.md</br>
git commit -m "first commit"</br>
git branch -M main</br>

git push -u origin main</br></br>

<h3>…or push an existing repository from the command line</h3></br>
git remote add origin https://github.com/moisesamartins/github.git</br>
git branch -M main</br>
git push -u origin main</br></br>

<h3>…or import code from another repository</h3></br>
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.</br>

</lo>
<h3>Fontes Consultadas</h3></br> 
<a href="https://www.youtube.com/watch?v=kB5e-gTAl_s">Curso de Git e Github COMPLETO 2021 [Iniciantes] + Desafios + Muita Prática - Canal Dev Apreder</a></br>
<a href="https://www.youtube.com/watch?v=UBAX-13g8OM">COMO USAR GIT E GITHUB NA PRÁTICA! - desde o primeiro commit até o pull request! 2/2 - Canal Rafaella Ballerini</a></br>
</html>