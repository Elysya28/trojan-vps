# trojan-vps
ini hanya menggunakan protokol trojan

# Direkomendasikan menggunakan Debian 12

  ```html
 apt update; apt install curl wget dnsutils gnupg tmux libssl-dev -y
 ```

  ```html
wget -O install.sh https://raw.githubusercontent.com/Elysya28/trojan-vps/main/install.sh; chmod +x install.sh; ./install.sh; sed -i 's/\r$//' /root/trojan-manager/*.sh; /root/trojan-manager/main.sh
 ```
