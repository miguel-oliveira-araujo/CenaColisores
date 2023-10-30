# Cena Colisores
# Feito por: Leonardo Macêdo e Miguel OLiveira
# Link do Projeto
link

# Descrição
Esse é um projeto onde utilizaremos os colisores: <br>
1. Static Collider <br>
2. Rigidbody Collider <br>
3. Kinematic Rigidbody Collider <br>
4. Static Trigger Collider <br>
5. Rigidbody Trigger Collider <br>
6. Kinematic Rigidbody Trigger Collider <br>

# Cena 1
Fizemos o Morumbi e o jogador tem que pegar a chuteira em movimento para liberar a passagem para a bola, onde ele chutará no gol e trocará de cena ao tocar na rede. <br>
Utilizamos GameObjects Modelados no Blender: Morumbi, chueteira e Belligol. <br>
Do unity: Bola, rede, bloqueio, materiais com imagens. <br>
<img src = "img/cena1.png"> <br>

# Cena 2
A cena 2 é quando você faz o gol e é a comemoração do Belligol, e ao cliclar na bola você pode fazer o gol novamente. <br>
<img src = "img/cena2.png"> <br>

# Scripts
## Movimentacao
Foi adicionado ao Belligol e nesse script tem simples códigos para movimentação, rotação de câmera e 'congelar' ele para não tombar. <br>
<img src = "img/movimentacao.png"> <br>

## Chuteira
Esse script foi adcionado a chuteira e serve para ele movimentar de um lado para o outro automaticamente.<br>
<img src = "img/chuteira.png"> <br>

## Colisoes
Esse script foi adicionado no Belligol, que quando ocorre a colisão com a chuteira desativa o bloqueio, a chuteira é destruida e o texto 1 é desativado enquanto o texto 2 é ativado.<br>
<img src = "img/chuteira.png"> <br>

## ForcaNaBola
Esse script foi adicionado no Belligoll, que serve para ele "chutar" a bola, quando ocorre a colisão com ela ma força é aplicada na direção em que o Belligol está olhando.<br>
<img src = "img/forca.png"> <br>

## TrocarCena
Esse script foi adicionado as redes do gol para quando ocorrer a colisão com a bola carregar a cena 2.<br>
Também criei um método Jogar para carregar a cena 1, e adicionei ele em um evento de OnClick do botão da bola na cena 2.<br>
<img src = "img/cena.png"> <br>

# Colisores
## Static Colidder
É um colisor onde o componente fica parado, utilizamos no estádio, nas traves e no bloqueio.
<img src = "img/colisoes.png"> <br>




