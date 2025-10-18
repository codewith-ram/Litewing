# esp-drone andriod Joystick

The esp-drone PC client is a fork of the [Crazyflie PC client](./ORIGIN_README.md). The communication with esp-drone and the implementation of the CRTP protocol to control the esp-drone is handled by the modified [cflib]([https://github.com/leeebo/crazyflie-lib-python](https://github.com/codewith-ram/Litewing.git))

## cflib
The client requires the folked [cflib]([https://github.com/leeebo/crazyflie-lib-python](https://github.com/codewith-ram/Litewing.git)).
If you want to develop with the lib too, follow the cflib readme to install it.

## Installation

Clone repository:
```bash
git clone https://github.com/codewith-ram/Litewing.git
cd crazyflie-clients-python
```
Install the client from source:
```bash
pip3 install -e .
```
## Run

```bash
cfclient
```



