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

# BelliGol
<img src = "imagens/belligol.jpg"> <br>

# Cena 1
Fizemos o Morumbi, e o jogador tem que pegar a chuteira em movimento para liberar a passagem para a bola, onde ele chutará no gol e trocará de cena ao tocar na rede. <br>
Utilizamos GameObjects Modelados no Blender: Morumbi, chueteira e Belligol. <br>
Do unity: Bola, rede, bloqueio, materiais com imagens e um áudio da torcida do São Paulo cantando o hino. <br>
<img src = "imagens/cena1.png"> <br>
<img src = "imagens/hino.jpg"> <br>

# Cena 2
A cena 2 é quando você faz o gol e é a comemoração do Belligol, e ao cliclar na bola você pode fazer o gol novamente. <br>
Colocamos um áudio de comemoração do Belligol.<br>
<img src = "imagens/cena2.png"> <br>
<img src = "imagens/audiobelli.jpg"> <br>

# Scripts
## Movimentacao
Foi adicionado ao Belligol e nesse script tem simples códigos para movimentação, rotação de câmera e 'congelar' ele para não tombar. <br>
<img src = "imagens/movi1.png"> <br>
<img src = "imagens/movi2.png"> <br>
<img src = "imagens/movi3.png"> <br>

## Chuteira
Esse script foi adcionado a chuteira e serve para ele movimentar de um lado para o outro automaticamente.<br>
<img src = "imagens/chuteira.png"> <br>

## Colisoes
Esse script foi adicionado no Belligol, que quando ocorre a colisão com a chuteira desativa o bloqueio, a chuteira é destruida e o texto 1 é desativado enquanto o texto 2 é ativado.<br>
<img src = "imagens/chuteira.png"> <br>

## ForcaNaBola
Esse script foi adicionado no Belligoll, que serve para ele "chutar" a bola, quando ocorre a colisão com ela ma força é aplicada na direção em que o Belligol está olhando.<br>
<img src = "imagens/forca.png"> <br>

## TrocarCena
Esse script foi adicionado as redes do gol para quando ocorrer a colisão com a bola carregar a cena 2.<br>
Também criei um método Jogar para carregar a cena 1, e adicionei ele em um evento de OnClick do botão da bola na cena 2.<br>
<img src = "imagens/cena.png"> <br>

# Colisores
## Static Colidder
É um colisor onde o componente fica parado, utilizamos no estádio, nas traves e no bloqueio. Utilizamos Box e Mesh Collider. <br>
<img src = "imagens/boxco.jpg"> <br>
<img src = "imagens/mesh.jpg"> <br>

## RigidBody Collider
Utilizamos esse colisor no Belligol, na chuteira e na bola para dar física para eles.<br>
<img src = "imagens/rigid.jpg"> <br>

## Kinematic Rigidbody Collider
Adicionamos ele na chuteira e no Belligol para movimentar eles com scripts. Para isso ativamos a propiedade Is Kinematic.<br>
<img src = "imagens/rigid.jpg"> <br>

## Static Trigger Collider
Usamos ele nas redes do gol para quando ocorrer colisão e a bola atravessar mude a cena. Para isso ativamos a propieade Is Trigger, sem a propieade Is Trigger a bola só iria bater e não iria atravessar e responder o script.<br>
<img src = "imagens/trigger.jpg"> <br>

## Rigidbody Trigger Collider
Utilizamos ele na chuteira que adicionamos RigidBody para usar Is Kinematic (próximo) e um Box Collider para quando o Belligol atravessar e ocorrer a colisão, libere a segunda parte da cena. Para isso ativamos a propieade Is Trigger.<br>
<img src = "imagens/rigid.jpg"> <br>
<img src = "imagens/trigger.jpg"> <br>

## Kinematic Rigidbody Trigger Collider
Utilizamos ele na chuteira que adicionamos RigidBody para usar o Is Kinematic onde movimentamos a chuteira de um lado para o outro com script. També colocaos um Box Collider para quando o Belligol atravessar e ocorrer a colisão, libere a segunda parte da cena. Para isso ativamos a propieade Is Trigger. Como o Is trigger está ativado a física não irá responder.<br>
<img src = "imagens/rigid.jpg"> <br>
<img src = "imagens/trigger.jpg"> <br>

# Cena rodando com todos os colisores
