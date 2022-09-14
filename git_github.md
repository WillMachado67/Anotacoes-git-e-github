# Configurando o usuário no git

    * git config --global user.name "" (para criar o nome de usuário)
    * git config user.name (para verificar o nome do usuário)
    * git config --global user.email "" (para criar o email do usuário)
    * git config user.email (para verificar o email do usuário)

# Repositório

    * É onde os arquivos do seu projetos ficam armazenados

# Iniciando repositório no git

    * comando: git init

# Verificar status do projeto

    * comando: git status

# Adicionando arquivos para serem monitorados

    * git add nomeDoArquivo (para acionar arquivo especifico)

    * git add . (para adicionar todos os aquivos da pasta)

# Salvando arquivos no repositório (commit)

    * git commit nomeDoArquivo -m "" (arquivo será salvo no repositório en seguida escreva um mensagem ex: o que se trata a alteração, se não escrever o nome do arquivo todos os arquivos serão salvos)


# Github

    * hospeda/gerencia repositórios

# Subindo aquivos para o repositório remoto
     #### ultilizader os comandos quando for subir pela primeira vez o repositori
    * git branch -M main
    * git remote add origin linkDoRepositorio.git
    * git push -u origin main
    
    * git push (depois de ter ativado todos os comandos anteriores, publica arquivos no repositório remoto (GitHub))

# Baixar alterações que estão no repositório remoto (github)
    * git pull
# Clonando um repositório

    * git clone endereçoDoRepositório (para clonar a pasta com nome do repositório, para clonar apenas arquivos sem pasta digite " ." no final)

# Acessando o histórico de atualização

    * git log (para acessar a ultima atualização, aperte enter para ir vendo as atualizações mais antiga)
    para sair use tecla 'Q'

# Voltar um arquivo para o status original (rollback)

    * git checkout nomeDoArquivo (se o arquivo nao foi salvo)

# Ignorar arquivos

    * criar um arquivo com o nome .gitignore e dentro do arquivo inserir o nome dos arquivos e/ou pastas que serão ignorados pelo git (se for pasta colocar / antes do nome)

# resetar arquivos

    * git reset --hard origin/main (reseta o arquivo enviado para a repositório (github))
# Branch

    * É uma maneira que o git disponibiliza para separar versões do projeto.

# Visualizar e criar brach

    * git branch (visualiza quanta branch tem o repositório e qual esta ativa no momento)
    * git branch nome (nome da nova branch)

# Mudando de branch

    * git checkout nome (nome da branch que você quer ir)

# Criar e mudar para a branch criada

    * git checkout -b "" (dentro das apas digite o nome da nova branch)

# Deletando branch

    * git branch -d nome (nome da branch que deseja deletar)
    
# Unindo branch

    * git merge nomeDaBranch (trás todas as alterações da branch, para a branch atual)

# Substituir e salvar alterações

    * git stash (retorna para o tatus inicial da branch, deleta e salva as ultimas alterações)
    * git stash list (mostra uma lista de stash criada)
    * git stash apply X (troque X pelo numero do id da stash list para recuperar um stash)
    * git stash show -p X (troque o X pelo numero do id para saber o que foi alterado naquela stash)

# Tag

    * git tag -a nomeDaTag -m "descrição" (cria uma tag)
    * git tag (visualizar tags)
    * git show nomeDaTag (visualiza detalhes da tag)
    * git checkout nomeDaTag (alterna entre as tags)
    * git push origin nomeDaTag (envia tag para o repositório remoto)
    * git push origin --tags (envia todas as tag para o repositório remoto)

# Enviar alterações feitas em um repositório clonado para repositório remoto original

    * git push --set-upstream origin cadastro (também pode copiar esse comando depois de dar um git push)

# Ver alterações enviada de um repositório clonado para o repositório original

    * git fetch -a

# Limpar arquivos desnecessários

    * git gc

# Ver o histórico de commit commit criados

    * git shortlog
# Ver mudanças feitas

    * git diff (se colocar nome da branch ve mudanças entre as branch) 
    * git diff HEAD: nomeDoArquivo (para ver mudanças em um arquivo especifico)

# Reflog

    * git reflog (Exibe todos os detalhes precisos nesse repositório)
