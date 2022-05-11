Arquivo ensinando a usar o Git

---------------------------------------------------------------------------------------
git init {Cria um novo subdiretório chamado .git que contem todos os arquivos necessários de seu repositório}
git add "nomedoarquivo" {adiciona um arquivo específico }
git commit -m "mensagem de registro"
git commit -m "mensagem de registro" --amend {Refazer commit quando esquecer de adicionar um arquivo no Stage}
git branch -M main (ou master) {}
git remote add origin (Link do repositório remoto)
git push -u origin main

---------------------------------------------------------------------------------------
git checkout -b "nome" {cria uma branch e muda de lugar para ela}
git checkout main (ou master) {volta para branch principal}
git merge "nome" {junta a branch com a principal}

---------------------------------------------------------------------------------------
git clone(link) {clona uma repositório existente}
git pull {atualiza repositório}
---------------------------------------------------------------------------------------
git diff {mostra as linhas exatas que foram adicionadas e removidas}
git help {comando}