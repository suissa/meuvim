MeuVim
======

Meus arquivos de configuração para o Vim.

Comecei montar esse Vim para tentar substituir o grandalhão NetBeans no dia-a-dia como desenvolvedor WEB.

Eu trabalho principalmente com PHP, JavaScript, CSS e HTML. Ocasionalmente Python e C++.

Missão
------

Substituir todos os editores do mundo! muahuahuahau

Como usar
---------

Interessado em usar esta configuração para o seu vim? Faz o seguinte (Usando GNU/Linux, claro):


 *  Clone do repositório do GitHub: git clone git://github.com/InFog/meuvim.git
   *  Ou baixe aqui: https://github.com/InFog/meuvim
 *  Coloque o conteúdo do projeto no diretório ~/.vim
 *  Copie o arquivo vimrc para ~/.vimrc
 *  Use seu novo vim =)
 * (Dá para usar com o GVim no Windows, mas aí é com você)

Dependências
------------

Só algumas dependências para tudo funcionar certinho:

 *  **exuberant-ctags** para o TagList.
 *  Para que o autocomplete Python funcione é necessário ter o vim compilado com a opção **+python**.
    No Debian instale o pacote **vim-gnome** que resolve.

Opções
------

Snippets : Adicionei o plugin snipMate que tem snippets para várias linguagens. Adicionei algumas opções:


 *  ci\_controller<tab>
   * Cria a estrutura básica para um controller CI\_Controller
 *  ci\_model<tab>
   * Cria a estrutura básica de uma model CI\_Model
 * foreacht<tab>
   * Cria uma estrura *foreach* em um template html
 * echot<tab>
   * Cria uma estrutura *echo* em um template html
 * ift<tab>
   * Cria uma estrutura *if* em um template html

Buffer Explorer : Use \\be no modo comando

NERDTree : Use a tecla F5

TagList  : Use a tecla F6

Autocomplete de funções do Python: ctrl + x, ctrl + o. Funciona super bem, mostra até a documentação.

PHPDoc : *,doc* para adicionar um trecho PHPDoc.

Abas : *,t* abre uma nova aba, *,n* avança para a aba seguinte e *,b* volta uma aba.

Identação de todo o arquivo: *ctrl+i* para corrigir a identação de todo um arquivo
(testei com PHP, não é tão bom assim... Mas desenvolvedor tem que fazer sua identação).

Sparkup: A função do Sparkup foi mapeada para *ctrl+d*.

Comandos úteis
--------------

 * *%* no modo de comandos vai para o abre/fecha parênteses/chaves/colchetes correspondente.
   * Adicionei o matchit que faz o *%* também funcionar com tags html e outras linguagens.
     Detalhe que ele reconhece até a sintaxe alternativa para *if*, *foreach* e outros do *php*.

Afazeres
--------

 *  Procurar algum plugin que complete nomes de funções em classes e mostre o PHPDoc.
 *  O TagList mostra funções, métodos, classes e variáveis, mas não segue o PHPDoc =( Sad, sad robot...
