Step 1 : Before proceeding for installation , install the dependencies

    sudo apt install libssl-dev libpcap-dev
    sudo apt-get install libglib2.0-dev
    sudo apt-get install -y libgcrypt11-dev
    sudo apt-get install qt5-default
    sudo apt-get install qttools5-dev-tools

Step 2 : Download the source file fom their download page or use the below command and extract it

    wget https://1.na.dl.wireshark.org/src/wireshark-2.4.0.tar.xz
    tar xf wireshark-2.4.0.tar.xz 

Step 3 : Configure the source

    ./configure

Step 4 : Compile the wireshark

    make && make install
