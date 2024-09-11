An IP Scanner is a simple yet powerful tool that scans a given range of IP addresses . This project allows users to discover all active devices within a specified network range
Installation Instuctions:
copy the code from the project file from the repository i.e 'ip scanner' file and paste in text editor in pc and save the file with '.py extension. another option is you can download the file and save it the file with ".py" extension.
Change the start_ip and end_ip variables in the if __name__ == "__main__": block to match the range you want to scan. For example, if your local network is 192.168.1.x, you can use 192.168.1.1 to 192.168.1.255. Save the changes in file
To run the script, open Powershell in pc
Navigate to the directory where you saved ip_scanner.py file.
Run the script using the following command:
   python3  “ip_scanner.py”
The script will output the active IPs it finds in the specified range.
