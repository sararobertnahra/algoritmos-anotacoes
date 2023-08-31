# The Legendary Octo Potato

Repositório git criado para documentar os comandos apresentados pelo professor e possibiltiar a execução das atividades do lab1.

## Aula de Github
    Pré requisitos: criar uma conta no github e um repositório público...

### Cria uma nova pasta
    mkdir fatec

### Lista os arquivos e pastas do diretório
    ls -a

### Move para o diretório desejado
    cd fatec

### Cria um clone de um repositório git
    git clone https://github.com/caiopalma/legendary-octo-potato.git
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

## Sites úteis
    //todo
