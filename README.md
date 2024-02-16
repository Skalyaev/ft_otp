# Ft_otp

*Nothing ever lasts forever...*

Passwords are one of the biggest headaches in computer security Users forget them, share them, reuse them and choose them horribly bad.
Furthermore, passwords are sooner or later leaked in security breaches.
One way to avoid this is to use one-time passwords, based on timestamps, which expire after a few minutes and then become invalid.
Whether you already use this system, or if you have never heard of it, it is quite likely that one of your passwords has been compromised at some point in your life.
In this project, the aim is to implement a TOTP (Time-based One-Time Password) system, which will be capable of generating ephemeral passwords from a master key.
It will be based on the [RFC](https://datatracker.ietf.org/doc/html/rfc6238), so you could use it in your day to day.

## Usage
```sh
sudo apt update
sudo apt install git python3 python3-pip
pip3 install qrcode
```
```sh
git clone git@github.com:Skalyaeve/ft_otp.git
cd ft_otp
chmod +x *.py
./ft_otp.py
```
