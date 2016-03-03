Import selenium:
```
from selenium import webdriver
```

Store browser object to call methods on it:
(note that this step will open the browser)
```
browser = webdriver.Chrome()
browser = webdriver.Firefox()
```

Open website in browser (e.g., gmail.com):
```
browser.get('https://www.gmail.com')
```
Find element identifying username field and store in variable
Send username and submit

```
box = browser.find_element_by_name('Email')
box.send_keys('jasondixonmail@gmail.com')
box.submit()
```
Use GetPass to prompt for secure password input
```
import getpass
pw = getpass.getpass('Enter pw: ')
>>>Enter pw: 
```
Find element identifying password field and store in variable
Send password and submit

pw = browser.find_element_by_name('Passwd')
pw.send_keys(pw)
pw.submit()
```
