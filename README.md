# Articles

g01u00
g01



git clone https://github.com/g00u00/Articles.git

<или>

git init

git remote add origin git@github.com:g00u00/Articles.git

git pull origin main

</или>

cd Articles

su

root

apt install python3.8-venv

exit


python3 -m venv env

. env/bin/activate

pip install -r requirements.txt

python manage.py runserver 10.0.2.15:8000

admin admin admin

deactivate

iptables -t nat -A PREROUTING -i eth0 -p tcp --dport 80 -j REDIRECT --to-port 8000

-------------=

pip freeze > requirements.txt

pip install -r requirements.txt
