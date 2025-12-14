# Android FTP Client–Server Application

## Overview
This project is an Android-based FTP Client–Server application that enables fast and secure file transfer between devices over a local Wi-Fi network. It eliminates the need for USB cables, internet connectivity, or third-party cloud services.

## Key Features
- Wireless file upload and download over LAN
- Android device acts as an FTP Server
- Supports multiple client connections
- High-speed transfer up to 75 Mbps on local Wi-Fi
- No internet connection required
- Simple and user-friendly interface

## Technology Stack
- Language: Kotlin
- Platform: Android
- Protocol: FTP
- Server Library: Apache FTPServer
- IDE: Android Studio

## Application Architecture
- Android device runs an embedded FTP Server
- FTP clients connect using IP address and port
- File operations handled in background services

## Performance
- Achieves up to 75 Mbps transfer speed over local Wi-Fi
- Significantly faster than Bluetooth and traditional USB MTP transfer

## How to Run
1. Clone the repository
2. Open the project in Android Studio
3. Build and run the app on an Android device
4. Connect client and server on the same Wi-Fi network
5. Transfer files using FTP credentials

## Use Cases
- Large file transfer between phone and PC
- Local network file sharing
- Offline data exchange

## Author
Darshan Bhade
