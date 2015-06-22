server
./tunnel.py -s 86 -l 10.1.2.1/24
Allocated interface t1

client
./tunnel.py -c 184.22.224.212,86,2012 -l 10.1.2.2/24
