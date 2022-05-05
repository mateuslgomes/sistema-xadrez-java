# SISTEMA   JOGO DE XADREZ COMPLETO

### Peças: Rei(K), peão(P), torre(R), bispo(B), rainha(Q), cavalo(N).

![1](https://user-images.githubusercontent.com/97681752/166970517-2867725f-ec8b-4fcf-8752-9537ef364b95.jpg)

## Sistema de capturas de peças.

Assim que uma peça é capturada, ela vai para uma lista de peças capturas, e essa lista é exibida logo abaixo.

![Captura de tela 2022-05-05 135749](https://user-images.githubusercontent.com/97681752/166975485-130fb6e8-7960-4405-b9d3-5cf9695b241d.jpg)

# Todas as peças foram programadas para se movimentar conforme as regras do jogo.

## Demontrações das movimentações das peças.

Rei: Pode ser movimentado em qualquer direção do tabuleiro, mas apenas de casa em casa.

![k](https://user-images.githubusercontent.com/97681752/166980674-9883da11-b41c-4c20-a942-f616fdef7f36.jpg)

Rainha: Sem restrições, a Rainha tem livre movimentação no jogo na horizontal, vertical e diagonais.

![q](https://user-images.githubusercontent.com/97681752/166980749-7072516b-eb36-499b-91ff-c5697077324e.jpg)

Torre: pode correr sem restrição de número de casas e em todas as direções (frente, trás, direita, esquerda).

![r](https://user-images.githubusercontent.com/97681752/166981390-1abe0818-238b-4592-b535-0f13d2845efd.jpg)

Bispo: Sem restrição de número de casas, mas somente no sentido diagonal.

![b](https://user-images.githubusercontent.com/97681752/166980862-1ad56810-0f11-4414-8a2a-0f14b07b0249.jpg)

Cavalo: Realiza movimentos em “L”, ou seja, duas casas em um sentido e uma casa em sentido perpendicular àquele, em qualquer direção.

![n](https://user-images.githubusercontent.com/97681752/166980884-b96f963d-4f86-4ca0-93e3-9c863d2e2e88.jpg)

Peão: Pode apenas realizar movimentos frontais, de forma que o primeiro movimento de cada peão abranja até duas casas, e os demais se limitam a uma casa à frente. O ataque do peão sempre ocorre na diagonal.

![Captura de tela 2022-05-05 134407](https://user-images.githubusercontent.com/97681752/166972113-e4a2b0a2-9851-4f19-af25-95680a1731c2.jpg)

![Captura de tela 2022-05-05 135726](https://user-images.githubusercontent.com/97681752/166974757-3a85f940-c2b2-4296-b0ef-51913730e0aa.jpg)

## Quando um peão chega na ultima casa do outro lado do tabuleiro ele é promovido e o jogador deve escolher tornar-se uma rainha ou torre ou bispo ou cavalo.

![image](https://user-images.githubusercontent.com/97681752/166982265-3bc6fcbf-6fb0-4542-b922-e94bfa82727f.png)

#

Observações: 

O jogo deve ter 2 jogadores.

A jogabilidade do game é pelo terminal, usando uma letra e um número conforme a posição da peça(mesma lógica de batalha naval).

O jogo deve rodar na pasta bin, pelo Git Bash, é um terminal que permite cores, assim não comprometendo a visualização do game, e evitando erros.
