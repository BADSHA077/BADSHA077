- 👋 Hi, I’m @BADSHA077
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
BADSHA077/BADSHA077 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

import os

os.system(' clear ')



logo = '''


\x1b[1;92m
█ ▀█▀ █▀  
█ ░█░ ▄█  
\x1b[1;92m
           ▄▀█ █▀ █░█ █▀█ ▄▀█ █▀▀ █░█ █░░
           █▀█ ▄█ █▀█ █▀▄ █▀█ █▀░ █▄█ █▄▄
 
 
'''


def menu():
print( logo )
print(50*'\033[1;31m_')

print(' [1] -FACEBOOK-  ASHRAFUL ISLAM JOY ')
print(' [2] -WHATSAPP- ASHRAFUL ISLAM JOY ')
print(' [0] exit ') 

print(50*'\033[1;31m_')


JOY = input(' 🇧🇩 CHOICE THE OPTION 🇧🇩 ')

if JOY in['1','01']:
       os.system(' xdg-open https://www.facebook.com/ASHRAFUL.ISLAM.JOY.143 ')
  elif JOY('2','02'):
       os.system(' xdg-open https://wa.me/qr/LUDKEPJ4IOTIN1 ')
       
elif JOY('0','00'):
       os.system(' xdg-open ')
       
exit()

else:exit(' WORNG INPUT!! PLEASE CARECT THE RIGHT INPUT ')

menu()





