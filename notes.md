Iniciamos o repositório »»
 Working Diretory (Modified ) »» 
    Stage Are »» Repositóry (Staged /preparado) »» 
        Repository (commited)


git init 
git status 
git log 

git add . »
    git commit -m "escrever o comentário"  »
        
         

git commit --amend -m "nova mensagem" (Usado para modificar o ultimo commit)    

git reset --soft HEAD~1 (Usado para desfazer o último commit feito)

git diff (ajuda a comparar as ultimas modificações com o ultimo commit)    

git restore <nome do file> ou git restore . (para restaurar tudo para versão anterior)

git restore --stage . (fazer o restore do stage  voltando para o estagio de Working Diretory)

git ignore » .gitignore dentro do arquivo podemos por o nome de pastas ou arquivos que nao queremos subir no github, eles vao ser ignorados. 

git keep » é colocado dentro da pasta que queremos manter no projeto, mesmo q ela ainda esteja vazia por exemplo

git clone » clona o projeto para que ele possa ser utilziado remotamente, nao sendo necessario fazer todas as configuraçoes inicias.

git pull » vai puxar todas as atulizações feitas no projeto dentro do github

