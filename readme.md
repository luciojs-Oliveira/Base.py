GIt - É uma ferramenta de versionamento de arquivos.

GitHub - É uma plataforma para você hospedar os arquivos.

O que são repositórios, eles são os diretórios ou pastas.
projetos, landig pages etc.

fork é uma cópia de um projeto.

Branch é uma ramificação do projeto.

Commit é uma nova versão do projeto.

Merge é uma junção da brench com a ramificação.

Remote 

Push - É utilizado para colocar o commit feito na maquina local no remote ou github.

Pull - É usado para adicionar novos arquivos do github na maquina local.

Comando basicos do git no computador.

git --version 
Mostra a versão do git.

Após criar a pasta do projeto.

Com o botão direito, clicar em abrir com Bash.

Readme.md = md é a extensão markdow.
É uma linguagem de marcação. É usado para colocar as instruções do projeto.


Após abrir o gitbash.

comando para inicializar um arquivo.
Initialized empty Git repository in C:/Users/Estudos/Desktop/Base.py/.git/
git init = inicializa um repósitorio git vazio.

comando para adicionar arquivos.
git add = manda os arquivos para os stage do git

comando para ver mudanças a serem feitas.
git status = mostra os arquivos a serem commitados. 

comando para commitar um arquivo.
git commit -m "primeiro comit"


comando para trocar de master para main
git brench -M "main"


Comando basicos do github.

Clicar no botão New

Criar um novo repositório.
Create a new repository.

Repostory name.
nome do repositório = nome do projeto.

Description
Descrição. = descrição do projeto.

comando para fazer o link do repositório local com o github.
git remote add origin + endereço do projoto: https://github.com/luciojs-Oliveira/Base.py.git

comando para empurrar os arquivos do repositório local para o github.
git push -u origin main












…or create a new repository on the command line
…ou crie um novo repositório na linha de comando

echo "# logica-funcoes-lista" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/luciojs-Oliveira/nome do arquivo
git push -u origin main


…or push an existing repository from the command line
…ou envie um repositório existente a partir da linha de comando

git remote add origin https://github.com/luciojs-Oliveira/nome do arquivo
git branch -M main
git push -u origin main