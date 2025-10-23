# UTS Manajemen Basis Data
## Nurdiansyah Pratama – NIM Akhir: 139

### 📦 Deskripsi
Proyek ini menyiapkan dua kontainer Docker untuk PostgreSQL dan PGAdmin4 sesuai instruksi UTS.

---

### ⚙️ Langkah Menjalankan

1. Clone repository:
   ```bash
   git clone https://github.com/username/uts_postgres_nurdiansyah.git
   cd uts_postgres_nurdiansyah
   ```

2. Jalankan container:
   ```bash
   docker-compose up -d
   ```

3. Cek container aktif:
   ```bash
   docker ps
   ```

4. Akses PGAdmin:
   - URL: [http://localhost:44139](http://localhost:44139)
   - Email: `admin@kampus.ac.id`
   - Password: `admin123`

5. Tambah Server di PGAdmin:
   - Name: `PostgresLocal`
   - Host: `postgres_nurdiansyah`
   - Username: `postgres`
   - Password: `ifunggul`

6. Tes koneksi eksternal di DBeaver:
   - Host: `localhost`
   - Port: `22139`
   - Database: `postgres`
   - Username: `postgres`
   - Password: `ifunggul`

---

### 🧠 SQL Files
- `create_schema.sql`: membuat schema *salam* dan tabel *mahasiswas* dengan constraint.
- `create_roles.sql`: membuat user `backend_dev`, `bi_dev`, dan `data_engineer`.

---

### 🧾 Dokumentasi yang Harus Disertakan
- Screenshot Docker Desktop (kedua kontainer jalan)
- Screenshot PGAdmin4 terhubung
- Screenshot DBeaver konek (port eksternal)
- Screenshot uji constraint
- Screenshot pengujian user-role
- URL GitHub repository

---

### 🕓 Deadline
**Minggu ke-8 (maks. 26 Oktober 2025, 23:00 WIB)**
