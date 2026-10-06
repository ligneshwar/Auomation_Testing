# Auomation_Testing
## 06-10-26 : 

1. **How do you automate filling out the Vinoth QA Academy demo form using Selenium WebDriver in Python, including entering text, selecting radio buttons and checkboxes, and handling form fields?**

# CODE : 

```PY
from selenium import webdriver
from selenium.webdriver.common.by import By
import time

driver = webdriver.Edge()

driver.get("https://vinothqaacademy.com/demo-site/")


time.sleep(5)
driver.find_element(By.NAME, "vfb-5").send_keys("LIGNESHWAR")

time.sleep(2)
driver.find_element(By.NAME, "vfb-7").send_keys("K")

time.sleep(2)
driver.find_element(By.ID, "vfb-31-1").click()

time.sleep(2)
driver.find_element(By.ID, "vfb-20-0").click()

time.sleep(2)
driver.find_element(By.ID, "vfb-20-4").click()

time.sleep(2)
driver.find_element(By.ID, "vfb-20-2").click()

time.sleep(2)
driver.find_element(By.ID, "vfb-13-address").send_keys("NO 291/1, CHINNAKOLTHUVANCHERRY")

time.sleep(2)
driver.find_element(By.ID, "vfb-13-address-2").send_keys("CHINNAKOLTHUVANCHERRY")

time.sleep(2)
driver.find_element(By.ID, "vfb-13-city").send_keys("Tiruvallur")

time.sleep(2)
driver.find_element(By.ID, "vfb-13-zip").send_keys("631203")

time.sleep(2)
driver.find_element(By.ID, "vfb-13-state").send_keys("TAMIL NADU")

time.sleep(2)
driver.find_element(By.ID, "vfb-14").send_keys("ligneshwar2006@gmail.com")

time.sleep(15)
```

### Output :

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0f6b4fbe-769f-4bc7-8099-d62f0e80e7d7" />
