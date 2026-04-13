termux-setup-storage && \
pkg update -y && pkg upgrade -y && \
pkg install python python-pip git clang make libjpeg-turbo zlib -y && \
pip install pycryptodome qrcode pillow pyinstaller
