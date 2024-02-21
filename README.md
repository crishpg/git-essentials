# git-essentials

# Adicionado um texto dentro do Readme.MD via github


#Comandos Git Essenciais: Guia Completo
Configuração
git config --global user.name "Seu Nome": Define seu nome de usuário global para commits.
git config --global user.email "Seu Email": Define seu email global para commits.
git config --global core.editor "Seu Editor de Texto": Define o editor de texto padrão para mensagens de commit.
#Gerenciando Repositórios
git init: Inicializa um novo repositório Git no diretório atual.
git clone <url>: Clona um repositório remoto para o seu computador.
git add <arquivo>: Adiciona arquivos ao índice de staging para serem comitados.
git commit -m "Mensagem do Commit": Registra as alterações no índice de staging como um commit.
git push: Envia seus commits locais para o repositório remoto.
git pull: Recebe as últimas alterações do repositório remoto e as integra ao seu repositório local.
Navegando por Branches
git branch: Lista todas as branches existentes no repositório.
git checkout <nome-da-branch>: Troca para a branch especificada.
git branch <nome-da-branch>: Cria uma nova branch.
git merge <nome-da-branch>: Integra as alterações de outra branch na branch atual.
git delete <nome-da-branch>: Exclui uma branch (após mesclá-la com a branch principal).
Visualizando Alterações
git status: Mostra o estado do repositório, incluindo arquivos modificados e comitados.
git log: Mostra o histórico de commits do repositório.
git diff: Mostra as diferenças entre as versões de um arquivo ou entre branches.
Desfazendo Alterações
git reset HEAD <arquivo>: Desfaz as modificações locais em um arquivo.
git reset --hard HEAD: Desfaz o último commit local.
Recursos Adicionais
git help: Mostra ajuda sobre qualquer comando Git.
git init --bare: Cria um repositório remoto bare para compartilhamento.
git tag: Cria uma marca para um commit específico.
git submodule: Adiciona um submódulo (outro repositório Git) ao seu projeto.
Dicas:

Use o atalho git log --oneline para uma visão mais compacta do histórico de commits.
Utilize o alias git co para git checkout.
Aprenda a usar o git rebase para reescrever o histórico de commits.
Explore a vasta quantidade de recursos online para aprender mais sobre o Git.
