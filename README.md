<h1 align="center">SalamHunter</h1>
<p align="center">It is a useful project for developers that includes useful tools for Instagram</p>

![](https://img.shields.io/badge/salammzere3-orange?style=for-the-badge&logo=python.svg) 
<p align="center">
<a href="#"><img title="Made in IRQ" src="https://img.shields.io/badge/MADE%20IN-IRQ-red.svg?style=for-the-badge&logo=github"></a>

</p>
<p align="center">
<img alt="salammzere3' Github Stats" src="https://github-readme-stats.vercel.app/api?username=salammzere3&show_icons=true&include_all_commits=true&hide_border=true" />

</p>
<p align="center">
<a href="#"><img title="telegram Num" src="https://img.shields.io/badge/telegram%20Num-salammzere3-red.svg?style=for-the-badge&logo=telegram"></a>
</p>
<p align="center">
<a href="https://github.com/salammzere3/followers"><img title="Followers" src="https://img.shields.io/github/followers/salammzere3?color=blue&style=flat-square"></a>
</p>

## Installation :
```
pip install SalamHunter
```
### Login Usage

``` python
from SalamHunter import *

username = "<your email or phone or username>"
password ="<your password >"
SalamReq = salammzere3.Instalogin(str(username),str(password))

if SalamReq['status'] =='Success':
	print ("login successful")
	
elif SalamReq['status'] =='challenge_required':
	print("Error account is security")
elif SalamReq['status'] =='error_login':
	print("Error account is bad")

```
### Get Available Gmail

```python
from SalamHunter import *

email = "enter_email@gmail.com"
gmail = salammzere3.gmail(email)


if gmail['status'] == 'Success':
    print('available email:',email)

else:
    print('not found email:',email)
```
	
## Follow us on social media
[![Github](https://img.shields.io/badge/Githusalammzere3-orange?style=for-the-badge&logo=github)](https://github.com/salammzere3/)
[![Telegram](https://img.shields.io/badge/Telegram-T5B55-orange?style=for-the-badge&logo=Telegram)](https://t.me/T5B55)


