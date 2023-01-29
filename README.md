## Luas Lingkaran ##

Alur/flow yang harus di buat
* Membuat variable r sebagai input jari-jari dengan nilai float
* Membuat variable phi sebagai 3,14
* Membuat variable luas sebagai rumus luas lingkaran

![fl](https://user-images.githubusercontent.com/123666514/215314665-cc4ac3fb-68fc-4cda-ba98-59b1a228ed40.PNG)

Program yang di buat
```python
# input nilai variable
r = float(input("Masukan nilai jari-jari : "))

# menetapkan variable
phi = 3.14
luas = phi*r*r

# menampilkan hasil
print("Luas dari lingkaran adalah =",luas)
```
Hasil yang di tampilkan
![hl](https://user-images.githubusercontent.com/123666514/215311936-ae089484-201c-45f6-9b1d-18af2d2a0d2d.PNG)

## Keliling Lingkaran ##

Alur/flow yang harus di buat
* Membuat variable r sebagai input jari-jari dengan nilai float
* Membuat variable phi sebagai 3,14
* Membuat variable keliling sebagai rumus keliling lingkaran

![fk](https://user-images.githubusercontent.com/123666514/215314965-f2724a96-054b-4427-a2bd-a8799a8bdf0f.PNG)

Program yang di buat
```python
# input nilai variable
r = float(input("Masukan nilai jari-jari : "))

# menetapkan variable
phi = 3.14
keliling = 2*phi*r

# menampilkan hasil dan membuat nilai keliling menjadi 2 angkat di belang koma
print("Keliling dari lingkaran adalah =",round(keliling,2))
```

Hasil yang di tampilkan
![hk](https://user-images.githubusercontent.com/123666514/215312340-0b0c7f88-f99b-4e52-aea4-ef2ee9b1382c.PNG)

## Luas dan Keliling lingkaran ##

Alur/flow yang harus di buat
* Membuat variable r sebagai input jari-jari dengan nilai float
* Membuat variable phi sebagai 3,14
* Membuat variable luas sebagai rumus luas lingkaran
* Membuat variable keliling sebagai rumus keliling lingkaran

![flk](https://user-images.githubusercontent.com/123666514/215315002-ae511092-507f-4091-be77-96c046f0e951.PNG)

Program yang di buat
```python
# input nilai variable
r = float(input("Masukan nilai jari-jari : "))

# menetapkan variable
phi = 3.14
luas = phi*r*r
keliling = 2*phi*r

# menampilkan hasil dan membuat nilai keliling menjadi 2 angkat di belang koma
print("Luas dari lingkaran adalah =",round(luas,2))
print("Keliling dari lingkaran adalah =",round(keliling,2))
```

Hasil yang di tampilkan
![hlk](https://user-images.githubusercontent.com/123666514/215315194-bb194528-06a9-4221-a84d-929c7d4d55db.PNG)

## Latihan 1 ##

### Penggunaan end ##
Parameter end berfungsi untuk mengganti karakter terakhir bawaan yang dicetak di layar. Jadi secara bawaan, setiap kali kita memanggil fungsi print() untuk mencetak sesuatu, python akan mencetak karakter ganti baris () di setiap output.

Program
```python
# menampilkan varible dengan mengosongkan karakter setelah variable
print('A', end='')
print('B', end='')
print('C', end='')

# menampilkan ganti baris
print()

# menampilkan varible
print('X')
print('Y')
print('Z')
```
Hasil yang di tampilkan
![end](https://user-images.githubusercontent.com/123666514/215315752-b5564bbe-e118-46f8-bf2d-e7f2d8a3b51e.PNG)

### Penggunaan separator ##

Separator adalah komponen yang menentukan pemisah yang akan digunakan saat memisahkan string. Komponen ini bersifat optional. 

program
```python
# input variabel
w, x, y, z = 10, 15, 20, 25 

# menampilkan varible
print(w, x, y, z)

# menampilkan varible dengan "," sebagai pemisah antar variable 
print(w, x, y, z, sep=',')

# menampilkan varible dengan tidak menggunakan pemisah antar variable 
print(w, x, y, z, sep='')

# menampilkan varible dengan ":" sebagai pemisah antar variable 
print(w, x, y, z, sep=':')

# menampilkan varible dengan "-" sebagai pemisah antar variable 
print(w, x, y, z, sep='-----')
```

Hasil yang di tampilkan
![separator](https://user-images.githubusercontent.com/123666514/215316785-8cbf6a9c-1cbb-4302-83d4-dd3fd002620f.PNG)
