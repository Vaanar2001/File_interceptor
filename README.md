# File_interceptor
This program will replace the download file of the target machine with your evil file.
but thos program will run only on websites which are http requested not on https requested.
how to use:
pip install netfilterqueue
edit the code by changing path of your evil file on line 20.
iptables -I FORWARD -j NFQUEUE --queue-num 0
now in other terminal 
python repalce_download.py
after you have completed your task 
iptables --flush
