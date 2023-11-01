# -n = int(input('n = '))
arr = []
res_set = set()
for _ in range(n):
    city = input('->')
    if city in arr:
        res_set.add(city)
    arr.append(city)
print(len(res_set))
