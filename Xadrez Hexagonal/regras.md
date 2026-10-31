# Xadrez Hexagonal: conjunto de regras

O Xadrez Hexagonal é uma variante do xadrez tradicional disputada em um tabuleiro de casas hexagonais, que altera a geometria dos movimentos, as relações de ataque e defesa e as estratégias de posicionamento das peças.

É importante distinguir que não existe uma única versão universal do Xadrez Hexagonal. Há variantes com tabuleiros, peças, movimentos e condições de vitória diferentes. Um exemplo conhecido é a versão de Glinski, criada por Władysław Gliński, que utiliza um tabuleiro de 91 casas hexagonais e seis direções de movimento.

A seguir, apresento as regras da variante de Glinski, uma das versões mais conhecidas e adequadas para uma descrição sistematizada do jogo.

## 1. Objetivo do jogo

O objetivo é dar xeque-mate ao rei adversário: colocar o rei sob ataque de modo que o jogador não tenha nenhum lance legal capaz de eliminar a ameaça.

- Participantes: 2 jogadores.
- Duração: variável, conforme a experiência dos jogadores.
- Jogadores: um controla as peças brancas e o outro, as pretas.
- Primeiro lance: as brancas.
- Vitória: xeque-mate, conforme as regras de Gliński.
- Empate: depende das condições específicas de empate e da regra de pontuação adotada para o afogamento.
  
## 2. Tabuleiro e disposição inicial

[Hexagonal Chess / �checs hexagonaux](https://images.openai.com/static-rsc-4/83KoCX-XVaSOl0ojpV4NDxPxyh2-ETpFHnrIapYGWlEP956aPaH1FVQ2XIR8C6aTwfVh8ysGNgZjXMX68ZsurOcOoyHRPczHvCCFjVffwO1A-fGZ4-NQP5WZjTzugF6pQW974EykoaCAC0saO8JmCK2CM2PNyNSu_mg7lCmVz4k?purpose=inline)

[zpag.net](https://zpag.net/Jeux/Echec/hexagonal_chess.html?utm_source=chatgpt.com)

O tabuleiro possui 91 casas hexagonais, organizadas em um grande hexágono com seis casas em cada lado externo. As casas são distribuídas em três cores, permitindo distinguir as diagonais dos bispos.

As colunas são identificadas pelas letras `a` a `l`, omitindo-se a letra `j` na notação tradicional de Gliński. As fileiras são numeradas de 1 a 11, mas nem todas as colunas possuem o mesmo número de casas. A coluna central `f` tem 11 casas; as colunas laterais ficam progressivamente menores.

## 3. Peças de cada jogador

Cada jogador começa com 18 peças, totalizando 36 peças na partida.

| Peça    | Quantidade por jogador |
| ------- | ---------------------- |
| Rei     | 1                      |
| Dama    | 1                      |
| Torres  | 2                      |
| Cavalos | 2                      |
| Bispos  | 3                      |
| Peões   | 9                      |
| Total   | 18                     |

A principal diferença em relação ao xadrez convencional é que cada jogador tem um bispo e um peão adicionais. Os três bispos começam em casas de cores distintas.

## 4. Movimentação das peças

A geometria hexagonal modifica as direções disponíveis. Para compreender os movimentos, considere dois tipos de deslocamento: através de lados compartilhados pelas casas e através de vértices.

[What are the rules of Glinski's Hexagonal Chess? - Chess Stack Exchange](https://images.openai.com/static-rsc-4/35fEbsfaIYGh9gCOlo6-sLEFhAwEkHnw32ISCgFSShXgVqmJ1Zu3EXPiQGL3Tz9lIO74MNAuGyk5-IUh54i9Iv0XHgeos5otLldREFTVpmsW-BulLLpQa-S58a_YpXA-cqNwESdOCkmvt94VhlnvZuTcXZ-aw4yQtIPmZqxY5Ok?purpose=inline)

Torre

Move-se qualquer número de casas em linha reta, nas seis direções que passam por lados compartilhados entre hexágonos. Não pode saltar sobre outras peças.

Bispo

Move-se qualquer número de casas pelas seis direções diagonais, passando pelos vértices dos hexágonos. Não pode saltar sobre peças e permanece sempre na mesma cor de casa.

[Hexasakk:A figurák lépései](https://images.openai.com/static-rsc-4/_MTMtUf-TihT3npaf6mHhl8AdCq6OIHaFW48GFjjYZgsVK993GNBEa7NgrhriqyAHBpmQIYX7S-v-bHhmWA8x6cyJjo3j-xWC2Dw3Doo5sPXra8UDfysssjP-mDoRpX_iNlSykBKZuPyP0kcthrv21-6EbDBannA7eRDbWSbpWw?purpose=inline)

Dama

Combina os movimentos da torre e do bispo. Pode percorrer as seis direções de cada tipo, desde que o caminho esteja livre.

Rei

Move-se uma casa por vez em qualquer uma das 12 direções adjacentes: seis através de lados e seis através de vértices. Nunca pode terminar um lance em uma casa atacada pelo adversário.

[code golf - Working on my Knight moves - Code Golf Stack Exchange](https://images.openai.com/static-rsc-4/aPJcF6yePAW6Hw0qRFcr9v4zsqFOGb-oItyx_-ELnuPauz1o7xOMShnNWxxeZx2EkSSDak8kGxuR5IY3IOEjhliJpAQ9iLAy599vdvKjmxVBUc-0AGb6FrPiC9-BQG6px8sEzfS1vOE71KAusOMnR7BrXKvSdTPqp-Hw4bj_Jao?purpose=inline)

Cavalo

Realiza saltos em padrão próprio da geometria hexagonal, alcançando até 12 casas possíveis a partir de posições centrais. Pode saltar sobre peças intermediárias.

[Szachy heksagonalne](https://images.openai.com/static-rsc-4/3dRUoKdbj3VoUMcy9L2TWIU3v2T0O5mOono1LboEx15w5rreHSqCFj3PZ9BVhUaDj_rX9GnhcEVdM6jzkIHkMqCjHAnVAg8KELXQdR3xUUw0AyFBrbCnbC0MR1hourWoTfjdGyLe2ZpKytfvXlwsnCx9OmqTwqXfS3C-Qx1qf4o?purpose=inline)

Peão

Avança em direção ao território adversário, seguindo sua linha de avanço. Captura uma peça adversária em uma das duas direções oblíquas para a frente. Não captura avançando diretamente para a frente.

## 5. Regras específicas dos peões

Os peões possuem regras próprias, adaptadas ao formato do tabuleiro.

1. Avanço: o peão avança uma casa em direção ao lado adversário, desde que a casa esteja livre.
2. Captura: captura uma peça adversária em uma das duas direções oblíquas para a frente.
3. Primeiro avanço duplo: na versão tradicional de Gliński, os peões podem avançar duas casas a partir de suas casas iniciais, desde que o caminho esteja livre. Algumas implementações digitais adotam variantes que não permitem esse lance.
4. En passant: pode ser permitido nas regras modernas que adotam o avanço duplo, mas não faz parte de todas as versões históricas. É necessário definir qual conjunto de regras será utilizado.
5. Promoção: quando alcança a borda oposta do tabuleiro, o peão é promovido a dama, torre, bispo ou cavalo, conforme as regras adotadas.

## 6. Captura de peças

A captura ocorre quando uma peça realiza um movimento legal até uma casa ocupada por uma peça adversária. A peça capturada é retirada do tabuleiro.

- Não é permitido capturar uma peça própria.
- Exceto o cavalo, as peças não podem saltar sobre outras peças.
- O rei não pode ser capturado: deve ser protegido contra ataques.
- Um lance que deixe o próprio rei em xeque é ilegal.

Esses princípios preservam a lógica fundamental do xadrez, embora as casas e os movimentos sejam hexagonais.

## 7. Xeque, xeque-mate e afogamento

Xeque: o rei está sob ataque de uma peça adversária. O jogador deve eliminar a ameaça, seja movendo o rei, capturando a peça atacante ou bloqueando o ataque quando isso for possível.

Xeque-mate: o rei está em xeque e não existe nenhum lance legal para escapar. O jogador que aplicou o mate vence.

Afogamento: o jogador da vez não está em xeque, mas não possui nenhum lance legal. Aqui há uma particularidade importante: nas regras originais de Gliński, o afogamento não é necessariamente tratado como empate convencional. O jogador que provoca o afogamento recebe três quartos de ponto, enquanto o jogador afogado recebe um quarto de ponto. Algumas plataformas, entretanto, adotam o empate tradicional.

## 8. Roque

Não existe roque na variante de Gliński. Portanto, não há lance especial que permita movimentar simultaneamente o rei e uma torre.

## 9. Promoção e finais de partida

Quando um peão atinge uma casa de promoção na borda oposta, deve ser substituído por uma peça permitida pelas regras da variante.

A partida termina por xeque-mate ou por uma condição de empate aplicável à versão escolhida. Entre as condições de empate que algumas implementações utilizam estão:

- acordo entre os jogadores;
- repetição de posições;
- ausência de capturas e movimentos de peões durante o limite de lances estabelecido;
- material insuficiente para produzir mate.

Os detalhes exatos devem ser fixados antes da partida, porque nem todas as implementações de Xadrez Hexagonal adotam as mesmas regras de empate.

## 10. Notação dos lances

A notação de Gliński utiliza letras para as colunas e números para as fileiras, com a particularidade de que a letra `j` é omitida.

As peças podem ser identificadas por letras, conforme a convenção utilizada, e os lances seguem princípios semelhantes à notação algébrica do xadrez tradicional:

- movimento de peça: identificação da peça e casa de destino;
- captura: uso de `x`;
- xeque: `+`;
- xeque-mate: `#`;
- promoção: indicação da nova peça.

A notação exata pode variar entre publicações e plataformas, por isso é recomendável utilizar a convenção adotada pelo tabuleiro ou regulamento escolhido.

## 11. Resumo das diferenças em relação ao xadrez tradicional

| Característica       | Xadrez tradicional      | Xadrez de Gliński                    |
| -------------------- | ----------------------- | ------------------------------------ |
| Formato do tabuleiro | Quadrado                | Hexagonal                            |
| Número de casas      | 64                      | 91                                   |
| Cores das casas      | 2                       | 3                                    |
| Bispos por jogador   | 2                       | 3                                    |
| Peões por jogador    | 8                       | 9                                    |
| Direções da torre    | 4                       | 6                                    |
| Direções da dama     | 8                       | 12                                   |
| Roque                | Permitido sob condições | Não permitido                        |
| Geometria do cavalo  | Até 8 destinos          | Até 12 destinos                      |
| Afogamento           | Empate                  | Pontuação especial na regra original |

## 12. Referências para consulta

- [Hexagonal Chess Rules — regras e movimentos ilustrados](https://hexchess.plyyard.com/rules/?utm_source=chatgpt.com).
- [Hexchess — regras, notação e disposição das peças](https://k15z.github.io/hexchess-zero/docs/rules?utm_source=chatgpt.com).
- [Green Chess — variante de Gliński](https://www.greenchess.net/en/rules.php?v=glinski\&utm_source=chatgpt.com).
- [Wikibooks — Chess Variants: Hexagonal Chess](https://en.wikibooks.org/wiki/Chess_Variants/Hexagonal_Chess?utm_source=chatgpt.com).

Observação importante: se o objetivo é produzir um regulamento oficial para um jogo físico do Laboratório Maker, convém especificar expressamente que se trata da variante de Gliński e fixar as regras de avanço duplo, en passant, promoção e afogamento. Sem isso, duas pessoas podem jogar com conjuntos de regras diferentes, ambos chamados de Xadrez Hexagonal.
