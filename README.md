# 2022

7/9

Howdy! I'm giving Python a shot and exploring GitHub. As a kid I used a Commodore 64, mostly for playing games. I've always had a fascination with programming, but honestly didn't have the attention span. I'm older now and a little more focused so I'm thinking I will put my powers to good use.
I love playing the card game Uno. As I learn the basics of Python, I started thinking about how I could combine the two. 

This is where I am right now.


#Dealing the cards

numbers=('1 ', '2 ', '3 ', '4 ', '5 ','6 ')
colors=('red ', 'yellow ', 'blue ', 'green ')

print("Your hand: ")

def uno():
    i=0
    list=[]
    while i<6:
        cards=(random.choice(colors) + random.choice(numbers))
        print(cards)
        i=i+1
        list.append(cards)
    return[list]
    
uno() #calling function

yourCard = input("what card are you playing")

