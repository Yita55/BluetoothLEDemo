# BluetoothLEDemo
Implement iOS app to demo Bluetooth Low Energy connect(interworking) to QCA402X BLE.

· CBCentralManager: 藍牙的控制中心，此類別主要用於對外部設備進行搜尋、發現以及連接。
· CBPeripheral: 此類別代表每一個外圍藍牙設備對應一個CBPeripheral對象，通過對應的外圍藍牙設備獲取RSSI值、發送數據以及讀取數據，且外圍設備由通用唯一標識符(UUID)表示為NSUUID對象，可能包含一項或多項服務。
