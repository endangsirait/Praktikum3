# Praktikum3
# Latihan

• Lengkapi latihan class Mahasiswa dengan setter dan getter.

• Implementasikan java code diagram class berikut:

![Screenshot 2024-10-16 143534](https://github.com/user-attachments/assets/f919fa67-7627-4c0c-83ce-2cbc396a59e7)

# Class Mahasiswa dengan setter dan getter
# INPUT
  
![6](https://github.com/user-attachments/assets/421c668c-15cf-481a-8b63-a38a5e1a642a)

![7](https://github.com/user-attachments/assets/dc24d1ab-c55a-44aa-843b-a8ae84c663c6)

![8](https://github.com/user-attachments/assets/e3b6303f-0bdd-4ca3-9eca-4359662f48b9)

# OUTPUT

![9](https://github.com/user-attachments/assets/beddea28-4ab8-4735-9ff9-c4db5c2641b1)

Penjelasan:
* Class Mahasiswa memiliki 4 atribut: nama, nim, jurusan, dan ipk.
* Setiap atribut memiliki method setter untuk mengatur nilai dan getter untuk mendapatkan nilai.
* Method cetakInfo() digunakan untuk mencetak informasi mahasiswa.
* Di dalam Main class, objek Mahasiswa digunakan untuk menguji fungsi setter dan getter serta menampilkan informasi mahasiswa.

# implementasikan diagram class yang mencakup Pegawai, Programmer, dan Manager
# INPUT
# Class Pegawai
![1](https://github.com/user-attachments/assets/cbc9d86d-43d1-4024-af0f-708bbff8f8df)

Penjelasan:
* Pegawai adalah class dasar (superclass) yang menyimpan atribut dasar seorang pegawai: nama dan gajiPokok.
* Setter (setNama(), setGajiPokok()) digunakan untuk mengubah atau mengatur nilai atribut nama dan gajiPokok.
* Getter (getNama(), getGajiPokok()) digunakan untuk mendapatkan nilai dari atribut tersebut.
* Method cetakInfo(): Mencetak informasi pegawai, yaitu nama dan gajiPokok.

# Class Programmer (subclass dari pegawai)

![2](https://github.com/user-attachments/assets/5760f4f1-558b-4504-9543-2e5a71856dc6)

Penjelasan:
* Programmer adalah subclass dari Pegawai, artinya class Programmer mewarisi semua atribut dan method dari class Pegawai.
* Atribut tambahan: Programmer memiliki dua atribut tambahan, yaitu tunjangan dan bonus.
* Setter dan Getter: Terdapat method setter dan getter untuk mengatur dan mendapatkan nilai dari atribut tunjangan dan bonus.
* Override cetakInfo(): Method ini di-override dari class Pegawai untuk menambahkan informasi tambahan seperti tunjangan dan bonus setelah mencetak nama dan gajiPokok menggunakan method super.cetakInfo().
* Method tambahan: cetakTunjangan() dan cetakBonus() disediakan untuk mencetak tunjangan dan bonus secara terpisah.


# Class Manager (Subclass dai pegawai)

![3](https://github.com/user-attachments/assets/79c972ba-4507-4258-8fa0-978e92a7c92a)

Penjelasan:
* Manager adalah subclass dari Pegawai yang memiliki atribut dan method serupa dengan Programmer, yaitu menambahkan tunjangan dan bonus.
* Override cetakInfo(): Sama seperti Programmer, method ini digunakan untuk menambahkan informasi tunjangan dan bonus setelah mencetak data dasar dari Pegawai.
* Method tambahan: Ada method khusus untuk mencetak tunjangan (cetakTunjangan()) dan bonus (cetakBonus()).
  
# Penggunaan di Main class

![4](https://github.com/user-attachments/assets/bf545a27-0dce-4296-86b8-894e7d98daeb)

Penjelasan:
* Pada Main Class, objek Programmer dan Manager dibuat untuk menguji fungsionalitas dari masing-masing class.
* Programmer programmer = new Programmer(): Membuat objek programmer, kemudian setter digunakan untuk mengatur nama, gaji pokok, tunjangan, dan bonus.
* cetakInfo(): Mencetak informasi lengkap Programmer, termasuk tunjangan dan bonus.
* cetakTunjangan() dan cetakBonus(): Mencetak tunjangan dan bonus secara terpisah.


# OUTPUT

![5](https://github.com/user-attachments/assets/2dcdca51-e9aa-463c-a8f7-046df12f79a4)

Penjelasan Output:
Programmer:
* Nama programmer adalah Budi.
* Gaji pokok programmer adalah 5.000.000.
* Tunjangan programmer adalah 1.000.000.
* Bonus programmer adalah 500.000.
* Tunjangan dan bonus dicetak dua kali karena ada method tambahan cetakTunjangan() dan cetakBonus().
  
Manager:
* Nama manager adalah Andi.
* Gaji pokok manager adalah 8.000.000.
* Tunjangan manager adalah 2.000.000.
* Bonus manager adalah 1.000.000.
* Sama seperti Programmer, tunjangan dan bonus dicetak dua kali dengan method tambahan cetakTunjangan() dan cetakBonus().













