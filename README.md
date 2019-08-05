# pro13.py
vv,gg=map(int,input().split())
bac=[]
sines=[]
viji=[int(m) for m in input().split() ]
for i in range(0,gg):
    z1,s1=map(int,input().split())
    for j in range(z1-1 ,s1):
        sines.append(viji[j])
    mah=sorted(sines)
    bac.append(min(sines))
    del sines[:]
for z in range(0,len(bac)):
    print(bac[z])
