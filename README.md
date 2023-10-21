# game-projects-1
Batalha Pokemon Em Python 

importrandom
print ("Bem vindo a batalha pokemon\n")

vida_inimigo =50
vida = 50

while  vida > 0  andvida_inimigo> 0:
    print ("Lista de ataques possíveis do pikachu")
    print ("a - choque do trovão")
    print ("b - cabeçada")
    print ("c - trovão megamasterblaster")

    ataque = input("Escolha qual ata que você quer usar: ")

if ataque == "a":
         print ("Você usou o choque do trovão")
vida_inimigo = vida_inimigo - 12
elif ataque == "b":
         print ("Você usou a cabeçada")
vida_inimigo = vida_inimigo - 7
else:
         print ("Você usou o trovão negamasterblaster")
vida_inimigo = vida_inimigo - 18

    print("A vida do inimigo agora é", vida_inimigo)

ifvida_inimigo<= 0:
        break

    print("O chamander te ataca")
ataque_inimigo_chance = random.randint(0,1)

ifataque_inimigo_chance == 1:
        print("Chamander usa a bola de fogo")
        vida = vida - 15
else:
        print("chamander usa a arranhão")
        vida = vida - 8
    print("Sua vida agora é", vida, "\n")

if vida > 0:
print("Parabens, o pikachu venceu")
else:
    print("Que pena, o chamander venceu")
