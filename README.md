# Download videos from Linux Academy / LinuxAcademy-DL

###### Python script to download videos from your LinuxAcademy account for offline viewing
#
#
### Requirements
- Python 3.5 and above
- BeautifulSoup - https://pypi.org/project/beautifulsoup4/
- html5lib - https://pypi.org/project/html5lib/
- Selenium - https://pypi.org/project/selenium/
- ChromeDriver - http://chromedriver.chromium.org/
- youtube_dl - https://pypi.org/project/youtube_dl/
- cookies.txt - https://chrome.google.com/webstore/detail/cookiestxt/njabckikapfpffapmjgojcnbfjonfjfg?hl=en

### Usage

> Clone the repo

> Download all the programs from the links above.
> If you face any issue with SSL error, then go to /Applications/Python 3.7 and then Install certificate from below command
"./Install Certificates.command"
> You might need to check your browser version and dowload same for chromedriver.


cd to the cloned directory, Get the cookies of your video playlist, like : Open the course "https://linuxacademy.com/cp/modules/view/id/266" , download cookies.txt and put it in root folder of your cloned repo. 
Command to use:

python3 driver.py Username Password https://linuxacademy.com/cp/modules/view/id/266

