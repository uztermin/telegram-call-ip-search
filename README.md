# Telegram Call IP Finder

Ushbu loyiha Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0) litsenziyasi ostida tarqatiladi. 

Bu loyiha Telegram qo'ng'iroqlarini STUN IP manzillarini aniqlab, ularni geolokatsiya qilish imkonini beradi.

## Platformaga(OS) ga qarab  Foydalaning :

Siz bu loyihani quyidagi holatlarda ishlatishingiz mumkin:
- Dasturdan foydalanish (ko‘rish, ishlatish).
- Dasturda o‘zgartirishlar kiritish taqiqlanadi.

### [Linux versiyasi](./Linux-telegram-call)
- Terminalda :
- Avval clone qilib oling git bilan:
```shell
sudo apt install git
git clone https://github.com/uztermin/telegram-call-ip-search.git
```
![image alt](https://github.com/uztermin/telegram-call-ip-search/blob/666981c188d5d45ab601b6dd405a8c786e9283dc/Screenshot%20From%202025-05-09%2004-52-46.png)




- Keyin shu Directory ga o'tib olasiz:
```shell
cd telegram-call-ip-search
cd Linux-telegram-call
```
![image alt](https://github.com/uztermin/telegram-call-ip-search/blob/4a0f515bb51bea7d22e57c128bda184109b2aa1b/Screenshot%20From%202025-05-09%2004-50-52.png)




- Python yordamida venv muhiti yaratib olishingiz kerak:
```shell
python -m venv venv
cd venv
cd bin
source activate
cd ..
cd ..
```
![image alt](https://github.com/uztermin/telegram-call-ip-search/blob/b2368456d2cc22c776ca6e6dd897a37844eb3051/Screenshot%20From%202025-05-09%2004-55-42.png)





- Endi kerakli kutubxonalarni install qilib olishingiz zarur:
```shell
pip install -r requirements.txt 
```
- yoki
```shell
pip3 install -r requirements.txt
```
![image alt](https://github.com/uztermin/telegram-call-ip-search/blob/f29bd0dc1e27b47b9d4cbce9fe8d500a65a22060/Screenshot%20From%202025-05-09%2004-56-42.png)




- Va Kodni ishga tushrishingiz mumkin:
```shell
python linux-telegram-call.py
```
![image alt](https://github.com/uztermin/telegram-call-ip-search/blob/7c4cbda6d9e9a5dbdbf670c61d33ac3023071d18/Screenshot%20From%202025-05-09%2004-57-49.png)





### [Windows versiyasi](./Windows-telegram-call)
- Avvalo windows uchun Wireshark ni o'rnatib olasiz :
https://www.wireshark.org/download.html

![image](https://github.com/uztermin/telegram-call-ip-search/blob/29cca875fbe6fd3accbae1f3b92c21179e1aef0e/photo_2025-05-09_07-15-17.jpg)





- Windows uchun versiyani git clone qilib yoki zip faylini yuklab olib zipdan ochib ishlatishingiz maqsadga muvofiq bo'ladi.!!!

- CMD  da zipdan ochgan  Windows-telegram-call faylining direktoriyasiga o'tib oling.
```shell
cd  telegram-call-ip-search
cd Windows-telegram-call
```
- Python kutubxonalari uchun venv muhit yaratishingiz kerak:
```shell
python -m venv venv
cd venv\Scripts
activate
cd ..
cd ..
```
![image alt](https://github.com/uztermin/telegram-call-ip-search/blob/755e82545f95ede7ffab83c739fe8b30fc22c457/photo_2025-05-09_07-14-44.jpg)




- Keyin kerakli kutubxonalarini install qilish mumkin:
```shell
pip3 install -r requirements.txt
```
![image alt](https://github.com/uztermin/telegram-call-ip-search/blob/f24751f3db1829fbcf6dfae2c96311e7c1ed40ee/photo_2025-05-09_07-15-07.jpg)




- Va tayyor kodni ishga tushurishingiz mumkin:
```shell
python win-tg-call.py
```

## Mualliflik huquqi

Muallif: [uztermin](https://github.com/uztermin)  
Litsenziya: Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)

Barcha foydalanishda mualliflik huquqi saqlanadi va sizning foydalanishingizda yuqoridagi litsenziya matni ko‘rsatilishi kerak.
