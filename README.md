# control network
# r00_Hx
This script is designed for network monitoring and signalling about error  in the network.
For convenieence, there is a timer that scan the network again.
To reduce the network bandwidth load, the script sends a signal packet.
There is aslo a detailed collection of logs about each event, up to a second, the log is devided into two files, success and failur, the are stored in a folder with the date of scan.
Logs are deleted automatically, every day. In order to keep the logs permanently, it is necessary to comment out a line - func_remove_time.
The host files records the required IP addresses for the scan.
# For questions, contact us at axmetret@gmail.com
