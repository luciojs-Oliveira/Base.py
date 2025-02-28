                    Como usar o git e github.

fazer uma conta no github
1º ........... email
2º ........... senha = (colocar senha forte)

............................................................................................................

Configuração no computador

1º .................. instalar o git no computador.

2º .................. Baixar o git com instalador (Standalone Installer)

3º - habilitar as variáveis de ambientes.

....... iniciar

....... editar variáveis de ambientes.

....... variáveis de ambientes.

....... variaveis do sistema.

....... path

....... editar

....... adicionar a variável; exe : C:programas\Git\cmd

4º - configurar a cominicação do git com o github

git config --global user.email "you@example.com" git config --global user.email "luciojs.oliveira@gmail.com"

git config --global user.name "Your Name" git config --global user.name "luciojs-Oliveira"

................................................................................................................

Atenção = Caso Não tenha um repositório local use esse comando para fazer um repositório local.

…or create a new repository on the command line echo "# GitGitHub" >> README.md git init --------------------------------------------------------------------------- inicializa um projeto git add README.md git commit -m "first commit" git branch -M main git remote add origin https://github.com/luciojs-Oliveira/GitGitHub.git git push -u origin main

Atenção = Caso já tenha um repositório local.
…or push an existing repository from the command line git remote add origin https://github.com/luciojs-Oliveira/GitGitHub.git git branch -M main git push -u origin main

................................................................................................................

comandos

git --version ------------------------------------------------------------------ Exibe a versão do git

git add . ---------------------------------------------------------------------- Adiciona todos os arquivos

git commit -m "mensagem do commit" --------------------------------------------- Adiciona uma mensagem ao commmit

Atenção = trocar protocolo Http para SSH
git remote add origin git@github.com:luciojs-Oliveira/GitGitHub.git ------------- Conecta repositório local ao git hub.

git push -u origin main --------------------------------------------------------- Envia os arquivos para o github.


gerando chave ssh pelo terminal

comando : ssh-keygen -t ed25519 -C "luciojs.oliveira@gmail.com"

Após gerar a chave, ela estará na pasta 'ssh'. colar está chave no git hub = Add new SSH Key.


                **(Para excluir um repositório no github: Danger Zone)

Entrar no repositório que deseja excluir.

Settings

Descer até o final da página.

Escolher a opção: Delete this repository.

Isso excluirá permanentemente o repositório luciojs-Oliveira/GitGitHub, wiki, problemas, comentários, pacotes, segredos, execuções de fluxo de trabalho e removerá todas as associações de colaboradores. This will permanently delete the luciojs-Oliveira/GitGitHub repository, wiki, issues, comments, packages, secrets, workflow runs, and remove all collaborator associations.

Quero excluir este repositório I want to delete this repository

Eu li e compreendi esses efeitos I have read and understand these affects

Para confirmar, digite "luciojs-Oliveira/GitGitHub" na caixa abaixo To confirm, type "luciojs-Oliveira/GitGitHub" in the box below

..............................................................................................................

O que é GIt ?
R: É uma ferramenta de versionamento de arquivos.

..............................................................................................................

O que é GitHub ?
R: É uma plataforma para você hospedar os arquivos.

..............................................................................................................

O que são repositórios ?
R: São os diretórios ou pastas, projetos, landig pages etc.

..............................................................................................................

O que é um fork ?
R: é uma cópia de um projeto.
R: No GitHub, um fork é um novo repositório que compartilha configurações de código
e visibilidade com o repositório original. No GitHub, um fork permite que alterações sejam feitas
publicamente em um projeto. 

..............................................................................................................

O que é uma Branch ?
R: É uma ramificação do projeto.
R: No Git, uma branch é uma linha de desenvolvimento independente que funciona como um ponteiro para um commit. É como uma cópia do código existente que permite trabalhar nele sem interferir no código principal. 

Os branches são úteis para: 

Desenvolver recursos
Corrigir erros
Experimentar novas ideias
Isolar a implementação de novas funcionalidades
Facilitar a colaboração entre membros da equipe
Otimizar o desenvolvimento de projetos
Evitar conflitos entre equipes ou desenvolvedores individuais

Para criar, listar, renomear e excluir branches, você pode usar o comando git branch.

Comandos git branch 

git branch Lista todas as ramificações no repositório
git branch <branch> Cria uma nova ramificação chamada <branch>
git branch -d <branch> Exclui a ramificação especificada, mas só se não houver mudanças não mescladas
git branch -D <branch> Força a exclusão da ramificação especificada, mesmo que ela tenha mudanças não mescladas
git branch -m <branch> Renomeia a ramificação atual para <branch>
git branch -a Lista todas as ramificações remotas
Para alternar entre branches, você pode usar o comando git checkout. 

..............................................................................................................

O que é um Commit ?
R: É uma ação que salva alterações em um repositório de controle de versão ou
em um banco de dados. É uma operação que envia os dados ou códigos para armazenamento.

..............................................................................................................

O que é um Merge ?
R: É uma operação que combina as alterações de uma ramificação para a outra. 
É uma forma de unificar um histórico bifurcado.

..............................................................................................................

O que é um git remote ? 
R: É um comando que permite criar. ver e remover coneções com repositórios remotos. 
Essas coneções são como marcadores que referenciam URLs de repositórios. 

Como usar o git remote?

Para adicionar uma nova conexão remota, use o comando ................. git remote add 
Para ver quais conexões remotas estão ativas, use o comando ........... git remote 
Para remover uma conexão remota, use o comando ........................ git remote 
Para alterar a URL de um repositório remoto, use o comando ............ git remote set-url 
Para obter informações detalhadas sobre a configuração de um remoto, use o subcomando show anexado ao git remote 

..............................................................................................................

Como usar o git fetch ?

Para buscar uma branch remota, use o comando .......................... git fetch [remote-name]
Para buscar e mesclar automaticamente um branch remoto no seu branch atual, use o comando ...... git pull

..............................................................................................................

Push - É utilizado para colocar o commit feito na maquina local no remote ou github.

..............................................................................................................

Pull - É usado para adicionar novos arquivos do github na maquina local.

..............................................................................................................

Comando basicos do git no computador.

git --version 
Mostra a versão do git.

Após criar a pasta do projeto.

Com o botão direito, clicar em abrir com Bash.

Readme.md = md é a extensão markdow.
É uma linguagem de marcação. É usado para colocar as instruções do projeto.

..............................................................................................................


Após abrir o gitbash.

comando para inicializar um arquivo.

Initialized empty Git repository in C:/Users/Estudos/Desktop/Base.py/.git/
git init  ........................... inicializa um repósitorio git vazio.

..............................................................................................................

comando para adicionar arquivos.

git add  ............................  Manda os arquivos para os stage do git
git add. ............................  É usado para enviar todos os arquivos alterados de uma só vez.
git add + nome do arquivo  ..........  Para alterar um arquivo selecionado.

..............................................................................................................

comando para ver mudanças a serem feitas.
git status ..........................  Mostra os arquivos a serem commitados. 

..............................................................................................................

comando para commitar um arquivo.
git commit -m "primeiro comit" ....   Comando usado para fazer o commit de um projeto.

..............................................................................................................

comando para trocar de master para main
git brench -M "main"

..............................................................................................................

comando para voltar para a brench main
git checkou main 

..............................................................................................................

comando para juntar uma brench
git marg + nome da alteração.

..............................................................................................................

Comando basicos para criar um novo repositório no github.

Clicar no botão New

Criar um novo repositório.
Create a new repository.

Repostory name.
nome do repositório = nome do projeto.

Description
Descrição. = descrição do projeto.

comando para fazer o link do repositório local com o github.
git remote add origin + endereço do projoto: https://github.com/luciojs-Oliveira/Base.py.git
git remote é usado apenas uma vez. ao inicializar um projeto.

comando para empurrar os arquivos do repositório local para o github.
git push -u origin main

..............................................................................................................

Lista resumida de comandos basicos do git Bash

clear é usado para limpar a tela.

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
..............................................................................................................

Para alterar o nome de um repositório no GitHub, é necessário ser proprietário da organização ou ter permissão de administrador no repositório. 


Para renomear um repositório no GitHub, pode: 

..... Ir até o repositório que deseja editar
..... Clicar em "Configurações"
..... No campo "Nome do Repositório", digitar o novo nome
..... Clicar em "Renomear"

Quando se renomeia um repositório, todas as informações existentes são redirecionadas para o novo nome, com exceção das URLs do site do projeto. 

..... Para renomear uma organização no GitHub, pode: 
..... Selecionar a foto de perfil no canto superior direito do GitHub
..... Selecionar "Suas organizações"
..... Clicar em "Configurações" ao lado da organização
..... Clicar em "Renomear organização" na parte inferior da página de configurações
..... Digitar um novo nome para a organização
..... Clicar em "Alterar nome da organização"
