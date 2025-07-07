# Wi-Fi-Sharing-App
LAN(Wi-Fi or ethernet) sharing application easy , robust and secure
LANshare - File Sharing Application
====================================

This application allows you to share files over your local network.

HOW TO USE:
-----------

1. Run LANshare.exe
2. Choose your mode:
   - "Send" - Share files from your computer
   - "Download" - Download files from another computer
  
## Configuration Files ##

The application creates these files automatically:
- server_state.json - Saved shared files (Server mode)
- server_log.txt - Server activity logs
- client_config.json - Saved connection details (Client mode)

SEND MODE (Server):
------------------
- Click "Add..." to select files or folders to share
- The app will show your IP address and port (9999)
- Other users can connect to your IP:9999 to download files
- Your shared files and logs are automatically saved

DOWNLOAD MODE (Client):
----------------------
- Enter the server IP address and port (default: 9999)
- Click "Connect" to see available files
- Select files and click "Download Selected"
- Choose where to save the downloaded files
- Your last connection details are automatically saved

FEATURES:
---------
- Automatic file/folder structure preservation
- Progress tracking for downloads
- Persistent settings (remembers your files and connections)
- Simple and intuitive interface

REQUIREMENTS:
------------
- Windows 10/11
- Network connection
- No Python installation needed - everything is included!

FIRST TIME SETUP:
-----------------
1. Run LANshare.exe
2. Windows will ask: "Do you want to allow this app to communicate through Windows Firewall?"
3. Click "Allow" - this is required for network file sharing
4. The app will now work normally

TROUBLESHOOTING:
----------------
- If connection fails, check Windows Firewall settings
- Make sure both computers are on the same network
- Verify the IP address is correct
- Port 9999 must be accessible
- If firewall was denied, run as administrator and try again

For support or questions, please refer to the application logs. 
