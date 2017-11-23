# list_overlap
Python : code to go through 2 random list and find the common number and put them into a separate list


import random as r

br=r.sample(range(20),15)
ar=r.sample(range(20),18)
cr=[]
for stuff in ar:
	for st in br:
		if stuff==st:
			if stuff not in cr:
			  cr.append(stuff)


print(cr)
