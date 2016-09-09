# TrabalhoAlgoritmo

O trabalho está dividido em duas partes, sendo a primeira referente a um jogo de Caça-palavras e a
segunda um jogo de Labirinto. A descrição de cada parte está a seguir:

Caça-palavras: é um jogo que consiste em uma matriz quadrada ou retangular de letras organizadas
de maneira aleatória com a presença de algumas palavras em sua forma escrita correta ou invertida.
O objetivo é encontrar todas as palavras completas presentes na matriz. Desta forma, dado um
caçaa-palavras composto por uma matriz de caracteres, em que o usuário deve informar o tamanho
(número de linhas e número de colunas) e os caracteres de cada posição da matriz, desenvolver
um programa que busque na matriz a ocorrência de uma palavra informada pelo usuário. Caso
a palavra seja encontrada o programa deve informar em que coordenadas encontrou e se esta em
ordem normal ou invertida de escrita.
As palavras podem estar distribuídas pela matriz na horizontal e vertical, em ordem normal ou
inversa. Para encerrar o jogo o usuário deve digitar a palavra sair, caso contrário deve continuar
pedindo uma nova palavra para buscar.


Cego no Labirinto de Vidro: o jogo do labirinto corresponde a um conjunto de caminhos com o
propósito de atrapalhar o jogador na busca por um único caminho que o guie para fora de um
ambiente. Os labirintos podem conter uma ou várias saídas e um ou vários possíveis caminhos.
No jogo proposto neste trabalho um cego é posicionado em uma determinada coordenada de uma
grade/matriz e a partir desta posição deve seguir certas direções para tentar encontrar uma saída.
Porém, o chão deste labirinto é de vidro, e a cada passo a posiço anterior é quebrada impossibilitando
o retorno.
O cego do jogo somente pode andar seguindo uma ordem de escolhas, sendo elas: primeiro ele
tenta andar ao norte, após tenta nordeste, leste, sudeste, sul, sudoeste, oeste e por fim noroeste.
Caso ele não consiga andar em nenhuma direção ele “morre”. Lembre que o caminho do nosso
personagem pode conter obstáculos como paredes e quadros de vidro quebrados por já ter passado
por aqueles locais. A(s) saída(s) do jogo esta(ao) posicionada(s) na(s) lateral(is) do quadro.
O jogo deve receber como entrada o tamanho da matriz (linhas e colunas) e todos os valores de
suas posições (cada uma delas). Em seguida, deve receber a posição inicial do cego (número da
linha e número da coluna) e a partir daí o jogo deve tomar as decisões dos passos sozinho independente
do jogador, exibindo na tela para qual posição o cego andou. O jogo termina quando o
cego consegue chegar a uma saída ou quando não existem opções de passos possíveis.
Se o personagem chegar a uma saída você deve imprimir na tela que ele saiu e em qual posição,
caso contrário imprimir que ele morreu e em qual posição.
