# Regras completas do Xadrez Hexagonal

O Xadrez Hexagonal é uma família de variantes do xadrez tradicional em que as peças se movimentam sobre um tabuleiro formado por casas hexagonais. A geometria do tabuleiro altera os movimentos, as possibilidades de ataque, a defesa do rei e as estratégias de controle do espaço.

Existem diferentes versões desse jogo, com regras próprias. Para apresentar um conjunto completo e coerente de regras, vou utilizar como referência o Xadrez Hexagonal de Gliński, uma das variantes mais conhecidas, criada pelo engenheiro polonês Władysław Gliński em 1936.

As regras abaixo correspondem a essa variante específica, e não devem ser misturadas com as versões de McCooey, Shafran ou De Vasa.

## 1. Objetivo do jogo

O objetivo é dar xeque-mate ao rei adversário: atacar o rei de modo que o adversário não disponha de nenhum lance legal para eliminar a ameaça.

- Participantes: 2 jogadores.
- Início da partida: as brancas jogam primeiro.
- Turnos: os jogadores alternam um lance por vez.
- Capturas: uma peça captura uma peça adversária ao ocupar sua casa.
- O rei nunca é efetivamente capturado; a partida termina com o xeque-mate.

## 2. Tabuleiro e peças

[File:Hexagonal chess.svg - Wikimedia Commons](https://images.openai.com/static-rsc-4/pvh7BrPUsVBpr85d2rXMJjmXTO1020FiPWi9SJToJG-km1b0ERC1Mt3Fss2uPN4FA0K0UztjomOz3LtEXS76PJcyQlOGtdHdWewro3THrNe1Dt8g6jbO3YPhKD5MJ1hxlmu0VOQdgZEPfrGMzPPN9hnJ59kE05LNJ9oQqznmKmw?purpose=inline)

[commons.wikimedia.org](https://commons.wikimedia.org/wiki/File%3AHexagonal_chess.svg?utm_source=chatgpt.com)

O tabuleiro de Gliński é composto por 91 casas hexagonais, distribuídas em formato de hexágono maior e organizadas em três cores.

Cada jogador dispõe de 18 peças:

| Peça    | Quantidade por jogador |
| ------- | ---------------------- |
| Rei     | 1                      |
| Dama    | 1                      |
| Torres  | 2                      |
| Bispos  | 3                      |
| Cavalos | 2                      |
| Peões   | 9                      |
| Total   | 18                     |

Os três bispos são necessários porque cada um permanece na mesma cor de casas durante toda a partida.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://k15z.github.io\&sz=32)

k15z.github.io+1



### Organização inicial

A disposição exata deve seguir o diagrama de abertura da variante escolhida. Na configuração de referência de Gliński, o rei fica na região central da fileira inicial, acompanhado pela dama, pelas torres, pelos cavalos e pelos três bispos; os nove peões formam a linha avançada.

É importante utilizar um tabuleiro específico para essa variante, pois não basta desenhar casas hexagonais em um tabuleiro convencional.

## 3. Como cada peça se movimenta

A principal diferença em relação ao xadrez convencional está nas direções de movimento. O tabuleiro hexagonal oferece seis direções principais e seis direções diagonais.

[What are the rules of Glinski's Hexagonal Chess? - Chess Stack Exchange](https://images.openai.com/static-rsc-4/35fEbsfaIYGh9gCOlo6-sLEFhAwEkHnw32ISCgFSShXgVqmJ1Zu3EXPiQGL3Tz9lIO74MNAuGyk5-IUh54i9Iv0XHgeos5otLldREFTVpmsW-BulLLpQa-S58a_YpXA-cqNwESdOCkmvt94VhlnvZuTcXZ-aw4yQtIPmZqxY5Ok?purpose=inline)

Torre

Move-se por qualquer distância em uma das seis direções principais, desde que não haja peças bloqueando o caminho. Não pode saltar sobre outras peças.

Bispo

Move-se por qualquer distância nas seis direções diagonais, passando de uma casa para outra da mesma cor. Cada jogador tem três bispos, um para cada cor do tabuleiro.

[Hexasakk:A figurák lépései](https://images.openai.com/static-rsc-4/_MTMtUf-TihT3npaf6mHhl8AdCq6OIHaFW48GFjjYZgsVK993GNBEa7NgrhriqyAHBpmQIYX7S-v-bHhmWA8x6cyJjo3j-xWC2Dw3Doo5sPXra8UDfysssjP-mDoRpX_iNlSykBKZuPyP0kcthrv21-6EbDBannA7eRDbWSbpWw?purpose=inline)

Dama

Combina os movimentos da torre e do bispo. Pode percorrer as seis direções principais e as seis diagonais, sem saltar peças.

Rei

Move-se uma casa por vez em qualquer uma das 12 direções possíveis: seis principais e seis diagonais. Não pode deslocar-se para uma casa atacada por uma peça adversária.

[code golf - Working on my Knight moves - Code Golf Stack Exchange](https://images.openai.com/static-rsc-4/aPJcF6yePAW6Hw0qRFcr9v4zsqFOGb-oItyx_-ELnuPauz1o7xOMShnNWxxeZx2EkSSDak8kGxuR5IY3IOEjhliJpAQ9iLAy599vdvKjmxVBUc-0AGb6FrPiC9-BQG6px8sEzfS1vOE71KAusOMnR7BrXKvSdTPqp-Hw4bj_Jao?purpose=inline)

Cavalo

Executa um salto característico da geometria hexagonal: percorre duas casas em uma direção principal e muda 60° para alcançar a casa de destino. Pode saltar sobre peças intermediárias e alcançar até 12 destinos a partir de determinadas casas centrais.

[Szachy heksagonalne](https://images.openai.com/static-rsc-4/3dRUoKdbj3VoUMcy9L2TWIU3v2T0O5mOono1LboEx15w5rreHSqCFj3PZ9BVhUaDj_rX9GnhcEVdM6jzkIHkMqCjHAnVAg8KELXQdR3xUUw0AyFBrbCnbC0MR1hourWoTfjdGyLe2ZpKytfvXlwsnCx9OmqTwqXfS3C-Qx1qf4o?purpose=inline)

Peão

Avança em direção ao lado adversário, normalmente uma casa por lance. Captura uma peça adversária em uma das duas direções oblíquas para a frente. Não captura avançando diretamente.

As direções exatas dependem da geometria das casas e de sua posição no tabuleiro. Os diagramas específicos da variante são a melhor referência visual para aprender os movimentos.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://k15z.github.io\&sz=32)

k15z.github.io+2



## 4. Regras especiais dos peões

### Movimento inicial

Na versão de Gliński que admite o avanço duplo, um peão ainda na sua casa inicial pode avançar duas casas em linha reta, desde que ambas estejam livres.

Essa possibilidade não existe depois que o peão deixa sua casa inicial, salvo regras específicas de determinadas edições para peões que capturam e passam a ocupar outra casa inicial.

### Captura en passant

A captura en passant é uma captura especial associada ao avanço duplo do peão. Quando esse avanço permite a captura, um peão adversário elegível pode capturar o peão como se ele tivesse avançado apenas uma casa.

A captura deve ser realizada imediatamente no lance seguinte; caso contrário, perde-se a oportunidade.

### Promoção

Quando um peão alcança a borda oposta do tabuleiro, é promovido. O jogador substitui o peão por uma das seguintes peças:

- Dama;
- Torre;
- Bispo;
- Cavalo.

A escolha não depende das peças que já foram capturadas. Assim, um jogador pode ter mais de uma dama ou mais de duas torres.

A disposição irregular das casas significa que a região de promoção não deve ser interpretada simplesmente como a oitava fileira do xadrez convencional.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.hexagonalchess.com\&sz=32)

hexagonalchess.com+2



## 5. Xeque, defesa e xeque-mate

Xeque ocorre quando o rei está sob ataque de uma peça adversária.

O jogador em xeque precisa realizar um lance legal que elimine a ameaça. Isso pode ser feito de três formas:

1. Mover o rei para uma casa segura.
2. Capturar a peça que está dando xeque.
3. Interpor uma peça entre o atacante e o rei, quando o tipo de ataque permite essa defesa.

Não é permitido ignorar o xeque, movimentar uma peça de maneira que deixe o próprio rei exposto ou deslocar o rei para uma casa atacada.

Xeque-mate ocorre quando o rei está em xeque e nenhuma defesa legal é possível. Nesse caso, o jogador que deu o mate vence imediatamente.

## 6. Roque e outras diferenças em relação ao xadrez tradicional

No xadrez de Gliński, não existe roque. O rei e as torres não executam o movimento conjunto especial do xadrez convencional.

As principais diferenças são:

- Tabuleiro com 91 casas hexagonais.
- Três cores de casas.
- Três bispos e nove peões por jogador.
- Seis direções principais para a torre.
- Seis direções diagonais para o bispo.
- Até 12 direções de movimento para a dama e para o rei, conforme a peça e a posição.
- Ausência de roque.

As regras de movimento não podem ser substituídas pelas regras do xadrez tradicional sem alterar a natureza do jogo.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://k15z.github.io\&sz=32)

k15z.github.io+1



## 7. Empates e encerramento da partida

As regras de empate podem variar entre as edições. Para uma partida casual, recomendo combinar previamente os critérios utilizados.

| Situação              | Regra                                                                   |
| --------------------- | ----------------------------------------------------------------------- |
| Xeque-mate            | Vitória do jogador que deu o mate.                                      |
| Afogamento            | O jogador da vez não está em xeque, mas não tem nenhum lance legal.     |
| Repetição             | Uma posição é repetida três vezes, conforme as regras adotadas.         |
| Regra dos 50 lances   | Passam-se 50 lances de cada jogador sem captura nem movimento de peão.  |
| Material insuficiente | Não há material suficiente para produzir mate, segundo a regra adotada. |
| Acordo                | Os dois jogadores concordam em encerrar a partida empatada.             |
| Desistência           | Um jogador abandona e concede a vitória ao adversário.                  |

Atenção ao afogamento: na regra original de Gliński, ele não é necessariamente um empate convencional. A pontuação de torneio atribui ¾ de ponto ao jogador que provoca o afogamento e ¼ ao jogador afogado. Algumas implementações modernas adotam o empate comum, com meio ponto para cada lado.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://mindzug.com\&sz=32)

MindZug+2



## 8. Recomendações para uma primeira partida

- Comece aprendendo os seis movimentos da torre e os seis do bispo.
- Desenvolva os cavalos e os bispos para controlar a região central.
- Proteja o rei desde os primeiros lances.
- Observe as ameaças em mais direções do que no xadrez convencional.
- Não presuma que as aberturas tradicionais de xadrez funcionem da mesma forma.
- Antes de começar, combinem se o afogamento será considerado empate ou seguirá a pontuação original de Gliński.

## Fontes para consulta

- Hexagonal Chess — [regras ilustradas e movimentos das peças](https://www.hexagonalchess.com/rules?utm_source=chatgpt.com).
- MindZug — [explicação em português do xadrez hexagonal de Gliński](https://mindzug.com/pt/glossary/glinskis-hexagonal-chess?utm_source=chatgpt.com).
- Green Chess — [regras da variante de Gliński](https://greenchess.net/rules.php?v=glinski\&utm_source=chatgpt.com).

Observação final: se a intenção for produzir um manual para um jogo físico do Laboratório Maker, vale definir explicitamente qual variante será utilizada, pois o nome “Xadrez Hexagonal” não identifica sozinho um único conjunto universal de regras.
