Note: Not working since Diawi2 was rolled out and I haven't had time to fix it.  Here's an alternative you should check out: https://github.com/BarryReid/another-diawi-cli

# diawi-cli
A simple command line script to deploy Ad-Hoc iOS apps using diawi.com.

## Usage
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

## Requirements

This script requires Python 2 with TLS v1.2 support.  This was added in Python 2.7.9, but the version of Python that ships with Mac OS X El Capital claims to be 2.7.10 and it does not support TLS v1.2.  The script will check to make sure it's supported and print out an error message if not; if it isn't you will need to upgrade your Python interpreter (or in the case of OS X, install the latest from source or Homebrew).

Tested on Mac OS X El Capitan using Python 2.7.11 installed from Homebrew.
