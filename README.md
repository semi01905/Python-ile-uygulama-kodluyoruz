print("""*************Hesap Makinesi**************\n1-)Toplama İşlemi(+) \n2-)Çıkarma İşlemi(-) \n3-)Çarpma İşlemi(*) \n4-)Bölme İşlemi(/)""")
sayi1=float(input("Birinci sayıyı giriniz: "))
sayi2=float(input("İkinci sayıyı giriniz: "))
islem=input("Yapılacak işlemi seçiniz(+,-,*,/): ")
if islem=="+":
        sonuc=sayi1+sayi2
        print(sonuc)
elif islem=="-":
        sonuc=sayi1-sayi2
        print(sonuc)
elif islem=="*":
        sonuc=sayi1*sayi2
        print(sonuc)
elif islem=="/" and sayi2!=0:
        sonuc=sayi1/sayi2
        print(sonuc)
else:
       print("Malesef hatalı giriş yatpınız")
