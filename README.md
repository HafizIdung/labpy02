# Struktur kondisi
Nama: HAFIZ ABDUROHMAN 

Kelas: TI.24.A4

NIM: 312410333

Matkul: Bahasa Pemrograman

# Soal latihan
![gambar](https://github.com/andreanbadeh/fotoo/blob/f2ee036ad9f00134b2fdb34c85445e84a3559dcb/Screenshot%20From%202024-10-22%2010-49-34.png)

# Latihan 1
```python
nama = input("Masukkan nama:")
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
print("Keterangan :",keterangan)
````
