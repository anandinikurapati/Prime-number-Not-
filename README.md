# Prime-number-Not-
# Approach - 1
'''
n = int(input())
c = 0
for i in range(1,n+1):
  if n%i == 0:
    c = c + 1
if c == 2:
  print("Prime Number")
else:
  print("Not a Prime number")
'''
# Approach - 2
'''
n = int(input())
k = 0
for i in range(2,n):
  if n%i == 0:
    k = 1
    break
if k == 1:
  print("Not Prime")
else:
  print("Prime")
'''
# Approach - 3
'''
n = int(input())
for i in range(2,n):
  if n%i == 0:
    print("Not a Prime")
    break
else:
  print("Prime")
'''
# Approach - 4
'''
n = int(input())
for i in range(2,n//2):
  if n%i == 0:
    print("Not a Prime")
    break
else:
  print("Prime")
'''
# Approach - 5
'''
n = int(input())
for i in range(2,int(n**0.5)):
  if n%i == 0:
    print("Not a Prime")
    break
else:
  print("Prime")
