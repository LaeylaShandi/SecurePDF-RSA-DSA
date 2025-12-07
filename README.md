# SecurePDF-RSA-DSA

**Sistem Enkripsi Asimetris (RSA) dan Tanda Tangan Digital (DSA) untuk Dokumen Rahasia**

SecurePDF-RSA-DSA adalah aplikasi desktop berbasis Python yang dirancang untuk memberikan keamanan ganda pada pertukaran dokumen digital (khususnya PDF). Aplikasi ini menggabungkan **Enkripsi Hybrid (RSA + AES)** untuk menjaga kerahasiaan dan **Digital Signature (DSA)** untuk menjamin keaslian serta integritas data.

Dibangun dengan antarmuka grafis (GUI) menggunakan **Tkinter** dan pustaka kriptografi **PyCryptodome**.

---

## Fitur Utama

Aplikasi ini menjamin dua aspek keamanan informasi utama:

1.  **Kerahasiaan (Confidentiality):** Dokumen hanya dapat dibaca oleh penerima yang memiliki Kunci Privat yang sesuai. Menggunakan mekanisme *Hybrid Encryption* (AES untuk data, RSA untuk kunci).
2.  **Keaslian & Integritas (Authenticity & Integrity):** Penerima dapat memverifikasi bahwa dokumen benar-benar berasal dari pengirim yang sah dan belum diubah di tengah jalan menggunakan algoritma DSA.

---

## Persyaratan Sistem & Instalasi

### Prasyarat
* **Python 3.x**
* **Tkinter** (Biasanya sudah disertakan dalam instalasi standar Python)
* **PyCryptodome**

### Instalasi
1.  Clone repositori ini atau unduh source code.
2.  Install library dependensi menggunakan pip:

```bash
pip install pycryptodome
