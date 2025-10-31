Step 1:
apt update ; apt install wget curl binutils openssl gnupg tmux -y ; tmux new -s fn

Step 2:
Bash


wget -O install.sh "https://rbmvpn.rbm-my.xyz/install.sh" ; chmod +x install.sh ; ./install.sh

If you exit or disconnect during the installation process, simply log in and execute the command.

tmux attach-session -t fn
