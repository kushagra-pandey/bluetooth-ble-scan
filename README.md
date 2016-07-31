# bluetooth-ble-scan
Scan for Bluetooth and BLE devices using Raspberry Pi and a Bluetooth Dongle



This code will scan for ble and bluetooth devices using the Raspberry Pi. It was originally intended to scan for beacons, 
so if you want to do that you must modify the dictionary to link the Mac Address of the beacon to the beacon number.

The bluetooth scanner is for reference. For example, you can write a program in a database to pinpoint the Raspberry Pi's location based on
the beacons it scans and the the bluetooth devices it picks up. NOTE: This program will not do that for you. It will just scan the devices.


To run it, type in:
python /path/to/blescan.py &
python /path/to/bluetooth.py &
