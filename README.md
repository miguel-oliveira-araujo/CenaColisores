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
A cena 2 é quando você faz o gol e é a comemoração do Belligol, e ao cliclar na bola você pode fazer o gol novamente.
<img src = "img/cena2.png"> <br>

# Scripts
## Movimentacao
### Movimento
No movimento utilizamos as variáveis fast e jump, que é a velocidade que ele anda e a altura que ele pula, respectivamente. <br>
No método Update o código funciona quando clica WASD e Espaço ele incrementa o número da variável no Vector3.<br>

### Rotação
<br>

### Gravidade
A gravidade so verificamos se o personagem existe no método Start e se sim ela ativa a freezeRotation dele.<br>
Também mudamos a força da gravidade via script. <br>

# Colisores
# Static Colidder
É um colisor onde o componente fica parado, utilizamos no estádio, nas traves e no bloqueio.
<img src = "img/static.png"> <br>




