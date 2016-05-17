# Bluefence
A BlueProximity alternative written in python.

## Usage
- Use a MAC address, this does not need the device to be connected:

`python bluefence.py MAC_ADDR`

- Use the RSSI to check for distance and set a maximum distance:

`python bluefence.py -d 5 MAC_ADDR`

- Try using the verbose mode:

`python bluefence.py --verbose MAC_ADDR`

- Check the help for more help using:

`python bluefence.py --help`

## Functions
- Scan for devices with the MAC address
- Scan for a devices distance using the RSSI
- Execute a command if distance is too large

## Credits
- Blueproximity for the RSSI part
- Bluefence for the basis

## TODO
- List dependencies
- Create PKGBUILD
- Config load from /etc

## Copyright

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
