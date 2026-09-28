# serverlive

## Menjalankan aplikasi

Aplikasi ini menggunakan Streamlit. Jalankan dengan:

```bash
python -m streamlit run streamlit_app.py
```

Video yang diunggah disimpan di direktori `streamlit_uploads/`. Batas upload
Streamlit dikonfigurasi hingga 4 GB per file, bergantung pada ruang disk
workspace yang tersedia.

Di halaman **Video File Library**, pilih file untuk:

- melihat file yang sudah tersimpan beserta ukuran dan waktu modifikasinya;
- mengunduh file yang dipilih;
- melihat preview video;
- memakai file tersebut sebagai sumber tombol **Start Streaming**.

Untuk Streamlit Cloud, gunakan `streamlit_app.py` sebagai **Main file path**.
Repository dan branch pada halaman deploy harus menunjuk ke repository GitHub
yang benar-benar ada dan memiliki file tersebut.