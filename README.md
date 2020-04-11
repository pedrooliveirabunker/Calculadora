"# Calculadora" 

Primeiro Exemplo a usar o GIT :) :)

MOre :)


GIT

Version Control System
3 stages
- Commited
- Modified
- Staged

CMD

*Configuraçoes de cada utilizador*
git config --global user.name "Pedro Oliveira"

git config --global user.email "Pedro.alex.Oliveira@gmail.com"

Sem o global podemos identificar um só projeto

*Verificar as configuraçoes do GIT
git config --list
git config user.name

*Help
git help

* Inicializar o GIT
Escolher o diretorio que queremos....cd
git init

dir/a vemos o diretorio .git

passar este ficheiros para a Cloud
- GitHub
- GitLab
- BitBucket

*Criar conta no GitHub

* Criar um repositorio no GitHub
Repositorio Https
https://github.com/pedrooliveirabunker/Calculadora.git
OU * criei ficheiro readme.md com o interior "# Calculadora"

…or create a new repository on the command line
echo "# Calculadora" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/pedrooliveirabunker/Calculadora.git
git push -u origin master

Vamos inserir todos os outros ficheiros
git add .
Adicionar texto ao Add anterior
git commit -m "First Commit"

git push -u origin master


Alterei o ficheiro Readme
git add .
git commit -m "Second Commit"
git push -u origin master

Status mais simples
git status -s
M - modified
A - new file added
?? - new file not added


Status com mais pormenor

git diff --staged
git diff --staged --no-renames



git status

git log
