2nd program code

l=[]
i=int(input("Enter number : "))
for x in range(1,i+1):
    l.append(input())  
k=[]      
for i in range(len(l)):
    if l[i]=='':k.append(x)
    else:k.append(l[i])
4th program code:
lst1=[1,2,3,4]
lst2=[3,4,5,6]
common=set(lst1)&set(lst2)
print(common)
5th program code:
lst=['1','2','3','4','5','6','7']
str=''.join(map(str,lst))
print(str)
6th program code:
lst=[1,2,5,7,9,11,20]
s=set(lst)
print(s)
7th program code:
lst1=['brave','courage','respect','honour']
lst2=[27,28,29,11]
dictionary=dict(zip(lst1,lst2))
print(dictionary)
