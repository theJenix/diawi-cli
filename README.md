# diawi-cli
A simple command line script to deploy Ad-Hoc iOS apps using diawi.com.

Usage: diawi-cli [-h] [-c COMMENT] [-e EMAIL] [-p PASSWORD] [-n] [-u] [-w]
                 filename

positional arguments:
  filename              The .ipa file to deploy.

optional arguments:
  -h, --help            show this help message and exit
  -c COMMENT, --comment COMMENT
                        Comment to display to the installer
  -e EMAIL, --email EMAIL
                        Email to receive the deployed app link
  -p PASSWORD, --password PASSWORD
                        Password for the deployed app
  -n, --notif           Notify when user installs application
  -u, --udid            Allow testers to find by UDID on Daiwi
  -w, --wall            List icon on Diawi 'Wall of Apps'


Many of these features are currently untested.  Please let me know if something doesn't work as expected, or fix it and send a pull request.
