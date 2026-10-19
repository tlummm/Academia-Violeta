# O que é a Eficiência de Foco

A **Eficiência de Foco** mede quanto uma **Habilidade** ou um **Talento** entrega por ponto de **Foco** gasto. É uma régua de desenvolvimento: serve para criar e balancear [[Habilidades e Talentos]], e não aparece na mesa.

* **Por que Foco**: toda [[Ações|Ação]] de **Combate** gasta **Foco**, e o **Foco** só volta com [[Descanso]]. Ele é a moeda comum de tudo o que um **Personagem** faz numa luta.
* **A régua**: a **Ação de Ataque** custa 1 de **Foco** e causa um **Ataque** de **Dano**. Ela vale **100%**. Uma **Habilidade** de 100% entrega o mesmo que uma **Ação de Ataque** para cada ponto de **Foco** que custa.
* **Tudo vira Dano**: **Efeitos**, movimento, controle e **Dissipação** recebem um preço em **Dano** (a tabela de **Valores**, abaixo). Assim uma **Habilidade** de controle pode ser comparada com uma de **Dano**.
* **Dois cenários**: contra **1 alvo** e contra **5 alvos**. Um golpe individual de 100% vale 20% contra 5, porque acerta só um deles. Uma **Área** que acerta os cinco mantém a porcentagem.

### Meta

| **Ranque** | **Eficiência** |
| :-: | :-: |
| 1 | 100% |
| 2 | 125% |
| 3 | 150% |

O **Ranque 3** fica em 150% de número. O que ele ganha além disso vem em jogada nova: outro alvo, um gatilho ou mais usos por **Combate**, e não só um número maior.

#### Talentos

Os **Talentos** não custam **Foco** e seguem meta própria, medida como valor por **Rodada** ÷ 7,5:

| **Ranque** | **Eficiência** |
| :-: | :-: |
| 1 | 25% |
| 2 | 50% |
| 3 | 75% |

### Área

Uma **Habilidade** em **Área** causa **um terço** do **Dano** de uma **Habilidade** de alvo único com o mesmo **Foco**.

| **Alvos atingidos** | **Total, comparado com o alvo único** | **Coluna de 5 alvos** |
| :-: | :-: | :-: |
| 1 | 33% | 7% |
| 3 | 100% | 20% |
| 5 | 167% | 33% |

* **Por quê**: a **Área** empata com o alvo único quando acerta 3, perde quando acerta menos e ganha quando acerta mais.
* **Na Lista**: um golpe de alvo único de 100% aparece com 20% na coluna de 5 alvos. Uma **Área** que segue a regra aparece com 33% (**Área grande**) ou 20% (**Área pequena**, que acerta 3 dos 5).

---

# Como calcular

1. **Ler a Habilidade** e separar as partes: o **Dano**, cada **Efeito**, cada metro de movimento e cada controle.
2. **Dar o valor de cada parte** com a tabela de **Valores**.
3. **Multiplicar pela chance de acerto** tudo o que depende de acertar.
4. **Somar** as partes.
5. **Dividir** pelo custo, conforme o cenário:

| **Cenário** | **Conta** |
| :---------- | :-------- |
| **1 alvo** | Valor ÷ (**Foco** × 7,5) |
| **5 alvos** | Valor somado nos 5 ÷ (5 × **Foco** × 7,5) |
| **Sem custo** (**Talentos** e **Habilidades** de **Foco** 0) | Valor por **Rodada** (ou por uso) ÷ 7,5 |

O 7,5 é o **Dano** médio de uma **Ação de Ataque** no cenário genérico (**Ataque** 10 × 75% de acerto).

---

# Cenário genérico

O cálculo não usa nenhuma criatura da [[Fera Base]]. Ele usa um alvo e um **Personagem** genéricos, para que a mesma **Habilidade** dê sempre o mesmo número.

| **Quem** | **Ataque** | **Defesa** | **Esquiva** | **Vida** | **Velocidade** | **Outros** |
| :------- | :-: | :-: | :-: | :-: | :-: | :--------- |
| **Alvo genérico** | 10 | 0 | 0 | 40 | 10 | aplica, por **Combate**, 1 **Atordoamento**, 1d4 de **Sangramento** e 1d4 de **Redução de Ataque** |
| **Personagem** | 10 | 6 | — | — | 10 | grupo de 4; os aliados sem **Defesa** |

* **Horizonte**: a luta ainda tem 4 **Rodadas** quando a **Habilidade** é usada.
* **Área pequena** (**Cone** de 2 metros, ao seu lado, 1d4 metros): acerta 3 dos 5. **Área grande** (**Cone** de 3 metros, 2 metros ao redor, 1d8 metros ou mais): acerta os 5. **Linha** de 2 metros: 2.
* **Dado**: vale a média (1d4 = 2,5; 1d6 = 3,5; 1d8 = 4,5; 1d10 = 5,5; 1d12 = 6,5; 1d20 = 10,5).

### Chance de acerto

| **Precisão** | **Chance** |
| :----------- | :-: |
| **Garantida** | 100% |
| **Normal** | 75% |
| **Difícil** | 55% |
| **Improvável** | 35% |

---

# Valores

Quanto cada coisa vale, em **Dano**.

### Recursos e ações

| **O quê** | **Vale** | **Por quê** |
| :-------- | :-: | :---------- |
| **Ação de Ataque** | 7,5 | **Ataque** 10 × 75% (a régua) |
| 1 de **Foco** ganho ou devolvido | 3,75 | sem **Foco** o golpe sai pela metade, então 1 de **Foco** compra só a outra metade |
| 1 de **Vida** | 1 | 1 de **Dano** |
| **Ação de Movimento** a mais | 7,5 | custa 1 de **Foco** |
| 1 metro andado (quando precisa) | 0,75 | um **Movimento** de 10 metros vale 7,5 |
| 1 metro que um **Oponente** é empurrado | 0,75 | ele gasta o mesmo para voltar |
| **Turno** a mais de um aliado | 10 | **Ataque** e um pouco de **Habilidade** |

### Efeitos positivos

| **Efeito** | **Vale** | **Por quê** |
| :--------- | :-: | :---------- |
| 1 **Aumento de Ataque** | 3 | +1 em 4 golpes × 75% |
| 1 **Aumento de Defesa** | 1,5 | meio ponto em 4 golpes × 75% |
| 1 **Letalidade** | 1,5 | meio ponto de **Dano** em 4 golpes × 75% |
| 1 de **Precisão** ou **Esquiva** | 2 | 5% de acerto em 4 golpes de 10 |
| 1 de **Crítico** | 1,5 | 5% de dobrar 4 golpes × 75% |
| 1 de **Velocidade** | 1,5 | 1 metro em metade das 4 **Rodadas** |
| 1 **Regeneração** | 4 | 1 por **Rodada** |
| 1 **Barreira** | 1 | 1 de **Dano** evitado |
| 1 **Equilíbrio** | 3,75 | vale 1 de **Foco** ganho |
| **Proteção** | 7,5 | anula um golpe |

### Efeitos negativos e controle

| **Efeito** | **Vale** | **Por quê** |
| :--------- | :-: | :---------- |
| 1 **Sangramento** ou **Desgaste** | 4 | 1 por **Rodada** |
| 1 **Redução de Defesa** | 6 | meio ponto em 12 golpes do grupo |
| 1 **Redução de Precisão** | 2 | 5% de acerto a menos em 4 golpes |
| 1 **Redução de Velocidade** | 1,5 | 1 metro em metade das 4 **Rodadas** |
| **Enraizamento** | 15 | em metade das **Rodadas** o **Oponente** não alcança ninguém |
| **Desarme** | 15 | metade do que o **Oponente** faz em 4 **Rodadas** |
| **Atordoamento** | 10 | um **Turno** do **Oponente** |
| **Medo** | 30 | o **Oponente** fora do resto da luta (4 **Rodadas** × 7,5) |
| **Habilidade** do **Oponente** travada | 7,5 por uso | uma **Ação de Ataque** dele |

### Outros

| **O quê** | **Vale** | **Por quê** |
| :-------- | :-: | :---------- |
| **Dissipação** do que o **Oponente** genérico aplica | 14,1 | **Atordoamento** (10), metade do **Sangramento** (5) e metade da **Redução de Ataque** (3,75), × 75% |
| **Vida** máxima que o alvo perde | 1 por ponto | **Dano** que não precisa ser causado |
| Derrubar o alvo (**Executar**) | a **Vida** que sobra | um quinto da **Vida** dá, em média, 1/10 dela |
| Aliado sem alvo (**Duelo**) | −7,5 por **Rodada** | a **Ação de Ataque** que ele perde |

---

# Exemplos

### Carga (Cavaleiro, Grau 2, Ranque 1)

**Foco** 5. Anda até o dobro da **Velocidade**, faz uma **Ação de Ataque** e, depois de 10 metros, empurra **1d10** metros e aplica 1 **Enraizamento**.

| **Parte** | **Conta** | **Valor** |
| :-------- | :-------- | :-: |
| **Ataque** | 10 × 75% | 7,5 |
| 20 metros | 20 × 0,75 | 15 |
| Empurrão | 5,5 × 0,75 × 75% | 3,1 |
| **Enraizamento** | 15 × 75% | 11,3 |
| **Total** | | **36,8** |

* **1 alvo**: 36,8 ÷ (5 × 7,5) = **98%**.
* **5 alvos**: 36,8 ÷ (5 × 5 × 7,5) = **20%**.

### Intimidação (Cavaleiro, Grau 1, Ranque 1)

**Foco** 5. **Precisão Difícil**. Aplica **Medo** num **Normal**.

* **Valor**: 30 × 55% = 16,5.
* **1 alvo**: 16,5 ÷ (5 × 7,5) = **44%**.

### Golpe Crescente (Esgrima, Grau 0, Ranque 1)

**Foco** 3. **Cone** de 2 metros: metade do **Ataque** em cada um, empurra 2 metros, e você ganha **1d4** de **Aumento de Velocidade**.

* **Por alvo**: (5 + 2 × 0,75) × 75% = 4,9.
* **Velocidade**: 2,5 × 1,5 = 3,8.
* **1 alvo**: (4,9 + 3,8) ÷ (3 × 7,5) = **38%**.
* **5 alvos** (o **Cone** pequeno acerta 3): (3 × 4,9 + 3,8) ÷ (5 × 3 × 7,5) = **16%**.

### Guarda Alta (Esgrima, Grau 0, Ranque 1)

Sem custo. As **Ações de Ataque** contra você causam **1d4** a menos.

* **Por Rodada**: um golpe recebido × 75% × 2,5 = 1,9.
* **1 alvo**: 1,9 ÷ 7,5 = **25%**.
* **5 alvos**: 5 golpes recebidos, então 9,4 ÷ (5 × 7,5) = **25%**.

---

# Limites

* **Sem Tabuleiro**: os valores de movimento e de **Enraizamento** são médias. Numa sala apertada valem menos; num campo aberto, mais.
* **Alvo genérico**: o que depende do tipo de alvo (ignorar **Defesa**, cortar cura, tirar **Aumento**, **Medo** só em **Normais**) é calculado como se a condição valesse, e a nota da **Lista de Eficiência** diz quando não vale.
* **Fora do Combate**: o que vale em [[Interpretação]] não entra na conta.
* **Foco ganho e Foco gasto**: o **Foco** que uma **Habilidade** custa vale 7,5, porque adianta o **Exausto**. O **Foco** que ela dá ou devolve vale 3,75, porque só tira a metade de **Dano** que o **Exausto** perde. A [[Simulação 19_|Simulação 19]] mostrou que contar 7,5 nos dois superestima quem dá **Foco**.
* **Os preços são ajustáveis**: se um valor parecer errado, muda-se a tabela e todas as **Habilidades** são recalculadas (script `Testes_/scripts/eficiencia_completa.py`, dicionário `PRECO`).