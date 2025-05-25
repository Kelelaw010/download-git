## Cara Download dan Install Git

1. **Kunjungi situs resmi Git:**  
   Buka browser dan pergi ke [https://git-scm.com/downloads](https://git-scm.com/downloads)

2. **Pilih sistem operasi kamu:**  
   Pilih versi Git sesuai OS kamu (Windows, macOS, Linux).

3. **Download installer:**  
   Klik link untuk mengunduh installer Git terbaru.

4. **Jalankan installer:**  
   Ikuti langkah instalasi yang muncul di layar.  
   - *Windows:* Klik `Next` sampai selesai.  
   - *macOS:* Bisa menggunakan installer atau Homebrew dengan perintah:  
     ```bash
     brew install git
     ```  
   - *Linux:* Gunakan package manager, contoh untuk Ubuntu/Debian:  
     ```bash
     sudo apt update
     sudo apt install git
     ```

5. **Cek instalasi:**  
   Buka terminal atau Command Prompt lalu ketik:  
   ```bash
   git --version
   ```
   Jika muncul versi Git, instalasi berhasil.

## Cara Menggunakan Git Dasar

1. **Konfigurasi Git pertama kali:**
   Atur nama dan email kamu (untuk identitas commit):
   ```bash
    git config --global user.name "Nama Kamu"
    git config --global user.email "emailkamu@example.com"
   ```
2. Inisialisasi repositori Git di folder proyek:
   ```bash
   git init
   ```
3. Menambahkan file ke staging area:
   ```bash
    git add nama_file
   ```
   Atau untuk menambahkan semua file sekaligus:
   ```bash
    git add .
   ```
4. Membuat commit:
   ```bash
    git commit -m "first commit"
   ```
5. Cek status repositori:
   ```bash
    git status
   ```
6. Melihat riwayat commit:
   ```bash
    git log
   ```

## Cara Push ke GitHub

1. Buat repositori di GitHub:
    * Masuk ke akun GitHub kamu.
    * Klik tombol New Repository.
    * Beri nama dan deskripsi (opsional), lalu klik Create repository.
2. Hubungkan repositori lokal ke GitHub:
   Salin URL repositori GitHub kamu (misal: https://github.com/username/nama-repo.git), lalu jalankan:

   ```bash
    git remote add origin https://github.com/username/nama-repo.git
   ```
4. Push ke GitHub:
   ```bash
    git branch -M main
    git push -u origin main
   ```

## Cara Clone Repositori dari GitHub
1. Salin URL repositori GitHub (misalnya: https://github.com/username/nama-repo.git)
2. Jalankan perintah berikut di terminal:
   ```bash
    git clone https://github.com/username/nama-repo.git
   ```
3. Masuk ke folder proyek:
   ```bash
    cd nama-repo
   ```



   
