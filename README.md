# MasterRepo
Repositório Mestre destinado aos estudantes de HTML, CSS, JS e Git



Instruções aos navegantes da Arca:

1. Criar conta no github

2. Criar conta no Trello

3. Ingressar no Board do Projeto: https://trello.com/invite/b/P5BYxl4Y/a4dfc963e6405fce7f6e4e7eaba4a891/gerador-de-relat%C3%B3rios-em-gsheets

4. Dar fork no projeto do git (o projeto original possui somente um arquivo txt chamado README.md)



Instruções iniciais do projeto:

Gerar sua própria versão do projeto, através um MVP(minimum viable product) de acordo com as histórias de usuário presentes no Board.




Como configurar seu VSCode, Git e Github:

Dando fork no projeto no github 

1. Criar pasta Master-Repo no PC;
2. Abrir VSCode dentro dessa pasta (open folder);
3. Vá até o terminal (cmd) do VSCode (ctrl + j);

    $ git init (iniciando o git)

    $ git config --global user.name Seu Nome 
(se ja tiver feito isso antes, com global, utilizar apenas $ git config user.name e aguardar seu nome aparecer no terminal)

    $ git config --global user.email Seu@email.com 
(se ja tiver feito isso antes, com global, utilizar apenas $ git config user.name e aguardar seu email aparecer no terminal)

4. Vá no github principal (https://github.com/devops-da-arca/MasterRepo) e clique em fork, em seguida clique no número que aparece logo ao lado;

5. Clique em /MasterRepo ao lado do seu nome de usuário;

6. Clique em Clone or Download e copie o link;

7. Volte para o terminal do VSCode;

    $ git remote add origin https://github.com/yandrade11/MasterRepo.git

    $ git pull

    $ git checkout -b nomeDoInfeliz 
(caso você já tenha criado uma branch manualmente pelo site do github, esse comando não será necessário, no momento em que você der git pull, essa branch virá junto com a master)