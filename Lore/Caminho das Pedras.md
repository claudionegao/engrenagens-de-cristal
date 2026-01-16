# Caminho das Pedras

## Estrutura da Árvore de Decisão (8 Gemas → 4 → 2 → 1)

*Há momentos em que o mundo parece pulsar com urgência, como se cada pedra guardasse um segredo de força ou astúcia. O silêncio entre dois trovões revela que nem sempre o caminho mais rápido é o mais seguro, e que a fúria pode ser tão valiosa quanto o cálculo paciente. O destino se desenha entre o ímpeto e o olhar atento, convidando você a sentir o peso de cada escolha.*

### Pergunta 1: Qual seu estilo predominante?
- **A)** Força, agressividade ou resistência física. → Grupo 1
- **B)** Magia, técnica ou agilidade. → Grupo 2

#### Grupo 1: (Ametista, Rubí, Topázio, Safira)
#### Grupo 2: (Peridoto, Pedra da Lua, Pérola, Obsidiana)

*O campo se abre como um palco de possibilidades. Alguns corações marcham como trovões, prontos para o impacto e o confronto. Outros preferem a distância, onde cada movimento é calculado e cada flecha lançada é uma escolha entre o risco e a precisão. O caminho se bifurca entre o rugido e o olhar atento.*

### Pergunta 2A (Grupo 1): Como prefere enfrentar desafios?
- **A)** Combate direto, impacto e brutalidade. → Subgrupo 1A
- **B)** Controle de campo, ataques à distância ou evasão. → Subgrupo 1B

#### Subgrupo 1A: Ametista, Rubí
#### Subgrupo 1B: Topázio, Safira

*Entre véus de energia e correntes de vento, o caminho se divide. Há quem sinta o chamado do arcanismo, onde cada gesto desenha runas invisíveis e o poder se acumula como tempestade. Outros preferem a explosão de velocidade, cortando o espaço com pura destreza, como relâmpagos que cruzam o horizonte. O tempo parece desacelerar, esperando sua escolha entre o mistério e o ímpeto.*

### Pergunta 2B (Grupo 2): Qual seu foco principal?
- **A)** Velocidade, combos e técnica marcial. → Subgrupo 2A
- **B)** Magia, suporte ou manipulação arcana. → Subgrupo 2B

#### Subgrupo 2A: Peridoto, Pedra da Lua
#### Subgrupo 2B: Pérola, Obsidiana

*Diante do altar da força, o chão vibra com cada batida do coração. O ar é pesado, e a decisão se faz entre o impacto que tudo destrói e a fúria que se espalha como fogo. O poder se revela na escolha entre resistência e agressividade.*

### Pergunta 3A (Subgrupo 1A): O que define seu ataque?
- **A)** Força bruta, resistência e impacto. → **Ametista** (Edge Punisher)
- **B)** Dano em área, sangramento e agressividade. → **Rubí** (Flick Reaper)

*No topo da torre, o vento sopra e a visão se expande. O horizonte convida à precisão, onde cada flecha busca seu alvo, ou à acrobacia, onde cada passo é uma dança entre golpes e esquivas. O caminho se desenha entre estratégia e evasão.*

### Pergunta 3B (Subgrupo 1B): Como prefere agir?
- **A)** Precisão à distância, estratégia. → **Topázio** (Steam Gunner)
- **B)** Evasão, acrobacia e contra-ataques. → **Safira** (Macabre Dancer)

*Espelhos d’água refletem possibilidades, e o som das lâminas ecoa como uma dança entre sombras e luz. O destino se revela entre a velocidade que desafia limites e a técnica que une magia e espada em um só movimento.*

### Pergunta 3C (Subgrupo 2A): Qual seu diferencial?
- **A)** Mobilidade extrema, múltiplos ataques. → **Peridoto** (Twin Blade)
- **B)** Técnica refinada, magia e espada. → **Pedra da Lua** (Blade Brandier)

*No santuário oculto, a luz e a sombra disputam espaço. O aroma de cura e o mistério das trevas se misturam no ar, convidando à escolha entre proteger e restaurar ou dominar e transformar com magia profunda.*

### Pergunta 3D (Subgrupo 2B): O que mais te atrai?
- **A)** Suporte, cura e proteção. → **Pérola** (Harvest Cleric)
- **B)** Magia sombria, amplificação e manipulação arcana. → **Obsidiana** (Shadow Warlock)

---

## Representação Hierárquica da Árvore

```
1) Qual seu estilo predominante?
   ├── (A) Força, agressividade ou resistência física. → Grupo 1
   │    ├── (A) Combate direto, impacto e brutalidade. → Subgrupo 1A
   │    │    ├── (A) Força bruta, resistência e impacto → AMETISTA (Edge Punisher)
   │    │    └── (B) Dano em área, sangramento e agressividade → RUBÍ (Flick Reaper)
   │    └── (B) Controle de campo, ataques à distância ou evasão. → Subgrupo 1B
   │         ├── (A) Precisão à distância, estratégia → TOPÁZIO (Steam Gunner)
   │         └── (B) Evasão, acrobacia e contra-ataques → SAFIRA (Macabre Dancer)
   └── (B) Magia, técnica ou agilidade. → Grupo 2
       ├── (A) Velocidade, combos e técnica marcial. → Subgrupo 2A
       │    ├── (A) Mobilidade extrema, múltiplos ataques → PERIDOTO (Twin Blade)
       │    └── (B) Técnica refinada, magia e espada → PEDRA DA LUA (Blade Brandier)
       └── (B) Magia, suporte ou manipulação arcana. → Subgrupo 2B
           ├── (A) Suporte, cura e proteção → PÉROLA (Harvest Cleric)
           └── (B) Magia sombria, amplificação e manipulação arcana → OBSIDIANA (Shadow Warlock)
```