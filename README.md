# estudosGit-rethink
## Passos iniciais para começar no Git
Para iniciar no git, primeiramente, é necessário criar um repositório no Github, para isso basta seguir os seguintes passos:
- Criar uma conta no Github e fazer login
- No canto superior esquerdo da tela na aba "Repositories" clicar em New

Na tela de criação de repositório é possível já inicializa-lo com o arquivo README.md , o que é recomendado, onde são detalhados as funcionalidades do projeto.

Após a criação do repositório, é necessário clona-lo para sua máquina usando o comando `git clone`, que tem a seguinte sintaxe : 
```bash 
git clone "link do repositório"
```
# Conceitos Importantes
## O que é uma branch
Branch é basicamente a criação de  ramificação do seu código afim de realizar alterações sem prejudicar o "main code". Com a criação de uma branch funcional você pode escolher se irá realizar um `merge` dela em seu código.

## MERGE
O merge é a fusão da sua branch atual com alguma outra branch de interesse, normalmente a main (principal).

## O que é um commit
O comando commit rotula um conjunto de alterações adicionadas ao Index, Index é como chamamos o espaço onde todos os itens que damos `git add` ficam armazenados.

