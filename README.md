x ="+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

parola =int(input("parola uzunluğu girin ")) 

şifre = ""

for i range(parola):
    şifre = şifre + rondom.choice(karakter)


print("oluşturulan şifre:", şifre)
