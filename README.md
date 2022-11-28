# Praktikum5.1
## Tugas Praktikum 5 
Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan :

- Program dibuat dengan menggunakan Dictionary
- Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)
- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
- Buat flowchart dan penjelasan programnya pada README.md.
- Commit dan push repository ke github

## Flowchart 


## Penjelasan Programnya 
1. Pertama input data sesuai keinginan anda dengan format Dictionary ``data = {}``
2. Gunakanlah perulangan While True untuk menampilkan data sebanyak banyaknya
3. Lalu masukan perintah ``c = input("\nPilih Opsi: ")`` untuk memilih opsi (T)ambah, (U)bah,(H)apus   (C)ari, (L)ihat, (K)eluar 
4. selanjutnya untuk membuat program keluar gunakan perintah 
``python
    if c.lower() == 'k':
        break
``
seperti gambar dibawah ini 
<img width="959" alt="ss1" src="https://user-images.githubusercontent.com/115479946/204201138-cc04e9b1-de97-4460-9f91-9b81b2a7c65d.png">

5. alu jika ingin memilih "(L)ihat" gunakan fungsi 'elif' dan gunakan fungsi ``for tabel in data.values():`` untuk memasukan data kedalam tabel data yang kita inputkan, dengan perintah "l". jika data yang tidak terdaftar = 0
Seperti gambar dibawah ini 
<img width="960" alt="ss2" src="https://user-images.githubusercontent.com/115479946/204201180-6b63db06-5e7a-4a38-be56-9ae2ca6901d2.png">

6. Untuk menambahkan data gunakan fungsi elif, lalu masukan nama, nim, tugas, uts, uas, nilaiakhir, nilai akhir didapat dari = ``round((float(tugas) * 0.3)+(float(uts) * 0.35)+(float(uas) * 0.35),2)``
seperti gambar dibawah ini 
<img width="958" alt="ss3" src="https://user-images.githubusercontent.com/115479946/204201193-696772d3-fa94-4c6a-b93a-ecb82c48cdaf.png">

<img width="958" alt="ss4" src="https://user-images.githubusercontent.com/115479946/204201206-ca61e680-4207-460a-98b6-703d32f02815.png"

<img width="958" alt="ss5" src="https://user-images.githubusercontent.com/115479946/204201214-c60b67ba-78b9-4b1d-bfba-44656ad1312c.png">

7. Lalu untuk mengedit data gunakan pilihan "(U)bah" gunakan fungsi 'elif' kemudian gunakan fungsi`` if nama in data.keys():'`` untuk mengubah data yang ada 
seperti gambar dibawah ini 
<img width="960" alt="ss6" src="https://user-images.githubusercontent.com/115479946/204203859-c1e209d0-743c-4a12-b3ec-404df33b0af0.png">

<img width="957" alt="ss7" src="https://user-images.githubusercontent.com/115479946/204201275-2b960a4b-3b5c-4f1a-9e87-542101

<img width="953" alt="ss8" src="https://user-images.githubusercontent.com/115479946/204201294-d06a5422-b2dd-491c-aea5-ea7df610eec2.png">

8. lalu untuk mencari data bisa menggunakan pilihan "(C)ari"" gunakan fungsi 'elif' kemudian gunakan fungsi`` if nama in data.keys():'``    untuk mencari data nama kemudian gunakan fungsi 'else' untuk menampilkan data nama yang kita cari tidak ada
seperti gambar dibawah ini 
