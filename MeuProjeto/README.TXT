----------------------------------------------------------------------------
1. Explique qual a função da Máquina Virtual Java (JVM).

A Máquina Virtual Java é uma máquina que emula uma aplicação em uma máquina real que permite a portabilidade do código Java, pois todo código Java é compilado para um formato intermediário, o bytecode.
Esse formato é interpretado por uma JVM destinada a um sistema operacional espécifico (Windows, Linux, Mac, etc..) por meio dessa interpretação podemos desenvolver uma aplicação sem nos preoculparmos onde ela será executada,
pois uma vez que a JVM está instalada, nossa aplicação irá executar sem nenhum envolvimento com o sistema operacional.

2. Qual a diferença entre JRE e JDK?

Ambos possuem uma função diferente, porém são destinadas ao desenvolvimento o JDK e composto por um conjunto de ferramentas responsável por compilar o código-fonte, já o JRE se trata de um ambiente onde e fornecido as bibliotecas para o JDK compilar e a JVM executar o programa.

3. Crie um programa Java que imprima o seguinte texto “Terminei a primeira aula com um programa Java!”.

Feito

4. Compile o programa desenvolvido no exercício anterior. A seguir apague 
o arquivo .class gerado e tente executar o programa. O que aconteceu?

Os seguintes erros são apresentados, o programa não foi executado.

Error: Could not find or load main class MeuPrograma
Caused by: java.lang.ClassNotFoundException: MeuPrograma


5. Mude o nome do método “main” para “start”, compile e execute. O que 
aconteceu?


6. Crie um programa Java para imprimir duas linhas de texto usando duas 
linhas de código “System.out”, onde aparecerá o seu nome na primeira 
linha e na segunda linha aparecerá o time para o qual você torce.

7. Experimente escrever todo o programa anterior em maiúsculo, compile e 
execute. O que aconteceu?

Não foi possível compilar.


8. Experimente salvar o arquivo com um nome diferente do nome da classe, 
compile e execute. O que aconteceu?

Renomeiou o arquivo.
------------------------------------------------------------------------
