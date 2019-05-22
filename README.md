# Git/GitHub 

## Configurações  do git 
Navegar até a pasta do projeto

**** Ex:cd diretório/pasta/

### Iniciar Git na pasta
**** git init</br>
Verificar remote local existente</br>
****git remote -v</br>
Resultado Console:</br>
seu-git-remote-local https://github.com/lleonnssilva/heroku.git (fetch)</br>
seu-git-remote-local https://github.com/lleonnssilva/heroku.git (push)</br>


### Excluir remote local existente (seu-git-remote-local ) caso queira usar passo 1.2</br>
**** git remote rm seu-git-remote-local</br></br>
1. Pegar as alterações do repositório GitHub com brach master</br>

1.1 Com repositório remote local existente</br>

Baixar as mudanças do GitHub em  seu  seu-git-remote-local</br>
****git pull seu-git-remote-local master</br>
1.2 Sem repositório remote local existente</br>

### Criar um repositório remote local</br>
****git remote add seu-git-remote-local  https://github.com/...</br>


### Baixar as mudanças do GitHub em  seu  seu-git-remote-local</br>
****git pull seu-git-remote-local master</br>

### Subir as alterações no repositório GitHub com brach master</br>
Adiciona os arquivos modificados no seu seu-git-remote-local  </br>
****git add . </br>
Adiciona o commit com a descrição da alteração feita no seu seu-git-remote-local</br>
****git commit -m 'Descrição das alterações’</br>
Efetivar a alteração do seu seu-git-remote-local no GitHub</br>
****git push -u origin master</br>

3. Criar no brach </br>


