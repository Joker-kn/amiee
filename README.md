
clear
figlet BKR GO  | lolcat
echo "====================================================

# nem  : Bgs
# Github  : https://github.com/Joker-kn
====================================================" | lolcat
sleep 1
echo " Pilih Nomornya : " | lolcat
echo " [1] SpamCall (SpamTelepon)" | lolcat
echo " [2] SpamSms (SpamSms)" | lolcat
echo " [3] SpamGmail" | lolcat
echo " [4] Spam Whatsapp" | lolcat
echo " Nomor  : " | lolcat
read nomor

if [ $nomor = 1 ] || [ $eue = 01 ]
then
clear
echo " Install SpamCall.. " | lolcat
sleep 1
pkg install php -y
git clone https://github.com/Joker-kn/Bkr1
cd Bkr1
php Scl.php
fi

if [ $nomor = 2 ] || [ $nomor = 02 ]
then
clear
echo " Install SpamSms.. " | lolcat
pkg  install php -y
git clone https://github.com/Joker-kn/Bkr2
cd Bkr2
php sas.php
fi

if [ $nomor = 3 ] || [ $nomor = 03 ]
then
clear
echo " install SpamGmail.." | lolcat
pkg install php -y
git clone https://github.com/Joker-kn/Bkr3
cd Bkr3
php Gmail.php
fi

if [ $nomor = 4 ] || [ $nomor = 04 ]
then
clear
echo " Install SpamWhatsapp.." | lolcat
pkg install php -y
git clone https://github.com/Joker-kn/Bkr4
cd Bkr4
php wa.php
fi




