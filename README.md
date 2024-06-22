# Aleo-Node
#cek vps
wget -qO- bench.sh | bash

#auto setup
wget -O aleo.sh https://raw.githubusercontent.com/Megumiiiiii/Aleo/main/aleo.sh && chmod +x aleo.sh && ./aleo.sh

#Untuk kembali, pakai command 
screen -Rd aleo

#Jika ingin uninstall Node
cd ~/snarkOS
rustup self uninstall

cd
rm -f aleo.sh
rm -rf snarkOS
