
---

# O que é o [[Combate]]

O [[Combate]] é o modo do **Jogo** para lutas. Fora dele, em [[@Interpretação]], as [[Ações]] são livres e o tempo corre como a história pedir. Dentro dele, o tempo é dividido em **Turnos**, cada **Personagem** age na sua vez e cada [[Ações|Ação]] gasta **Foco**.

O **Combate** acontece num **Tabuleiro** de casas, e cada casa vale 1 metro. Todo mundo que luta, seja **Jogador**, **NPC** ou **Monstro**, é uma **Unidade** (veja [[@Unidades]]).

---

# Começar e ordem dos Turnos

1. **Começa** quando alguém ataca ou quando o **Mestre** declara que a luta começou. Todos colocam as suas **Unidades** no **Tabuleiro**.
2. **Ordem**: todas as **Unidades** agem numa só fila, da maior **Velocidade** para a menor. Em empate, os **Jogadores** vão primeiro e decidem entre si.
3. **Rodada**: quando todas as **Unidades** agiram, termina a **Rodada** e a fila recomeça do topo.

> A **Velocidade** é a linha da **Agilidade** (veja [[Atributos]]). Ser rápido não é só andar mais: é agir antes.

---

# O Turno

Cada **Turno** tem três partes, sempre nesta ordem:

1. **Início do Turno**: os [[Efeitos]] que estão em você agem. Um **Sangramento** tira **Vida**, uma **Regeneração** devolve. Os **Atributos Secundários** de **Concentração** e **Regeneração** também agem aqui.
2. **Ações**: você faz até três [[Ações]] (**Movimento**, **Ataque** e **Principal**), uma de cada, na ordem que quiser, pagando o **Foco** de cada uma. Pode pular as que não quiser.
3. **Fim do Turno**: nada some. Os [[Efeitos]] **não** diminuem com o tempo: um **Efeito** negativo só sai com tratamento (veja [[Cuidados]]), e um positivo só sai quando é consumido ou quando o **Combate** acaba.

> Passar o **Turno** inteiro também é uma escolha. Você não gasta **Foco**, mas os [[Efeitos]] do **Início do Turno** acontecem do mesmo jeito.

---

# Acertar

Toda [[Ações|Ação]] contra um **Oponente** pede um **d20**:

* **Rolagem**: **d20** + sua **Precisão** − **Esquiva** do alvo.
* **Precisão pedida**: o resultado precisa chegar a um número. **Normal** 8, **Difícil** 12, **Improvável** 16. A **Ação de Ataque** e os [[@Itens]] são **Normal**, se nada disser o contrário.
* **Acerto Crítico**: 20 no dado (antes de somar) acerta sempre e **dobra o Dano**, **Eficiências** e inclusive [[Efeitos]]. O **Atributo Secundário** **Crítico** reduz esse número em 1 por ponto.
* **Erro Crítico**: 1 no dado erra sempre e **termina o seu Turno** na hora. As [[Ações]] que faltavam se perdem.

---

# Dano e Alcance

* **Dano Físico**: vem do **Ataque** e é reduzido pela **Defesa** do alvo.
* **Dano Mágico**: vem da **Maestria** e é reduzido pelo **Espírito** do alvo.
* **Corpo a Corpo**: desarmado ou com arma de mão, o **Alcance** é 1 metro (casas vizinhas, inclusive na diagonal).
* **Longo Alcance**: arcos, bestas e armas de arremesso alcançam o que a arma disser, mas causam **metade** do **Dano**, **Eficiências** e dos [[Efeitos]] (arredondado para baixo).
* **Alcance** (o **Atributo Secundário**) soma 1 metro por ponto, exceto em **Corpo a Corpo** e **Movimento**.

Os tipos de **Dano** e as suas fraquezas estão em [[Tipos de Dano]].

---

# Cair

Quando a **Vida** chega a 0, a **Unidade** fica **Caída**:

* **Não age**: perde os **Turnos** seguintes, mas continua na fila e os [[Efeitos]] do **Início do Turno** continuam agindo.
* **Levantar**: um aliado ao lado usa a **Ação Principal** com [[Medicina_]] ou com um [[@Itens|Item]] de cura e a **Unidade** volta com 1 de **Vida**. Fora isso, ela só se levanta depois do **Combate**.
* **Morrer**: qualquer **Dano** sofrido enquanto **Caída** mata.

> **Monstros** e **NPCs** comuns morrem direto ao chegar a 0, se o **Mestre** não disser o contrário.

---

# Fugir e terminar

* **Fugir**: uma **Unidade** que termina o **Movimento** numa casa da borda do **Tabuleiro**, sem nenhum **Oponente** a 1 metro, sai do **Combate**. Os **Oponentes** podem perseguir: o **Mestre** decide se começa outro **Combate** mais à frente.
* **Terminar**: o **Combate** acaba quando um dos lados não tem mais **Unidades** de pé no **Tabuleiro**, seja por **Vida** em 0 ou por fuga. Todos voltam para [[@Interpretação]].
* **Depois**: o **Foco** e a **Vida** **não** voltam no fim do **Combate**. Só com [[Descanso]] (veja [[Ações]]).
* **Derrota**: se todos os **Jogadores** estão **Caídos** quando o **Combate** acaba, ninguém morre de imediato: o **Mestre** decide o que os **Oponentes** fazem com eles (prender, roubar, abandonar).

---

# Exemplo de Rodada

**Fulano** (**Velocidade** 5, **Precisão** 3, **Ataque** 6) e **Ciclana** (**Velocidade** 7) enfrentam uma **Fera** (**Velocidade** 5, **Esquiva** 1, **Defesa** 2, **Vida** 12).

* **Ordem**: **Ciclana** (7), **Fulano** (5, ganha o empate por ser **Jogador**) e a **Fera** (5).
* **Ciclana** anda e usa uma **Habilidade** de [[Táticas_]].
* **Fulano** está com 1 **Sangramento** desde a luta anterior: no **Início do Turno** perde 1 de **Vida**. Depois anda até a **Fera** e ataca: rola 7, + 3 − 1 = **9**, acerta (**Normal** 8). **Dano** 6 − 2 = **4**. A **Fera** fica com 8.
* No **Fim do Turno**, o **Sangramento** de **Fulano** continua. Ele vai perder 1 de **Vida** a cada **Turno** até alguém tratá-lo.
* **Fera** ataca **Fulano** e rola 1: **Erro Crítico**, o **Turno** dela acaba ali.

---
