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

# Horaco ZX-SWTGW218AS 8x 2.5G + 1x SFP+ web managed switch
Flash chip: FM25Q16A 16mbit 3.3V

# Horaco LG-SWTG018AS 8x 2.5G + 1x SFP+ unmanaged switch
Flash chip: 25Q40M 4mbit 3.3V
UART port: device TX (square), GND, device RX, VCC. Connect using 57600 baud.

# Davuaz Da-K6402W
Flash chip: Boya Micro 25Q16BS 16mbit 3.3V

# Hasivo S1100P-8GT (RTL8373 + RTL8224 variant)
Flash chip: KH 25L3233F 32mbit 3.3V

# Sirivision SR-S25G2109FP 8x 2.5G + 1x SFP+ web managed switch with POE
Flash chip: GD 25Q16ESIG 16mbit 3.3V
