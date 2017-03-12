x = range(2, 11)
y = []
print ('What is the number you want to divide by?')
div = int(input())
for elem in x: 
  if elem%div == 0:
    y.append(elem)
    
print(y)
