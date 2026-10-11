
---

# O que são os [[Tipos de Dano]]

Todo **Dano** tem um tipo. O tipo diz **o que reduz** aquele **Dano** e **quem é mais fraco** contra ele. Existem três grandes grupos:

| **Dano**    | **Vem de**                                          | **É reduzido por**                |
| :---------- | :-------------------------------------------------- | :-------------------------------- |
| **Físico**  | **Ataque**: golpes, armas, quedas, garras           | **Defesa**                        |
| **Mágico**  | **Maestria**: **Habilidades** e [[@Itens]] dos **Poderes** anormais | **Espírito**          |
| **Puro**    | Fontes raras, e todo **Dano** de [[@Efeitos]]       | Nada                              |

> **Defesa** e **Espírito** estão em [[Atributos]]. Um golpe de 5 contra **Defesa** 2 causa 3; uma **Habilidade** de 5 contra **Espírito** 2 também causa 3.

---

# Sem dano mínimo

Se a **Defesa** ou o **Espírito** do alvo for maior ou igual ao **Dano**, ele não sofre nada. Um bando de inimigos fracos não derruba um guardião bem protegido só por ser numeroso: para feri-lo, é preciso **Dano** de verdade, um **Acerto Crítico**, **Dano Puro** ou levar a melhor pelo **Poder**.

---

# Dano Físico

O **Dano** do que existe de fato: músculo, aço, pedra, queda. Tem três tipos:

1. **Contusão**: pancadas e esmagamento. Maças, martelos, socos, quedas.
2. **Corte**: lâminas e garras. Espadas, machados, mordidas.
3. **Perfuração**: pontas e projéteis. Lanças, flechas, virotes, presas.

Cada arma diz o seu tipo (veja [[@Equipamentos]]). O tipo importa contra **Unidades** com **Fraqueza** ou **Resistência** (abaixo): uma armadura de placas aguenta **Corte** melhor do que **Contusão**.

---

# Dano Mágico

O **Dano** que vem dos quatro **Poderes** anormais (veja [[Cinco Poderes]]). O tipo é o próprio **Poder**:

1. **Sagrado**: luz, milagre, juízo. Veja [[Artes Sagradas_]].
2. **Sombrio**: trevas, maldição, corrupção. Veja [[Artes Sombrias_]].
3. **Selvagem**: espíritos, ancestrais, a fúria da natureza. Veja [[Artes Selvagens_]].
4. **Mágico**: **Arcano**, ou um elemento (**Água**, **Fogo**, **Terra**, **Vento**). Sem elemento dito, é **Arcano**. Veja [[Artes Mágicas_]].

---

# Dano Puro

Ignora **Defesa** e **Espírito**: o alvo sofre exatamente o que está escrito. Vem de:

* **[[@Efeitos]]**: o **Dano** de um **Sangramento** ou de qualquer outro **Efeito** é sempre **Puro**.
* **Fontes raras**: quedas muito altas, **Habilidades** que digam "**Dano Puro**", armadilhas e catástrofes.

---

# Poder contra Poder

Toda **Unidade** pertence a um dos [[Cinco Poderes]], e todo **Dano** também (o **Físico** de quem é **Real** também é **Real**). Quando o **Poder** do **Dano** leva a melhor sobre o **Poder** do alvo, o **Dano** aumenta:

* **Ter vantagem**: o **Dano** dobra (×2).
* **Subjugar**: o **Dano** triplica (×3).

| **Poder do Dano** | **Triplica contra** | **×Dobra contra** |
| :---------------- | :------------------ | :---------------- |
| **Sagrado**       | Sombrio             | Mágico            |
| **Sombrio**       | Selvagem e Real     | Mágico            |
| **Selvagem**      | Real                | Nenhum            |
| **Mágico**        | Nenhum              | Real e Selvagem   |
| **Real**          | Nenhum              | Sagrado           |

> Por que cada **Poder** leva a melhor sobre outro está em [[Cinco Poderes]]. Aqui fica só a conta.

---

# Fraqueza e Resistência

Algumas **Unidades** têm **Fraqueza** ou **Resistência** a um tipo (**Corte**, **Fogo**, **Sombrio**...), escrita na sua ficha:

* **Fraqueza**: o **Dano** daquele tipo dobra (×2).
* **Resistência**: o **Dano** daquele tipo cai pela metade (×0,5).
* **Imunidade**: o **Dano** daquele tipo é 0.

> O mesmo se repete para **Eficiências** e [[@Efeitos]].

---

# A conta, na ordem

1. **Dano Base**: o **Ataque** (**Físico**) ou a **Eficiência** da **Habilidade** ou do **Item** (**Mágico**).
2. **Multiplicadores**: **Acerto Crítico** (que dobra também **Eficiências** e [[@Efeitos]], veja [[Combate]]), **Poder contra Poder**, **Fraqueza** e **Resistência**. Multiplique todos e arredonde para baixo.
3. **Redução**: tire a **Defesa** (**Físico**) ou o **Espírito** (**Mágico**). **Puro** pula esta etapa. Se ficar abaixo de 0, o **Dano** é 0.

---

# Exemplo

**Fulano** (**Real**, **Ataque** 6) acerta com uma maça num **Espectro** (**Sagrado**, **Defesa** 3, **Fraqueza** a **Contusão**).

1. **Dano Base**: 6, **Físico** de **Contusão**.
2. **Multiplicadores**: **Real** tem vantagem sobre **Sagrado** (×2) e o **Espectro** é fraco a **Contusão** (×2). 6 × 2 × 2 = 24.
3. **Redução**: 24 − 5 de **Defesa** = **14**.

Com uma espada (**Corte**), seria 6 × 2 = 12, menos 3: **6**. Escolher a arma certa dobrou o **Dano**.

---