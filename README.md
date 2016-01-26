# diawi-cli
A simple command line script to deploy Ad-Hoc iOS apps using diawi.com.

Usage: diawi-cli [-h] [-c COMMENT] [-e EMAIL] [-p PASSWORD] [-n] [-u] [-w]
                 filename

positional arguments:  
&nbsp;&nbsp;filename              The .ipa file to deploy.  

optional arguments:  
&nbsp;&nbsp;-h, --help &emsp;&emsp;           show this help message and exit  
&nbsp;&nbsp;-c COMMENT, --comment COMMENT&emsp;&emsp;Comment to display to the installer  
&nbsp;&nbsp;-e EMAIL, --email EMAIL&emsp;&emsp;Email to receive the deployed app link  
&nbsp;&nbsp;-p PASSWORD, --password PASSWORD&emsp;&emsp;Password for the deployed app  
&nbsp;&nbsp;-n, --notif&emsp;&emsp;           Notify when user installs application  
&nbsp;&nbsp;-u, --udid&emsp;&emsp;           Allow testers to find by UDID on Daiwi  
&nbsp;&nbsp;-w, --wall&emsp;&emsp;            List icon on Diawi 'Wall of Apps'  


Many of these features are currently untested.  Please let me know if something doesn't work as expected, or fix it and send a pull request.
