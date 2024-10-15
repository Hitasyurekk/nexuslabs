# nexuslabs

Selamlar bugün birlikte nexus kurulumu yapacağız.

Yüksek bir sisteme ihtiyaç yok yanına eklentileri kurabilirsiniz.

## Giriş Paketleri yüklemek


sudo apt update && sudo apt upgrade -y

sudo apt install curl -y
sudo apt install iptables -y
sudo apt install build-essential -y
sudo apt install git -y
sudo apt install wget -y
sudo apt install lz4 -y
sudo apt install jq -y
sudo apt install make -y
sudo apt install gcc -y
sudo apt install nano -y
sudo apt install automake -y
sudo apt install autoconf -y
sudo apt install tmux -y
sudo apt install htop -y
sudo apt install nvme-cli -y
sudo apt install pkg-config -y
sudo apt install libssl-dev -y
sudo apt install libleveldb-dev -y
sudo apt install tar -y
sudo apt install clang -y
sudo apt install bsdmainutils -y
sudo apt install ncdu -y
sudo apt install unzip -y
sudo apt install libleveldb-dev -y

sudo curl https://sh.rustup.rs -sSf | sh

source $HOME/.cargo/env
export PATH="$HOME/.cargo/bin:$PATH"

rustup update

rustc --version


## Nexus kurulumuna giriş

screen -S nexus

sudo curl https://cli.nexus.xyz/install.sh | sh
