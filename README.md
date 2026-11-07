# Day 1 – Workshop Documentation

**Nama:** Mirza Mochtadi  
**Kelompok:** Hitman: Absolution  
**Kegiatan:** Day 1 Proyek Workshop 2026  
**Topik:** Building with AI, Managing Change with GitHub  
**Pemateri:** Nugi Farhan – Senior Product Designer

## Deskripsi Repository

Repository ini berisi dokumentasi dan catatan pembelajaran selama kegiatan Day 1 Proyek Workshop 2026 yang diselenggarakan oleh HIMATIK PNJ.

Dokumentasi mencakup rangkuman materi, poin-poin penting, serta refleksi pribadi mengenai materi yang disampaikan selama workshop.

## Tujuan Repository

- Mendokumentasikan materi dan kegiatan workshop.
- Menyimpan catatan pembelajaran secara terstruktur.
- Memahami penggunaan Git dan GitHub untuk version control.
- Mempelajari penerapan AI dalam proses pengembangan aplikasi.
- Menjadi arsip pembelajaran yang dapat diakses secara daring.

## Dokumentasi Materi Workshop

### 1. Prompt Engineering

Prompt Engineering merupakan proses merancang instruksi agar model AI dapat menghasilkan jawaban yang tepat, relevan, dan sesuai kebutuhan.

Prompt dapat berupa pertanyaan sederhana, kata kunci, instruksi kompleks, maupun potongan kode.

**Pentingnya Context**

Konteks membantu AI memahami tujuan, kebutuhan, batasan, dan hasil yang diharapkan. Prompt yang spesifik dan memiliki konteks cenderung menghasilkan respons yang lebih sesuai dibandingkan instruksi yang terlalu umum.

**Struktur Prompt yang Baik**

Empat komponen utama dalam menyusun prompt:

- **Role:** Menentukan peran AI.
- **Task:** Menjelaskan tugas yang harus dilakukan.
- **Context:** Memberikan latar belakang dan kebutuhan.
- **Format:** Menentukan bentuk hasil yang diinginkan.

**Keuntungan Prompt Engineering**

- Meningkatkan relevansi dan kualitas hasil AI.
- Mengurangi kemungkinan respons yang tidak sesuai.
- Meningkatkan kontrol dan prediktabilitas hasil.
- Memberikan pengalaman penggunaan AI yang lebih baik.

### 2. Git dan GitHub

**Git** adalah distributed version control system yang digunakan untuk melacak dan mengelola perubahan pada file proyek. Git dikembangkan oleh Linus Torvalds pada tahun 2005.

**GitHub** adalah platform berbasis web untuk menyimpan repository Git secara daring serta mendukung kolaborasi antar pengguna.

| Git | GitHub |
|---|---|
| Version control system | Platform hosting repository |
| Berjalan secara lokal maupun terdistribusi | Berbasis layanan daring |
| Melacak perubahan proyek | Menyimpan dan memfasilitasi kolaborasi proyek |

### 3. Git Workflow

Git memiliki tiga bagian utama dalam alur pengelolaan perubahan:

1. **Working Directory:** Tempat pengguna mengedit dan mengembangkan file proyek.
2. **Staging Area:** Tempat menyiapkan perubahan yang akan dimasukkan ke commit berikutnya.
3. **Git Directory / Repository:** Tempat Git menyimpan riwayat perubahan dan informasi repository.

Alur sederhananya:

`Working Directory → Staging Area → Repository`

### 4. Essential Git Commands

| Command | Fungsi |
|---|---|
| `git init` | Membuat repository Git baru. |
| `git add .` | Menambahkan perubahan ke staging area. |
| `git add --all` | Menambahkan seluruh perubahan, termasuk penghapusan file. |
| `git commit -m "message"` | Menyimpan perubahan sebagai commit. |
| `git status` | Memeriksa status perubahan repository. |
| `git log` | Melihat riwayat commit. |
| `git remote add origin <url>` | Menghubungkan repository lokal dengan remote. |
| `git push origin main` | Mengirim commit ke remote repository. |
| `git pull origin main` | Mengambil dan menggabungkan perubahan dari remote. |

### 5. Git Setup

Tahapan dasar konfigurasi Git:

1. Menginstal Git sesuai sistem operasi.
2. Memeriksa instalasi menggunakan `git --version`.
3. Mengatur identitas pengguna:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

4. Memeriksa konfigurasi:

```bash
git config --global --list
```

### 6. SSH Authentication

SSH dapat digunakan untuk menghubungkan komputer dengan GitHub tanpa harus memasukkan kredensial akun pada setiap operasi Git.

Workshop memperkenalkan penggunaan algoritma Ed25519 untuk membuat SSH key:

```bash
ssh-keygen -t ed25519 -C "email@domain.com"
```

Public key kemudian ditambahkan ke pengaturan SSH and GPG keys pada GitHub.

Koneksi dapat diperiksa menggunakan:

```bash
ssh -T git@github.com
```

Catatan: Beberapa instruksi konfigurasi pada materi menggunakan macOS. Langkah konfigurasi SSH pada Windows dapat berbeda.

### 7. AI-Assisted Development Workflow

Workshop juga memperkenalkan alur pengembangan aplikasi dengan bantuan AI:

1. Menginstal atau menggunakan platform AI-assisted development.
2. Menyusun prompt untuk membuat aplikasi atau web.
3. Menginisialisasi Git menggunakan `git init`.
4. Melakukan commit dan push ke GitHub.
5. Mengembangkan atau memperbarui aplikasi.
6. Melakukan commit dan push kembali untuk menyimpan perubahan.

Contoh proyek yang digunakan sebagai latihan adalah **Student Task Planner**, yaitu aplikasi sederhana untuk membantu mahasiswa mengelola tugas dan tenggat waktu.

## Poin Pembelajaran

- Konteks merupakan bagian penting dalam menyusun prompt AI.
- Prompt yang terstruktur membantu menghasilkan keluaran yang lebih sesuai.
- Git dan GitHub memiliki fungsi berbeda, tetapi saling melengkapi.
- Commit memungkinkan perubahan proyek dilacak berdasarkan riwayat.
- Staging area membantu menentukan perubahan yang akan disimpan.
- Remote repository memungkinkan proyek disimpan dan dikelola secara daring.
- AI dapat membantu proses pengembangan aplikasi, tetapi hasilnya tetap perlu diperiksa dan diuji.

## Pendapat Pribadi

Menurut saya, materi Day 1 memberikan pemahaman dasar mengenai pemanfaatan AI dalam pengembangan aplikasi serta pentingnya version control menggunakan Git dan GitHub.

Saya mempelajari bahwa penggunaan AI tidak hanya bergantung pada model yang digunakan, tetapi juga pada bagaimana instruksi dan konteks diberikan. Selain itu, Git membantu pengelolaan perubahan proyek agar lebih terstruktur dan mudah ditelusuri.

Materi ini menjadi dasar yang berguna untuk mengembangkan proyek secara bertahap serta membiasakan dokumentasi dan pengelolaan pekerjaan menggunakan GitHub.

## Referensi

- Materi presentasi workshop: *Building with AI, Managing Change with GitHub* — Nugi Farhan.
- Google Cloud: [What is Prompt Engineering?](https://cloud.google.com/discover/what-is-prompt-engineering)
- Git Documentation: [https://git-scm.com/doc](https://git-scm.com/doc)
- GitHub Documentation: [https://docs.github.com/](https://docs.github.com/)

---

*Dokumentasi Day 1 Proyek Workshop 2026 – HIMATIK PNJ.*
