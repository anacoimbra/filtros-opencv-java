# Filtragem e Operações em Imagens com Opencv

Aplicação para desktop feita em Java que realiza operações de adição, subtração, multiplicação, divisão, lógicas (and, not, or, xor), faz aplicação de ruídos gaussiano aditivo e sal e pimenta e, por fim, aplica filtros como media, mediana, moda, gaussiano, máximo, mínimo.

## Ambiente de Desenvolvimento

O projeto está configurado para abrir com o NetBeans IDE, mas algumas outras IDEs oferecem suporte para importação (Não me responsabilizo por problemas na importação).
* A classe _PrimeiroTrabalho_ consiste na tela inicial com dois botões para escolher qual a função desejada (operações ou filtros)
* A classe _Questao1_ é a tela que irá realizar, a partir de duas imagens escolhidas pelo usuario, alguma operação entre elas.
* A classe _Questao2_ deixa o usuário escolher uma imagem principal e, a partir dela, gerar ruidos gaussiano e sal e pimenta e aplicar os filtros já mencionados.

### Considerações importantes

* Ideal utilizar imagens com resolucao 256x256. Existem algumas 
na pasta do projeto para utilizacao
* As imagens devem estar na pasta raiz do projeto pois, devido a um 
problema de segurança, o programa não consegue ler e manipular arquivos em outros diretórios
* Atualmente nao esta implementado tratamento de erros e ainda existem 
alguns bugs na vizualizacao das imagens, principalmente as de saida. Entao,
se for o caso, basta abrir a imagem output.jpg dentro da pasta do projeto.
