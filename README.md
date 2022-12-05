print("Welcome to my math game!")

playing = input("Sunteti gata? ")


if playing.lower() != "da":

    quit()

print("Okay! Let's play")

score = 0

answer = input("Este numarul 39 divizibil cu 3? ")

if answer.lower() == "da":

    print('Foarte bine!')
    
    score += 1
    
else:

    print("Recapituleaza!")


answer = input("Cum pot afla daca un numar se imparte exact la alt numar fara a face calculele? ")

if answer.lower() == "criteriile de divizibilitate":

    print('Corect!')
    
    score += 1
    
else:

    print("Mai recapituleaza!")

answer = input("Cat este x din ecuatia: 2x+3=13? ")

if answer.lower() == "5":

    print('Super!')
    
    score += 1
    
else:

    print("Mai recapituleaza!!")
    

answer = input("Este numarul 123 divizbil cu 5? ")

if answer.lower() == "nu":

    print('Bravo!')
    
    score += 1
else:

    print("Mai recapituleaza!")
    

print("Ai raspuns corect la " + str(score) + " intrebari!")

print("Ai reusit sa faci corect " + str((score / 4) * 100) + "%.")

