# Linguagem: C

## Explicação

Pasta para códigos e exemplos da linguagem de programação C. Dentro dela, você encontrará subpastas chamadas: *codigos*, a qual deve ser manualmente criada, na qual você deverá armazenar seus códigos; *exemplos*, onde estão disponíveis diversos exemplos de como funciona a linguagem, os quais também podem ser utilizado para testar se os métodos de criação de arquivos executáveis está funcionando; *.vscode*, na qual está armazenado os arquivos que o programa Visual Studio Code utiliza para configurar o projeto corretamente.

## Instalação

1. Verifique se o C está instalado em sua máquina com o comando `gcc --version` no terminal. Caso esteja, já está tudo pronto! Caso contrario, prossiga para o proximo passo;
2.
   1. Se estiver utilizando Windows, baixe o MSYS2 em [https://www.msys2.org/](https://www.msys2.org/) e siga os passos de instalação. Após isso, abra o MSYS2 e execute o comando `pacman -S mingw-w64-x86_64-gcc` para instalar o compilador C;
   2. Se estiver utilizando Linux, instale o compilador C via gerenciador de pacotes da sua distribuição Linux;
3. Adicione o C ao PATH do seu sistema operacional, para que o terminal possa reconhecer o comando `gcc`;
4. Instale as extensões recomendadas para C no Visual Studio Code, caso esteja utilizando-o;
5. Pronto! Agora você pode utilizar o C em seu terminal e no Visual Studio Code.

## Como usar

Caso esteja utilizando a IDE chamada Visual Studio Code, simplesmente abra esta pasta chamada ***C*** no programa e comece a programar! Quando necessitar compilar e testar seu programa, na parte esquerda, vá na aba de *Run and Debug* (acessível também pela combinação Ctrl+Shift+D) e selecione o tipo de tarefa que quer executar¹ e clique no botão verde. Nas vezes subsequentes, basta estar com o arquivo aberto e apertar *F5* que a tarefa deve executar automaticamente.

¹ O grupo PET Computação já deixou uma pré-pronta que deve funcionar na maioria dos casos.

## Cadeiras Aplicáveis

* Algoritmos e Programação - INF01202
* Estrutura de Dados - INF01203
* Classificação e Pesquisa de Dados - INF01124

## Como Modificar

Para modificar a maneira na qual o programa VSCode realiza o processo de compilação e debug do seu código é necessário modificar os conteúdos da pasta .vscode. Lá dentro, estão 4  arquivos que modificam as propriedades da area de trabalho atual.

* *extensions.json:* armazena as extensões recomendadas;
* *settings.json:* armazena configurações especificas para esta pasta;
* *launch.json:* armazena o os processos que devem ser executados na aba de *Run and Debug*, para executar o processo de depuração com argumentos de linha de comando, basta adiciona-los ao item `"args"` do arquivo;
* *tasks.json:* armazena os processos de pré-depuração, normalmente executa a compilação dos arquivos para serem executados.

## Links de referencia

* [https://www.learn-c.org/](https://www.learn-c.org/) - Guia da Linguagem C [EN]
* [https://en.cppreference.com/w/c](https://en.cppreference.com/w/c) - Guia de referencia da linguagem C e suas versões [EN]
* [https://www.gnu.org/software/gnu-c-manual/gnu-c-manual.html](https://www.gnu.org/software/gnu-c-manual/gnu-c-manual.html) - Manual da Implementação de GNU de C [EN]
* [https://www.feg.unesp.br/Home/PaginasPessoais/profmarcosapereira3168/programacaodecomputadoresi/manual-de-sintaxe-da-linguagem-c.pdf](https://www.feg.unesp.br/Home/PaginasPessoais/profmarcosapereira3168/programacaodecomputadoresi/manual-de-sintaxe-da-linguagem-c.pdf) - Guia da UNESP de C [PT]
* [https://www.ibm.com/docs/en/i/7.1?topic=extensions-standard-c-library-functions-table-by-name](https://www.ibm.com/docs/en/i/7.1?topic=extensions-standard-c-library-functions-table-by-name) - Lista de todas as funções das bibliotecas padrões [EN]
