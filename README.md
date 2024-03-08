**Jalankan pada terminal/powershell**

# set environment menggunakan venv

cd myproject

python -m venv .venv

# Aktifkan Envoronment

**Windows command prompt**
.venv\Scripts\activate.bat

**Windows PowerShell**
.venv\Scripts\Activate.ps1

**macOS and Linux**
source .venv/bin/activate

# Run streamlit app

streamlit run dashboard.py **bila tidak bisa run >** python -m streamlit run dashboard.py 
