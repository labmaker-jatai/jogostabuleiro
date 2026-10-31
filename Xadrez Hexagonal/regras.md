# Regras completas do Xadrez Hexagonal

O Xadrez Hexagonal é uma família de variantes do xadrez jogadas em tabuleiros formados por casas hexagonais. Existem diferentes versões, com regras, formatos de tabuleiro e movimentos das peças que podem variar bastante entre si.

Para apresentar um regulamento completo e coerente, é importante distinguir as variantes. Uma das mais conhecidas é a de Gliński, criada pelo engenheiro polonês Władysław Gliński e popularizada a partir de 1936. Ela utiliza um tabuleiro hexagonal com 91 casas e mantém o objetivo tradicional do xadrez: dar xeque-mate ao rei adversário.

As regras a seguir se referem à variante de Gliński, e não a outras versões de xadrez hexagonal.

## 1. Objetivo do jogo

O objetivo é dar xeque-mate ao rei adversário: atacar o rei de modo que o oponente não tenha nenhum lance legal capaz de eliminar a ameaça.

O jogo é disputado por duas pessoas, uma controlando as peças brancas e a outra as pretas. As brancas fazem o primeiro lance.

O regulamento de Gliński conserva a maior parte das regras do xadrez tradicional, mas modifica os movimentos em razão da geometria do tabuleiro.

## 2. Tabuleiro

O tabuleiro possui 91 casas hexagonais, organizadas em um hexágono regular com seis casas em cada lado.

As casas apresentam três cores diferentes, de modo que casas vizinhas não compartilham a mesma cor.

A disposição é caracterizada por:

- 11 colunas, identificadas pelas letras de `a` a `l`, sem a letra `j`.
- 11 fileiras numeradas de 1 a 11.
- Uma coluna central, `f`, que contém 11 casas, de `f1` a `f11`.
- Colunas laterais progressivamente menores, com 6 casas nas extremidades.
- Uma casa central, `f6`.

A quantidade de casas por coluna é a seguinte:

| Coluna | Quantidade de casas |
| ------ | ------------------- |
| a e l  | 6 cada              |
| b e k  | 7 cada              |
| c e i  | 8 cada              |
| d e h  | 9 cada              |
| e e g  | 10 cada             |
| f      | 11                  |

A soma é de 91 casas. A numeração segue a convenção própria da variante de Gliński, não a do tabuleiro convencional de oito por oito.

## 3. Peças e composição de cada exército

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

A diferença mais evidente em relação ao xadrez tradicional é a presença de um bispo e um peão adicionais para cada jogador.

Os três bispos são necessários porque o tabuleiro possui três cores de casas. Cada bispo fica restrito a uma dessas cores durante toda a partida.

## 4. Preparação e posição inicial

Antes do início, distribua as peças conforme a disposição original de Gliński.

As peças brancas ficam na extremidade inferior e as pretas na extremidade superior. Os reis ficam alinhados na coluna central, em lados opostos do tabuleiro.

A disposição branca, na notação de Gliński, é:

| Peça    | Casas iniciais                      |
| ------- | ----------------------------------- |
| Rei     | f1                                  |
| Dama    | e1                                  |
| Bispos  | d1, f2 e g2                         |
| Cavalos | c1 e g1                             |
| Torres  | b1 e h1                             |
| Peões   | b2, c2, d2, e2, f3, g3, h3, i2 e j2 |

A disposição das pretas é simétrica em relação à das brancas:

| Peça    | Casas iniciais                            |
| ------- | ----------------------------------------- |
| Rei     | f11                                       |
| Dama    | g11                                       |
| Bispos  | h11, f10 e e10                            |
| Cavalos | i11 e e11                                 |
| Torres  | j11 e d11                                 |
| Peões   | j10, i10, h10, g10, f9, e9, d9, c10 e b10 |

Essa configuração corresponde a uma disposição inicial publicada para a variante.

## 5. Movimentação das peças

No tabuleiro hexagonal existem dois conjuntos principais de direções:

- Seis direções ortogonais: os movimentos entre casas conectadas por uma aresta.
- Seis direções diagonais: os movimentos entre casas alinhadas pela geometria dos vértices dos hexágonos.

As peças percorrem as linhas permitidas pela sua movimentação, respeitando as ocupações das casas e os limites do tabuleiro.

### 5.1. Rei

O rei pode mover-se uma casa por vez em qualquer uma das 12 direções disponíveis: seis ortogonais e seis diagonais.

Regras:

- Não pode mover-se para uma casa atacada por uma peça adversária.
- Não pode permanecer em xeque.
- Não pode capturar uma peça protegida se, após a captura, ficar sob ataque.
- Não pode aproximar-se do rei adversário de modo a ficar numa casa atacada por ele.

Não existe roque nesta variante.

### 5.2. Dama

A dama combina os movimentos da torre e do bispo.

Pode deslocar-se por qualquer quantidade de casas livres em uma das 12 direções, tanto ortogonais quanto diagonais.

Não pode saltar sobre peças. Seu movimento termina antes de uma peça da mesma cor ou na casa ocupada por uma peça adversária, quando a captura é legal.

### 5.3. Torre

A torre pode mover-se por qualquer quantidade de casas livres em uma das seis direções ortogonais.

Ela:

- Move-se em linha reta.
- Não salta sobre peças.
- Pode capturar uma peça adversária situada em sua trajetória.
- Não pode atravessar uma peça para capturar outra que esteja atrás dela.

### 5.4. Bispo

O bispo move-se por qualquer quantidade de casas livres em uma das seis direções diagonais.

A principal particularidade é que cada bispo permanece sempre em casas da mesma cor. Como existem três cores no tabuleiro, cada jogador possui três bispos, um para cada cor.

O bispo não pode saltar sobre outras peças.

### 5.5. Cavalo

O cavalo executa um movimento em forma de salto, diferente do movimento da torre ou do bispo.

Sua movimentação consiste em avançar duas casas em uma direção ortogonal e depois uma casa em uma direção ortogonal a 60 graus dessa direção inicial, conforme a geometria do tabuleiro.

O cavalo:

- Pode saltar sobre outras peças.
- Pode terminar o movimento numa casa vazia.
- Pode capturar uma peça adversária na casa de destino.
- Não pode terminar numa casa ocupada por uma peça da própria cor.
- Deve respeitar as casas existentes e os limites do tabuleiro.

O cavalo pode alcançar até 12 destinos diferentes a partir de uma posição central, embora nas bordas do tabuleiro tenha menos possibilidades.

### 5.6. Peão

O peão avança em direção ao lado adversário, seguindo a direção vertical definida pela orientação do tabuleiro.

Suas regras são:

- Avança uma casa para a frente, se estiver livre.
- Pode avançar duas casas para a frente a partir de uma casa inicial de peão, desde que ambas as casas estejam livres.
- Não pode saltar sobre peças.
- Captura uma peça adversária numa casa diagonalmente à frente, segundo as direções próprias dos peões na geometria hexagonal.
- Não pode capturar uma peça que esteja diretamente à sua frente.
- Não pode recuar.

A possibilidade de avançar duas casas depende de o peão estar numa casa inicial de peão da sua cor, e não exclusivamente de nunca ter se movimentado. Isso significa que um peão que capture uma peça e passe a ocupar outra casa inicial de peão pode conservar ou recuperar a possibilidade de avançar duas casas, conforme as regras tradicionais de Gliński.
## 6. Capturas

Uma captura acontece quando uma peça se move para uma casa ocupada por uma peça adversária, retirando esta última do tabuleiro.

As regras gerais são:

1. Uma peça não pode terminar o movimento numa casa ocupada por outra peça da própria cor.
2. Torre, bispo e dama não podem atravessar peças.
3. O cavalo pode saltar sobre peças intermediárias.
4. O rei não pode realizar uma captura que o deixe em xeque.
5. Nenhuma peça pode executar um lance que deixe seu próprio rei em xeque.

As capturas obedecem às regras gerais do xadrez, adaptadas às direções permitidas pela geometria hexagonal.

## 7. Movimentos especiais dos peões

### 7.1. Avanço duplo

Um peão numa casa inicial de peão pode avançar duas casas numa única jogada, desde que:

- A casa intermediária esteja vazia.
- A casa de destino esteja vazia.
- O movimento seja realizado na direção correta.

Se o avanço duplo possibilitar uma captura en passant pelo adversário, essa captura poderá ser feita imediatamente no lance seguinte.

### 7.2. Captura en passant

A captura en passant é uma captura especial entre peões.

Ela pode acontecer quando um peão adversário avança duas casas de uma vez e passa por uma casa na qual poderia ser capturado por um peão inimigo.

O peão que tem direito à captura pode mover-se para a casa atravessada pelo peão adversário, retirando-o do tabuleiro como se ele tivesse avançado apenas uma casa.

Essa captura deve ser realizada imediatamente no lance seguinte. Se o jogador fizer outro movimento, perde o direito à captura en passant naquela oportunidade.

### 7.3. Promoção

Quando um peão alcança a extremidade oposta do tabuleiro, ele deve ser promovido.

O jogador substitui o peão por uma peça de sua escolha, de acordo com as regras da variante. A promoção ocorre ao alcançar o final de qualquer coluna.

Na aplicação mais comum das regras de Gliński, a escolha inclui:

- Dama.
- Torre.
- Bispo.
- Cavalo.

A peça promovida passa a obedecer imediatamente às regras de movimento da peça escolhida. A promoção não depende de a peça escolhida ter sido capturada anteriormente.

## 8. Xeque

O rei está em xeque quando é atacado por uma peça adversária.

O jogador em xeque deve obrigatoriamente executar um lance legal que elimine a ameaça.

As respostas possíveis são:

1. Mover o rei para uma casa que não esteja atacada.
2. Capturar a peça que está dando xeque, se a captura for legal.
3. Interpor uma peça entre o atacante e o rei, quando o tipo de ataque permitir essa defesa.

O rei não pode ignorar um xeque e não pode realizar um lance que deixe o rei sob ataque.

## 9. Xeque-mate

O xeque-mate ocorre quando o rei está em xeque e não existe nenhum lance legal que elimine o ataque.

O jogador que dá xeque-mate vence imediatamente a partida.

Não é necessário capturar o rei: a partida termina no momento em que o xeque-mate é estabelecido.

## 10. Afogamento ou empate por falta de lances

No xadrez tradicional, o afogamento acontece quando o jogador da vez não está em xeque, mas não possui nenhum lance legal.

Na versão original de Gliński, o afogamento não é considerado empate integral. Em competições que adotam a pontuação tradicional dessa variante:

- O jogador que provoca o afogamento recebe ¾ de ponto.
- O jogador afogado recebe ¼ de ponto.

Essa regra difere de muitas versões modernas e aplicativos que tratam o afogamento como empate comum. Por isso, é importante definir previamente qual sistema de pontuação será utilizado.

## 11. Empates

Além do afogamento, uma partida pode terminar empatada conforme as regras adotadas para a variante e para a competição.

As situações normalmente consideradas incluem:

- Acordo entre os jogadores: ambos aceitam o empate.
- Repetição de posição: a mesma posição ocorre três vezes, nas condições previstas pelo regulamento aplicado.
- Regra dos 50 lances: passam-se 50 lances de cada jogador sem movimento de peão nem captura, respeitadas as condições de reivindicação.
- Material insuficiente: não existe possibilidade de produzir xeque-mate de acordo com a posição e as peças restantes.

A aplicação dessas regras de empate deve seguir o regulamento específico da partida. Algumas plataformas e variantes simplificadas utilizam regras de empate diferentes das regras históricas de Gliński.

## 12. Fim da partida

A partida termina quando ocorrer uma das situações previstas no regulamento:

- Xeque-mate.
- Afogamento, com a pontuação própria da variante.
- Empate válido.
- Desistência de um jogador.
- Outra condição de encerramento prevista no regulamento de competição adotado.

O jogador também pode abandonar a partida, reconhecendo a vitória do adversário.

## 13. Notação dos lances

A notação identifica as peças e as casas do tabuleiro por letras e números.

A coluna `j` é omitida; portanto, as colunas são identificadas por `a`, `b`, `c`, `d`, `e`, `f`, `g`, `h`, `i`, `k` e `l`.

A notação algébrica utiliza, em geral:

- `K` para rei.
- `Q` para dama.
- `R` para torre.
- `B` para bispo.
- `N` para cavalo.
- Para peões, normalmente registra-se diretamente a casa de destino.
- `x` indica captura.
- `+` indica xeque.
- `#` indica xeque-mate.

Exemplos de notação de destino incluem `Nf4` para um movimento de cavalo até f4 e `Qe6+` para um movimento de dama até e6 que dá xeque. A notação exata pode variar conforme o sistema utilizado.

## 14. Diferenças em relação ao xadrez tradicional

| Característica       | Xadrez tradicional                 | Xadrez hexagonal de Gliński          |
| -------------------- | ---------------------------------- | ------------------------------------ |
| Formato do tabuleiro | Quadrado                           | Hexagonal                            |
| Número de casas      | 64                                 | 91                                   |
| Cores das casas      | 2                                  | 3                                    |
| Direções ortogonais  | 4                                  | 6                                    |
| Direções diagonais   | 4                                  | 6                                    |
| Bispos por jogador   | 2                                  | 3                                    |
| Peões por jogador    | 8                                  | 9                                    |
| Movimento do cavalo  | Até 8 destinos                     | Até 12 destinos em posições centrais |
| Roque                | Permitido em condições específicas | Não existe                           |
| Promoção             | Na última fileira                  | Na extremidade oposta da coluna      |
| Afogamento           | Empate                             | Pontuação especial na regra original |

Essas diferenças fazem com que o controle do espaço, a coordenação das peças e a proteção do rei tenham características próprias.

## 15. Regras essenciais para consulta rápida

1. As brancas começam.
2. O objetivo é dar xeque-mate ao rei adversário.
3. O tabuleiro possui 91 casas hexagonais e três cores.
4. Cada jogador tem um rei, uma dama, duas torres, dois cavalos, três bispos e nove peões.
5. A torre percorre seis direções ortogonais.
6. O bispo percorre seis direções diagonais e permanece na mesma cor.
7. A dama combina os movimentos da torre e do bispo.
8. O rei move-se uma casa em qualquer uma das 12 direções.
9. O cavalo salta conforme a geometria hexagonal.
10. Os peões avançam para a frente, capturam obliquamente e podem avançar duas casas a partir de uma casa inicial.
11. São permitidas a captura en passant e a promoção.
12. Não existe roque.
13. O rei não pode permanecer em xeque.
14. O xeque-mate encerra a partida.
15. O afogamento segue a pontuação específica da variante original de Gliński.

Observação importante: o nome “Xadrez Hexagonal” também designa outras variantes, como as de McCooey, Shafran e De Vasa. Elas podem alterar a posição inicial, o movimento dos peões e as condições de encerramento. Este regulamento é especificamente da variante de Gliński.### Fontes para consulta

- Chess Variants/Hexagonal Chess — [Regras e descrição das variantes hexagonais](https://en.wikibooks.org/wiki/Chess_Variants/Hexagonal_Chess?utm_source=chatgpt.com).
- Gliński's Hexagonal Chess — [História e regras da variante de Gliński](https://en.wikipedia.org/wiki/Hexagonal_chess?utm_source=chatgpt.com).
- [Green Chess — regras da variante de Gliński](https://www.greenchess.net/en/rules.php?v=glinski\&utm_source=chatgpt.com).
