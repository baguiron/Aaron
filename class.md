class Sports:
    
    sport_name = 'Basketball'

    
    def __init__(self, name, number):
    
        self.name = name
        self.number = number
       

s1 = Sports("Michael Jordan", 23)

print('Player 1:', s1.name)

s1 = Sports("Michael Jordan", 23)

print('Jersey Number:',  s1.number)
print('Sports:', Sports.sport_name)
print(" ")

s1.name = 'Shoyo Hinata'
s1.number = 10
print('Player 2:', s1.name)
print('Jersey Number:',  s1.number)

Sports.sport_name = 'Volleyball'
print('Sports:', Sports.sport_name)
