# Comandos Git

- `git status´ -> para visualizar os arquivos que sofreram alterações
- `git add´ -> para adicionar os arquivos alterados na staging da sua branch (aqui a gente prepara o arquivo para salvar)
- `git restore --staged´ -> tira os arquivos da área de staging e impede o commit deles
- `git restore´ -> descarta todas as alterações feitas no arquivo e faz ele voltar ao estado inicial
- `git commit -m´ -> para de fato confirmar o salvamento dos arquivos na branch que está sendo utilizada / -m -> permite incluir uma mensagem para explicar a alteração realizada
- `git log´ -> mostra o histórico de commits 
- `git log --graph --oneline --decorate --all´ -> mostra toda a árvore do grapho entre a main e as branchs alternativas criadas
- `git reset -- hard "hash do commit"´ -> para resetar/reverter a versão do código para outra
- `git clone "caminho repositório"´ -> para clonar um repositório remoto para a sua máquina local
- `git remote -v´ -> para ver em qual repositório está conectado
- `git config --global user.name "seu usuário"´ -> para indicar globalmente ao git seu usuário e permitir interagir com o github
- `git config --global user.emai "seu email"´ -> para indicar globalmente ao git seu email e permitir interagir com o github
- `git pull origin main´ -> para atualizar o seu repositório local com as alterações commitadas na branch main do repositório remoto
- `git push -u origin "nome branch"´ -> para enviar as alterações feitas no repositório local para o repositório remoto na branch que você está utilizando
- `git branch´ -> mostra em qual branch você está trabalhando
- `git branch -d "nome da branch"´ -> deleta uma branch no repositorio local
- `git push origin --delete "nome da branch"´ -> para enviar a atualização de deleção da branch para o repositório remoto
- `git checkout -b "nome da branch"´ -> para criar uma nova branch
- `git checkout "nome da branch"´ -> para abrir uma branch específica, main ou alternativa
- `git diff´ -> mostra o que tem de diferença entre os arquivos, antes de adicionar ele em staging


## OBS:

- `git add / git restore --staged´ -> você especifica arquivo por arquivo ou pode colocar um "." que vai adicionar todos que estiverem ali

- `branch´ -> é uma ramificação do seu código que representa a evolução do projeto ao longo do tempo. funciona como uma "cópia" do código principal
nessa cópia, você vai trabalhar e fazer os ajustes e melhorias necessários e depois de validar tudo certinho, vai mergear o que foi feito no projeto principal 
essa prática existe, para não afetar projetos que estão funcionando enquanto você está testando funcionalidades