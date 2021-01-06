# FINAL PROJECT SISTEM OPERASI
# Program Menghitung Luas dan Keliling Bangun Datar
import os

def persegi():
    print ('-------------------------------------------')
    print ('')
    print ('-------------------------------------------')
    print ('')
    print (' Menghitung Luas dan keliling Persegi ')
    print ('*******************************************')
    s=float(input ('panjang sisi :'))
    lpersegi=s*s
    kpersegi=4*s
    print ('------------------------')
    print ('|| Luas Persegi     : ', lpersegi)
    print ('|| Keliling Persegi : ', kpersegi)
    print ('------------------------')
def lpersegipanjang():
    print ('--------------------------------------------')
    print ('')
    print ('---------------------------------------------')
    print ('')
    print ('Menghitug Luas dan Keliling Persegi panjang')
    print ('********************************************')
    p=float(input('Masukkan Panjang : '))
    l=float(input('Masukkan Lebar : '))
    lpersegipanjang=p*l
    kpersegipanjang=(p+l)*2
    print ('--------------------------------')
    print ('|| Luas Persegi Panjang     : ', lpersegipanjang)
    print ('|| Keliling Persegi panjang : ', kpersegipanjang)
    print ('--------------------------------')
def lsegitiga():
    print ('--------------------------------------------')
    print ('')
    print ('--------------------------------------------')
    print ('')
    print ('Menghitung Luas dan Keliling Segitiga')
    print ('********************************************')
    a=float(input('Masukkan nilai alas : '))
    t=float(input('Masukkan nilai tinggi : '))
    print ('--------------------------------------------')       
    s1=float(input('Masukkan sisi 1 : '))
    s2=float(input('Masukkan sisi 2 : '))
    s3=float(input('Masukkan sisi 3 : '))
    lsegitiga=a*t/2
    ksegitiga=s1+s2+s3
    print ('-------------------------')
    print ('|| Luas Segitiga     : ', lsegitiga)
    print ('|| Keliling Segitiga : ', ksegitiga)
    print ('-------------------------')
def ljajargenjang():
    print ('--------------------------------------------')
    print ('')
    print ('--------------------------------------------')
    print ('')
    print ('Menghitung Luas dan Keliling Jajar Genjang')
    print ('********************************************')
    a=float(input('Masukkan nilai alas : '))
    t=float(input('Masukkan nilai tinggi : '))
    print ('---------------------------------------------')
    sm=float(input('Masukkan Sisi Miring : '))
    ljajargenjang=a*t
    kjajargenjang=a+sm*2
    print ('----------------------------')
    print (' Luas Jajar Genjang     : ', ljajargenjang)
    print (' Keliling Jajar Genjang : ', kjajargenjang)
    print ('----------------------------')
def llingkaran():
    print ('--------------------------------------------')
    print ('')
    print ('--------------------------------------------')
    print ('')
    print ('Menghitung Luas dan Keliling Lingkaran')
    print ('********************************************')
    r=float(input('Masukkan jari-jari : '))
    llingkaran=3.14*r
    klingkaran=2*3.14*r
    print ('-------------------------')
    print ('|| Luas Lingkaran   : ', llingkaran)
    print (' Keliling Lingkaran : ', klingkaran)
    print ('-------------------------')
    
def ulang() :
    print('================================================')
    ulang=input('Kembali ke menu awal (y/n) ? : ')
    if ulang == "y" :
        os.system('cls')
        menu()
    elif ulang == "n" :
        print('================================================')
        print('Terima Kasih Telah Menggunakan Program Ini')
    else :
        print('Hanya ada y/n !')
        ulang()

def menu() :    
    print ('=======================================================')
    print ('|  Program Menghitung Luas dan Keliling Bangun Datar  |')
    print ('=======================================================')
    print ('Program Hitung Bangun Datar')
    print ('1. Persegi')
    print ('2. Persegi Panjang')
    print ('3. Segitiga')
    print ('4. Jajar Genjang')
    print ('5. Lingkaran')
    print ('6. Keluar')
    pilih = input ("Pilih Bangun Datar :") 
    if pilih == '1' :
        persegi()
        ulang()
    elif pilih == '2' :
        lpersegipanjang()
        ulang()
    elif pilih== '3':
        lsegitiga()
        ulang()
    elif pilih== '4':
        ljajargenjang()
        ulang()
    elif pilih == '5' :
        llingkaran()
        ulang()
    else :
        print (' ' )
        print ('Terima Kasih Telah Menggunakan Program ini')

print ('=======================================================')
print ('|  Program Menghitung Luas dan Keliling Bangun Datar  |')
print ('=======================================================')
print ('Program Hitung Bangun Datar')
print ('1. Persegi')
print ('2. Persegi Panjang')
print ('3. Segitiga')
print ('4. Jajar Genjang')
print ('5. Lingkaran')
print ('6. Keluar')
pilih = input ("Pilih Bangun Datar :") 
if pilih == '1' :
    persegi()
    ulang()
elif pilih == '2' :
    lpersegipanjang()
    ulang()
elif pilih== '3':
    lsegitiga()
    ulang()
elif pilih== '4':
    ljajargenjang()
    ulang()
elif pilih == '5' :
    llingkaran()
    ulang()
else :
    print (' ' )
    print ('Terima Kasih Telah Menggunakan Program ini')
