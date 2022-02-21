# 21-02-2022-assignment-2
#program for printing revers of stars 
n=int(input('Enter n value:'))
for i in range(n+1,0,-1):
      for j in range(0,i-1):
        print('*',end=" ")
      print("\n")


output:
====================== RESTART: C:/Python37/patterns.py ======================
Enter n value:5
* * * * * 

* * * * 

* * * 

* * 

* 


