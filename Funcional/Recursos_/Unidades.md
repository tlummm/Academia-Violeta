# O que são [[Unidades]]

Uma **Unidade** é qualquer ser que ocupa casas no **Tabuleiro** e age no [[Combate]]. Tudo o que tem **Turno** é uma **Unidade**; o que só está ali (uma porta, uma muralha) é **Estrutura** (veja [[Talentos Gerais]]).

| **Papel**      | **Quem controla** | **O que é**                                         |
| :------------- | :---------------- | :-------------------------------------------------- |
| **Personagem** | Um **Jogador**    | Feito na [[Criação de Personagem]]                  |
| **NPC**        | O **Mestre**      | Aliado ou neutro: não luta contra o grupo           |
| **Oponente**   | O **Mestre**      | Luta contra o grupo; tem **Nível** e [[Escala]]     |

> Um **NPC** pode virar **Oponente** e o contrário. Muda só o lado em que ele está, não a ficha.

---

# Racionais e Criaturas

Toda **Unidade** é de um de dois tipos. O tipo diz o que ela pode usar e como se comporta.

| **Tipo**     | **Itens**                 | **Talentos Gerais**           | **Moedas** | **Fora do Combate**              |
| :----------- | :------------------------ | :---------------------------- | :--------: | :------------------------------- |
| **Racional** | Usa como um **Personagem** | **São** (e **Bestial** se tiver) |    Sim     | Conversa, negocia, se rende      |
| **Criatura** | Não usa                   | **Bestial**                   |    Não     | Segue o **Temperamento**         |

* **Racional**: pensa a longo prazo e entende o que os outros querem. **Personagens** são sempre **Racionais**.
* **Criatura**: age por instinto, fome e território. Não planeja nem barganha; a [[Interpretação]] com ela é ler o seu **Temperamento**, a sua comida e o seu lugar.

> **Moedas** e **Saque** de cada tipo estão em [[Economia]] e [[Recompensas]].

---

# Tamanho

O **Tamanho** diz quantas casas a **Unidade** ocupa.

| **Tamanho**  |            **Casas**             | **Exemplos**                      |
| :----------- | :------------------------------: | :-------------------------------- |
| **Pequeno**  | menos de 1 (divide em 3 ou mais) | Inseto, gato, ave pequena         |
| **Médio**    |                1                 | Gente, lobo, cavalo               |
| **Grande**   |               3×3                | Urso, touro, golem                |
| **Enorme**   |               5×5                | Elefante, troll                   |
| **Colossal** |           7×7 ou mais            | Dragão, baleia (escrito na ficha) |

* **Dividir casa**: até três **Unidades** **Pequenas** cabem numa casa em uma dimensão (9 por 9).
* **Alcance**: conta a partir de qualquer casa que a **Unidade** ocupa.
* **Mover outra Unidade**: empurrar, puxar ou arremessar só funciona em quem for do mesmo **Tamanho** ou menor, a não ser que a **Habilidade** diga o contrário.
* **Passar**: uma **Unidade** pode atravessar a casa de outra que seja de um **Tamanho** menor, sem gastar mais **Movimento**.

---

# Temperamento

Toda **Unidade** do **Mestre** tem um **Temperamento**: o que ela faz quando encontra o grupo fora do **Combate**.

| **Temperamento** | **Ao ver o grupo**                            |
| :--------------- | :-------------------------------------------- |
| **Fugidio**      | Apenas foge ao ver outras [[@Unidades]]       |
| **Dócil**        | Se aproxima e tenta criar uma relação         |
| **Pacífico**     | Ignora e segue a vida                         |
| **Territorial**  | Ataca quem entra no seu território            |
| **Hostil**       | Ataca quem entra no alcance dos seus sentidos |

* **Condição**: a ficha pode dizer o que muda o **Temperamento** (ex.: "**Territorial**; vira **Hostil** se for atacado").
* **Moral**: no [[Combate]], **Criaturas** **Normais** que não sejam **Hostis** tentam **Fugir** (veja [[Combate]]) quando metade do seu lado já caiu.
* O **Temperamento** é a base da [[@Domesticação_]].

---

# Ficha do Oponente

**Personagens** usam a [[Ficha Base]]. **Oponentes** e **NPCs** usam uma ficha curta:

> **Nome**

| **Nível** | **Escala** | **Poder** | **Tipo**  | **Tamanho** | **Temperamento** |
| :-------: | :--------- | :-------- | :-------- | :---------- | :--------------- |
|     5     | Normal     | Real      | Criatura  | Médio       | Territorial      |

| **Ataque** | **Defesa** | **Maestria** | **Espírito** | **Precisão** | **Esquiva** |
| :--------: | :--------: | :----------: | :----------: | :----------: | :---------: |
|     0      |     0      |      0       |      0       |      0       |      0      |

| **Vida** | **Foco** | **Velocidade** | **Fraqueza** | **Resistência** |
| :------: | :------: | :------------: | :----------- | :-------------- |
|    0     |    0     |       0        | —            | —               |

> **Habilidades e Talentos**
> * **Nome**: regra, ou link para a **Arte** ou para os [[Talentos Gerais]].

> **Recompensas**
> **XP** pela [[Progressão]]; **Saque** pelas [[Recompensas]].

<small>Aparência e hábitos, sem regra.</small>

* **Poder**: um dos [[Cinco Poderes]]. Decide o **Poder contra Poder** do **Dano** que ela causa e sofre (veja [[Tipos de Dano]]).
* **Atributos Secundários**: só aparecem na ficha quando não forem 0.

---

# Montar um Oponente

O **Mestre** monta qualquer **Oponente** em três passos: pontos, distribuição e o que a **Escala** acrescenta.

### 1. Pontos

Um **Personagem** de **Nível** N tem, nas seis pontas, mais ou menos **22 + N** pontos (12 da base, 10 da criação e 2 a cada **Nível** par). Esse é o **Total** do **Oponente** do mesmo **Nível**, mudado pela **Escala**:

| **Escala**   | **Pontos nas pontas**                | **Vida**                           | **Foco**                               | **Habilidades e Talentos** |
| :----------- | :----------------------------------- | :--------------------------------- | :------------------------------------- | :------------------------- |
| **Normal**   | Metade do **Total**                  | **Ataque** + **Defesa**            | 5 + **Maestria** + **Espírito**        | 1 por **Grau** (mínimo 1)  |
| **Elite**    | O **Total**                          | (10 + **Ataque** + **Defesa**) × 2 | 10 + **Maestria** + **Espírito**       | 2 por **Grau** (mínimo 2)  |
| **Chefe**    | O **Total** × 1,5                    | (10 + **Ataque** + **Defesa**) × 2 por **Personagem** | (10 + **Maestria** + **Espírito**) por **Personagem** | 3 por **Grau** (mínimo 3)  |
| **Soberano** | Definido depois do **Limite Humano** | —                                  | —                                      | —                          |

* **Velocidade**: 5 + **Precisão** + **Esquiva**, em todas as **Escalas**.
* **Arredondar**: sempre para baixo.
* **Oponentes Reais** param de ganhar pontos no **Nível 39**, como os **Personagens** (veja [[Progressão]]). Os de outros **Poderes** seguem até o 99.

### 2. Distribuição

O **Mestre** distribui os pontos como quiser. Para ir rápido, use um molde (cada número é quantos décimos do total vão naquela ponta; arredonde para baixo e dê as sobras, uma a uma, às pontas de maior número do molde):

| **Molde**   | **Ataque** | **Defesa** | **Maestria** | **Espírito** | **Precisão** | **Esquiva** |
| :---------- | :--------: | :--------: | :----------: | :----------: | :----------: | :---------: |
| **Bruto**   |     3      |     3      |      1       |      1       |      1       |      1      |
| **Ágil**    |     2      |     1      |      1       |      1       |      3      |      2      |
| **Muralha** |     1      |     4      |      1       |      2       |      1      |      1      |
| **Místico** |     1      |     1      |      3       |      3       |      1      |      1      |

### 3. O que a Escala acrescenta

* **Normal**: morre ao chegar a 0 de **Vida** (veja [[Combate]]) e segue a **Moral**.
* **Elite**: uma **Resistência** a um tipo de **Dano** ou a um [[Efeitos|Efeito]], à escolha do **Mestre**.
* **Chefe** e **Soberano**:
  * **Um Turno por Personagem**: o primeiro na sua **Velocidade**, como qualquer **Unidade**. Cada um dos outros vem logo depois do **Turno** de um **Personagem**, na ordem da fila, até acabarem. Se sobrar algum (por **Personagens** caídos), ele vem no fim da **Rodada**.
  * **Feito para o grupo**: a **Vida** e o **Foco** do **Chefe** dependem de quantos **Personagens** o enfrentam (veja a tabela). A ficha escreve o valor por **Personagem**.
  * **Segunda Fase**: quando a **Vida** chega à metade pela primeira vez, dissipa todos os **Efeitos** de **Atordoamento**, **Medo** e **Controle** que carrega e ganha a **Habilidade** ou o **Talento** marcado como **Fase 2** na ficha.

---

# Exemplo

Um **Lobo**, **Normal** de **Nível 5**, **Criatura** **Real**, **Médio**, **Territorial**.

1. **Pontos**: **Total** 22 + 5 = 27. **Normal**, metade: **13**.
2. **Molde Ágil**: 13 pontos em décimos dá **Precisão** 4, **Ataque** 3, **Esquiva** 3, **Defesa** 1, **Maestria** 1, **Espírito** 1.
3. **Linhas**: **Vida** 3 + 1 = **4**; **Foco** 5 + 1 + 1 = **7**; **Velocidade** 5 + 4 + 3 = **12**.
4. **Talentos** (**Grau 0**, 1): **Matilha** ([[Talentos Gerais]]).

> **Lobo**

| **Nível** | **Escala** | **Poder** | **Tipo**  | **Tamanho** | **Temperamento**                      |
| :-------: | :--------- | :-------- | :-------- | :---------- | :------------------------------------ |
|     5     | Normal     | Real      | Criatura  | Médio       | Territorial; Hostil se estiver com fome |

| **Ataque** | **Defesa** | **Maestria** | **Espírito** | **Precisão** | **Esquiva** |
| :--------: | :--------: | :----------: | :----------: | :----------: | :---------: |
|     3      |     1      |      1       |      1       |      4       |      3      |

| **Vida** | **Foco** | **Velocidade** | **Fraqueza** | **Resistência** |
| :------: | :------: | :------------: | :----------- | :-------------- |
|    4     |    7     |       12       | —            | —               |

> **Habilidades e Talentos**
> * **Matilha**: [[Talentos Gerais]].

> **Recompensas**
> **50 XP** (10 × **Nível** 5).

<small>Caçam em grupos de quatro a oito e cercam a presa antes do primeiro bote. Um lobo sozinho quase sempre está ferido ou foi expulso da matilha.</small>