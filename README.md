#1
a = int(input())
b = int(input())
if (a>b):
    print("a is greater")
else:
    print("b is greater")


#2
a = int(input())
b = int(input())
c = int(input())
if (a>b and a>c):
    print("a is greater")
elif(b>c and b>c):
    print("b is greater")
elif(c>a and c>b):
    print("c is greater")
    
    
#3
a = int(input())
if(a>0):
    print("a is positive")
elif(a<0):
    print("a is negitive")
else:
    print("a is equal to 0")
    
    
#4
n = int(input())
if(n % 5 == 0 and n % 11 == 0):
    print("n is divisible be 5 And 11")
else:
    print("not divisible")
    
#5
n = int(input())
if (n%2==0):
    print("even")
else:
    print("odd")

#6
n = int(input())
if n%4==0 and n%100!=0 or n%400==0:
    print("n is leap yr")
else:
    print("not a leap yr")
    
#7
ch = input()
if(ch >= 'a' and ch <= 'z' or ch >= 'A' and ch <= 'Z'):
    print("ch is alphabet")
else:
    print("ch is not a alphabet")

    
#8
ch = input()
if(ch >= 'a' and ch <= 'z'):
    print("ch is lower")
elif(ch >= 'A' and ch <= 'Z'):
    print("ch is upper")
else:
    print("noa a alphabet")
    
    
#9
month = int(input())
if(month == 1):
    print("31 days");
elif(month == 2):
    print("28 or 29 days");
elif(month == 3):
    print("31 days");
elif(month == 4):
    print("30 days");
elif(month == 5):
    print("31 days");
elif(month == 6):
    print("30 days");
elif(month == 7):
    print("31 days");
elif(month == 8):
    print("31 days");
elif(month == 9):
    print("30 days");
elif(month == 10):
    print("31 days");
elif(month == 11):
    print("30 days");
elif(month == 12):
    print("31 days");
else:
    print("invalid enter b/w 1 to 12")
#19  
mat = int(input())
phy = int(input())
che = int(input())
bio = int(input())
com = int(input())

per = (mat+phy+che+bio+com)/5
print(f"{per:.2f}",per)
if per>=90:
    print("a grade")
elif per>=80:
    print("b grade")
elif per>=70:
    print("c grade")
elif per>=60:
    print("d grade")
elif per>=40:
    print("e grade")
elif per<40:
    print("f grade")
else:
    print("fail")
    
    
#20
bs = int(input())
if(bs <=10000):
    da  = bs * 0.8
    hra = bs * 0.2
elif(bs >10001 and bs<=20000):
    da  = bs * 0.9
    hra = bs * 0.25
else:
    da  = bs * 0.95
    hra = bs * 0.3
gs = bs + da + hra
print(gs)

#21
units = int(input())
if units <= 50:
    amount = units * 0.50
elif units <= 150:
    amount = (50 * 0.50) + ((units - 50) * 0.75)
elif units <= 250:
    amount = (50 * 0.50) + (100 * 0.75) + ((units - 150) * 1.20)
else:
    amount = (50 * 0.50) + (100 * 0.75) + (100 * 1.20) + ((units - 250) * 1.50)
surcha = amount * 0.20
totalamt = amount + surcha
print(totalamt)


### switch cases

n = int(input())
match(n):
    
    case 1:
        print("monday")
        
    case 2:
        print("tuesday")
        
    case 3:
        print("wednesday")
        
    case 4:
        print("Thursday")
        
    case 5: 
        print("Friday")
        
    case 6: 
        print("Saturday")
        
    case 7: 
        print("Sunday")
        
    case _:
        print("invalid")
        
#2

n = int(input())
match(n):
    case 1:
        print("31 days");
    case 2:
        print("28 or 29 days");
    case 3:
        print("31 days");
    case 4:
        print("30 days");
    case 5:
        print("31 days");
    case 6:
        print("30 days");
    case 7:
        print("31 days");
    case 8:
        print("31 days");
    case 9:
        print("30 days");
    case 10:
        print("31 days");
    case 11:
        print("30 days");
    case 12:
        print("31 days");
    case _:
        print("invalid enter b/w 1 to 12")
        

#3
a = int(input())
b = int(input())
if a > b:
    result = 1
elif b > a:
    result = 2
else:
    result = 3
match(result):
    case 1:
        print("a is greater")
    case 2:
        print("b is greater")
    case 3:
        print("equal")
    case _:
        print("invalid")
        


    

    
    
    
    
    
    
    
    
    
