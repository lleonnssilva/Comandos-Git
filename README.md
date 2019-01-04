Git/GitHub 

Configurações  do git 
Navegar até a pasta do projeto

Ex:cd diretório/pasta/

Iniciar Git na pasta
-git init
-Verificar remote local existente
-git remote -v
Resultado Console:
seu-git-remote-local https://github.com/lleonnssilva/heroku.git (fetch)
seu-git-remote-local https://github.com/lleonnssilva/heroku.git (push)
outros....

Excluir remote local existente (seu-git-remote-local ) caso queira usar passo 1.2
-git remote rm seu-git-remote-local


1-Pegar as alterações do repositório GitHub com brach master

1.1-Com repositório remote local existente

Baixar as mudanças do GitHub em  seu  seu-git-remote-local
-git pull seu-git-remote-local master
1.2-Sem repositório remote local existente

Criar um repositório remote local
-git remote add seu-git-remote-local  https://github.com/...


Baixar as mudanças do GitHub em  seu  seu-git-remote-local
-git pull seu-git-remote-local master

2-Subir as alterações no repositório GitHub com brach master
Adiciona os arquivos modificados no seu seu-git-remote-local  
-git add . 
Adiciona o commit com a descrição da alteração feita no seu seu-git-remote-local
-git commit -m 'Descrição das alterações’
Efetivar a alteração do seu seu-git-remote-local no GitHub
-git push -u origin master

3-Criar no brach 


