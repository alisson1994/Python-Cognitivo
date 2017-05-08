# Python-Cognitivo

ten_things = "Apples Oranges Crows Telephone Light Sugar"

print "Wait there are not 10 things in that list. Let's fix that."
stuff = ten_things.split(' ')
more_stuff = ["Day", "Night", "Song", "Frisbee", "Corn", "Banana", "Girl", "Boy"]
# Só para testar ! 
print stuff
print more_stuff

while len(stuff) != 10:
    next_one = more_stuff.pop()
    print "Adding: ", next_one
    stuff.append(next_one)
    print "There are %d items now." % len(stuff)
    
    
print "There we go: ", stuff


print "Let's do some things with stuff."

print stuff[1]
print stuff[-1] # Whoa ! Fancy
print stuff.pop()
print ' '.join(stuff) # What? Cool ! 
print '#'.join(stuff[3:5]) # Super Stellar ! 



# Explicando as funções do print ! 

print stuff[1]
# Vai trazer o item 1 da lista, lembrando que em python a contagem começa em 0
print stuff[-1]
# Esse vai retornar o negativo do primeiro, no caso o ultimo item da lista
print stuff.pop()
# Este por sua vez, vai trazer um resultado aleatório
print ' '.join(stuff)
# Este aqui, vai mostrar os itens 
print '#'.join(stuff[3:5])
# Retornara os indices entre 3 e 5 sem contar o último indice numerado no comando
