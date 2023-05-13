###sonning raqamlari yig'indisini topish
son = input("biror son kiriting:   ")
son_len = len(son)
summa = 0
for n in list(range(0, son_len)):
    summa = summa + float(son[n])
print(summa)
