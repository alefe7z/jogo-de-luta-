# Eclipse — Arena de Combate

Jogo de luta 2D para navegador, inspirado na atmosfera de jogos clássicos como Mortal Kombat, com personagens e arte originais desenhados em Canvas. Primeira versão protótipo, sem dependências externas.

## Jogar

Baixe o repositório e abra `index.html` no navegador. Clique em **Nova partida** ou pressione **Enter**.

Também pode servir a pasta com `python -m http.server 8000` e acessar http://localhost:8000.

## Controles

| Tecla | Ação |
| --- | --- |
| A / D | Mover |
| W | Pular |
| S | Defender |
| J | Soco |
| K | Chute |
| L | Projétil de energia |
| Enter | Iniciar / revanche |

Inclui controles por toque, três dificuldades de IA, efeitos sonoros opcionais, combos, energia regenerativa, cronômetro de 60 segundos e vitória em dois rounds.

## Publicar no GitHub Pages

Em Settings → Pages, escolha Deploy from a branch, a branch padrão e a pasta / (root), depois Save. O endereço esperado é https://alefe7z.github.io/jogo-de-luta-/ após a publicação.

## Validação

JavaScript validado sintaticamente. Verificações automatizadas de início de round, dano de soco, custo e criação de projétil, pontuação, troca de round e execução do desenho com Canvas simulado. A aparência e os controles ainda precisam de teste em navegador real.

## Estrutura

`index.html` contém interface, arte procedural, física e regras. Não requer instalação nem build.
