# Mokerlink 8x 2.5G switch

Flash dump of the Mokerlink 2G080G 8x 2.5G switch.
The chip is a Macronix MX25L3233F 32mbit 3V NOR flash.

Dumping flash:
```
sudo apt install libusb-1.0-0-dev
git clone https://github.com/setarcos/ch341prog.git
cd ch341prog && make
./ch341prog -i
./ch341prog -r flash.bin
```