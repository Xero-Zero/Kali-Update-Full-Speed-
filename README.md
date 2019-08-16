# Kali-Update-Full-Speed-

Open Terminal and type - leafpad /etc/resolv.conf
add this - nameserver 8.8.8.8
nameserver 8.8.4.4
save and exit

now open new terminal and type 
- leafpad /etc/apt/sources.list

add this - #Repositories : 

deb http://kali.cs.nctu.edu.tw/kali kali-rolling main contrib non-free 
deb-src http://kali.cs.nctu.edu.tw/kali kali-rolling main contrib non-free

now save and exit

Open new Terminal and type apt-get update && apt-get upgrade && apt-get dist-upgrade

press enter
now see this working 

#Credit Orginal Discover man
