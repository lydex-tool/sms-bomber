Kurulum

---TERMUX---
apt update && apt upgrade
pkg install python
pkg install python3
git clone https://github.com/leydex-tool/sms-bomber
cd sms-bomber
pip install -r requirements.txt
python3 smsbomber.py

---KALI---
apt update && apt upgrade
apt-get install python
apt-get install python3
git clone https://github.com/lydex-tool/sms-bomber
cd sms-bomber
pip install -r requirements.txt
python3 smsbomber.py
