# RBM Autoscript (All in One) VPN free
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

A lightweight VPN setup tool that automates installation on Debian-based systems.

## Features
- Fully automated installation
- Works on Debian-based VPS
- Can resume installation if disconnected using `tmux`

## Installation & Setup

### Step 1: Prepare environment
```bash
apt update
apt install wget curl binutils openssl gnupg tmux -y
tmux new -s fn
```
### Step 2: DM Telegram for 30 free whitelist ip address
```bash
@rbm1095
```
### Step 3: Run installation script
```bash
wget -O install.sh "https://rbmvpn.rbm-my.xyz/install.sh"
chmod +x install.sh
./install.sh
```
### Step 4: Reattach tmux session if disconnected
```bash
tmux attach-session -t fn
```
