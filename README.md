# projetParis
#premier match chelsea vs arsenal ,choissisez votre equpie a l'aide des nombres
#si victoire de chelsea taper 1 si victoire arsenal taper 2
#si vous gagner, votre gain est mutiplier par le nombre de cote
#bonne chance
chelsea = 1
arsenal = 2
choix=int(input("choisissez une equipe a l'aide des nombres pour la premiere recontre entre chelsea et arsenal:"))
gain=int(input("entrez un montant a partir de 100fr :"))
#chelsea cote = 2 , arsenal = 3
if chelsea > arsenal :
	print("chelsea remporte le match")
elif chelsea < arsenal :
	print("arsenal remporte le match")
else:
	print("match nul")

def somme ():
	if chelsea < arsenal :
		return gain*3


print("bravo votre gain pour la 1er rencontre est de:",gain * 3)
print("-"*70)
#la deuxieme renconte
barcelone = 3
seville = 4
choix=int(input("choisissez une equipe a l'aide des nombres pour la premiere recontre entre barcelone et seville:"))
gain1=int(input("entrez un montant a partir de 100fr pour la 2e rencontre :"))
#cote barcelone =1 ,seville =  4
if barcelone > seville:
    print("barcelone remporte le match")
elif barcelone < seville:
    print("seville remporte le match")
else:
    print("match nul")

def somme1 ():
	if barcelone < seville :
		return gain1*4

print("bravo votre gain pour la 2er rencontre est de:",gain1*4)
print("-"*70)
# troisieme rencontre
paris = 5
marseille = 6
choix=int(input("choisissez une equipe a l'aide des nombres pour la premiere recontre entre paris et marseille:"))
gain2=int(input("entrez un montant a partir de 100fr pour la 3e rencontre :"))
#cote paris =2 ,marseille =  3
if paris > marseille:
    print("paris remporte le match")
elif paris <  marseille:
    print("marseille remporte le match")
else:
    print("match nul")

def somme2 ():
	if paris < marseille :
		return gain2*3

print("bravo votre gain pour la 3e rencontre est de:",gain2*3)
print("-"*70)



def sommeT():
    if chelsea<arsenal and barcelone < seville and paris < marseille:
        return (gain*3)+(gain1*4)+(gain2*3)

print("felicitation! vous avez gagner :",(gain*3)+(gain1*4)+(gain2*3),"merci pour votre fideliter")















