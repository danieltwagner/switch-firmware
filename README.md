# Mokerlink 2G080G 8x 2.5G unmanaged switch
Flash chip: Macronix MX25L3233F 32mbit 3.3V NOR

# Mokerlink 2G080GM 8x 2.5G web managed switch
Flash chip: FM25Q128 128mbit 3.3V

Dumping flash:
```
sudo apt install libusb-1.0-0-dev
git clone https://github.com/setarcos/ch341prog.git
cd ch341prog && make
./ch341prog -i
./ch341prog -r flash.bin
```