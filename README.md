# Tugas 6 - Mini Habit Tracker

**Nama:** Sakahayu Pribadi  
**NPM:** 4522210062  
**Dosen Pengampu:** Adi Wahyu Pribadi S.SI., M.Kom.  
**Program Studi:** Teknik Informatika  
**Universitas Pancasila - 2025**

---

## 1. Jalankan aplikasi (flutter run).

**Screenshot:** \
![1](screenshots/1.png)

## 2. Uji Strikethrough: Centang dan batalkan centang habit. Perhatikan teksnya.

**Screenshot:** \
![2](screenshots/2.png)
![3](screenshots/3.png)

## 3. Uji Tambah Habit:

- Klik tombol + di AppBar.
  **Screenshot:** \
  ![4](screenshots/4.png)

- Coba simpan tanpa mengisi nama (validasi harus mencegah).
  **Screenshot:** \
  ![5](screenshots/5.png)

- Isi form dan simpan. Verifikasi habit baru muncul di list.
  **Screenshot:** \
  ![6](screenshots/6.png)
  ![7](screenshots/7.png)

## 4. Uji Edit Habit:

- Klik menu tiga titik pada habit, pilih "Edit".
- Dialog harus muncul dengan data habit tersebut.
  **Screenshot:** \
  ![8](screenshots/8.png)

- Ubah nama/deskripsi dan simpan. Verifikasi perubahan di list.
  **Screenshot:** \
  ![9](screenshots/9.png)
  ![10](screenshots/10.png)

## 5. Uji Hapus Habit:

- Klik menu tiga titik pada habit, pilih "Hapus".
  ![11](screenshots/11.png)

- Dialog konfirmasi harus muncul. Coba batalkan.
  ![12](screenshots/12.png)
  ![13](screenshots/13.png)

- Coba hapus lagi dan konfirmasi. Verifikasi habit hilang dari list.
  ![14](screenshots/14.png)

## 6. Uji Progress Bar: Pastikan progress di AppBar terupdate setelah menambah, menghapus, atau mencentang habit.

**Screenshot:** \
![15](screenshots/15.png)
![16](screenshots/16.png)
![17](screenshots/17.png)

## 7. Uji Reset: Tombol reset harus mengembalikan semua isDone ke false.

**Screenshot:** \
![18](screenshots/18.png)
![19](screenshots/19.png)

## 8. Uji Ephemeral State: Tutup paksa aplikasi dan buka kembali. Semua perubahan (tambah, edit, hapus) seharusnya hilang, dan hanya data dari habits.json yang tampil.

**Screenshot:** \
![20](screenshots/20.png)

## 9. Amati Output print: Perhatikan konsol debug. Kapan saja print('build ${habit.name}') muncul? Bagaimana ini berkaitan dengan aksi Anda (check, add, edit, delete)?

### 1. Saat aplikasi pertama kali selesai memuat JSON

### 2. Saat menambahkan habit baru

### 3. Saat mengedit habit

### 4. Saat menghapus habit

### 5. Saat men-centang / un-centang checkbox

**Screenshot:** \
![21](screenshots/21.png)

---

## Lisensi

Proyek ini dibuat untuk keperluan pembelajaran Praktikum Pemrograman Berbasis Mobile.
