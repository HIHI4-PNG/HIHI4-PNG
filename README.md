pkg update -y && pkg upgrade -y
pkg install git
pkg install python
pkg install pip
git clone https://github.com/M-logique/Atomic
cd Atomic
pip install -r requirements.txt
python main.py

