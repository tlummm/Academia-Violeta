# Montanha dos Sonhos — Referência do Sistema e Briefing do Projeto

> Este documento complementa o **campo de instruções** do projeto Claude. O campo cuida das regras operacionais sempre ativas; este arquivo serve como referência de terminologia, estrutura e convenções do sistema, para que o Claude nunca contradiga o que já foi estabelecido.

---

## 1. Visão Geral

**Montanha dos Sonhos** é um **RPG de Mesa** ambientado em um universo fictício centrado em uma **Montanha que realiza desejos**. O sistema é construído em torno da diversidade: diferentes modalidades de jogo (histórias, lutas, aventuras, enigmas, entre outras) e liberdade total de estilo, estratégia e construção de personagem.

A filosofia central é **incentivar cada pessoa a jogar do seu próprio jeito**, oferecendo recursos para todos os perfis — de habilidades estranhas para personagens exóticos a itens sérios para fichas cuidadosamente construídas. A história de cada campanha é um **recurso narrativo** para unir e direcionar o grupo, nunca uma coleira: os jogadores podem perseguir objetivos secundários ou explorar áreas fora do enredo principal.

O projeto é gerenciado no **Obsidian**, com todo o conteúdo em **Markdown**.

---

## 2. Glossário do Sistema (terminologia canônica)

Respeite sempre a grafia e o sentido dos termos abaixo. Ao escrever regras, habilidades ou lore novos, use estes termos como base e não introduza sinônimos concorrentes.

### Os dois Planos

O jogo acontece em dois **Planos**:

- **[[@Interpretação]]** — modo mais livre, de narrativa e ação fora de combate.
- **[[@Combate]]** — modo com regras estritas: ordem de **Turnos** pelo **Atributo** de **Velocidade** (jogadores primeiro, depois oponentes, do mais rápido ao mais lento); três **Ações Controladas** por turno (Movimento, Ataque e Principal) em ordem livre; fases não controladas de **Início de turno** (aplicação de **Efeitos**) e **Fim de turno** (redução de cada **Efeito** em 1). O **Tabuleiro** usa casas de 1 metro quadrado. Um **Erro Crítico** (1 no **d20**) encerra o turno.

### Aspectos e Classes

Cada **Aspecto** amarra uma **Classe**:

- **Força → Guerra**
- **Inteligência → Magia**
- **Agilidade → Astúcia**

As demais **Classes** ficam em [[@Classes_]]. A **Classe** é a decisão central da [[@Ficha]].

### Aspectos e Atributos

Detalhados em [[@Aspectos_]]. Recursos base: **Vida** e **Mana**.

- **Atributos Primários**: Alcance, Ataque, Defesa, Domínio, Espírito, Maestria, Sorte, Velocidade, Vigor.
- **Atributos Secundários**: Crítico, Precisão, Letalidade, Esquiva, entre outros.

### Habilidades e Talentos

Organizados em [[@Habilidades e Talentos]], progridem por **Nível** de 0 a 9:

0. Novato (Nível Inicial)
1. Regular
2. Entusiasta
3. Especialista
4. Veterano
5. Mestre
6. Gênio
7. Lorde
8. Rei
9. Lenda

No **Nível 9**, cada **Classe** evolui seu **Talento Principal** (ex.: Guerra → Maestria Duelista, Magia → Maestria Elemental, Astúcia → Maestria Estratégica).

**Escala de Raridade dos Itens (separada da escada de classe)**: os [[@Itens]] — [[@Ferramentas]], [[@Equipamentos]] e [[@Uso Único]] — têm raridade própria por **Nível**, de 0 a 9.

### Precisão

Níveis de **Precisão** de uma **Ação**: **Garantida**, **Normal**, **Difícil**, **Improvável**.

### Dano

- **Físico** — subtipos Contusão, Corte, Perfuração. Mitigado por **Defesa**.
- **Mágico** — Arcano por padrão; ganha tipo pelo **Conhecimento**: Aqua (água/gelo), Ignis (fogo), Gaia (terra), Ventus (vento). Mitigado por **Espírito**.
- **Puro** — ignora qualquer mitigação.

**Regra do mínimo**: **Dano Físico** e **Mágico** sempre causam pelo menos 1, mesmo com mitigação total (salvo menção explícita em **Habilidade**, **Item** ou **Talento**).

### Efeitos

Anotados em [[@Efeitos]]. Funcionam com **pilhas** e **duração**, reduzidos em 1 no **Fim de turno**. Podem ser removidos por **Dissipação** (Fraca, Média, etc.).

### Itens

Três categorias: [[@Ferramentas]], [[@Equipamentos]] e [[@Uso Único]]. **Jogadores** têm inventário de **5 espaços**, expansível por **Mochilas**.

### Tipos de Unidade

**Jogador**, **NPC**, **Monstro**, **Chefe** (algumas regras tratam **Chefes** de forma diferenciada).

---

## 3. Convenções de Escrita e Formatação (Obsidian) — INEGOCIÁVEL

- **SEMPRE preservar os links `[[wiki]]` do Obsidian**, inclusive aliases (`[[Página|texto exibido]]`). Nunca converter para texto simples nem para Markdown `[texto](url)`.
- Manter cabeçalhos, listas e estrutura existentes ao editar; só reorganizar quando a reorganização for o objetivo do pedido.
- Não reescrever documentos inteiros quando o pedido é um ajuste pontual.

---

## 4. Tom das Campanhas

O sistema suporta múltiplos tons. Identifique qual está em jogo e adapte a escrita; se não estiver claro, pergunte.

- **Épico** — grandioso, heroico, de alto risco e escala.
- **Aventureiro** — exploração, descoberta, ritmo dinâmico.
- **Sombrio** — tenso, ameaçador, com peso emocional e moral.
- **Cômico** — leve, absurdo, com espaço para o inesperado e o exótico.

---

## 5. Como o Claude Colabora

- Atua como **co-criador**: contribui ativamente com ideias e alternativas, respeita decisões já tomadas e propõe melhorias sem impor.
- **Sinaliza** inconsistências de lore e problemas de balanceamento assim que os identifica.
- Recebe arquivos **um de cada vez**, com instruções específicas, e constrói o contexto de forma progressiva, retendo o que já foi estabelecido na sessão.
- **Pergunta quando falta contexto**, em vez de assumir.

---