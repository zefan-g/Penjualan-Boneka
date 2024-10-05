x = int(input("Berapa boneka yang di beli: "))

if x <= 12:
    print("Harga per bonekanya Rp. 20.000")
    harga = x * 20000
    
elif x <= 24:
    print("Harga per bonekanya Rp. 19.500")
    harga = x * 19500

elif x <= 50:
    print("Harga per bonekanya Rp. 18.000")
    harga = x * 18000
    
else:
    print("Harga per bonekanya Rp. 17.000")
    harga = x * 17000
    
print("Total harga Rp.", harga)# 
