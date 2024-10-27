#BIODATA
NAMA : ADELLIA REZQI SALAMBILLAH
NIM: 312410395
KELAS : TI 24.A4


![Screenshot 2024-10-27 200535](https://github.com/user-attachments/assets/ca50ff75-5ceb-4d1e-9dd8-6a078626cbc9)
```PYHTON
(nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")

akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
if akhir > 80:
    huruf = "A"
elif akhir > 70:
    huruf = "B"
elif akhir > 50:
    huruf = "C"
elif akhir > 40:
    huruf = "D"
else:
    huruf = "E"
print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan))
````
Untuk menentukan nilai akhir pada Python, Anda bisa menggunakan pernyataan return untuk menandai akhir fungsi atau Menggunakan fungsi print() dan menentukan nilai yang akan dikembalikan. Pernyataan return dapat mengembalikan berbagai jenis data, seperti integer, float, string, list, dictionary, dan fungsi lainnya. Untuk menentukan nilai akhir dalam Python, Anda bisa membuat program yang menghitung nilai akhir berdasarkan pembobotan nilai.

```PYTHON
(nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0])
````
Fungsi input() dalam Python berfungsi untuk mengambil informasi dari pengguna melalui papan ketik. Fungsi ini membuat program menjadi lebih interaktif.
```PYTHON
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
````


Fungsi integer int dalam bahasa pemrograman adalah menyimpan nilai numerik dalam bentuk bilangan bulat positif atau negatif. Integer merupakan tipe data yang paling umum digunakan oleh programmer untuk menyimpan angka tanpa komponen desimal atau pecahan.

Untuk yang diatas Nilai int di * dalam bahasa manusia itu di kalikan, Yang artinya "Input Integer dikalikan  .2 yang aktinya 0,2 yang Hasilnya akan keluar bagaimana mestinya

Contoh nilai tugas yang di masukan 100, nanti akan dikalikan dengan program diatas .2 yang artiya (0,2) akan keluar cetakan 20
```PYHTON
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0])
````

Keterangan ini hanya sebuah variable yang nantiya aka di cetakan, dan di hasil akhir akan mengproses [variable akhir lebih besar dari 60.0]

```PYHTON
if akhir > 80:
huruf = "A"
elif akhir > 70:
huruf = "B"
elif akhir > 50:
huruf = "C"
elif akhir > 40:
huruf = "D"
else:
huruf = "E"
````

Ini adalah Struktur Kondisi Yang Menggunakan If, Elif, dan Else
```PYHTON
if akhir > 80:
huruf = "A"
````
Jika Hasil dari variable (Akhir) Lebih besar dari 80 maka output yang keluar dString A, dan seterusnya begitu dalam bahasa manusia

```PYHTON
else:
huruf = "E"
````
Jika tidak sesuai semuanya pada program diatas output akan keluar E

```PYHTON
print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)
````
#Menampilkan Status Gaji Karyawan
```PYHTON
gaji = int(input("Masukkan gaji:"))
berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]
punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]


if gaji > 3000000:
    print ("Gaji sudah diatas UMR")
    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")
    else:
        print ("Tidak perlu ikutan asuransi")
    if punya_rumah:
        print ("wajib bayar pajak rumah")

    else:
        print ("tidak wajib bayar pajak rumah")
else:
    print ("Gaji belum UMR")
````
Struktur Kondisi Ini menggunakan desision if, elif, dan else`
```PYHTON
gaji = int(input("Masukkan gaji:"))
````
Inputan ini akan memasukan angka Gaji, Karna memiliki fungsi integer
```PYHTON
(berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]
punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"])
````
Inputan ini menggunakan fungsi string yang dimasukan berupa Huruf, dan (False, True) ini adalah fungsi pemilihan Y atau T, supaya tidak menggunakan if dilanjutan program tersbut
```PYHTON
if gaji > 3000000:
    print ("Gaji sudah diatas UMR")
    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")
    else:
        print ("Tidak perlu ikutan asuransi")
````

Jika angka gaji lebih dari 3 juta maka Output yang akan keluar "Gaji sudah diatas UMR", dan jika tidak Output yang keluar "Tidak perlu ikutan asuransi"

```PYTHON
if punya_rumah:
        print ("wajib bayar pajak rumah")

    else:
        print ("tidak wajib bayar pajak rumah")
````

Jika Memiliki rumah Output yang keluar "Wajib bayar Pajak", jika tidak output yang keluar "Tidak wajib bayar pajak"

```PYHTON
else:
    print ("Gaji belum UMR")
````

else yang dibawah sendiri ini terhubung dengan if Gaji > 3000000:, karna kalau gaji tidak melebihi 3 juta Output yang keluar "Gaji belum UMR"

#Menggunakan kondisi or dengan menginputkan 3 bilangan

```PYTHON
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))

if a+b == c or b+c == a or c+a == b:
    print("BENAR")
else:
    print("SALAH")
````
Operator or dalam Python mengevaluasi beberapa kondisi dan mengembalikan True jika salah satu kondisinya benar

```PYTHON
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))
````

Program ini akan menginputkan sesuatu integer yang menggunakan variable a, b, c.
 ```PYTHON
if a+b == c or b+c == a or c+a == b:
    print("BENAR")
else:
    print("SALAH")
````
Jika (a) ditambah (b) hasilnya (c) atau yang bahasa programnya itu or (b) ditambah (c) hasilnya a, atau (c) ditambah (a) hasilnya (b), Maka Output yang keluar ialah "BENAR".

Jika tidak sesuai dengan program Output akan Keluar "SALAH"


![tiket biskop](https://github.com/user-attachments/assets/8614ec4a-546b-4050-be8a-d087a63a12e4)


