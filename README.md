آموزش نصب ربات 

ابتدا در ترمینال کد های زیر را وارد کنید

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev ppa-purge python3-pip python3-dev
sudo pip3 install redis
sudo service redis-server restart
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade
sudo ppa-purge

از سرور خارج شده و مجدد وارد میشوید و کد های نصب ربات را میزنید

git clone https://github.com/hoseinmohseni/SezarTG && cd SezarTG && chmod +x sezar.sh && ./sezar.sh install && ./sezar.sh

شماره ربات را درج میکنید 
سپس آیدی ربات و خود را در فایل های bot ، تولز و کانفیگ قرار میدهید.
یکبار از سرور خارج شده مجدد وارد میشود و دستورات زیر را وارد میکنید
cd SezarTG
screen ./sezar.sh

ربات شما راه اندازی میشود
