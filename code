l1 = list(map(int, input().split(" ")))
l2 = list(map(int, input().split(" ")))
if len(l1) != len(l2):
    print("输入的两行元素个数需要相等")
else:
    l3 = [] 
    dim = len(l1)
    h = - int(l1[0] / l2[0])
    for i in range(dim):
        i1 = l1[i]
        i2 = l2[i]
        i1 += h * i2
        l3.append(i1)
    print(l3)
