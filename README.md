## Interpretador de Pascal com Python
O projeto "Interpretador de Pascal com Python" tem como objetivo construir um interpretador para a linguagem Pascal utilizando a linguagem de programação Python. O interpretador é responsável por analisar, executar e fornecer saída para programas escritos em Pascal.

### O projeto é dividido em três partes principais:

- Lexer: O Lexer é responsável por analisar o código-fonte Pascal e transformá-lo em uma sequência de tokens. Os tokens representam os elementos mais básicos da linguagem, como palavras-chave, identificadores, símbolos e literais. O Lexer identifica e classifica cada token presente no código-fonte.

- Parser: O Parser recebe a sequência de tokens gerada pelo Lexer e constrói uma árvore de análise sintática, conhecida como Árvore de Sintaxe Abstrata (AST). A AST representa a estrutura hierárquica do programa Pascal. O Parser utiliza regras gramaticais da linguagem para interpretar os tokens e criar a estrutura da AST.

- Interpretador: O Interpretador percorre a AST gerada pelo Parser e interpreta as instruções correspondentes a cada nó da árvore. Ele executa as instruções Pascal e realiza as operações necessárias, como atribuições de variáveis, cálculos aritméticos, execução de comandos condicionais e repetição de loops. O Interpretador é responsável por fornecer a saída correta para o programa Pascal.  

Além dessas três partes, uma funcionalidade adicional do interpretador é a geração de um arquivo DOT (Graphviz) que representa a árvore de análise sintática.

### Considerações
Esse é um projeto em constante construção e faz parte de uma série de tutoriais, onde parei apenas na parte 10 (isso no ano passado, subo esse repositório agora, mas ainda não retomei) e ao final de 19 partes irá resultar num Interpretador de Pascal mais complexo e elaborado se eu chegar lá. Atualmente a melhor versão minha é essa. Se você tiver interesse em tentar também, pode começar aqui com os tutoriais "Build a simple interpreter".  
https://ruslanspivak.com/lsbasi-part1/
