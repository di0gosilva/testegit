Repositório teste github

----- Configuração user -----
- git config --global user.name "Fulano de Tal"
- git config --global user.email fulanodetal@exemplo.br

----- Versionamento -----
- git init
- git add . (para adicionar todos os arquivos)
- git commit -m "mensagem de alteração"


----- Comandos úteis -----
- git checkout (nome do arquivo) para desfazer algum commit
- git status - para saber o que precisa ser adicionado ou commitado
- git log - exibe um log com todos os commits feitos até o momento
- git dif (usar antes de adicionar/commitar) - mostrar quais os arquivos foram alterados 
- get show ("d93ae96a79d01c4a634068a74707b0af8fb594e4" - exemplo) - para mostrar o que foi alterado/commitado

---- Adicionar em um repositório no github ----- 
- git remote add origin "link do respositório"
- git branch -M main / master
- git push -u origin main / master

----- Clonar repositório do github -----
- git clone "link do repositório" 
