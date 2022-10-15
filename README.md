Como usar o GitHub na prática
1 - Criar uma conta no github (https://github.com/) 
2 - Criar um repositório no github
- …or create a new repository on the command line
Link: https://github.com/moisesamartins/github.git

Configurações global
 git config --global user.name "Moisés Martins"
 git config --global user.email "moisesam@gmail.com"

echo "# github" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/moisesamartins/github.git
git push -u origin main

- …or push an existing repository from the command line
git remote add origin https://github.com/moisesamartins/github.git
git branch -M main
git push -u origin main

- …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

3 - 