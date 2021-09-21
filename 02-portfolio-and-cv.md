Tugas
1. membuat sebuah folder kosong dengan namamu sendiri =>
mkdir andrew
cd andrew

2. membuat sebuah file dengan nama README.md, isi file tersebut dengan kalimat
"Halo perkenalkan aku halaman utama" =>
echo Halo perkenalkan aku halaman utama > README.md

3. inisialisasi folder tersebut dengan Git, kemudian dokumentasikan menggunakan commit dengan pesan
"Inisialisasi Git Repository" =>
echo Halo perkenalkan aku halaman utama > README.md

4. buat branch baru dengan nama cv, hal ini berguna agar histori kita tidak tercampur =>
git branch cv

5. pindah branch kedalam cv, kemudian buat file dengan nama cv.txt dan isi file tersebut dengan kalimat:
"Ini adalah file CV" =>
git checkout cv
echo Ini adalah file CV > cv.txt

6. kemudian dokumentasikan menggunakan commit dengan pesan "Inisialisasi CV" =>
git add cv.txt
git commit -m "Inisialisasi CV"

7. tambahkan 3 perusahaan yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi menggunakan commit
echo Google >> cv.txt
git add cv.txt
git commit -m "menambahkan perusahaan pertama"
echo Netflix >> cv.txt
git add cv.txt
git commit -m "menambahkan perusahaan kedua"
echo Tokopedia >> cv.txt
git add cv.txt
git commit -m "menambahkan perusahaan ketiga"
8. kembali ke branch master
git checkout master

9. ubah file README.md menjadi
	Halo perkenalkan aku halaman utama
	Ini adalah update pertama pada branch master
  jangan lupa untuk mendokumentasikannya menggunakan commit dengan pesan "update master pertama"
echo Halo perkenalkan aku halaman utama \nIni adalah update pertama pada branch master > README.md
git add .
git commit -m "update master pertama"

10. gabungkan branch cv kedalam branch master menggunakan perintah git merge
git merge cv

11. unggah Git Repository tersebut kedalam GitHub
git remote add origin git remote add origin https://github.com/andrewelitar/04-git-and-github.git
git push -u origin master

![Screenshot from 2021-09-21 22-24-08](https://user-images.githubusercontent.com/83164857/134199940-2244cea5-6031-40b3-b34e-1bb0865f3768.png)
