# ⚔️ Trench Crusade: Regras Avançadas e Glossário

## 1. Sistema Completo de Keywords (Palavras-Chave)

As Keywords dividem-se em dois tipos: **Tags** (características permanentes do modelo/arma) e **Effects** (efeitos acionados em jogo).

### Tags de Modelo

| Keyword | Efeito |
| :--- | :--- |
| **ELITE** | Modelo nomeado que ganha XP, pode ser promovido e tem Trauma Roll ao ser removido. |
| **LEADER** | Apenas 1 por warband. Enquanto ativo, bônus de moral para aliados próximos. Se morrer, teste de moral imediato. |
| **SKIRMISHER** | Pode mover e atirar sem penalidade. Pode recuar do combate sem sofrer ataque gratuito. |
| **FLYING** | Ignora terreno ao mover. Não pode ser carregado por modelos sem FLYING. |
| **GOLEM** | Imune a Fear, Poison e Gas. Não realiza Trauma Roll. Não tem Blood Markers padrão (regras especiais). |
| **TOUGH** | Quando recebe resultado *Down*, role novamente: em 4+ ignora o resultado e fica com 1 Blood Marker em vez disso. |
| **REGENERATE** | No início de cada ativação, remova 1 Blood Marker do modelo (cura natural). |
| **INFILTRATOR** | Pode ser colocado em qualquer local do campo de batalha (exceto zona de deployment inimiga) antes do início da partida. |
| **FEAR** | Modelos inimigos que queiram atacar este modelo devem primeiro passar em um teste de moral. Falha = não podem atacar. |
| **STRONG** | Pode usar armas e itens com a tag **HEAVY** sem penalidade de movimento. |
| **HEAVY** | Requer STRONG para usar sem penalidade; caso contrário, -1 ação por turno. |
| **ASSAULT** | Pode mover e atacar à distância na mesma ativação sem penalidade. Pode atirar após Charge. |
| **DEADLY** | Ao realizar uma Injury Roll com Sucesso Crítico, adicione +1 dado extra à Injury Roll. |
| **CLEAVE(X)** | Se o ataque remover um modelo, o excesso de dano (X) é aplicado a outro modelo adjacente. |

### Tags de Arma / Efeito de Ataque

| Keyword | Efeito |
| :--- | :--- |
| **AUTOMATIC(X)** | Ao ter sucesso no ataque, role X Injury Rolls adicionais contra o mesmo alvo. |
| **BLAST(X")** | Ataque de área com raio X". Todos os modelos dentro do raio sofrem Injury Roll. Não requer LOS direto. |
| **RELOAD** | Após disparar, a arma precisa ser recarregada (gasta 1 ação). |
| **PISTOL** | Pode ser usada em combate corpo a corpo sem penalidade. Não requer 2 mãos. |
| **BAYONET LUG** | A arma tem um gancho para baioneta; pode usar como arma de combate próximo (Me básico). |
| **FOCUSED FIRE** | Ao atirar em grupo (2+ modelos com Focused Fire no mesmo alvo), adicionam Success Dice entre si. |
| **SHRAPNEL** | Em Blast, modelos na área recebem Blood Markers extras mesmo em falhas. |
| **FLAMETHROWER** | Área em linha (template de chama). Ignora Cover. Alvo recebe marcador FIRE mesmo em resultado "Sem Efeito". |
| **IGNORE ARMOUR** | A Armadura (A) do alvo não é aplicada à Injury Roll. |
| **CRITICAL** | Em Sucesso Crítico, role +2 dados na Injury Roll em vez de +1. |
| **RISKY** | Em resultado de Falha, o atirador também sofre uma Injury Roll. |
| **DESPATCH** | Se o alvo estiver *Down*, ignora a Armadura (A) automaticamente. |
| **INFECTION MARKER** | Ao ferir, coloca um marcador de Infecção que reduz atributos permanentemente até o fim da batalha. |
| **FRESH MEAT** | Modelos com este efeito são alvos preferenciais de criaturas com *Hunger* ou *Predator*. |
| **OTHISMOS** | Empurra o alvo D6" para trás na direção do ataque após hit bem-sucedido. |
| **BATTER (MELEE)** | A arma pode ser usada em corpo a corpo com bônus Me adicional. |

---

## 2. Estados de Condição (Condition States)

| Estado | Como é Adquirido | Efeito |
| :--- | :--- | :--- |
| **Down** | Injury Roll resultado 7–8. | Não pode agir. Aliados podem levantar (1 ação). Inimigos podem finalizá-lo com ação de luta. |
| **Out of Action** | Injury Roll resultado 9+, ou 6 Blood Markers. | Removido do campo. Se ELITE, rola Trauma Roll pós-batalha. |
| **On Fire (Fogo)** | Armas com FIRE ou FLAMETHROWER. | No início de cada ativação: Injury Roll automática. Pode apagar com 1 ação (teste de Speed). |
| **Gassed (Gás)** | Armas com GAS. | Penalty Dice em todos os testes; Blood Marker extra por turno. Removido com máscara de gás ou ao sair da nuvem. |
| **Infected** | Armas com INFECTION MARKER. | -1 permanente em atributo por marcador até o fim da batalha. |
| **Feared** | Falha em teste de moral contra FEAR. | Não pode atacar o modelo causador do medo neste turno. |

---

## 3. Sistema de Marcadores Completo

### 🩸 Blood Markers
- Máx. 6. Ao atingir 6: *Out of Action* automático.
- Cada marcador: **+1 à Injury Roll** feita contra o modelo.
- O oponente pode usar Blood Markers para forçar **Penalty Dice** em testes do portador.
- **Bloodbath Roll**: gaste 6 (alvo saudável) ou 3 (alvo Down) Blood Markers → role **3D6** na Injury Roll.

### ✨ Blessing Markers
- Máx. 6. Não causam penalidade ao acumular.
- Gaste 1 para: adicionar +DICE a qualquer rolagem de Sucesso OU anular 1 Blood Marker.
- Fontes: relíquias, orações, habilidades de líderes religiosos.

### 🟡 Glory Points (☼)
- Moeda de campanha usada para contratar mercenários e comprar equipamentos especiais.
- Cada facção tem uma lista de itens de Glória exclusivos.
- Ganhos ao completar objetivos de campanha e feitos heroicos.

---

## 4. Regras de Terreno (Detalhado)

| Tipo | Efeito de Movimento | Combate/Cobertura |
| :--- | :--- | :--- |
| **Open** | Normal | Sem cobertura |
| **Difficult** | 2" por 1" movido | Cobertura leve em algumas peças |
| **Dangerous** | Normal, mas exige teste de Speed ao entrar | Falha no teste = Injury Roll automática |
| **Impassable** | Intransponível | N/A |
| **Cover Leve** | Normal | -1 ao ataque à distância |
| **Cover Pesado** | Normal | Penalty Dice ao ataque à distância |
| **Trincheiras** | Entrada/saída custa movimento extra | Heavy Cover para quem está dentro |

### Arquétipos de Campo de Batalha
- **No Man's Land**: Vasto campo com crateras (Difficult), arame farpado (Dangerous) e posição de francos atiradores. Pouca cobertura sólida.
- **Decimated Ruins**: Edifícios destruídos, muros caídos. Abundante Heavy Cover mas muitos cantos cegos.
- **Trench Lines**: Redes de valas que canalizam o movimento. Defender trincheiras = Heavy Cover; atacar de fora = exposto.

---

## 5. Glossário Técnico Completo

| Termo | Definição |
| :--- | :--- |
| **Activation** | O ato de agir com um único modelo durante a Fase de Ativação. |
| **Down** | Estado onde o modelo está caído, sem poder atacar ou mover-se normalmente. |
| **Out of Action (OOA)** | Remoção total do modelo do campo de batalha. |
| **Line of Sight (LOS)** | Visibilidade direta entre dois modelos (traço da cabeça/torso). |
| **Engagement Range** | 1" ao redor da base de qualquer modelo. Entrar = engajamento obrigatório. |
| **Success Dice (+DICE)** | Role dados extras e escolha os 2 melhores resultados. |
| **Penalty Dice (-DICE)** | Role dados extras e seja forçado a escolher os 2 piores. |
| **Warband** | Grupo de modelos controlados por um jogador. |
| **Elite** | Modelo com nome, XP e capacidade de progressão. Tem Trauma Roll. |
| **Follower** | Modelo de infantaria básica. Não ganha XP; não tem Trauma Roll. |
| **Field Strength** | Número máximo de modelos que uma warband pode levar em campo por jogo. |
| **Ducats (👑)** | Moeda principal. Usada para comprar modelos, armas e equipamentos. |
| **Glory Points (☼)** | Moeda secundária para mercenários e itens especiais de campanha. |
| **Bloodbath Roll** | Rolagem de 3D6 em vez de 2D6 ao gastar Blood Markers de um alvo. |
| **Trauma Roll** | Rolagem D66 após uma batalha para determinar o destino de um ELITE removido como OOA. |
| **Patron** | Entidade sobrenatural que apoia a warband em uma campanha, fornecendo bônus únicos. |
| **D66** | Role 2D6; um dado representa as dezenas (1–6) e o outro as unidades (1–6). Resultados: 11–66. |
