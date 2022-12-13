# TR12_537643

## Pré-requisito
Para compilar e executar o codigo é necessario que tenha instalado o GCC ou G++. Com algum deles instalados, resta a você baixar o codio, para fazer isso:

1- Vá até o arquivo que você precisa baixar.

2- Clique no arquivo e você verá os eu conteúdo.

3- Clique na opção Raw (está na barra de opções acima do conteúdo).

4- Depois pressione o botão direito do mouse e clique em Salvar como.

5- Defina o nome e extensão do arquivo, e pronto!

## Instalação
É necessario que os arquivos estejam na mesma pasta para que a compilação ococrra.

### Gerando a biblioteca
Como gerar a biblioteca para usar no seu código

Execute:

gcc -c heap.c
Será gerado um arquivo chamado heap.o

Exemplo de como compilar junto com seu código:

gcc main.c heap.o -o nome_do_programa
