# simple-calculator1
num1=int(input("enter a number  : \n"))
num2=int(input('enter another number :\n'))
print('''choose 1 for addition \nchoose 2 for multiplication\nchoose 3 for subtraction\nchoose 4 for division\n''')
sel=int(input('enter operation :\n'))
if sel == 1:
   print("add:",num1+num2)
elif sel==2:
   print("multiplication:",num1*num2)
elif sel==3:
   print("subtraction",num1-num2)
else :
   print("division",num1/num2)
