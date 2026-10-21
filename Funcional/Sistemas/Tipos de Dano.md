
---

# O que são os [[Tipos de Dano]]

Todo **Dano** tem um tipo. O tipo diz **o que mitiga** aquele **Dano** e **quem é mais fraco** contra ele. Existem três grandes grupos:

| **Dano**    | **Vem de**                                                          | **É mitigado por** |
| :---------- | :------------------------------------------------------------------ | :----------------- |
| **Físico**  | **Ataque**: golpes, armas, quedas, garras                           | **Defesa**         |
| **Anormal** | **Maestria**: **Habilidades** e [[@Itens]] dos **Poderes** anormais | **Espírito**       |
| **Puro**    | Fontes raras, e todo **Dano** de [[Efeitos]]                        | Nada               |

> **Defesa** e **Espírito** estão em [[Atributos]]. Cada 2 pontos mitigam 1 de **Dano**: um golpe de 5 contra **Defesa** 4 causa 3; uma **Habilidade** de 5 contra **Espírito** 4 também causa 3.

---

# Dano mínimo

Todo acerto causa pelo menos **1** de **Dano**, por maior que seja a **Defesa** ou o **Espírito** do alvo. Um guardião bem protegido aguenta muito, mas não para sempre: um bando de inimigos fracos o desgasta aos poucos. O **Poder** multiplica esse 1 normalmente (vira 2 ou 3), e só a **Imunidade** faz um acerto causar 0.

---

# Dano Físico

O **Dano** do que existe de fato: músculo, aço, pedra, queda. Tem três tipos:

1. **Contusão**: pancadas e esmagamento. Maças, martelos, socos, quedas.
2. **Corte**: lâminas e garras. Espadas, machados, mordidas.
3. **Perfuração**: pontas e projéteis. Lanças, flechas, virotes, presas.

Cada arma diz o seu tipo (veja [[@Equipamentos]]). O tipo importa contra **Unidades** com **Fraqueza** ou **Resistência** (abaixo): uma armadura de placas aguenta **Corte** melhor do que **Contusão**.

---

# Dano Anormal

O **Dano** que vem dos quatro **Poderes** anormais (veja [[Cinco Poderes]]). O tipo é o próprio **Poder**:

1. **Sagrado**: luz, milagre, juízo. Veja [[Artes Sagradas_]].
2. **Sombrio**: trevas, maldição, corrupção. Veja [[Artes Sombrias_]].
3. **Selvagem**: espíritos, ancestrais, a fúria da natureza. Veja [[Artes Selvagens_]].
4. **Mágico**: **Arcano**, ou um elemento (**Água**, **Fogo**, **Terra**, **Vento**). Sem elemento dito, é **Arcano**. Veja [[Artes Mágicas_]].

---

# Dano Puro

Ignora **Defesa** e **Espírito**: o alvo sofre exatamente o que está escrito. Vem de:

* **[[Efeitos]]**: o **Dano** de um **Sangramento** ou de qualquer outro **Efeito** é sempre **Puro**.
* **Fontes raras**: quedas muito altas, **Habilidades** que digam "**Dano Puro**", armadilhas e catástrofes.

---

# Poder contra Poder

Toda **Unidade** pertence a um dos [[Cinco Poderes]], e todo **Dano** também (o **Físico** de quem é **Real** também é **Real**). Quando o **Poder** do **Dano** leva a melhor sobre o **Poder** do alvo, o **Dano** que passou pela **Mitigação** aumenta:

* **Ter vantagem**: o **Dano** dobra (×2).
* **Subjugar**: o **Dano** triplica (×3).

| **Poder do Dano** | **Triplica contra** | **×Dobra contra** |
| :---------------- | :------------------ | :---------------- |
| **Sagrado**       | Sombrio             | Mágico            |
| **Sombrio**       | Selvagem e Real     | Mágico            |
| **Selvagem**      | Real                | Nenhum            |
| **Mágico**        | Nenhum              | Real e Selvagem   |
| **Real**          | Nenhum              | Sagrado           |

A vantagem só vale para um lado. O **Selvagem** triplica contra o **Real**, mas o **Real** bate normal no **Selvagem**: quem não está na tabela causa **Dano** normal.

> Por que cada **Poder** leva a melhor sobre outro está em [[Cinco Poderes]]. Aqui fica só a conta.

---

# Fraqueza e Resistência

Algumas **Unidades** têm **Fraqueza** ou **Resistência** a um tipo (**Corte**, **Fogo**, **Sombrio**...), escrita na sua ficha. Elas valem sobre o **Dano** que passou pela **Mitigação**:

* **Fraqueza**: o **Dano** daquele tipo dobra (×2).
* **Resistência**: o **Dano** daquele tipo cai pela metade (×0,5).
* **Imunidade**: o **Dano** daquele tipo é 0.

> O mesmo se repete para **Eficiências** e [[Efeitos]].

---

# A conta, na ordem

1. **Dano Base**: o **Ataque** (**Físico**) ou a **Eficiência** da **Habilidade** ou do **Item** (**Anormal**). Um **Acerto Crítico** dobra este número (e também **Eficiências** e [[Efeitos]], veja [[Combate]]).
2. **Mitigação**: tire a metade da **Defesa** (**Físico**) ou do **Espírito** (**Anormal**), arredondada para baixo, e o que **Habilidades** e **Talentos** do alvo mitigarem. **Puro** pula esta etapa.
3. **Mínimo**: se ficar abaixo de 1, o **Dano** é **1**.
4. **Multiplicadores**: **Poder contra Poder**, **Fraqueza** e **Resistência**. Multiplique todos e arredonde para baixo, sem cair abaixo de 1 (só a **Imunidade** zera).

---

# Exemplo

**Fulano** (**Real**, **Ataque** 6) acerta com uma maça num **Espectro** (**Sagrado**, **Defesa** 3, **Fraqueza** a **Contusão**).

1. **Dano Base**: 6, **Físico** de **Contusão**.
2. **Mitigação**: metade da **Defesa** 3 é 1. 6 − 1 = 5.
3. **Mínimo**: 5 passa de 1.
4. **Multiplicadores**: **Real** tem vantagem sobre **Sagrado** (×2) e o **Espectro** é fraco a **Contusão** (×2). 5 × 2 × 2 = **20**.

Com uma espada (**Corte**), seria 5 × 2 = **10**. Escolher a arma certa dobrou o **Dano**.

Se o **Espectro** tivesse **Defesa** 20, a **Mitigação** tiraria 10 e sobraria 0. O **Mínimo** sobe para 1, e os multiplicadores fazem 1 × 2 × 2 = **4**.

---