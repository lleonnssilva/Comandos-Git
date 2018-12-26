# Comandos-Git

Comandos-Git
Adicionar projeto local ao remote 
git init 
git remote 
git remote add origin https://github.com/lleonnssilva/.... 
git commit "Primeiro Commit" git push -u origin master

Repositório Local 
Criar novo repositório 
git init

Verificar estado dos arquivos/diretórios 
git status

Adicionar um arquivo em específico 
git add meu_arquivo.txt

Adicionar um diretório em específico 
git add meu_diretorio 

Adicionar todos os arquivos/diretórios 
git add .

Adicionar um arquivo que esta listado no .gitignore 
git add -f arquivo_no_gitignore.txt

Comitar um arquivo 
git commit meu_arquivo.txt

Comitar vários arquivos 
git commit meu_arquivo.txt meu_outro_arquivo.txt 

Comitar informando mensagem 
git commit meuarquivo.txt -m "minha mensagem de commit"

Remover arquivo 
git rm meu_arquivo.txt

Remover diretório 
git rm -r diretorio

Exibir histórico git log

Exibir histórico com diff das duas últimas alterações 
git log -p -2

Exibir resumo do histórico (hash completa, autor, data, comentário e qtde de alterações (+/-)) 
git log --stat

Exibir informações resumidas em uma linha (hash completa e comentário) 
git log --pretty=oneline

Exibir histórico com formatação específica (hash abreviada, autor, data e comentário) 
git log --pretty=format:"%h - %an, %ar : %s" %h: Abreviação do hash; %an: Nome do autor; %ar: Data; %s: Comentário.

Exibir histório de um arquivo específico 
git log -- <caminho_do_arquivo>

Exibir histórico de um arquivo específico que contêm uma determinada palavra 
git log --summary -S [<caminho_do_arquivo>]

Exibir histórico modificação de um arquivo 
git log --diff-filter=M -- <caminho_do_arquivo>

O pode ser substituido por: Adicionado (A), Copiado (C), Apagado (D), Modificado (M), Renomeado (R), entre outros. Exibir histório de um determinado autor 
git log --author=usuario

Exibir revisão e autor da última modificação de uma bloco de linhas 
git blame -L 12,22 meu_arquivo.txt

Desfazendo operações Desfazendo alteração local (working directory) Este comando deve ser utilizando enquanto o arquivo não foi adicionado na staged area. 
git checkout -- meu_arquivo.txt

Desfazendo alteração local (staging area) Este comando deve ser utilizando quando o arquivo já foi adicionado na staged area.
git reset HEAD meu_arquivo.txt 


Exibir os repositórios remotos 
git remote
git remote -v 

Vincular repositório local com um repositório remoto
git remote add origin git@github.com:lleonnssilva/..

Exibir informações dos repositórios remotos 
git remote show origin

Renomear um repositório remoto 
git remote rename origin curso-git

Desvincular um repositório remoto 
git remote rm curso-git

Atualizar repositório local de acordo com o repositório remoto Atualizar os arquivos no branch atual 
git pull

Buscar as alterações, mas não aplica-las no branch atual 
git fecth

Clonar um repositório remoto já existente 
git clone git@github.com:lleonnssilva/..


Criando uma tag anotada 
git tag -a vs-1.1 -m "Minha versão "

Criando uma tag assinada 
git tag -s vs-1.1 -m "Minha tag assinada"

Criando tag a partir de um commit (hash) 
git tag -a vs-1.2 9fceb02

Criando tags no repositório remoto 
git push origin vs-1.2

Criando todas as tags locais no repositório remoto 
git push origin --tags


Criando um novo branch 
git branch bug-123

Trocando para um branch existente 
git checkout bug-123

Criar um novo branch e trocar 
git checkout -b bug-456

Voltar para o branch principal (master) git checkout master Resolver merge entre os branches 
git merge bug-123

