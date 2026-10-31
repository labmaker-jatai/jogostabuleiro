# GIPF – Regras completas do jogo

Jogo abstrato de estratégia para dois jogadores | Autor: Kris Burm | Projeto GIPF

O GIPF é um jogo de estratégia para dois jogadores, baseado em posicionamento, deslocamento de peças e captura de peças adversárias.

O objetivo é eliminar todas as peças especiais GIPF do adversário ou impedir que ele consiga realizar uma jogada por falta de peças na reserva.

As regras a seguir apresentam as três modalidades oficiais:

1. Jogo básico (Basic Game).
2. Jogo padrão (Standard Game).
3. Jogo de torneio (Tournament Game).

Também são apresentadas as regras complementares e situações especiais que podem surgir durante uma partida.

Importante: as três modalidades compartilham as regras de movimentação e captura, mas possuem diferenças importantes na preparação e nas condições de vitória.

## 1. Componentes do jogo

O jogo original contém:

- 1 tabuleiro.
- 18 peças brancas.
- 18 peças pretas.

As peças são utilizadas individualmente ou empilhadas, dependendo da modalidade.

### 1.1. O tabuleiro

O tabuleiro possui:

- 37 posições internas, nas quais as peças podem permanecer.
- 24 pontos externos, utilizados para introduzir peças no jogo.
- Linhas que conectam as posições e determinam as direções possíveis de movimentação.

As posições internas são chamadas de spots, enquanto os pontos externos são chamados de dots.

Os pontos externos não fazem parte da área de jogo. Eles funcionam exclusivamente como locais de entrada das peças.

### 1.2. Tipos de peças

Existem dois tipos principais:

Peça básica (Basic Piece):

Uma peça individual, branca ou preta.

Peça GIPF (GIPF Piece):

É formada por duas peças básicas da mesma cor, empilhadas uma sobre a outra.

Uma peça GIPF ocupa apenas uma posição no tabuleiro e conta como uma única peça para efeito de movimentação e formação de sequências.

Entretanto, ela representa duas peças básicas e possui regras especiais de captura.

## 2. Objetivo do jogo

O objetivo depende da modalidade, mas no jogo padrão e no jogo de torneio existem duas condições de vitória:

- Retirar do tabuleiro todas as peças GIPF do adversário.
- Fazer com que o adversário fique sem peças na reserva, impossibilitando-o de realizar sua próxima jogada.

O jogador perde imediatamente quando uma dessas condições é alcançada.

Uma observação importante: devolver peças próprias à reserva não significa capturar peças do adversário. A vitória está relacionada à eliminação das peças adversárias ou à impossibilidade de continuar jogando.

## 3. Regras de movimentação

As regras desta seção são comuns às três modalidades.

### 3.1. Introdução de uma peça

Cada jogada começa com a retirada de uma peça da reserva do jogador.

O jogador deve:

1. Escolher uma peça de sua própria reserva.
2. Colocá-la em um dos 24 pontos externos do tabuleiro.
3. Empurrá-la para uma posição interna, seguindo uma das linhas disponíveis.

A peça pode ser introduzida em uma posição vazia ou ocupada.

### 3.2. Introdução em uma posição vazia

Quando o ponto interno de destino está vazio, basta empurrar a peça do ponto externo para essa posição.

A jogada termina após a introdução da peça.

### 3.3. Introdução em uma posição ocupada

Quando a posição de destino já está ocupada, a peça que está nela deve ser deslocada para a posição seguinte, na mesma direção.

Se essa posição também estiver ocupada, a peça seguinte deverá ser deslocada igualmente.

Esse procedimento continua até que seja encontrada uma posição vazia.

A nova peça entra, então, na primeira posição que foi liberada.

Regra fundamental: todas as peças deslocadas devem seguir a mesma direção.

Não é permitido escolher uma direção diferente para cada peça.

### 3.4. Deslocamento das peças

Existem algumas restrições:

- Cada peça pode ser deslocada apenas uma posição por vez.
- Não é permitido saltar posições.
- Não é permitido deslocar peças individualmente por iniciativa própria.
- As peças existentes no tabuleiro somente se movimentam quando são empurradas pela introdução de uma nova peça.
- Peças brancas e pretas podem ser deslocadas por qualquer jogador.
- Peças básicas e peças GIPF podem ser deslocadas da mesma maneira.

### 3.5. Limite de deslocamento

É proibido empurrar uma peça para fora da área de jogo.

Se uma linha estiver completamente ocupada até sua extremidade, não será possível introduzir uma peça naquela direção.

O jogador deve escolher outro ponto externo ou outra direção que permita a entrada sem retirar peças do tabuleiro.

### 3.6. Uma jogada obrigatória por turno

Cada jogador deve introduzir uma peça em seu turno.

A retirada de peças resultante de uma captura não substitui a obrigação de realizar uma jogada.

Portanto, mesmo depois de uma captura, o jogador continua precisando introduzir uma peça quando chegar sua vez.

## 4. Regras de captura

A captura é o mecanismo central do GIPF.

### 4.1. Formação de uma sequência de quatro peças

Sempre que quatro ou mais peças básicas da mesma cor estiverem alinhadas em posições consecutivas de uma mesma linha, forma-se uma sequência válida para captura.

A sequência deve obedecer às seguintes condições:

- As quatro peças devem ser da mesma cor.
- Devem ocupar posições consecutivas.
- Não pode existir uma posição vazia entre elas.
- Os pontos externos do tabuleiro não contam como posições da sequência.
- Uma peça GIPF também pode fazer parte de uma sequência, pois conta como uma peça da sua cor.

A captura é obrigatória quando uma sequência válida é identificada.

### 4.2. Retirada das peças da sequência

O jogador responsável pela cor da sequência deve retirar as quatro peças alinhadas.

Além dessas quatro peças, também devem ser retiradas todas as peças que estejam diretamente conectadas à sequência, em suas extremidades.

Essas peças adicionais podem ser de qualquer cor.

Por exemplo, considere a seguinte sequência:

- Quatro peças brancas consecutivas.
- Uma peça preta imediatamente depois da quarta peça.

Nesse caso, as quatro peças brancas e a peça preta devem ser retiradas.

Se houver duas peças pretas consecutivas depois da sequência branca, ambas também serão retiradas.

A retirada ocorre em toda a extensão contínua da linha, até encontrar uma posição vazia ou o final da linha.

### 4.3. Destino das peças retiradas

O destino depende da cor da peça:

| Peça retirada          | Destino                                                                     |
| ---------------------- | --------------------------------------------------------------------------- |
| Peça da própria cor    | Retorna à reserva do jogador                                                |
| Peça da cor adversária | É capturada e eliminada do jogo                                             |
| Peça GIPF própria      | Retorna à reserva como duas peças básicas                                   |
| Peça GIPF adversária   | Pode ser capturada ou permanecer no tabuleiro, conforme as regras especiais |

No jogo básico, todas as peças são individuais. Portanto, não existe a distinção especial das peças GIPF.

### 4.4. Captura obrigatória

A captura é obrigatória independentemente de quem tenha formado a sequência.

Isso significa que um jogador pode realizar uma jogada que forme uma sequência de peças adversárias.

Nesse caso, será o adversário quem deverá retirar suas peças da sequência.

Não é permitido ignorar deliberadamente uma sequência válida para preservar peças no tabuleiro.

### 4.5. Formação simultânea de duas sequências

Pode acontecer de uma jogada formar duas ou mais sequências simultaneamente.

Existem duas situações:

Sequências que não se cruzam:

Todas devem ser retiradas.

Sequências que se cruzam:

O jogador responsável pela cor das sequências escolhe qual delas será retirada primeiro.

Depois da retirada da primeira sequência, a outra pode deixar de existir. Nesse caso, as peças restantes permanecem no tabuleiro.

Existe uma exceção importante envolvendo peças GIPF, explicada na seção 5.

### 4.6. Capturas simultâneas de peças das duas cores

Uma jogada pode provocar situações em que os dois jogadores precisam retirar peças.

Nesse caso, o jogador que realizou a jogada que provocou a situação tem prioridade e realiza primeiro sua retirada.

Depois disso, o adversário realiza a retirada que ainda for obrigatória.

### 4.7. A captura não é uma jogada independente

A retirada de peças não conta como uma jogada.

O jogador não pode utilizar uma captura como substituição à introdução obrigatória de uma peça.

Depois que todas as capturas obrigatórias forem resolvidas, a partida continua normalmente.

## 5. Regras especiais das peças GIPF

Esta seção aplica-se ao jogo padrão e ao jogo de torneio.

As peças GIPF possuem características especiais que as diferenciam das peças básicas.

### 5.1. Uma peça GIPF conta como uma peça

Apesar de ser formada por duas peças básicas empilhadas, uma peça GIPF:

- Ocupa apenas uma posição.
- Conta como uma única peça para formar sequências.
- Pode ser empurrada normalmente.
- Pode integrar sequências de quatro ou mais peças da mesma cor.

### 5.2. Captura opcional das peças GIPF

Quando uma peça GIPF integra uma sequência que precisa ser retirada, o jogador responsável pela retirada pode escolher entre:

- Retirar a peça GIPF.
- Deixar a peça GIPF no tabuleiro.

Essa regra vale tanto para peças GIPF próprias quanto para peças GIPF adversárias.

As demais peças básicas da sequência e suas extensões devem ser retiradas normalmente.

Portanto, não é obrigatório capturar uma peça GIPF, mesmo quando ela pertence ao adversário.

### 5.3. Duas sequências que se cruzam em uma peça GIPF

Existe uma situação especial quando duas sequências de quatro ou mais peças da mesma cor se cruzam exatamente na posição ocupada por uma peça GIPF.

O jogador responsável pela retirada pode escolher entre duas alternativas:

Alternativa A: retirar a primeira sequência, incluindo a peça GIPF. Nesse caso, a segunda sequência deixa de existir porque a posição de cruzamento foi desocupada.

Alternativa B: retirar a primeira sequência, mas deixar a peça GIPF na posição de cruzamento. Nesse caso, a segunda sequência continua existindo e também deverá ser retirada.

Na segunda alternativa, o jogador poderá decidir novamente se deseja retirar ou preservar a peça GIPF na segunda sequência.

### 5.4. Retorno de uma peça GIPF própria à reserva

Quando o jogador decide retirar uma peça GIPF de sua própria cor, ela é desmontada.

As duas peças básicas que a constituem retornam separadamente à reserva.

Elas não podem voltar a ser introduzidas como uma única peça GIPF, exceto durante a fase inicial do jogo de torneio, enquanto o jogador ainda não tiver introduzido sua primeira peça básica.

### 5.5. Sequências formadas exclusivamente por peças GIPF

No jogo de torneio, pode acontecer de quatro ou mais peças GIPF da mesma cor ficarem alinhadas.

Nesse caso, o jogador responsável por essa cor pode:

- Manter todas as peças GIPF no tabuleiro.
- Retirar uma ou mais peças GIPF.

Enquanto a sequência permanecer intacta, o jogador poderá decidir novamente o que fazer quando chegar seu próximo turno.

Essa possibilidade é uma exceção à regra geral de captura obrigatória.

## 6. Modalidade 1 – Jogo básico (Basic Game)

O jogo básico é a versão introdutória do GIPF.

Nessa modalidade, utilizam-se exclusivamente peças individuais, sem empilhamento.

### 6.1. Preparação

Cada jogador recebe 15 peças de sua cor.

As três peças restantes podem ser utilizadas para equilibrar a partida, concedendo uma vantagem ao jogador menos experiente.

Por exemplo, um jogador pode começar com 15 peças e o outro com 12, 13 ou 14.

### 6.2. Posição inicial

Cada jogador começa com três peças no tabuleiro.

As peças são colocadas nos pontos externos angulares, alternando as cores, e depois introduzidas na primeira posição interna em direção ao centro.

Ao final da preparação:

- Existem três peças brancas no tabuleiro.
- Existem três peças pretas no tabuleiro.
- Cada jogador possui 12 peças na reserva, na configuração normal.

### 6.3. Desenvolvimento

Os jogadores alternam seus turnos, começando pelas brancas.

Cada jogador introduz uma peça por turno, respeitando todas as regras de movimentação e captura apresentadas anteriormente.

### 6.4. Condição de vitória

O jogador vence quando o adversário fica sem peças na reserva e, consequentemente, não consegue realizar uma nova jogada.

Não existem peças GIPF nessa modalidade.

## 7. Modalidade 2 – Jogo padrão (Standard Game)

Esta é a versão que introduz o principal elemento estratégico do GIPF: as peças especiais.

### 7.1. Preparação

Cada jogador recebe 18 peças básicas.

São formadas três peças GIPF para cada jogador, empilhando duas peças básicas de sua cor.

Assim, cada jogador começa com:

- Três peças GIPF no tabuleiro.
- Doze peças básicas na reserva.

### 7.2. Posição inicial

A posição inicial é igual à do jogo básico, mas as três peças de cada jogador que começam no tabuleiro são peças GIPF.

As cores são alternadas nas posições iniciais.

### 7.3. Desenvolvimento

Os jogadores seguem as regras normais de movimentação e captura.

Cada jogador deve introduzir uma peça básica da reserva em cada turno.

As peças GIPF já presentes no tabuleiro podem ser empurradas normalmente.

O jogador deve tomar cuidado para não perder todas as suas peças GIPF.

### 7.4. Condições de vitória

Existem duas maneiras de vencer:

1. Capturar a última peça GIPF do adversário.
2. Fazer com que o adversário fique sem peças básicas na reserva para realizar uma nova jogada.

Um jogador que perde todas as suas peças GIPF perde a partida, mesmo que ainda possua peças básicas na reserva.

Da mesma maneira, um jogador que perde todas as peças de sua reserva também perde, mesmo que ainda tenha peças GIPF no tabuleiro.

## 8. Modalidade 3 – Jogo de torneio (Tournament Game)

O jogo de torneio é a modalidade competitiva e mais elaborada do GIPF.

Ela modifica principalmente a preparação e a introdução das peças no início da partida.

### 8.1. Preparação

Cada jogador recebe 18 peças básicas.

Diferentemente do jogo padrão, o tabuleiro começa completamente vazio.

Não existem peças previamente posicionadas.

### 8.2. Primeira jogada obrigatória

A primeira jogada de cada jogador deve obrigatoriamente utilizar uma peça GIPF.

Para isso:

1. O jogador retira duas peças básicas de sua reserva.
2. Empilha as duas peças.
3. Coloca a peça GIPF em um dos pontos externos.
4. Empurra a peça para uma posição interna do tabuleiro.

O adversário também deverá introduzir uma peça GIPF em seu primeiro turno.

Portanto, não é permitido começar a partida com uma peça básica individual.

### 8.3. Fase de introdução das peças GIPF

Depois da primeira jogada, os jogadores podem continuar introduzindo peças GIPF.

Não existe um limite fixo de peças GIPF que cada jogador pode introduzir nessa fase.

Cada jogador pode decidir quantas peças GIPF deseja colocar no tabuleiro antes de começar a utilizar peças individuais.

É permitido, por exemplo, começar com três, quatro ou mais peças GIPF.

### 8.4. Introdução da primeira peça básica

Quando um jogador decide introduzir sua primeira peça básica individual, ocorre uma mudança importante:

Esse jogador não poderá mais introduzir novas peças GIPF durante o restante da partida.

A partir desse momento, suas próximas introduções deverão utilizar exclusivamente peças básicas individuais.

O adversário, entretanto, ainda poderá continuar introduzindo peças GIPF enquanto não tiver introduzido sua própria primeira peça básica.

Isso significa que os dois jogadores podem iniciar a fase de peças individuais em momentos diferentes.

### 8.5. Remoção de peças GIPF durante a fase inicial

Se um jogador tiver quatro ou mais peças GIPF consecutivas durante essa fase, poderá optar por mantê-las no tabuleiro ou retirar uma ou mais delas.

Retirar uma peça GIPF não significa que o jogador tenha introduzido uma peça básica individual.

Portanto, ele ainda poderá continuar introduzindo peças GIPF enquanto não tiver realizado sua primeira jogada com uma peça básica individual.

### 8.6. Desenvolvimento da partida

Depois que os jogadores começarem a utilizar peças básicas individuais, a partida segue as regras do jogo padrão.

Continuam valendo:

- As regras de movimentação.
- As regras de captura.
- A possibilidade de preservar peças GIPF.
- As regras de sequências simultâneas.
- As duas condições de vitória.

## 9. Situações especiais e esclarecimentos

As seguintes regras ajudam a resolver dúvidas que podem aparecer durante uma partida.

### 9.1. Uma sequência não percebida

Se uma sequência válida de quatro ou mais peças não for percebida imediatamente, a captura poderá ser exigida posteriormente.

A obrigação de retirar a sequência não desaparece simplesmente porque os jogadores continuaram jogando sem percebê-la.

Se algum jogador identificar a sequência, poderá exigir que ela seja resolvida.

### 9.2. Quem decide sobre uma peça GIPF?

A decisão de retirar ou preservar uma peça GIPF pertence sempre ao jogador responsável pela retirada da sequência.

Não importa quem tenha provocado a formação da sequência.

### 9.3. Quem resolve primeiro as sequências simultâneas?

Quando uma jogada provoca sequências que pertencem às duas cores, o jogador que realizou a jogada tem prioridade para resolver primeiro suas próprias sequências.

Em seguida, o adversário resolve as dele.

### 9.4. Peças deslocadas durante uma captura

As peças retiradas são determinadas pela sequência completa, incluindo as extensões contínuas.

Uma posição vazia interrompe a sequência.

Não se pode retirar uma peça que esteja separada da sequência por uma posição vazia.

### 9.5. A peça GIPF não precisa ser capturada

A peça GIPF pode permanecer no tabuleiro mesmo quando faz parte de uma sequência que está sendo retirada.

Essa decisão é estratégica e cabe ao jogador que realiza a retirada.

### 9.6. Não é permitido empurrar peças para fora do tabuleiro

Mesmo que uma peça esteja na extremidade de uma linha, ela não pode ser deslocada para fora da área de jogo.

O jogador deve escolher outra entrada para realizar sua jogada.

### 9.7. Não existe empate convencional

O primeiro jogador que perde sua última peça GIPF ou fica sem peças na reserva perde a partida.

Existe, entretanto, uma situação teórica de repetição de posições e jogadas.

Nas competições, quando um mesmo padrão de tabuleiro aparece pelo menos três vezes, os jogadores podem chamar o árbitro para interromper a partida e reiniciá-la conforme as regras de competição.

## 10. Regras de procedimento e etiqueta

Além das regras de movimentação e captura, existem procedimentos importantes para garantir uma partida organizada.

1. Toda jogada começa com a colocação de uma peça em um ponto externo.
2. Enquanto a peça estiver no ponto externo, o jogador pode voltar atrás.
3. Quando uma peça é empurrada em direção a uma posição vazia, a jogada não pode mais ser desfeita.
4. Quando uma peça já posicionada no tabuleiro é tocada para ser deslocada, a jogada não pode mais ser desfeita.
5. Quando várias peças precisam ser deslocadas, elas devem ser movimentadas uma por vez, começando pela peça mais distante da entrada.
6. As peças devem permanecer corretamente posicionadas nos espaços do tabuleiro.
7. A retirada das peças deve ser realizada de maneira organizada, respeitando a sequência e as regras de captura.

Nas competições oficiais também existem regras específicas para utilização do relógio e aplicação de penalidades.

## 11. Comparação entre as três modalidades

| Característica                                       | Básico        | Padrão  | Torneio                                   |
| ---------------------------------------------------- | ------------- | ------- | ----------------------------------------- |
| Peças por jogador                                    | 15            | 18      | 18                                        |
| Tabuleiro inicial                                    | Ocupado       | Ocupado | Vazio                                     |
| Peças iniciais no tabuleiro                          | 3 individuais | 3 GIPF  | Nenhuma                                   |
| Utiliza peças GIPF                                   | Não           | Sim     | Sim                                       |
| Introdução obrigatória de GIPF                       | Não           | Não     | Sim, na primeira jogada                   |
| Pode introduzir GIPF durante a partida               | Não           | Não     | Somente antes da primeira peça individual |
| Captura opcional de GIPF                             | Não           | Sim     | Sim                                       |
| Vitória pela eliminação de todos os GIPF adversários | Não se aplica | Sim     | Sim                                       |
| Vitória por esgotamento da reserva adversária        | Sim           | Sim     | Sim                                       |

## 12. Referência rápida das regras

Para facilitar a consulta durante uma partida, seguem as regras fundamentais resumidas:

1. Cada jogador joga alternadamente.
2. Em cada turno, deve introduzir uma peça da própria reserva.
3. A peça entra pelo ponto externo e é empurrada para uma posição interna.
4. Uma peça pode empurrar outras peças, independentemente da cor.
5. Todas as peças empurradas seguem a mesma direção.
6. Nenhuma peça pode ser empurrada para fora do tabuleiro.
7. Quatro ou mais peças básicas da mesma cor alinhadas formam uma sequência de captura.
8. A sequência deve ser retirada obrigatoriamente.
9. As peças próprias retornam à reserva.
10. As peças adversárias são capturadas.
11. As extensões contínuas da sequência também devem ser retiradas.
12. Peças GIPF podem ser preservadas pelo jogador que realiza a retirada.
13. Se duas sequências da mesma cor não se cruzam, ambas devem ser resolvidas.
14. Se duas sequências se cruzam, o jogador escolhe qual resolver primeiro, observando as regras especiais das peças GIPF.
15. Se os dois jogadores precisarem retirar peças, quem provocou a situação resolve primeiro.
16. A captura não substitui a jogada obrigatória.
17. No jogo padrão e no jogo de torneio, perder todas as peças GIPF significa perder a partida.
18. Em todas as modalidades, ficar sem peças na reserva também significa perder.

## 13. Fontes oficiais e consulta complementar

As regras foram organizadas a partir da documentação oficial do projeto GIPF, criado por Kris Burm.

- [Complete Rules – Regras completas do GIPF](https://www.gipf.com/gipf/rules/complete_rules.html?utm_source=chatgpt.com): apresenta as três modalidades e suas regras detalhadas.
- [Short Cut Rules – Regras resumidas do jogo de torneio](https://www.gipf.com/gipf/rules/rules.html?utm_source=chatgpt.com): apresenta as regras essenciais da modalidade competitiva.
- [Frequently Asked Questions – Perguntas frequentes](https://www.gipf.com/gipf/faq/faq.html?utm_source=chatgpt.com): esclarece situações especiais, dúvidas de captura e procedimentos de competição.
- [Manual em PDF – Rio Grande Games](https://www.riograndegames.com/wp-content/uploads/2013/02/GIPF-Rules.pdf?utm_source=chatgpt.com): documentação do jogo.

Recomendação: para ensinar o GIPF a novos jogadores, comece pelo jogo básico, passe para o jogo padrão e, somente depois, apresente o jogo de torneio. Essa progressão permite compreender primeiro a movimentação e as capturas, antes de introduzir a complexidade estratégica das peças GIPF.
