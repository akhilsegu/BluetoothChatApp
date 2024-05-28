# **Bluetooth Chat App**

This project is an Android application that enables chat functionality between devices using Bluetooth. The app allows users to connect to nearby Bluetooth devices, send and receive messages, and manage Bluetooth connections.

## **Features**

- **Bluetooth Communication**: Connect and communicate with nearby Bluetooth devices.
- **Message Exchange**: Send and receive text messages between connected devices.
- **Connection Management**: Manage Bluetooth connections with ease.
- **Permission Handling**: Request and handle necessary permissions for Bluetooth and location services.

## **Permissions**

This app requires the following permissions:
- `BLUETOOTH`
- `BLUETOOTH_ADMIN`
- `BLUETOOTH_CONNECT`
- `ACCESS_FINE_LOCATION`

These permissions are necessary for Bluetooth communication and discovering nearby devices.

## **Usage**

1. **Enable Bluetooth**:
    - Ensure Bluetooth is enabled on your device. You can enable it through the app's menu.

2. **Connect to a Device**:
    - Use the "Search Devices" option in the menu to discover nearby Bluetooth devices.
    - Select a device to initiate a connection.

3. **Chat**:
    - Once connected, use the input field to type a message and press the "Send" button to send the message.
    - Received messages will be displayed in the chat list.

## **Code Structure**

- `MainActivity.java`: Handles the main user interface and Bluetooth management.
- `ChatUtils.java`: Manages Bluetooth connections, data transmission, and reception.
- `DeviceListActivity.java`: Lists available Bluetooth devices for connection.


