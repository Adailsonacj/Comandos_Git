## Git
- **Definir username:** git config -- global user.name "NOME_USUARIO"
- **Configurar e-mail:** git config --global user.email "EMAIL_USUARIO"
- **Situação atual do repositório:** git status
- **Fazer com que o git reconheça os arquivos:** git add NOME_ARQUIVO || git add . (adiciona todos os arquivos da pasta do projeto).
- **Criando um snapshot (versão no GIT [Gera um identificador de versão]):** git commit -m "MENSAGEM_DO_COMMIT"
- **Mostra identificação do commit/Autor/data/mensagem:** git log
- **Mostra todos os contribuintes do repositório, quantidades de commites
e quais são:** git shortlog
- **Observar mudanças antes de fazer o commit:** git diff
- *Retroceder*
- **Retorna arquivo para antes da edição:** git checkout NOME_ARQUIVO
- **Voltar ao commit anterior:** git reset
**--soft** (Destroi commit realizad, porém, mantém arquivos prontos para serem submetidos novamente).
**--mixed** (Destroi commit realizado e retorna os arquivos para antes de prontos, "modificados").
**--hard** (Destroi tudo que foi feito no commit. "Todas as modificações").
- *Branches*
- **Criar um branch:** git checkout -b NOME_DO_BRANCH
- **Mudar o branch selecionado:** git checkout NOME_DO_BRANCH
- **Mostra branchs existentes e qual o selecionado:** git branch
- **Apagar branch:** git branch -D NOME_DO_BRANCH
**Mesclar os arquivos de um branch secundário:** git merge NOME_DO_BRANCH
**Mesclar arquivos com linearmente** git rebase NOME_DO_BRANCH

