# labspy5
Labspy5
Pertama buatlah Data dictionary kosong (Data = {}).
Gunakan perulangan while. Masukkan inputan menu ( Quit, Look, Add, Edit, Delete, Search).
Gunakan kondisi if, elif, dan else untuk mengeksekusi perintah.
Untuk menu yang pertama adalah perintah Quit (keluar). Gunakan kondisi if untuk mengeksekusi perintah, jika hasilnya True maka program akan berhenti, tetapi jika hasilnya False / selain yang ada di menu , maka Anda akan diminta memasukkan inputan menu lagi ( yang ada pada menu).
Menu selanjutnya adalah perintah Look. Gunakan looping for ( for x in Data.items() ), lalu masukkan perintah print data dictionary.
Untuk perintah Add (menambahkan), inputkan data yang ingin Anda masukkan, seperti: Nama, Kelas, NIM, Nilai Tugas, Nilai UTS, Nilai UAS. Nilai Akhir dihitung dengan menggunakan rumus (Nilai Tugas * 30%) + (Nilai UTS * 35%) + (Nilai UAS * 35%).
Lalu menu untuk perintah Edit (mengubah). Inputkan Data[Nama] yang akan diedit. Gunakan kondisi if lagi ( if Nama in Data.keys() ), jika hasil adalah True maka Anda akan disuruh menginputkan data perubahannya. Tetapi jika hasilnya False, maka akan tercetak “Data ... tidak ada” dan muncul perintah untuk memasukkan inputan menu lagi.
Menu dengan perintah Delete (menghapus). Inputkan Data[Nama] yang akan di hapus,dengan menggunakan kondisi if, jika hasil True maka data akan terhapus dengan menggunakan perintah del Data[Nama], dan jika hasilnya False maka akan tercetak “Data ... tidak ada” dan muncul perintah untuk memasukkan inputan menu lagi.
Yang terakhir adalah menu dengan perintah search (mencari). Inputkan Data[Nama] yang akan dicari. Gunakan kondisi if , jika hasilnya True maka akan tercetak data yang dicari dengan menggunakan perintah print Data (Nama, Data[Nama]). Dan jika hasilnya False maka akan tercetak “Data ... tidak ada” dan muncul perintah untuk memasukkan inputan menu lagi.
Kondisi yang terakhir menggunakan else, jika menu yang Anda inputkan tidak ada pada menu maka Anda akan disuruh untuk menginputkan menu pilihan yang ada saja pada Data.
Berikut hasil program kompilasi di Run
