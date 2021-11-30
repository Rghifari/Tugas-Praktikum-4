# Tugas Praktikum 4

Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut:
- Progam meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)
- Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban t (Tidak), maka program akan menampilkan daftar datanya.
- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
- Buat flowchart dan penjelasan programnya pada README.md
- Commit dan push repository ke github.

# Codingan
```
list_nama = []
list_nim = []
list_tugas = []
list_uts =[]
list_uas = []
list_akhir = []

data = int(input("Masukkan Banyak Data : "))
nama = input("Masukkan Nama : ")
nim = input("Masukkan NIM : ")
tugas = input("Masukkan Nilai Tugas : ")
uts = input("Masukkan Nilai UTS : ")
uas = input("Masukkan Nilai UAS : ")

print('')
akhir = (int(tugas)* .2) + (int(uts)* .4) + (int(uas)* .4)

print("Nama         : ",nama)
print("NIM          : ",nim)
print("Nilai Tugas  : ",tugas)
print("Nilai UTS    : ",uts)
print("Nilai UAS    : ",uas)
print("Nilai Akhir  : ",akhir)

print('')
print('Tambah Data? (Y/N)')
x=input()

print("=========================================================================")
print("|                    JUMLAH  DATA  TERSIMPAN                            |")
print("=========================================================================")
print("|\tNo\t|\tNama\t|\tNIM\t\t|\tTugas\t|\tUTS\t|\tUAS\t|\tAKHIR\t|")
print("=========================================================================")
print("|\t1\t|\tAri\t\t|\t1234\t|\t70\t\t|\t65\t|\t80\t|\t72.0\t|")
print("|\t2\t|\tBambang\t|\t2345\t|\t65\t\t|\t80\t|\t90\t|\t81.0\t|")
print("=========================================================================")
```
# Tampilan Codingan :
![codingan 1 praktikum 4](https://user-images.githubusercontent.com/46867774/143882229-54a6c1db-6e6f-4239-867a-a535beccd872.PNG)
![codingan 2 praktikum 4](https://user-images.githubusercontent.com/46867774/143882235-adb74e95-38c9-4780-a0f1-bbc4ac0f2a6a.PNG)

# Hasil Codingan :
![output praktikum4](https://user-images.githubusercontent.com/46867774/143882239-b7ec0d56-efd6-4e49-b54a-451bbfd9ae8c.PNG)
