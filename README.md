# GameSir T1d Driver
This work is the result of reverse enginnering the BLE protocol of GameSir T1d Bluetooth Controller for DJI Tello Drone. The goal is to provide a simple interface for receiving events from the controller.

## Technical Information
 - BLE CHARACTERISTIC UUID : `00008651-0000-1000-8000-00805f9b34fb`

## Data Format 
 -  Event Type : `data[0:2]`
 -  Analog Sticks : `data[2:7]`
 -  Triggers : `data[7:9]`
 -  Keys : `data[9:10]`
 -  Trigger State : `data[10:11]`
 -  DPad : `data[11:12]`
 -  Unknown : `data[12:14]`
 -  Unknown : `data[14:16]`
 -  Unknown : `data[16:18]`
 -  Event Number : `data[18:20]`
