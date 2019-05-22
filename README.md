# Git/GitHub 

## Configurações  do git 
Navegar até a pasta do projeto
**cd diretório/pasta/**</br>
 Iniciar Git na pasta</br>
**git init**</br>
Verificar remote local existente</br>
**git remote -v**</br>
Resultado Console:</br>
seu-git-remote-local https://github.com/lleonnssilva/heroku.git (fetch)</br>
seu-git-remote-local https://github.com/lleonnssilva/heroku.git (push)</br>
outros...</br>
Excluir remote local existente (seu-git-remote-local ) caso queira usar passo 1.2</br>
**git remote rm seu-git-remote-local**</br></br>
Pegar as alterações do repositório GitHub com brach master</br>
Com repositório remote local existente</br>
Baixar as mudanças do GitHub em  seu  seu-git-remote-local</br>
**git pull seu-git-remote-local master**</br>
Sem repositório remote local existente</br>
Criar um repositório remote local</br>
**git remote add seu-git-remote-local  https://github.com/...**</br>
Baixar as mudanças do GitHub em  seu  seu-git-remote-local</br>
**git pull seu-git-remote-local master**</br>
Subir as alterações no repositório GitHub com brach master</br>
Adiciona os arquivos modificados no seu seu-git-remote-local  </br>
**git add .**</br>
Adiciona o commit com a descrição da alteração feita no seu seu-git-remote-local</br>
**git commit -m 'Descrição das alterações’**</br>
Efetivar a alteração do seu seu-git-remote-local no GitHub</br>
**git push -u origin master**</br>


