# Personal Portofolio Website - Najwa Aprisda Ramdhani

Proyek ini merupakan website portofolio pribadi yang menampilkan informasi tentang profil, keahlian, proyek, dan kontak.  
Dibangun sebagai bagian dari tugas *Praktikum Pemrograman Web* dengan tujuan memperkenalkan diri secara profesional menggunakan teknologi web dasar.

# Struktur Folder
ta-pemweb-percobaan-2/  
├── index.html  
├── style.css  
├── foto.jpg  
└── README.md 

## **Section pada index.html**
1. **Container Utama (`.container`)**
2. **Content Section (`.content`)**
3. **Sidebar (`.sidebar`)**
4. **Contact Section (`#kontak`)**
5. **Footer (`.footer`)**

## **Teknologi yang Digunakan**
- **HTML5** → Struktur konten dan elemen halaman.  
- **CSS3** → Desain tampilan, layout, dan efek visual.  
- **VS Code** → Text editor untuk pengembangan web.  
- **Git & GitHub** → Version control dan penyimpanan kode.

## **Cara Menjalankan Proyek**

# WORKFLOW GIT

1. Instalasi dan Konfigurasi Git
   Install Git (jika belum terinstall):
   * Windows: Download dari https://git-scm.com
   * macOS: brew install git
   * Linux: sudo apt-get install git

   ![Alt text](img/1.jpg)
   
   ```bash
   git config --global user.name "Nama Anda"
   git config --global user.email "email@example.com"
   git config --list
   ```
3. Membuat Repository Lokal
   - Buat direktori project baru:
      ![Alt text](img/2.jpg)

      ```bash
      mkdir my-web-project
      cd my-web-project
      ```
     
   - Inisialisasi Git repository:
      ![Alt text](img/3.jpg)

     ```bash
     git init ls -la # lihat folder .git yang terbentuk
     ```
     ```bash
     git status
     git add index.html
     git status
     ```
4. Commit dan History
   
   ![Alt text](img/4.jpg)
   
   ![Alt text](img/4(2).jpg)
   
   ![Alt text](img/5(3).jpg)
   ```bash
   git commit -m "Initial commit: Add index.html"
   git log git
   log --oneline
   ```
   Commit Perubahan:
   ```bash
   git add .
   git commit -m "Add CSS styling and link to index.html"
   git log --oneline
   ```

5. Remote Repository dengan GitHub
   
   ![Alt text](img/5.jpg)

   Hubungkan repository lokal ke remote:
   ```bash
   git remote add origin https://github.com/username/my-web-project.git
   git remote -v
   ```
   Push ke remote repository:
   ```bash
   git push -u origin main
   ```
   
7. Branching dan Merging
   
    ![Alt text](img/5(2).jpg)

   ```bash
   git branch feature-navigation git checkout feature-navigation # atau gunakan:
   git checkout -b feature-navigation
   ```
   Commit di feature branch:
   ```bash
   git add .
   git commit -m "Add navigation menu"
   ```
   Merge ke main branch:
   ```bash
   git checkout main
   git merge feature-navigation
   git branch -d feature-navigation
   ```
   Pull perubahan ke local:
   ```bash
   git pull origin main
   ```
## Contact 

* Email : najwaaprisdaa@gmail.com
* Instagram : https://www.instagram.com/najwaapdr?igsh=MXU0YXIwanJncGowMg== 
* Linkedin : www.linkedin.com/in/najwa-aprisda-ramdhani-7088b3293 

