# python
#Сумма ряда 0 - 88888888
print(sum(range(88888888)))

#Среднее арифметическое ряда [3, 4, 56, 100, 2, 2, 3]
y=[3, 4, 56, 100, 2, 2, 3]
print(sum(y)/len(y))

#Заменить в строке "asdxfghyxyx" все буквы "х" на "у"
z ='asdxfghyxyx'
v =''
for b in z:
    if b =='x':
        v+='y'
    else:
        v+=b
print (v)

#Сосчитать произведение чисел [3, 4, 56, 100, 15, 2, 20, 30], кратных и 3 и 5.
a=[3, 4, 56, 100, 15, 2, 20, 30]
b=1
for x in a:
    if x%3==0 and x%5==0:
        b*=x
print(b)

#Заменить все буквы "х" на "у" в исходной строке без использования дополнительной строки.
s="asdxfghyxyx"
print (s.replace("x", "y"))
