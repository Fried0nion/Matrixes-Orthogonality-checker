print("Amount of vectors in a collection: ")
a = int(input())
print("Amount of element in a vector: ")
b = int(input())
arr = []
for i in range(a):
  s = []
  for g in range(b):
    print("content of vector", i+1, "element-", g + 1)
    n = float(input())
    s.append(n)
  arr.append(s)
print(arr)

ok = True
for i in range(a):
  for j in range(i+1, a):
    sum = 0
    for k in range(b):
      sum += arr[i][k] * arr[j][k]
    if sum != 0:
      ok = False
      break
if ok:
  print("it is orthogonal")
else:
  print("NOT orthogonal")
