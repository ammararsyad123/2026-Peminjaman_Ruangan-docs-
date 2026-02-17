# Dokumentasi Proyek Peminjaman Ruangan

## 1. Studi Kasus
Aplikasi ini menangani manajemen dan peminjaman ruangan secara real-time untuk menghindari konflik jadwal.

## 2. Arsitektur Sistem
- **Frontend**: React TypeScript (Vite) + Bootstrap.
- **Backend**: ASP.NET Core Web API (NET 8).
- **Database**: SQL Server (Entity Framework Core) & Local Storage untuk log riwayat.

## 3. Spesifikasi API (API Spec)
Menggunakan Swagger untuk dokumentasi. Endpoint utama:
- GET /api/Rooms (Read)
- PUT /api/Rooms/{id} (Update status booking)

## 4. Refleksi
Selama pengerjaan, tantangan terbesar adalah memastikan sinkronisasi antara database SQL Server dan riwayat di Local Storage berjalan lancar.
