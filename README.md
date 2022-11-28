# Praktikum5.1
## Tugas Praktikum 5 
Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan :

- Program dibuat dengan menggunakan Dictionary
- Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)
- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
- Buat flowchart dan penjelasan programnya pada README.md.
- Commit dan push repository ke github

## Flowchart 
![flowchart](https://user-images.githubusercontent.com/115479946/204206624-c12c76f1-1bcd-4077-abd2-f37a8cf8575d.png)


## Penjelasan Programnya 
1. Pertama input data sesuai keinginan anda dengan format Dictionary ``data = {}``
2. Gunakanlah perulangan While True untuk menampilkan data sebanyak banyaknya
3. Lalu masukan perintah ``c = input("\nPilih Opsi: ")`` untuk memilih opsi (T)ambah, (U)bah,(H)apus   (C)ari, (L)ihat, (K)eluar 
4. selanjutnya untuk membuat program keluar gunakan perintah BREAK 
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

<img width="958" alt="ss4" src="https://user-images.githubusercontent.com/115479946/204204970-7f68abb6-02e5-47f3-a29a-fb6bc60eb3b3.png">

<img width="958" alt="ss5" src="https://user-images.githubusercontent.com/115479946/204201214-c60b67ba-78b9-4b1d-bfba-44656ad1312c.png">

7. Lalu untuk mengedit data gunakan pilihan "(U)bah" gunakan fungsi 'elif' kemudian gunakan fungsi`` if nama in data.keys():`` untuk mengubah data yang ada 
seperti gambar dibawah ini 
<img width="960" alt="ss6" src="https://user-images.githubusercontent.com/115479946/204203859-c1e209d0-743c-4a12-b3ec-404df33b0af0.png">

<img width="957" alt="ss7" src="https://user-images.githubusercontent.com/115479946/204204985-f80324a3-3b3e-4871-b490-16b50e0be48b.png">

<img width="953" alt="ss8" src="https://user-images.githubusercontent.com/115479946/204201294-d06a5422-b2dd-491c-aea5-ea7df610eec2.png">

8. lalu untuk mencari data bisa menggunakan pilihan "(C)ari"" gunakan fungsi 'elif' kemudian gunakan fungsi`` if nama in data.keys():``    untuk mencari data nama kemudian gunakan fungsi 'else' untuk menampilkan data nama yang kita cari tidak ada
seperti gambar dibawah ini 
<img width="959" alt="ss9" src="https://user-images.githubusercontent.com/115479946/204201316-dc08ef94-196e-43b0-b10c-9b8236c09fda.png">

9. Untuk menampilkan pilihan "(H)apus" gunakan fungsi 'elif' kemudian gunakan fungsi ``if nama in data.keys():`` kemudian fungsi'del.data[nama] jika nama yang kita hapus tidak ada dalam tabel maka gunakan fungsi 'else' untuk menampilkan data tidak ada.
seperti gambar dibawah ini 
<img width="956" alt="ss10" src="https://user-images.githubusercontent.com/115479946/204201345-740ca9ad-39c8-4f0f-adb6-305894f01db9.png">


## Hasil Outputnya


<img width="959" alt="OP1" src="https://user-images.githubusercontent.com/115479946/204207103-34ea795e-7b23-4e89-9d61-a7dc5303e4c2.png">

<img width="958" alt="OP2" src="https://user-images.githubusercontent.com/115479946/204207118-e4012538-ea3a-41f5-b486-dc5afe24d48a.png">

<img width="959" alt="OP3" src="https://user-images.githubusercontent.com/115479946/204207124-322e2e67-09b4-485d-8db1-68b82ffa212f.png">

<img width="959" alt="OP4" src="https://user-images.githubusercontent.com/115479946/204207133-313796c1-f6d5-4855-ae3f-c127f1f9d917.png">

