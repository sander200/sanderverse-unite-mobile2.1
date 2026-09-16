# SANDERVERSE UNITE 2.1

Correção: sprites sem quadro, mapa oficial, caminhos bloqueiam, Némesis Omega, ataques visíveis.


MOBA tático mobile em HTML5 Canvas puro (Vanilla JS).  
Três guerreiros jogáveis enfrentam Polo, Lupe, Topete e o boss colossal **Némesis**.

## Novidades da 2.0

- Partida de **3:00** com clímax nos últimos 60 s
- Seleção: **Sander**, **Cristian** (fogo) e **Babalu** (Blaster Canhão / Granada / Barragem)
- Dificuldade **Básico / Médio / Difícil**
- **Némesis** ~3× o tamanho do herói, barra de vida, 6 ataques do manual
- Gemas de energia no mapa (progressão + XP)
- Níveis 1–5 (curva `100 * L^1.65`) e **Guerreiro Diamante** no Sander a partir do Nv.4
- Teleporte com recarga de **30 s**
- Hover + sombra para Cristian e Némesis
- Minimapa rastreia o boss (pulso roxo)

## Controles

| Input | Ação |
| --- | --- |
| D-pad + analógico / WASD / setas | Movimento |
| ATACAR / Espaço / J | Ataque básico |
| 1 / Q | Habilidade 1 (Tornados / Lança / Blaster Canhão) |
| 2 / R | Habilidade 2 (Diamante / Mergulho / Granada) |
| 3 / E | Habilidade 3 (Resplandor / Descarga / Barragem) |
| T | Teleporte (30 s) |
| ⚡ / F / Shift | Dash |
| **G** / Enter / P / botão ANOTAR | Depositar auras na zona |

## Objetivo

Colete gemas, evolua o poder, deposite na zona **PONTUAR** e derrote Némesis antes do cronômetro.

## Como jogar

```bash
python3 -m http.server 8080
# abra http://localhost:8080
```

GitHub Pages: envie o conteúdo desta pasta para a branch `main`.

## Stack

HTML5 Canvas · CSS neon · Web Audio API · pool de ~520 partículas · Pointer Events · Fullscreen + landscape


## Babalu — especialista em armas

- **Ataque básico:** disparo do Blaster enquanto anda
- **Q Blaster Canhão:** projétil azul de alta energia, núcleo brilhante e rastro
- **W Granada:** lançamento em arco, explosão em área e knockback
- **E Barragem:** vários projéteis em sequência, movimento reduzido

## Mapa

Arena gerada com caminhos de pedra transitáveis, florestas/arbustos como parede, bases com portais e rota de pontuação dourada. Némesis segue os caminhos e aparece no minimapa.


## Controles estilo Pokémon Unite (celular / tablet)

- Minimapa no **canto superior esquerdo**
- Analógico grande no **canto inferior esquerdo**
- Cluster direito:
  - Q e W empilhados (habilidades)
  - E no alto
  - T teleporte e ⚡ dash
  - PONTUAR embaixo (Salida)
  - ATACAR círculo grande à direita (Unite move)
