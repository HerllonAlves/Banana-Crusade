# Trench Crusade: Core Rules Reference

## 1. Atributos Base (Stats)

| Atributo | Nome Completo | Descrição |
| :--- | :--- | :--- |
| **M** | Movement | Distância em polegadas que o modelo se move por ação. |
| **Me** | Melee | Bônus de dados adicionados às rolagens de combate corpo a corpo. |
| **Ra** | Ranged | Bônus de dados adicionados às rolagens de ataque à distância. |
| **A** | Armour | Modificador subtraído das rolagens de ferimento recebidas (Injury Modifier). |
| **S** | Speed | Usado para testes de iniciativa e esquiva. |
| **Base** | Base Size | Tamanho da base do modelo (25mm, 32mm, 40mm etc.). |

---

## 2. A Rolagem de Sucesso (Success Roll)

Todo teste no jogo usa o sistema de **2D6**:

| Resultado | Efeito |
| :--- | :--- |
| **2–6** | Falha |
| **7–11** | Sucesso |
| **12+** | Sucesso Crítico (+1 dado na rolagem de Ferimento consequente) |

### Modificadores de Dado
- **+DICE (Success Dice)**: Role dados extras; escolha os **2 resultados mais altos**.
- **-DICE (Penalty Dice)**: Role dados extras; é obrigado a escolher os **2 resultados mais baixos**.
- Modificadores se acumulam. Ex.: +2 DICE com 1 PENALIDADE = role 3 dados extras, escolha os 2 maiores.
- Bônus máximo: não há limite para o número de dados extras rolados.

---

## 3. A Rolagem de Ferimento (Injury Roll)

Quando um modelo é atingido e o atacante for bem-sucedido, role **2D6** na tabela abaixo:

| Resultado | Efeito |
| :--- | :--- |
| **1** | **Sem Efeito** — O ataque não causa dano. |
| **2–6** | **Golpe Leve (Blood Marker)** — O alvo recebe 1 marcador de sangue (⚡). |
| **7–8** | **Caído (Down)** — O modelo cai. Não pode se mover ou atacar; pode ser finalizado. |
| **9+** | **Fora de Ação (Out of Action)** — O modelo é removido do campo de batalha. |

### Modificadores de Ferimento (Injury Modifiers)
- **+INJURY DICE**: Role dados extras no Injury Roll; escolha os 2 maiores.
- **-INJURY DICE**: Role dados extras no Injury Roll; escolha os 2 menores.
- **+X INJURY MODIFIER**: Some +X diretamente ao resultado da rolagem de ferimento.
- **-X INJURY MODIFIER**: Subtraia X do resultado (ex.: armaduras).

---

## 4. Marcadores de Sangue e Bênção

### 🩸 Blood Markers (Marcadores de Sangue)
- Representam desgaste físico e mental acumulado.
- Cada marcador adiciona **+1 ao resultado da Injury Roll** feita contra o modelo.
- O oponente pode gastar Blood Markers do alvo para forçar **Penalty Dice** em testes.
- **Limite: 6 marcadores**. Ao atingir 6, o modelo é removido automaticamente como *Out of Action*.
- Modelos com marcadores de sangue ficam visivelmente debilitados.

### ✨ Blessing Markers (Marcadores de Bênção)
- Ganhos através de orações, relíquias ou atos heroicos (mais comuns em New Antioch e Trench Pilgrims).
- Podem ser **gastos** para adicionar +DICE a qualquer teste.
- Podem ser gastos para **anular** marcadores de sangue (1 para 1).
- **Limite: 6 marcadores**.

### 💀 Bloodbath Roll (Rolagem de Banho de Sangue)
Mecânica especial para finalizações letais:
- Um modelo pode gastar **6 Blood Markers** de um alvo saudável, **ou 3 Blood Markers** de um alvo *Down*, para realizar um **Bloodbath Roll**.
- Role **3D6** na tabela de Ferimento em vez de 2D6.
- Representa ataques frenéticos e letais.

---

## 5. Sequência de Turno

### Fase de Iniciativa
1. Ambos os jogadores revelam quantos modelos têm em campo.
2. O jogador com **menos modelos** ganha a Iniciativa automaticamente.
3. Em caso de empate, role um dado (maior resultado vence).
4. O vencedor escolhe quem ativa o **primeiro modelo** do turno.

### Fase de Ativação
Os jogadores **alternam** a ativação de modelos (um de cada vez):
- O jogador com Iniciativa ativa o primeiro modelo.
- Depois o oponente ativa um modelo, e assim por diante.
- Isso continua até que todos os modelos tenham sido ativados.

### Fase de Moral
Após todas as ativações:
1. Verifique se alguma warband atingiu o **limiar de moral** (geralmente quando perde metade dos modelos ou o líder).
2. Warbands que falham no teste de moral podem fugir ou ter modelos desativados.

---

## 6. Ações por Ativação

Cada modelo pode realizar **1 Ação Padrão** e pode executar **1 Ação Adicional** (à custo de uma penalidade):

| Ação | Descrição |
| :--- | :--- |
| **Mover (Move)** | Mova o modelo até M" em qualquer direção. |
| **Correr (Dash)** | Mova o modelo até 2× M" mas não pode atacar neste turno. |
| **Carregar (Charge)** | Mova em direção a um inimigo e entre em combate corpo a corpo. Deve terminar em contato com o alvo. |
| **Recuar (Retreat)** | Recue do combate corpo a corpo. O oponente recebe um ataque gratuito. |
| **Atirar (Shoot)** | Realize um ataque à distância com uma arma equipada. |
| **Lutar (Fight)** | Realize um ataque corpo a corpo contra um modelo em contato. |

### Restrições Importantes
- Modelos em **contato base a base** com inimigos estão *engajados* e não podem Atirar.
- **Atirar através de engajamento** aplica Penalty Dice.
- Modelos *Down* não podem realizar ações, mas aliados adjacentes podem ajudá-los a se levantar (1 ação).

---

## 7. Combate Corpo a Corpo (Melee)

1. **Declarar ataque**: O atacante declara o alvo (deve estar em contato base a base).
2. **Rolagem de Ataque**: Role 2D6 + bônus Me do atacante vs. 2D6 + bônus Me do defensor (ou outra stat relevante).
3. **Resultado**:
   - Se o **atacante vencer**, realize uma Injury Roll.
   - Se o **defensor vencer**, o ataque falha.
   - Em **empate**, role novamente.
4. Aplique o resultado da Injury Roll normalmente.

---

## 8. Combate à Distância (Ranged)

1. **Linha de Visão (LOS)**: O atirador deve ter visibilidade direta do alvo (traço de modelo para modelo).
2. **Alcance**: Verifique se o alvo está dentro do alcance da arma.
3. **Rolagem de Ataque**: Role 2D6 + bônus Ra do atirador.
   - Resultado 7–11: Sucesso → realize Injury Roll.
   - Resultado 12+: Crítico → realize Injury Roll com +1 dado.
   - Resultado 2–6: Falha.
4. **Modificadores de Atirador**:
   - Cobertura Leve: -1 ao resultado.
   - Cobertura Pesada: Penalty Dice.
   - Longa distância (além da metade do alcance): Penalty Dice.
   - Modelo *Down* como alvo: não pode ser alvo de ataques à distância normais.

---

## 9. Engajamento e Cobertura

- **Engagement Range**: 1" ao redor da base de qualquer modelo. Entrar nessa zona de um inimigo força o engajamento.
- **Light Cover (Cobertura Leve)**: -1 à rolagem de ataque à distância.
- **Heavy Cover (Cobertura Pesada)**: Penalty Dice (-DICE) à rolagem de ataque à distância.
- **Trincheiras**: Fornecem Heavy Cover para modelos dentro delas; mover-se dentro é terreno aberto.

---

## 10. Terreno

| Tipo | Regra |
| :--- | :--- |
| **Open (Aberto)** | Sem penalidade de movimento. |
| **Difficult (Difícil)** | Conta como 2" por 1" movido (ex.: lama, escombros). |
| **Dangerous (Perigoso)** | Ao entrar, teste de Speed. Falha = Injury Roll automática. |
| **Impassable (Intransponível)** | Não pode ser atravessado (paredes sólidas, abismos). |
| **Climb (Escalar)** | Sobe ou desce obstáculos verticais; conta como Difficult. |

### Arquétipos de Campo de Batalha
- **No Man's Land**: Campo aberto com crateras e arame farpado (Difficult/Dangerous aleatório).
- **Decimated Ruins (Ruínas Decimadas)**: Edifícios destruídos com muita Heavy Cover.
- **Trench Lines (Linhas de Trincheira)**: Redes de trincheiras que canalizam o movimento.
