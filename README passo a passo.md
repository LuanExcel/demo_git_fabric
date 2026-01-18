# Inicializar
git init

# Adicionando scripts
git add .

# Criando commit para mandar para nuvem
git commit -m "comentarios"

# Mnadando para nuvem
git push

# Vai pegar tudo que tem no main (principal) e joga lá ramificação dev
# e aqui ja entra na branch do dev
# Cria um branch dev apenas LOCALMENTE e já muda para ele.
git checkout -b dev

# Só depois que você der push que ela vai pra o github
git push -u origin dev

# Deletar branch
git branch -d dev

# Deletar o branch no GitHub (remoto)
git push origin --delete dev

# voltando pra branch do main
git switch main

# Atualizar
git fetch