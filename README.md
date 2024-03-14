t=int(input())
for _ in range(t):
  d={}
  a=input()
  for i in a:
    if i not in d:
      d[i]=1 
    else: 
      d[i]=d[i]+1 
  for i in d:
    if d[i]>1:
      print(i)
      break
  else:
    print(".")
