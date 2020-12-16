# SunScreen
![Logo](https://speartiplogo.s3.amazonaws.com/sunblock.png)

SunScreen is a tool that attempts to detect systems that are vulnerable to SunBurst, or that have been exploited by SunBurst.

## Usage

Download the latest copy of SunScreen: (https://github.com/SpearTip-Cyber-Counterintelligence/SunScreen/files/5705753/SunScreen.SPF.10.exe.zip)

Move the latest copy of SunScreen to your Desktop, and double click the application.

SunScreen will then begin scanning the system, outputting notifications in the bottom right hand corner of the Desktop.
![Logo](https://speartiplogo.s3.amazonaws.com/begin_Scan.png)
![notvuln](https://speartiplogo.s3.amazonaws.com/notvuln.png)
![vulnicon](https://speartiplogo.s3.amazonaws.com/vulnerable.png)
![ScanComplete](https://speartiplogo.s3.amazonaws.com/complete.png)

When it is complete, a text file titled SolarWinds_Info.txt will appear on the Desktop, providing you with further information.

If SunScreen locates the Orion.Core.BusinessLayer.dll, you need to assume your system has been compromised. 

As SpearTip discovered more Indicators of Compromise, SunScreen will recieve updates to reflect them.


## Contributing
Requests are welcome. Please open up an issue.
## License
[MIT](https://choosealicense.com/licenses/mit/)
