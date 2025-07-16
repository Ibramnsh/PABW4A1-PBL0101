# PABW4A1-PBL0101

## 🚀 Instalasi
1.  **Clone repositori ini:**
    ```bash
    git clone [https://github.com/](https://github.com/)[username-anda]/[nama-repositori].git
    cd [nama-repositori]
    ```

2.  **Buat dan aktifkan _virtual environment_ (dianjurkan):**
    * **Windows:**
        ```bash
        python -m venv venv
        .\venv\Scripts\activate
        ```
    * **macOS / Linux:**
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```

3.  **Instal semua dependensi yang dibutuhkan:**
    Proyek ini menggunakan file `requirements.txt` untuk mengelola dependensi.
    ```bash
    pip install -r requirements.txt
    ```

---

## ▶️ Menjalankan Aplikasi

Setelah instalasi selesai, Anda dapat menjalankan server pengembangan menggunakan **Uvicorn**.

```bash
uvicorn main:app --reload
