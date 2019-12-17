# basic
# find repetition 
x=['a','b','f','f','a','a']
print(x)
f=0
i=0
j=i+1

for i in range(len(x)):
    if j<len(x):
        if x[i]==x[j]:
            f=f+1
            j=j+1
        else:
            j+=1
print(f)
    
