# GO AND GIN FRAMEWORK

## Install GO:
  - https://go.dev/dl/

  - Executar os caomandos abaixo no terminal:
    
        export GOPATH=$HOME/go
        export PATH=$PATH:$GOPATH/bin

  - Feche o terminal e VSCode.

## GO VSCODE:
  - Instalar a extensão "GO" do "Go Team at Google";

### FERAMENTAS GO
  - Acessar os commands no VSCODE: `CMD + SHIFT + P`. Procurar por  `goinstall update/tools`. Selecuiar tudo e aplicar.

## Gerenciamento de dependencia/modulos

  Cirando um modulo, ou seja o projeto em sí:
  
      go mod init hello-world

  Adicionando todos os pacotes:

       go get

  Adicionando um pacote novo:

       go get nome_pacote

  Listando todos os pacotes:
    
    
      go list -m all

  Removendo dependencias:

      go mod tidy nome_dependencia

## Instalando GIN
  - Executar: 
  
        go get github.com/gin-gonic/gin

  - Obs: Se falhar, execute isso para ssl:

        git config --global http.sslverify "false"


