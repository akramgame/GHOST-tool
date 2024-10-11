


#!/bin/bash
clear
echo "Hello Ghost "
figlet -f cosmic -c Ghost | lolcat




echo -e "1) apt update "
echo -e "2) nano Hacker.sh "
echo -e "3) htop "
echo -e "4) lsof -i "
echo -e "5) netdiscover "
echo -e "6) msfconsole "


while true; do
read -p "please Enetr Your Options > " tryag
if [[ $tryag -eq '1' ]]; then
echo -e "whait...!"
sleep2
apt update
elif [[ $tryag -eq '2' ]]; then
echo -e "whait...!"
sleep 2
nano Hacker.sh
elif [[ $tryag -eq '3' ]]; then
echo -e "whait...!"
sleep 2
htop
elif [[ $tryag -eq '4' ]]; then
echo -e "whait...!"
sleep 2
lsof -i
elif [[ $tryag -eq '5' ]]; then
echo -e "whait...!"
sleep 2
netdiscover
elif [[ $tryag -eq '6' ]]; then
echo -e "whait...!"
sleep 2elif [[ $tryag -eq '0' ]]; then
echo -e "whait...!"
sleep 2
exit
echo -e "...........................whait....................===================>
exit 0
else
echo "===========================================> weong options <==============>
fi
done


msfconsole

