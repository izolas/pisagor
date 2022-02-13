def pisagor(x):
    if(x<=2):
        print("Lütfen 2 den büyük bir sayı giriniz")
    elif(x==4):
        print("en kısa kenarı 4 birim olan kenarları tam sayı bir dik üçgen yoktur")
    elif(x%2==0):
        x /= 2
        y = (x ** 2 - 1)
        print("{:.0f}-{:.0f}-{:.0f}".format(2 * x, y, y + 2))
    else:
        y = (x ** 2 - 1) / 2
        print("{:.0f}-{:.0f}-{:.0f}".format(x, y, y + 2))

sayi=int(input("""Hadi Özel Dik Üçgen(Pisagor) Bağıntıları'nı bulalım.
Siz üçgenin en kısa kenarını söyleyin. Bizde tüm kenarları bulalım
Ancak bulacağımız üçgenlerin kenarları aralarında asal olacaktır. 
Örneğin 3-4-5 üçgeninın bulacağız ama onun katlarından biri olan
 6-8-10 üçgenini veya diğer katlarını bulmayacağız, 
Lütfen bulmak istediğiniz üçgenin en kısa kenar uzunluğunu giriniz
(Girdiğiniz sayı 3' den küçük ve "4" olmamalı):"""))
pisagor(sayi)
