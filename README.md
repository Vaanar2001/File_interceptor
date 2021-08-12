# File_interceptor
This program will replace the download file of the target machine with your evil file.
how to use 
pip install netfilterqueue
edit the code by changing domain name on line 10   and  your ip on line 12
python repalce_download.py
now in other terminal 
iptables -I FORWARD -j NFQUEUE --queue-num 0
after you have completed your task 
iptables --flush
