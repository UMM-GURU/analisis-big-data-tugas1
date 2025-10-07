# Tugas 1: Dasar GitHub & Python

Selamat datang di tugas pertama Anda! Tugas ini dirancang untuk membantu Anda memahami dasar penggunaan GitHub dan Python.

---

## 📋 Instruksi

1. **Clone repositori ini** ke komputer lokal Anda:
   ```bash
   git clone https://github.com/UMM-GURU/tugas1-namauser.git
   cd assignment1-namauser

2. Buka file notebook tugas1.ipynb menggunakan Jupyter Notebook atau Google Colab.

3. Selesaikan tugas berikut:
  - Jalankan semua cell sampai sebelum bagian cetak nama dan NIM, lalu buat commit
  - Cetak NIM dan nama lengkap Anda di cell yang disediakan, lalu buat commit.
  - Update cell latihan 1, lalu buat commit
  - Update cell latihan 2, lalu buat commit
  - Lakukan push ke remote repository

**Minimal ada 4 commit tambahan**, Anda bisa memiliki lebih dari itu.

Contoh melakukan commit dan push menggunakan terminal:

    ```
    git add tugas.ipynb
    git commit -m "Menyelesaikan tugas 1"
    git push
    ```

Bisa juga menggunakan interface di IDE seperti VS Code

Jika mengerjakan menggunakan VS Code (sangat disarankan, standard dunia kerja):
- Pastikan python sudah terinstall
- Instalasi dan setup GitHub di komputer lokal:
  - MAC: https://www.youtube.com/watch?v=p0Js7IF17yI
  - Windows 11: https://www.youtube.com/watch?v=AdzKzlp66sQ
- Instalasi VS Code: https://code.visualstudio.com/docs/setup/setup-overview
- Menggunakan Git dengan VS Code: https://www.youtube.com/watch?v=Vn0LYZ8Qepc
- Clone dan instalasi packages + menjalankan file tugas
   - Jalankan perintah clone seperti di atas
   - Masuk ke folder repositori
   - Buat virtual environment:
      ```
      python -m venv venv
      ```
      atau
      ```
      python3 -m venv venv
      ```
   - Aktivasi virtual environment:
      ```
      # Windows command prompt:
      venv\Scripts\activate

      # Windows Power Shell
      .\venv\Scripts\Activate.ps1

      # macOS / Linux
      source venv/bin/activate
      ```
   - Install Dependencies dari requirements.txt
     ```
     pip install -r requirements.txt
     ```
   - Daftarkan kernel
     ```
     python -m ipykernel install --user --name=venv --display-name "Python (venv-tugas1)"
     ```
     atau
     ```
     python3 -m ipykernel install --user --name=venv --display-name "Python (venv-tugas1)"
     ```
   - Buka file: `tugas1.ipynb`
   - Pilih kernel yang baru saja diftarkan: `Python Environments → Python (venv-tugas1)`

Mengapa menggunakan virtual environment?
- Memisahkan komponen antar proyek/tugas agar tidak konflik.
- Menjaga versi dependensi tetap konsisten.
- Melindungi instalasi Python utama dari perubahan.
- Memudahkan reproduksi dan kolaborasi proyek.
- Dapat dihapus tanpa memengaruhi sistem.

Jika menggunakan Google Colab:
- Setiap kali menyelesaikan tahapan pengerjaan tugas, lakukan `Save a copy to GitHub`
