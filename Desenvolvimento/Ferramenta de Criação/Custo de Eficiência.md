
---

# O que é o Custo de Eficiência

O **Custo de Eficiência** mede quanto uma **Habilidade** ou um **Talento** entrega pelo que custa. É uma régua de desenvolvimento: serve para criar e balancear [[Habilidades e Talentos]], e não aparece na mesa.

* **Referência em Foco**: nem tudo custa **Foco**, mas cada coisa ganha uma **referência**, que é quanto **Foco** compraria aquilo a 100%. Assim **Dano**, **Efeitos**, movimento e [[Interpretação]] podem ser comparados.
* **A régua**: **1 Foco** compra **1d10** de **Dano** em **Combate**, ou **1 Teste Normal** vencido sem rolar fora dele.
* **Eficiência**: a soma das referências dividida pelo que a **Habilidade** custa.
* **Arredondamento**: só no final da conta, sempre para cima.

### Meta

A mesma para **Habilidades** e **Talentos**:

| **Ranque** | **Eficiência** |
| :-: | :-: |
| 1 | 100% |
| 2 | 125% |
| 3 | 150% |

O **Ranque 3** fica em 150% de número. O que ele ganha além disso vem em jogada nova: outro alvo, um gatilho ou mais usos, e não só um número maior.

---

# Como calcular

1. **Ler a Habilidade** e separar as partes: o **Dano**, cada **Efeito**, cada metro de movimento, cada controle e cada uso em [[Interpretação]].
2. **Dar a referência de cada parte** com as tabelas abaixo.
3. **Ajustar pela Precisão** tudo o que depende de acertar.
4. **Somar** as partes.
5. **Dividir** pelo custo:

| **O que é** | **Conta** |
| :---------- | :-------- |
| **Habilidade** | Soma ÷ **Foco** que ela custa |
| **Talento** | Soma num **Combate** inteiro ÷ 1 |
| **Talento** de [[Interpretação]] | **Testes Normais** que ele vale numa **Sessão** ÷ 1 |

6. **Aplicar as Restrições**, se houver (abaixo).
7. **Arredondar** para cima.

---

# Cenário genérico

O cálculo usa um alvo e um **Personagem** genéricos, para que a mesma **Habilidade** dê sempre o mesmo número.

| **Quem** | **Ataque** | **Defesa** | **Esquiva** | **Vida** | **Velocidade** |
| :------- | :-: | :-: | :-: | :-: | :-: |
| **Alvo genérico** | 10 | 0 | 0 | 40 | 10 |
| **Personagem** | 10 | 6 | — | — | 10 |

* **Horizonte**: a luta ainda tem 4 **Rodadas** quando a **Habilidade** é usada.
* **Dois cenários**: contra **1 alvo** e contra um grupo. **Área pequena** (**Cone** de 2 metros, ao seu lado, 1d4 metros) acerta 3. **Área grande** (**Cone** de 3 metros, 2 metros ao redor, 1d8 metros ou mais) acerta 5. **Linha** de 2 metros acerta 2.
* **Dado**: vale a média (1d4 = 2,5; 1d6 = 3,5; 1d8 = 4,5; 1d10 = 5,5; 1d12 = 6,5; 1d20 = 10,5).

### Precisão

As referências já supõem **Precisão Normal**. As outras multiplicam o que depende de acertar:

| **Precisão** | **Chance** | **Multiplica por** |
| :----------- | :-: | :-: |
| **Garantida** | 100% | 1,33 |
| **Normal** | 75% | 1 |
| **Difícil** | 55% | 0,73 |
| **Improvável** | 35% | 0,47 |

---

# Referências

### Dano

| **O quê** | **Referência** | **Por quê** |
| :-------- | :-: | :---------- |
| **1d10** de **Dano** (ou 6 fixo) | 1 **Foco** | a régua; valor fixo não cresce com o **Nível**, o **Atributo** cresce |
| Primeiro **Ataque** inteiro dentro da **Habilidade** | 2 **Foco** | o **Turno** já tem a **Ação de Ataque** (1 **Foco**) e a **Ação Principal**; um **Ataque** a mais custa o dobro |
| Segundo **Ataque** inteiro na mesma **Habilidade** | +4 **Foco** | no mesmo **Turno**, cada **Ataque** dobra o preço do anterior, como juros |
| Terceiro | +8 **Foco** | |
| **Metade de Ataque** (em **Área**) | 1 **Foco** por alvo atingido | |

* **Exemplos**: **Ataque** + 1d10 vale 3 **Foco**. Dois **Ataques** valem 6. Três valem 14.
* **Dano** que não está na tabela vira referência dividindo por 6.

### Recursos e movimento

| **O quê** | **Referência** | **Por quê** |
| :-------- | :-: | :---------- |
| 1 **Foco** ganho ou devolvido | 0,5 **Foco** | sem **Foco** o golpe sai pela metade, então 1 de **Foco** compra só a outra metade |
| 6 de **Vida** curada ou **Barreira** | 1 **Foco** | 6 de **Dano** evitado |
| **Ação de Movimento** a mais | 1 **Foco** | custa 1 de **Foco** |
| 1 metro andado ou empurrado | 0,1 **Foco** | um **Movimento** de 10 metros |
| **Turno** a mais de um aliado | 6 **Foco** | um **Turno** inteiro (abaixo) |

### Efeitos de intensidade

**Sangramento**, **Desgaste**, **Regeneração**, **Concentração**, **Aumento** e **Redução** perdem 1 **Acúmulo** no **Fim do Turno** e agem com a força que resta (3, depois 2, depois 1).

| **Acúmulos** | 1 | 2 | 3 | 4 | 5 | 6 |
| :-- | :-: | :-: | :-: | :-: | :-: | :-: |
| **Turnos-acúmulo** (horizonte de 4 **Rodadas**) | 1 | 3 | 6 | 10 | 14 | 18 |

**Referência** = **Dano** por **Turno** de 1 **Acúmulo** × **Turnos-acúmulo** ÷ 6.

| **Efeito** | **Dano por Turno** (1 **Acúmulo**) | **Por quê** |
| :--------- | :-: | :---------- |
| **Sangramento**, **Regeneração** | 1 | 1 de **Vida** |
| **Desgaste**, **Concentração** | 3 | 1 de **Foco** (0,5 **Foco** de referência) |
| **Aumento de Ataque**, **Letalidade** | 0,75 | +1 num golpe × 75% |
| **Aumento de Defesa** | 0,38 | meio ponto num golpe × 75% |
| **Redução de Defesa** | 1,5 | meio ponto em 3 golpes do grupo |
| **Aumento** ou **Redução** de **Precisão** ou **Esquiva** | 0,5 | 5% de acerto num golpe de 10 |
| **Aumento** ou **Redução** de **Velocidade** | 0,6 | 1 metro a mais ou a menos |

* **Exemplo**: 3 **Sangramento** = 1 × 6 ÷ 6 = **1 Foco**.

### Efeitos de estado

Cada **Acúmulo** é um **Turno** a mais. A referência é o que custaria comprar o que o **Oponente** perde: o **Ataque** dele (2), a **Ação Principal** (uma **Habilidade** média, 3) e o **Movimento** (1). Um **Turno** inteiro vale **6 Foco**.

| **Efeito** | **Foco por Acúmulo** | **O que o Oponente perde** |
| :--------- | :-: | :------------------------- |
| **Desarme** | 2 | o **Ataque** |
| **Enraizamento** | 2 | o **Movimento** e, muitas vezes, o alcance do **Ataque** |
| **Silêncio** | 3 | a **Ação Principal** |
| **Sono** | 3 | o **Turno**, mas acorda com qualquer **Dano** |
| **Banimento** | 4 | o **Turno**, mas também não pode ser atingido |
| **Atordoamento** | 6 | o **Turno** inteiro |
| **Medo** | 6 | o **Turno** inteiro, longe do grupo |
| **Controle** | 12 | o **Turno** inteiro, que ainda age contra o grupo |

* **Controle custa caro**: estes valores são o piso. Uma **Habilidade** de controle nunca fica abaixo deles.
* **Fora da especialidade**: se a **Classe** ou a **Arte** não é boa em controle (veja o **Perfil** da **Classe**), o preço pode subir. Não entra na conta; fica a critério de quem cria a **Habilidade**.

### Efeitos consumidos

Não perdem **Acúmulo** com o tempo; valem pelo que evitam ou pagam ao serem usados.

| **Efeito** | **Referência** |
| :--------- | :-: |
| **Barreira** | 1 **Foco** a cada 6 |
| **Equilíbrio** | 0,5 **Foco** |
| **Resistência** | o **Efeito** que ela anula, × metade |
| **Proteção** | 2 **Foco** (um **Ataque** anulado) |
| **Audácia** | 0,5 **Teste** (um **d20** de novo) |

### Permanente

O **Efeito Permanente** não perde **Acúmulo**, dura o **Combate** inteiro e ainda exige tratamento depois.

* **Referência** = referência por **Turno** × **Acúmulos** × 4 **Rodadas** × **2**.
* **Exemplo**: **Medo Permanente** = 6 × 4 × 2 = **48 Foco**, fora do alcance de uma **Habilidade** comum.

### Outros

| **O quê** | **Referência** | **Por quê** |
| :-------- | :-: | :---------- |
| **Dissipação** de um **Efeito** | a referência do **Efeito** removido | o que ele ainda faria |
| **Vida** máxima que o alvo perde | 1 **Foco** a cada 6 | **Dano** que não precisa ser causado |
| **Habilidade** do **Oponente** travada | 3 **Foco** por uso | a **Ação Principal** dele |

---

# Interpretação

**1 Foco** compra **1 Teste Normal** vencido sem rolar: **100%**.

| **O quê** | **Referência** |
| :-------- | :-: |
| **Teste Normal** vencido sem rolar | 1 **Foco** |
| **Teste Difícil** vencido sem rolar | 1,37 **Foco** |
| **Teste Improvável** vencido sem rolar | 2,14 **Foco** |
| +1 no **d20** de um **Teste** (1 aumento no **Modificador**) | 0,05 **Foco** |
| Uma capacidade nova | 0,2 **Foco** |
| Cinco capacidades novas ou mais | 1 **Foco** |

* **Abrir uma fechadura comum** (**Teste Normal** de [[Trapaça_]]): uma **Habilidade** de 1 **Foco** que abre sem rolar vale **100%**.
* **Capacidade**: algo que o **Personagem** passa a saber fazer, e que sem o **Talento** não faria ou faria mal: servir à mesa como um nobre, reconhecer brasões, acompanhar um rito. Saber fazer quer dizer não rolar **Testes Normais** daquilo: consegue sempre. Por isso esses **Testes** não somam à parte; já estão no preço da capacidade. Cada uma vale 0,2 **Foco**; cinco ou mais valem **100%**, e acima disso não sobe mais.
* **O resto nos Ranques**: mais **Testes**, **Testes** mais difíceis e outros usos entram nos **Ranques** da **Habilidade** ou do **Talento**.
* **Talento** de **Interpretação**: conta quantos **Testes** do tipo aparecem numa **Sessão**. Tipo amplo (comunicação, força): cerca de 3. Tipo estreito (**Religião**, **Música**): cerca de 1.
* **Exemplo**: um **Talento** que concede cinco capacidades de nobre e 1 aumento no **Modificador** para elas, num tipo amplo, vale 1 + 3 × 0,05 = **115%**.

---

# Restrições

Uma **Habilidade** que custa **Foco** pode ser usada de novo sempre que houver **Foco**. Quando ela tem um limite, pode entregar mais para compensar: divida a **Eficiência** pelo fator.

| **Restrição** | **Fator** |
| :------------ | :-: |
| Sem limite | 1 |
| 1 vez por **Combate** | 1,5 |
| 1 vez por **Descanso** | 2 |
| 1 vez por **Sessão** | 2,5 |
| **Desencadeado** por uma condição | 1 ÷ chance da condição (ex.: com metade da **Vida** ou menos, cerca de 50%: fator 2) |

---

# Exemplos

### Carga (Cavaleiro antigo, Ranque 1)

**Foco** 5. Anda até o dobro da **Velocidade**, faz um **Ataque** e, depois de 10 metros, empurra **1d10** metros e aplica 1 **Enraizamento**.

| **Parte** | **Conta** | **Referência** |
| :-------- | :-------- | :-: |
| **Ataque** | primeiro **Ataque** inteiro | 2 |
| 20 metros | 20 × 0,1 | 2 |
| Empurrão | 5,5 × 0,1 | 0,55 |
| **Enraizamento** | 1 **Acúmulo** | 2 |
| **Total** | | **6,55** |

* **Eficiência**: 6,55 ÷ 5 = 1,31, ou **131%**. Acima da meta do **Ranque 1**.

### Intimidação (Cavaleiro antigo, Ranque 1)

**Foco** 5. **Precisão Difícil**. Aplica 1 **Medo** num **Normal**.

* **Medo**: 6 × 0,73 = 4,38.
* **Eficiência**: 4,38 ÷ 5 = **88%**.

### Golpe Crescente (Esgrima antiga, Ranque 1)

**Foco** 3. **Cone** de 2 metros: metade do **Ataque** em cada um, empurra 2 metros, e você ganha **1d4** de **Aumento de Velocidade**.

* **Por alvo**: 1 (metade de **Ataque**) + 0,2 (empurrão) = 1,2.
* **Velocidade**: 2,5 **Acúmulos**, cerca de 4,5 **Turnos-acúmulo** × 0,6 ÷ 6 = 0,45.
* **1 alvo**: (1,2 + 0,45) ÷ 3 = **55%**.
* **Área pequena** (3 alvos): (3,6 + 0,45) ÷ 3 = **135%**.

### Guarda Alta (Esgrima antiga, Talento, Ranque 1)

Sem custo. As **Ações de Ataque** contra você causam **1d4** a menos.

* **Por Rodada**: um golpe recebido × 75% × 2,5 = 1,88.
* **Combate**: 1,88 × 4 = 7,5 de **Dano** evitado ÷ 6 = 1,25 **Foco**.
* **Eficiência**: **125%**. Acima da meta do **Ranque 1**.

---

# Limites

* **Sem Tabuleiro**: os valores de movimento e de **Enraizamento** são médias. Numa sala apertada valem menos; num campo aberto, mais.
* **Alvo genérico**: o que depende do tipo de alvo (ignorar **Defesa**, cortar cura, **Medo** só em **Normais**) é calculado como se a condição valesse, e a nota da **Habilidade** diz quando não vale.
* **Ajustável**: se uma referência parecer errada, muda-se a tabela e as **Habilidades** são recalculadas.

---