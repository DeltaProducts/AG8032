1. install 
	dpkg -i *.deb
which was installed into /broadcom dir

2. run 
for 32 prot mode
	cd /broadcom/ofdpa
	touch 32p.mode
	./launcher ofagentapp -t server_ip:6633 &
for 104 port mode
    cd /broadcom/ofdpa
    touch 104p.mode
    ./launcher ofagentapp -t server_ip:6633 &



