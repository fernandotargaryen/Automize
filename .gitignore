from selenium import webdriver
from selenium.webdriver.chrome.service import Service
from selenium.webdriver.common.by import By
from selenium.webdriver.common.keys import Keys
import time

Service = Service(executable_path="chromedriver.exe")
driver = webdriver.Chrome(service=Service)

driver.get("https://google.com")

#input_element = driver.find_element(By.CLASS_NAME, "gLFyf")
input_element = driver.find_element(By.XPATH, '//*[@id="APjFqb"]')
input_element.send_keys("Google Tradutor"+ Keys.ENTER)
time.sleep(5)
input_element = driver.find_element(By.XPATH, '//*[@id="tw-source-text-ta"]')
input_element.send_keys("Hello friends" + Keys.ENTER)
time.sleep(100000)
