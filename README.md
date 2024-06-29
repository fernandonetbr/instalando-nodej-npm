# instalando-nodej-npm

A instalação do Node.js e npm pode variar ligeiramente dependendo do sistema operacional que você está utilizando. Aqui estão os passos para instalar no Windows, macOS e Linux.

### 1. Instalando no Windows

#### Passo 1: Baixar o Instalador
1. Acesse o site oficial do Node.js: [nodejs.org](https://nodejs.org/)
2. Você verá duas versões para download: LTS (Long Term Support) e a versão atual. Para a maioria dos usuários, a versão LTS é recomendada.
3. Clique na versão que você deseja baixar. Isso irá baixar um arquivo `.msi`.

#### Passo 2: Executar o Instalador
1. Abra o arquivo `.msi` que você baixou.
2. Siga as instruções do instalador. Certifique-se de marcar a opção "Automatically install the necessary tools...".
3. Continue clicando em "Next" e, finalmente, "Install".

#### Passo 3: Verificar a Instalação
1. Abra o Prompt de Comando ou o PowerShell.
2. Digite `node -v` e pressione Enter. Isso deve retornar a versão do Node.js instalada.
3. Digite `npm -v` e pressione Enter. Isso deve retornar a versão do npm instalada.

### 2. Instalando no macOS

#### Passo 1: Usando Homebrew (Recomendado)
1. Se você não tiver o Homebrew instalado, abra o Terminal e execute o seguinte comando:
    ```sh
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```
2. Uma vez que o Homebrew esteja instalado, você pode instalar o Node.js executando:
    ```sh
    brew install node
    ```

#### Passo 2: Verificar a Instalação
1. Abra o Terminal.
2. Digite `node -v` e pressione Enter. Isso deve retornar a versão do Node.js instalada.
3. Digite `npm -v` e pressione Enter. Isso deve retornar a versão do npm instalada.

### 3. Instalando no Linux (Distribuições baseadas em Debian/Ubuntu)

#### Passo 1: Atualizar o Sistema de Pacotes
1. Abra o Terminal.
2. Execute os seguintes comandos para atualizar os pacotes:
    ```sh
    sudo apt update
    sudo apt upgrade
    ```

#### Passo 2: Adicionar o Repositório NodeSource
1. Execute o seguinte comando para adicionar o repositório NodeSource para Node.js 14.x (LTS):
    ```sh
    curl -fsSL https://deb.nodesource.com/setup_14.x | sudo -E bash -
    ```
   Você pode substituir `14.x` pela versão que você deseja instalar.

#### Passo 3: Instalar Node.js e npm
1. Execute o seguinte comando para instalar o Node.js e npm:
    ```sh
    sudo apt install -y nodejs
    ```

#### Passo 4: Verificar a Instalação
1. Digite `node -v` e pressione Enter. Isso deve retornar a versão do Node.js instalada.
2. Digite `npm -v` e pressione Enter. Isso deve retornar a versão do npm instalada.

### Conclusão

Após seguir os passos acima para o seu respectivo sistema operacional, você deve ter o Node.js e npm instalados e prontos para uso. Se encontrar algum problema durante a instalação, consulte a documentação oficial do Node.js ou o gerenciador de pacotes que você está utilizando.
