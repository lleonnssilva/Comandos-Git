# Git/GitHub 

## Configurações  do git 
Navegar até a pasta do projeto

Ex:cd diretório/pasta/

### Iniciar Git na pasta
-git init</br>
-Verificar remote local existente</br>
-git remote -v</br>
Resultado Console:</br>
seu-git-remote-local https://github.com/lleonnssilva/heroku.git (fetch)</br>
seu-git-remote-local https://github.com/lleonnssilva/heroku.git (push)</br>


Excluir remote local existente (seu-git-remote-local ) caso queira usar passo 1.2
-git remote rm seu-git-remote-local


1. Pegar as alterações do repositório GitHub com brach master

1.1-Com repositório remote local existente

Baixar as mudanças do GitHub em  seu  seu-git-remote-local
-git pull seu-git-remote-local master
1.2-Sem repositório remote local existente

Criar um repositório remote local
-git remote add seu-git-remote-local  https://github.com/...


Baixar as mudanças do GitHub em  seu  seu-git-remote-local
-git pull seu-git-remote-local master

. Subir as alterações no repositório GitHub com brach master
Adiciona os arquivos modificados no seu seu-git-remote-local  
-git add . 
Adiciona o commit com a descrição da alteração feita no seu seu-git-remote-local
-git commit -m 'Descrição das alterações’
Efetivar a alteração do seu seu-git-remote-local no GitHub
-git push -u origin master

3. Criar no brach 


