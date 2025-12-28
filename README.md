# spam-ngl
Tool berbasis Python yang jalan di terminal (Termux / Linux) buat ngirim pesan anonim ke akun NGL.
## ✨ Fitur
- Kirim pesan ke akun NGL
- Delay antar pesan bisa diatur
- Spam jalan otomatis (loop)
- Tampilan terminal berwarna
- Counter pesan + waktu realtime
- Bisa dihentikan kapan aja (CTRL + C)

## Platform yang Didukung
- Linux
- Termux (Android)

## 📸 Screenshots
![alt text](https://github.com/asta0x/spam-ngl/blob/main/images/main_menu.jpg?raw=true)

## 🚀 Instalasi
```bash
pkg update

pkg upgrade

pkg install python

pkg install python-cryptography -y

pkg install clang make openssl libffi

pip install pycryptodome

pkg install git

git clone https://github.com/asta0x/spam-ngl.git

cd spam-ngl

pip install requests colorama

python main.py
