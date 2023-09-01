# The Legendary Octo Potato

Repositório git criado para armazenar as notas de aula, documentar os comandos apresentados pelo professor e possibiltiar a execução das atividades dos laboratórios de banco de dados e outras disciplinas da graduação na Fatec.

Esse repositório poderá ser utilizado como rascunho para a elaboração das atividades, bem como compartilhamento de notas de aula e ensaios destrutivos. Sintam-se em casa! :D

[Link rápido do moodle do nadalete](https://www.lgnadalete.moodlecloud.com)

## Aula de Github

### Pré requisitos: 
- instalar o git
- [instalar o github CLI](https://cli.github.com)
- criar uma conta no github
- realizar a autenticação com o github via github CLI:
    ```
    gh auth login --web
    # Selecionar a opção ssh e pressionar enter em tudo.
    # No final, copiar o código que aparece no terminal (ctrl+shift+c) 
    # e colar no navegador, no formulário de autenticação.
    # Após dar as permissões, basta utilizar o git normalmente.
    ```
- criar um repositório público
- adicionar os colaboradores (obs.: os colaboradores precisam aceitar o convite!)

### Cria uma nova pasta
    mkdir fatec

### Lista os arquivos e pastas do diretório
    ls -a

### Move para o diretório desejado
    cd fatec

### Cria um clone de um repositório git (evitar de usar HTTPS)
    gh repo clone caiopalma/legendary-octo-potato
    cd legendary-octo-potato

### Lista as branchs
    git branch -a

### Cria uma branch e altera o apontamento do git
    git checkout -b lab1

### Lista o estado da branch
    git status

### Configura o git
    git config --global user.name "Caio Augusto Palma"
    git config --global user.email "caio.palma@fatec.sp.gov.br

### Adiciona o monitoramento a todos os arquivos da pasta local
    git add .

### Cria um commit com os arquivos monitorados no add
    git commit -m "Uma mensagem de commit"

### Mostra a diferença nas modificações
    git show

### Empurra as modificações para a branch
    git push --set-upstream origin lab1

### Atualiza o repositório local com as modificações do repositório remoto
    git pull

## Sites úteis

### Hello World!
- [Python: hello world interativo](https://www.learnpython.org)

### Vídeos
- [Docker: zero to hero!](https://www.youtube.com/watch?v=3c-iBn73dDE)
- [FreeCodeCamp: o melhor canal do youtube para aprender programação](https://www.youtube.com/@freecodecamp)

### Docs
- [Python: documentação oficial](https://docs.python.org/3/tutorial/index.html)
