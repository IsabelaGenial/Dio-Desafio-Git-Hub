# DIO - Desafio de Projeto Git/GitHub
_Dentro do Git  temos Commit, Tree e Blobs, entendendo o que são cada um podemos nos organizar melhor. Vamos usare a analogia de uma arvore o  commit,  é um tronco , o Tree nesse exemplo é o ramos, com isso as Blobs são as folhas.  Simplificando mais um pouco Commit > Tree > Blobs, então podemos ter  varias Blobs para um Tree, vários Tree para um Commit, mas não podemos ter vários Commit para um Tree e assim sucessivamente._

## Comandos iniciais do Git Bash 

- Configuração

  _Logo no inicio quando baixamos o [Git] (https://git-scm.com/) è necessário fazer algumas configurações._

  **Setar usuário** - Git config --global user.name "Isabela Genial"
  **Setar email** - git config --global user.email  "isabelamgenial@gmail.com"

- Repositório 

  _Criando e Commitando o repositório no Git Bash._

  **git init** - Criar novo repositório.
  **git status** - verificar o status do repositório. 

  **git add meu_arquivo.txt** - adicionar arquivo para staged 

  **git add .** - função de adicionar para staged, porem com o ponto será tudo os item dentro do arquivo
  **git commit meu_arquivo.txt** - comando para commitar arquivo.
  **git commit meuarquivo.txt -m "minha mensagem de commit"** - comando para commitar arquivo com mensagem. 
  **git rm meu_arquivo.txt** - comando para remover arquivo.

- Navegação

  _Quando estamos no Git Bash temos que ter a certeza que estamos na pasta certa. Esta informação conseguimos logo na abertura, caso não esteja onde quer, segue comandos para navegar nos repositórios e arquivos._

  **ls**- utilizado pata listar itens, assim podemos saber o que tem no repositório.

  **cd** -utilizado para mudar/entrar no repositório.

  **cd ..**  - este comando é utilizado para "voltar" ao repositório anterior. 

  **mv** - utilizado para mover um repositório para dentro de outro ou ao contrario também.

  **ls -a** - Utilizados para listar arquivos ocultos.

  
