# Splat Arena 2.0

Projeto independente do [Splat Arena original](https://github.com/witterveloso/splat-arena).

## Jogar

Abra `index.html` em um servidor HTTP estático. Para publicar pelo GitHub Pages, configure **Settings > Pages > Deploy from a branch > main / (root)**. A URL prevista, depois de ativado o Pages, é `https://witterveloso.github.io/splat-arena-2/`.

## Recursos implementados

- Motor 3D Three.js (carregado via CDN; requer internet).
- Onze cenários 3D procedurais.
- Partida local contra seis bots, tiros de tinta, pontuação, vida e reaparecimento.
- Teclado/mouse e controles de toque.
- Oito identidades selecionáveis com cores próprias para disparos; os modelos corporais exclusivos ainda não foram integrados.\n- Recarga de 1,5 segundo.\n- Sem dependência de modelos binários externos.

## Controles

WASD: mover; mouse: mirar; clique: disparar; Shift: correr; R: recarregar; Esc: menu. Em celulares: joystick virtual, arrastar para mirar e botão de disparo.

## Situação

Protótipo funcional em código, **ainda sem testes de execução em navegador**. Não contém ainda multiplayer online, modelos 3D individuais para os oito personagens, animações profissionais nem multiplayer online. Esses recursos precisam ser migrados ou reconstruídos e testados neste repositório. O repositório original não foi alterado nesta etapa.
