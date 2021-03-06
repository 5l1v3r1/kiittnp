# KiitTnp
A script that scraps the [kiittnp](http://kiittnp.in/tnp/usr/index.php) website for notices, downloads the latest ones and sends notifications to phone. (Only for KIIT University Students)

##Requirements:
  Python 2.7  
  Pip ( refer to this link if not installed - [https://pip.pypa.io/en/latest/installing/](https://pip.pypa.io/en/latest/installing/))  
  Modules : "mechanize", "beautifulsoup4", "requests", "lxml"   
  [IFTTT](https://ifttt.com/) Account  
  Download  "IF by IFTTT" app to your phone.

------------------------------------------------------------------------
  
##How-To:
  Go to [IFTTT](https://ifttt.com/), create an account.  
  Go to this link - [https://ifttt.com/recipes/458304-notice-notification](https://ifttt.com/recipes/458304-notice-notification).  
  Click on Connect then add.  
  Go to this link - [https://ifttt.com/maker/](https://ifttt.com/maker/)  
  Copy your key.  
  Download this repository.  
  Extract the zip file.  
  Open command prompt from the repository directory.  
  Type - `pip install -r requirements.txt`  (To install the required modules).  
    
  **>>_Windows users install "lxml" module from here -_ [LXML](https://pypi.python.org/packages/cb/b6/848494ec3987338fada4c33644300f43f038490bc34700ce4494d9c7baa0/lxml-3.5.0.win32-py2.7.exe)<<**  
  Then type - `python tnp.py` , or you can run the "tnp.py" script directly.   
  Provide the required details in your console.  
  Congrats ! , the script will run every 15 mins and check for new notices.  
  The downloaded notices are stored in "notices" sub-directory.  
  
  
###Note:
  The password input will be invisible to hide from bystanders.  
  The user id and password are stored in "creds.txt" file in encoded format(can't be deciphered by Human Eyes :P).  
  The latest notice number is stored in "notice.txt" file.  
  The script is made according to current design of the website, in case the design of the website changes , the script may or may not work , so modify accordingly.  
