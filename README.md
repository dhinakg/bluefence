# Bluefence
A BlueProximity alternative written in python.

## Usage
Use a MAC address, this does not need the device to be connected

`python bluefence.py MAC_ADDR`

Use the RSSI to check for distance and set a maximum distance

`python bluefence.py -d 5 MAC_ADDR`

Try using the verbose mode:

`python bluefence.py --verbose MAC_ADDR`

Check the help for more help using

`python bluefence.py --help`

## Functions
- Scan for devices with the MAC address
- Scan for a devices distance using the RSSI
- Execute a command if distance is too large

### Credits
- Blueproximity for the RSSI part
- Bluefence for the basis
