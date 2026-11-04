<img width="3440" height="1440" alt="ペルソナ２　罪 2026-10-31-19-20-45" src="https://github.com/user-attachments/assets/abae9edc-6479-412e-9696-02dd11c8abf6" />
<img width="3440" height="1440" alt="ペルソナ２　罪 2026-10-31-19-20-51" src="https://github.com/user-attachments/assets/cb192640-586a-4e35-b6c1-b605f9f247ce" />


# Persona 2: Tsumi (PlayStation, Japão) — Tradução PT-BR v1.0.6

Tradução completa do **Persona 2: Tsumi** (ペルソナ2 罪, «Innocent Sin») japonês de PlayStation para o português do Brasil, feita a partir do texto japonês original por **BRSniperX**.

**[📥 Baixar na página de Releases](https://github.com/BRSniperX/Persona-2-Tsumi-PlayStation-Jap-em-PT-BR/releases)**

## Duas edições: escolha uma

No japonês, vários personagens misturam inglês na fala (em katakana): o Eikichi diz «baby» e «okay», a Maya diz «Let's positive thinking!», a Elly solta «Target» e «Feeling». Por isso, a tradução tem duas edições:

| Edição | O que faz | Windows | Android, Mac, Linux |
|---|---|---|---|
| **Normal** | Mantém o inglês dos personagens, como no original | `Persona2-Tsumi-PTBR-v1.0.6.zip` | `Persona2-Tsumi-PTBR-v1.0.6-xdelta.zip` |
| **Sem inglês** | O inglês das falas vira português | `Persona2-Tsumi-PTBR-v1.0.6-sem-ingles.zip` | `Persona2-Tsumi-PTBR-v1.0.6-sem-ingles-xdelta.zip` |

### O que muda na edição sem inglês

São 461 mensagens trocadas; o resto do jogo é igual. Os personagens continuam com o jeito deles, mas perdem um pouco do sabor do original.

| Original | Nesta edição |
|---|---|
| baby | xuxu (falando de uma mulher: gatinha) |
| everybody | galera |
| biutiful | maravilindo |
| lady | dama |
| Okay (Eikichi) | Beleza |
| Let's positive thinking! | Pensamento positivo! |
| Give and take | Toma lá, dá cá |
| idol | ídola |

Continuam em inglês, de propósito:

- Nomes: Gas Chamber, MUSES, Joker, King Leo, Lady Scorpion, Coolest, Peace Diner, Miss Sevens, Devil Summoner, magias…
- «Mr. Lady»: termo criado no Japão; adaptar arriscaria uma ofensa que o original não tem.
- «Sorry-a»: é cantonês de Hong Kong, e a própria Lisa explica o que quer dizer numa das aulas dela.
- Um demônio que se gaba de saber inglês: «I love you», «You shall die!» e «FOOL». A piada é essa.
- Termos de jogo e interface: rank, blackjack, chat e o que já é inglês na arte do jogo.

É uma edição nova: as falas trocadas foram conferidas por ferramenta, mas nem todas foram vistas dentro do jogo.

## O tamanho do trabalho

| | quantidade |
|---|---|
| Textos traduzidos e revisados | **22.994** |
| Palavras (português) | **~300 mil** |
| Caracteres (português) | **~1,7 milhão** |
| Falas do contato com demônios | **6.308** |
| Blocos de cena (história e NPCs) | **621** |
| Tabelas de sistema (menus, itens, magias…) | **68** |

Cada texto passou por duas revisões: a tradução, feita com o japonês ao lado e conferindo quem fala e em que cena, e depois uma leitura só do português, cena por cena, para que tudo soe natural e cada personagem mantenha a própria voz. As conversas de contato com demônios foram revisadas uma a uma, por personalidade.

Ferramentas próprias conferem a largura de cada caixa de texto, o uso de memória do jogo (o PlayStation tem espaço fixo para o texto), os acentos da fonte e se sobrou japonês em algum lugar do disco.

Artes refeitas:

- tela de título;
- o poema do vídeo de abertura;
- interface: nomes do grupo, estados, status da Persona e listas da Sala de Veludo;
- placas das lojas, nomes dos lugares e botões do mapa da cidade;
- bússola do campo;
- nomes dos arcanos na fonte estilizada;
- a magia de fusão «Lenda Negra Jovem».

## O que está traduzido

- História completa e falas de NPCs, lojas, boatos e Sala de Veludo, inclusive as falas das Personas ao serem invocadas.
- Batalhas: comandos, mensagens, magias, itens e falas dos chefes.
- Contato com demônios: todas as conversas.
- Enciclopédia, cartas de tarô, menus, Status, mapas da cidade e placas das salas e dos locais.
- Tela de título e o poema do vídeo de abertura.

## O que ficou como no original

- Créditos finais (nomes da equipe japonesa).
- Palavras que já são inglês na arte do jogo (RESULT, NEXT, SCROLL, DASH…).
- Textos de teste e depuração que o jogo não mostra.

## Requisitos

- Imagem **.bin + .cue (MODE2/2352)** do Persona 2: Tsumi japonês **v1.0** (SLPS-02100), 691.925.472 bytes (o Windows mostra 675.709 KB).
- Não serve: ISO de 2048 bytes por setor, CHD, PBP, ECM, outra versão ou relançamento. CHD pode ser convertido de volta para .bin/.cue.
- **Windows 10/11:** PowerShell, já incluído. Nenhum programa extra.
- **Android, Mac, Linux:** um aplicativo de patch (UniPatch, xdelta3, Delta Patcher, ROM Patcher JS) e o dump exato, com SHA-1 `87da7209fe29bd16bda1b7d76c023660f957ac73`.
- Cerca de 700 MB livres.
- Emulador: testado no DuckStation.

## Instalação

**Windows** (zip da edição escolhida; aceita outros dumps do mesmo disco):

1. Extraia a pasta.
2. Coloque o `.bin` japonês original nela, ou arraste o `.bin`/`.cue` sobre o `APLICAR_PATCH.bat`.
3. Rode o `APLICAR_PATCH.bat`. Ele confere a imagem, cria a cópia traduzida e confere o resultado. A imagem original não é alterada.
4. Abra no emulador o `.cue` criado: `Persona 2 - Tsumi (PT-BR).cue` (normal) ou `Persona 2 - Tsumi (PT-BR) sem ingles.cue` (sem inglês).

**Android, Mac, Linux** (`-xdelta.zip` da edição escolhida; só no dump exato): o passo a passo está no `LEIA-ME_XDELTA.txt` de dentro do zip, junto com o `.cue` pronto.

**Já tinha uma versão anterior, ou quer trocar de edição?** Aplique na imagem **original** japonesa, do mesmo jeito. O patch não se aplica sobre uma imagem já traduzida. Os saves do cartão de memória valem nas duas edições.

O passo a passo completo está em `LEIA-ME.txt` (normal) e `LEIA-ME-sem-ingles.txt`. Os hashes estão em `SHA256SUMS.txt` (`sha256sum -c SHA256SUMS.txt`).

## Novidades

- **v1.0.6**: edição sem inglês. Nas duas edições, a fala da Maya com «imprinting» virou «instinto de filhote», e a do Eikichi com «smart» foi corrigida (na normal, «slim»; na sem inglês, «esbelto»).
- **v1.0.5**: na Sala de Veludo, as 150 falas de apresentação das Personas (ao invocar) estavam em japonês: agora estão em português. Escolhas da história com 4 opções: algumas respostas passavam por cima da vizinha e foram encurtadas. Mapas: placas da última sala de cada mapa e dois nomes de local em PT. Lojas: 10 descrições de item cabem na caixa; «Na bolsa» → «Possui», «Não equipa» → «Não usa». Restaurante: o efeito da comida mostra «FOR» (era «STR»). **Novo: patch .xdelta** para Android/Mac/Linux.
- **v1.0.4**: na batalha, a descrição de 121 magias e magias de fusão tinha uma linha a mais, que ficava por cima do nome da Persona e do custo de SP: agora cada descrição cabe na caixa. No contato com demônios, 38 respostas de escolha que passavam da borda da caixa foram encurtadas.
- **v1.0.3**: nas batalhas, a descrição das magias, das magias de fusão e dos itens e o perfil dos personagens (Status) apareciam em japonês: corrigido. Sobrenomes longos não invadem mais o nome no Status. Fala do Eikichi no contato ajustada para o erro dele soar intencional.
- **v1.0.2**: texto revisado. Mais duas leituras completas da história, dos NPCs e da cidade; cerca de 220 falas reescritas para soar mais naturais em português.
- **v1.0.1**: corrigido o travamento ao falar com um aluno no pátio do 1º andar do Colégio Sete Irmãs (capítulo 1).
- **v1.0**: primeira versão pública.

## Achou um problema?

Abra uma issue com **print da tela**, **onde estava no jogo**, a **versão** e a **edição** do patch (normal ou sem inglês). Cada relato é conferido com o japonês e, se for erro, vira correção numa versão nova.

---

## Créditos

- Tradução, revisão e artes: **BRSniperX**

---

Tradução de fã, sem fins lucrativos e sem vínculo com a Atlus, a SEGA ou a Sony. Persona é marca da Atlus/SEGA. Tenha o seu jogo original.
