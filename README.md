# O-Guerreiro
Desafio do guerreiro

class heroi:
    def __init__(self, nome, idade, tipo,):
        self.nome = nome
        self.idade = idade 
        self.tipo = tipo
    
    def atacar(self):
        ataque = "Espada"
        print (self.nome, self.tipo , ataque) 
        print(f"O {self.tipo} atacou usando a {ataque}")  


heroi1 = heroi("Shay Cormac", "32", "Guerreiro")
heroi1.atacar()

