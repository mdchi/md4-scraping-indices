#curso de beautifulsoup https://www.youtube.com/watch?v=yKi9-BfbfzQ
import os
from bs4 import BeautifulSoup
import requests
 
   
#11 tasa de interes futuros
soup11=BeautifulSoup(((requests.get('https://www.investing.com/central-banks/fed-rate-monitor')).text),"html.parser")
dato11=soup11.find_all('div',class_='fedRateCountdown')
dato11a=dato11[0].find_all('span')[0]
dato11a=dato11a.text[1]  #semanas
dato11b=dato11[0].find_all('span')[1]
dato11b=dato11b.text[1]  #dias


os.system("cls")
print(dato11a,"semanas y",dato11b,"dias")
