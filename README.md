# Make
depend on libqrencode.so 

apt install libqrencode-dev

gcc -o qrcode qrcode.c -ldl

# Usage
./qrcode "test string"
