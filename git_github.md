# Configurando o usuário no git

    * git config --global user.name "" (para criar o nome de usuário)
    * git config user.name (para verificar o nome do usuário)
    * git config --global user.email "" (para criar o email do usuário)
    * git config user.email (para verificar o email do usuário)

# Repsitorio

    * É onde os arquivos do seu projetos ficam armazenados

# Iniando repositorio no git

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

# Clonando um repositório

    * git clone endereçoDoRepositório (para clonar a pasta com nome do repositório, para clonar apenas arquivos sem pasta digite " ." no final)

# Acessando o histórico de atualização

    * git log (para acessar a ultima atualização, aperte enter para ir vendo as atualizações mais antiga)
    para sair use tecla 'Q'

# Voltar um arquivo para o status original (rollback)

    * git checkout nomeDoArquivo (se o arquivo nao foi salvo)

# Ignorar arquivos

    * criar um arquivo com o nome .gitignore e dentro do arquivo inserir o nome dos arquivos e/ou pastas que serão ignorados pelo git (se for pasta colocar / antes do nome)