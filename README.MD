
´Definir username´: git config -- global user.name "NOME_USUARIO"
´Configurar e-mail´: git config --global user.email "EMAIL_USUARIO"
Situação atual do repositório: git status
Fazer com que o git reconheça os arquivos: git add NOME_ARQUIVO || git add . (adiciona todos os arquivos da pasta do projeto).
Criando um snapshot (versão no GIT): git commit -m "MENSAGEM_DO_COMMIT"
^^^^^^---Gera um identificador de versão---^^^^^^
Mostra identificação do commit/Autor/data/mensagem: git log
Mostra todos os contribuintes do repositório, quantidades de commites
e quais são: git shortlog
Observar mudanças antes de fazer o commit: git diff
Retorna arquivo para antes da edição: git checkout NOME_ARQUIVO
´Voltar ao ultimo commit anterior:´
git reset
--soft (Destroi commit realizad, porém, mantém arquivos prontos para serem submetidos novamente).
--mixed (Destroi commit realizado e retorna os arquivos para antes de prontos, "modificados").
--hard (Destroi tudo que foi feito no commit. "Todas as modificações").