A = [
    [-1, -2, -3],
    [2, 3, -1],
    [-4, -5, -6]
]

for i in range(len(A)):
    if sum(A[i]) > 0:
        print(i)

