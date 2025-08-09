## Comandos Úteis do CMD com bat script

#### start = Inicia uma aplicação no sistema ou um link da internet
Exemplo:
  - start "instancia da linha de comando" cmd.exe
  - start www.google.com

#### color = Troca a paleta de cores do console
Exemplo:
  - color (sem argumento, reseta)
  - color /? mostra as opções de cores
  - color 02 (fundo preto, letras verdes)


## Gerenciamento de arquivos e pastas
  - dir = Mostra os itens da pasta atual
  - cd = Navega entre pastas
#### path = Isola a instancia atual e aponta para um local específico
Exemplo:
  path: Downloads
    Nesse caso, ele só vai aceitar execução de itens dentro dessa pasta
#### copy = Copia arquivos do diretório X para Y.
Exemplo:
  - copy {arquivo} {destino}
  - copy {arquivo} {destino}\{novo_nome}

#### replace = subescreve o arquivo (não aceita novo nome)
Exemplo:
  - replace {arquivo} {destino}
