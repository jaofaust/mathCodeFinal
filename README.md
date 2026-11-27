# MathCode — Aventura de Plataforma & Matemática

> Jogo 2D de plataforma educacional desenvolvido em HTML5, CSS3 e JavaScript puro para a disciplina **PAC: Jogos Digitais** (Católica SC — Turma 4B).

**Equipe:** Eduardo Alcala, João Paulo e Carlos Rodrigues

---

## Sobre o Jogo

No **MathCode**, você controla **Pip**, um raposinho aventureiro acompanhado pelo passarinho mentor **Pyrito**, atravessando **22 fases distribuídas em 7 mundos temáticos** até o **Castelo do Chefe**.

Para avançar, combine agilidade de plataforma com raciocínio matemático: grandes **Pedras das Contas** bloqueiam o caminho e só se abaixam quando Pip acerta o bloco com o resultado correto (pulando por baixo ou usando o Giro).

### Destaques
- **Tutorial "Aprender Jogando":** 8 lições progressivas em ambiente seguro (sem perder vidas), com dicas adaptativas e bônus de +30 moedas.
- **7 Mundos com Paralaxe e Fundos Animados:** Vale dos Cogumelos, Caverna de Cristais, Floresta Enluarada, Dunas Douradas, Montanha Gelada, Galáxia Neon e Vulcão Rúnico (culminando no Castelo do Chefe — Fase 22).
- **Mapa de Fases Interativo:** 22 fases com sistema de 1 a 3 estrelas e rejogabilidade.
- **Loja do Raposo:** 8 skins desbloqueáveis com moedas coletadas no jogo.
- **Áudio Completo + Menu de Pausa:** trilha sonora procedural adaptada ao clima de cada mundo, efeitos sonoros em todas as ações, sliders de volume e menu de pausa acessível a qualquer momento.

---

## Como Executar e Jogar

Não é necessário instalar nada nem usar servidor:

1. Extraia o arquivo `.zip` (ou clone este repositório) mantendo a pasta `img/` no mesmo diretório do `index.html`.
2. Dê **dois cliques em `index.html`** para abrir diretamente no navegador (Chrome, Edge, Firefox ou Opera).
3. Na primeira vez, clique em **"Aprender jogando ▶"** para fazer o tutorial interativo.

> **Observação:** o progresso (moedas, skins compradas, fase atual, estrelas e preferências de volume) fica salvo automaticamente no navegador via `localStorage`.

---

## Controles

| Ação | Teclas |
|---|---|
| **Mover** | `A` / `D` ou `←` / `→` |
| **Pular** (altura variável) | `Espaço`, `W` ou `↑` |
| **Giro** (quebrar caixas, derrotar inimigos e acertar blocos) | `Shift` ou `X` |
| **Pausar / Abrir Menu** | `P` ou `Esc` (ou botão **⏸ Menu** no canto superior direito) |
| **Ligar / Desligar Som** | Botão **🔊 / 🔇** no canto superior direito ou no Menu de Pausa |

---

## Principais Melhorias da Versão Final (N3)

### A partir da Ficha Técnica da N2 (Avaliação entre Grupos)
- **Menu de Pausa e Saída no Game Over:** adicionado botão **⏸ Menu** (e atalho `P`/`Esc`) durante o jogo + botão explícito **🏠 Menu Principal** nas telas de *Fim de Jogo*, *Vitória* e *Pausa*.
- **Música de Fundo e Efeitos Sonoros:** implementada trilha sonora procedural leve (Web Audio API) com temas por mundo e efeitos sonoros para todas as ações (pulo, giro, moeda, caixa, planta, acerto, erro, dano, vitória e fim de jogo), além de controles independentes de volume de Música e Efeitos.
- **Contraste em Fases Escuras (Fase 5 — Caverna de Cristais e mundos noturnos):** iluminação de cena aprimorada, bordas luminosas de alerta nos buracos, base de alto contraste nos espinhos, setas em plataformas móveis e halo sutil de visibilidade ao redor do Pip.
- **Ritmo e Progresso na Fase:** adicionada barra discreta de progresso no topo da tela indicando a posição do Pip, o status de cada Pedra das Contas e a distância até a bandeira, além de ajuste no ritmo das seções.

### A partir do Feedback do Professor
- *(A adicionar assim que incorporado o feedback do professor.)*

---

## Documentação e Links

- **Game Design Document (GDD):** [GDD.md](./GDD.md)
- **Instruções Rápidas Offline:** [LEIA-ME.txt](./LEIA-ME.txt)
- **Vídeo de Apresentação (10+ min):** `[INSERIR LINK]`
- **Trailer Cinematográfico:** `[INSERIR LINK]`
- **Versão Jogável (ZIP):** `[INSERIR LINK]`

---

## Créditos

Desenvolvido por **Eduardo Alcala**, **João Paulo** e **Carlos Rodrigues** — Católica SC (PAC: Jogos Digitais, Turma 4B).
