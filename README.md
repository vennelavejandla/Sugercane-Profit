# Sugercane-Profit
T=int(input())
for i in range(1,T+1):
  n=int(input())
  a=50*n
  su=int((20/100)*a)
  sm=int((20/100)*a)
  re=int((30/100)*a)
  total=su+sm+re
  pro=a-total
  print(pro)
