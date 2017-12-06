# nancyandallisonsproject
MIDI iOS Project using PSoC BLE and Garageband
The purpose of this project was to use the PSoC Creator software, the PSoC 4 BLE Pioneer kit, and the Garageband app to simulate a MIDI controller using the Capsense touch. 
The BLE Pioneer Kit acted as a iOS MIDI controller using Garageband's MIDI over BLE protocol.
We simulated a MIDI connection to iOS, which then sends MIDI events generated from the CapSense sensor on the PSoC 4 Bluetooth Low Energy Pioneer Kit powered from either the coin cell battery, or by the USB connected to the computer.
Once the program is loaded into the board, the iOS device will recognize the “midi controller” through a bluetooth connection provided by the board, through the garageband app. Once the connection is established, the Capsense slider will send the information over to the BLE.
