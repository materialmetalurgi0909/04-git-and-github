1.Fork repository GitHub https://github.com/impactbyte/tech4impact-students-bio.git menggunakan akun Github kamu
![Screenshot from 2021-09-21 22-44-56](https://user-images.githubusercontent.com/83164857/134208336-90d07230-e4a0-4e20-ab50-8a21c0e6d56e.png)


2.Clone remote repository dari hasil fork tersebut. Jangan clone dari repository originalnya.
```
git clone https://github.com/andrewelitar/tech4impact-students-bio
```

3.Buatlah branch baru dengan nama lengkap kamu. Misalnya david-winalda. Jangan melakukan perubahan pada branch master.
```
cd tech4impact-students-bio
git branch andrew-eliezer-tarigan
```
4.Checkout ke dalam branch tersebut yang telah kamu buat
```
git checkout andrew-eliezer-tarigan
```
5.Buatlah 1 file format .md dengan nama lengkap kamu. Contoh davidwinalda.md
```
touch andreweliezertarigan.md
```
6.Isi file tersebut davidwinalda.md dengan konten di bawah ini:
	Nama Lengkap: David Winalda
	Umur: 27
	Pesan yang ingin disampaikan: Semangat untuk kamu yang disana sedang berjuang
```
echo -e "echo Nama Lengkap: Andrew Eliezer Tarigan \nUmur: 20 \nPesan yang ingin disampaikan: Semangat yah" >>  andreweliezertarigan.md
```
7.Masukkan file .md tersebut ke dalam staging area
```
git add andreweliezertarigan.md
```
8.Commit dengan memberikan pesan nama file .md kamu
```
git commit -m "andreweliezertarigan.md"
```
9.Merge branch yang telah kamu buat ke dalam branch master
```
git checkout master
git merge andrew-eliezer-tarigan
```
10.Push ke dalam branch master
```
git push origin master
```
11.Lakukan pull request dari GitHub Repository yang telah kamu fork untuk digabungkan ke dalam branch master pada GitHub Repository aslinya.
![Screenshot from 2021-09-21 23-16-45](https://user-images.githubusercontent.com/83164857/134208357-13dff7a9-fad4-40ce-ad4d-d9d38e72321b.png)
