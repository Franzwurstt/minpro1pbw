# minpro1pbw
Nama: Prakasa Wira Mukti  
NIM: 2409116054  
Kelas: B 24  

## Tampilan Setiap Section/Fitur 

### Hero Section
- Navbar dengan button Home About Me dan Certification  
- Perkenalan singkat berupa nama dan status
- Button Instagram dan Linkedin yang akan langsung tertuju ke situs tersebut jika diclick  
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/fcaa7913-6df1-4bab-8cf3-27f3f025e85e" />

### Section About Me  
- Deskripsi diri  
- Skills (progress bar)  
- Pengalaman  
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/9c95bdc0-5bff-4deb-b124-5ac0d66b4905" />
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/d3afc415-7c44-443b-9583-0614610bc58a" />

### Section Certificates
-  Daftar sertifikat dalam bentuk card  
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/b91af495-5a4d-4a55-8a5f-e9c92e81f6fa" />  

## Penjelasan Code Setiap Section/Fitur

1. **Navbar**  
Bagian navigasi utama di paling atas halaman.  
Menggunakan Bootstrap `navbar` dengan: 
Menu: Home, About Me, Certificates  
Setiap menu memakai anchor link (`#home`, `#about`, `#certificates`) agar langsung menuju section terkait.  
Class `fixed-top` membuat navbar tetap terlihat saat halaman di-scroll.  
Warna navbar memakai class custom `bg-navy` dari `style.css`.

2. **Hero Section**  
Bagian pembuka portfolio pada section `id="home"`.  
Menampilkan:
Perkenalan nama  
Status/role (Mahasiswa Sistem Informasi, Computer Service Technician, Future Network Engineer)  
Tombol sosial media (Instagram dan LinkedIn) dengan ikon Font Awesome  
Foto profil di sisi kanan  
Section ini didesain sebagai area utama perkenalan singkat.

3. **Section About Me**  
Section `id="about"` berisi informasi pribadi dan kemampuan.  
Terdiri dari:
Description: latar belakang, minat, dan pengalaman umum  
Skills: kemampuan teknis dalam bentuk progress bar  
Experiences: daftar pengalaman/proyek dalam bentuk list  
Konten pada section ini ditampilkan dalam box menggunakan class `about-box`.

4. **Section Certificates**  
Section `id="certificates"` menampilkan pencapaian sertifikat.  
Struktur menggunakan Bootstrap card dalam layout 3 kolom.  
Setiap card berisi:
Gambar sertifikat  
Judul sertifikat  
Keterangan penyelenggara dan tahun  
Section ini berfungsi sebagai bukti kompetensi/aktivitas.

5. **Footer**  
Bagian penutup halaman di bagian paling bawah.  
Berisi copyright dan nama pemilik portfolio.  
Menggunakan tampilan sederhana: teks putih dengan background navy.

## Teknologi yang Digunakan
- HTML
- CSS
- Bootstrap 5
