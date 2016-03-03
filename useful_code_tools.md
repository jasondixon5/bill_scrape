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
