# Regras completas do Jogo Sesqui

O Sesqui é um jogo matemático de estratégia abstrata para dois jogadores, pertencente à família dos jogos de conexão. Seu nome vem do latim sesqui, que significa aproximadamente “um e meio” ou “mais metade”.

O desafio consiste em construir uma cadeia de peças que conecte duas margens opostas do tabuleiro, ao mesmo tempo que se impede o adversário de completar sua própria conexão.

As regras abaixo correspondem à versão tradicional descrita pela LuduScience e pelo regulamento dos Jogos Matemáticos.

## 1. Material necessário

- 1 tabuleiro quadrado de 8 × 8 casas (64 casas).
- 30 peças escuras (pretas).
- 30 peças claras (brancas).
- 2 jogadores.

## 2. Objetivo do jogo

Cada jogador possui um objetivo diferente:

- Jogador Vertical (peças escuras): deve formar uma cadeia contínua de peças que conecte as margens Norte e Sul do tabuleiro.
- Jogador Horizontal (peças claras): deve formar uma cadeia contínua de peças que conecte as margens Oeste e Este do tabuleiro.

Para que uma conexão seja válida, as peças podem estar ligadas umas às outras pelas direções:

- Vertical;
- Horizontal;
- Diagonal.

Não é necessário que a cadeia seja uma linha reta. Ela pode apresentar curvas e ramificações, desde que exista um caminho contínuo entre as duas margens correspondentes.

## 3. Preparação e início da partida

1. Coloque o tabuleiro vazio sobre uma superfície plana.
2. Cada jogador escolhe uma cor: escura ou clara.
3. O jogador Vertical, com as peças escuras, inicia a partida colocando uma peça em qualquer casa vazia do tabuleiro.
4. Em seguida, o jogador Horizontal, com as peças claras, coloca duas peças em quaisquer duas casas vazias.

Essa abertura assimétrica é uma característica importante do Sesqui: o primeiro jogador coloca uma peça, enquanto o segundo coloca duas.

## 4. Desenvolvimento das jogadas

Depois da abertura, os jogadores alternam os turnos. Em cada turno, o jogador deve realizar duas ações:

Ação 1 – Colocação de uma nova peça

- Escolher uma peça de sua cor que ainda não esteja no tabuleiro.
- Colocá-la em uma casa vazia.
- A casa escolhida deve ser adjacente, vertical ou horizontalmente, a pelo menos uma peça da mesma cor que já esteja no tabuleiro.

Importante: a adjacência diagonal não é suficiente para realizar uma colocação.

Ação 2 – Movimentação de uma peça existente

- Escolher uma peça de sua própria cor que já esteja no tabuleiro.
- Movimentá-la como uma rainha do xadrez.
- A movimentação pode acontecer na horizontal, na vertical ou na diagonal.
- A peça pode percorrer qualquer quantidade de casas vazias na direção escolhida.
- A peça deve terminar seu movimento em uma casa vazia.

A movimentação segue o princípio da rainha do xadrez: não é permitido saltar sobre outras peças.

Ordem das ações: o jogador pode escolher livremente se deseja primeiro colocar uma nova peça e depois movimentar uma peça existente, ou fazer primeiro a movimentação e depois a colocação.

## 5. Regra especial: proibição de cruzamento de peças

Esta é uma das regras mais importantes do Sesqui.

Em qualquer momento da partida, é proibido criar uma configuração de quatro peças em um quadrado de 2 × 2 na qual as cores estejam alternadas nas duas diagonais.

Existem duas configurações proibidas:

Configuração proibida A:

```
PRETA  BRANCA
BRANCA PRETA
```

Configuração proibida B:

```
BRANCA PRETA
PRETA  BRANCA
```

Em outras palavras:

- Duas peças de uma cor não podem ocupar uma diagonal do quadrado 2 × 2 enquanto as duas peças da outra cor ocupam a diagonal oposta.
- Essa proibição vale durante toda a partida.
- Nenhuma colocação ou movimentação pode produzir uma dessas configurações.

A regra impede que os jogadores construam cruzamentos entre suas cadeias de peças, preservando a característica estratégica do jogo.

## 6. Condições de vitória

A partida termina imediatamente quando um dos jogadores consegue estabelecer uma cadeia contínua de peças que conecte suas duas margens opostas.

- Vitória do jogador Vertical (pretas): quando existir uma cadeia de peças pretas conectando a primeira à última linha do tabuleiro, isto é, Norte e Sul.
- Vitória do jogador Horizontal (brancas): quando existir uma cadeia de peças brancas conectando a primeira à última coluna do tabuleiro, isto é, Oeste e Este.

Para determinar se uma conexão foi estabelecida:

1. As peças devem pertencer exclusivamente ao jogador que pretende realizar a conexão.
2. Cada peça da cadeia deve estar conectada a pelo menos outra peça da mesma cor.
3. São permitidas conexões horizontais, verticais e diagonais.
4. A cadeia pode mudar de direção quantas vezes forem necessárias.
5. Não é necessário ocupar todas as casas entre as margens.

Não existe necessidade de capturar ou retirar peças do adversário para vencer.

## 7. Restrições gerais

Durante toda a partida, devem ser observadas as seguintes restrições:

| Situação                                           | Regra                                       |
| -------------------------------------------------- | ------------------------------------------- |
| Colocar peça em casa ocupada                       | Proibido                                    |
| Colocar peça sem adjacência ortogonal da mesma cor | Proibido                                    |
| Colocar peça com adjacência apenas diagonal        | Proibido                                    |
| Movimentar peça para casa ocupada                  | Proibido                                    |
| Saltar sobre outras peças                          | Proibido                                    |
| Criar cruzamento 2 × 2 de cores alternadas         | Proibido                                    |
| Movimentar peça na diagonal                        | Permitido                                   |
| Movimentar peça na horizontal ou vertical          | Permitido                                   |
| Movimentar mais de uma casa                        | Permitido, desde que o caminho esteja livre |
| Conectar as margens por uma cadeia diagonal        | Permitido                                   |

## 8. Resumo da sequência de uma partida

| Etapa                  | Jogador Vertical (pretas)        | Jogador Horizontal (brancas)     |
| ---------------------- | -------------------------------- | -------------------------------- |
| Abertura               | Coloca 1 peça                    | Coloca 2 peças                   |
| Primeiro turno regular | Coloca 1 e movimenta 1           | —                                |
| Segundo turno regular  | —                                | Coloca 1 e movimenta 1           |
| Demais turnos          | Alternam as duas ações           | Alternam as duas ações           |
| Final                  | Vence quem conectar suas margens | Vence quem conectar suas margens |

## 9. Estratégias recomendadas

Embora não sejam regras obrigatórias, algumas estratégias ajudam a compreender a dinâmica do Sesqui:

- Construir caminhos alternativos: não depender de uma única sequência de peças para alcançar a margem oposta.
- Controlar o centro: ocupar regiões centrais pode facilitar a construção de conexões em diferentes direções.
- Bloquear possibilidades: utilizar a movimentação para dificultar a formação da cadeia adversária.
- Manter mobilidade: evitar concentrar peças de maneira que sobrem poucas possibilidades de movimentação.
- Planejar as duas ações: aproveitar a combinação entre colocação e movimentação para ampliar as próprias possibilidades estratégicas.

## 10. Referências e documentação

As regras foram organizadas a partir das seguintes referências:

1. LuduScience – Jogo Sesqui: [Descrição oficial do jogo e materiais](https://www.luduscience.com/sesqui.html?utm_source=chatgpt.com).
2. Campeonato Nacional de Jogos Matemáticos – Livro de Regras: [Regulamento em PDF (página 7)](https://amareleja.edu.gov.pt/site/pdf/CNJM/regrasCNJM12.pdf?utm_source=chatgpt.com).
3. BoardGameGeek – Sesqui: [Descrição e características do jogo](https://boardgamegeek.com/boardgame/457009/sesqui?utm_source=chatgpt.com).

Observação: o regulamento consultado não estabelece uma regra específica de empate, nem detalha procedimentos para situações em que um jogador não consiga realizar uma das duas ações obrigatórias. Portanto, não acrescentei regras de empate ou de passagem de turno que não estejam documentadas.

Síntese: o Sesqui combina construção de conexões, movimentação semelhante à da rainha do xadrez e uma restrição especial contra cruzamentos de peças. A vitória depende de conectar duas margens opostas do tabuleiro antes do adversário.
