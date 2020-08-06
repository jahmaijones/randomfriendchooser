# randomfriendchooser

import random #returns random number between 0 and 1 


friends = [

	'Lauren',
	'Carl',
	'Jahmai',
	'Susan',
	'Joanne',
	'Errol',
	'Nancy',
	'Jordan',
	'Francis',
]





#random.randint(1,5) ---> random number between 1 and 5
#random.choice(array) ----> random item in the array 

selected = random.choice(friends) #randomly choose a friend 

print ('Who should i facetime today ? ')
print (selected)
 

 
