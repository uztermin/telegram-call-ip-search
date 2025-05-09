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
- Python yordamida venv muhiti yaratib olishingiz kerak:
```shell
python -m venv venv
cd venv
cd bin
source activate
cd ..
cd ..
```
- Endi kerakli kutubxonalarni install qilib olishingiz zarur:
```shell
pip install -r requirements.txt 
```
- yoki
```shell
pip3 install -r requirements.txt
```
- Va Kodni ishga tushrishingiz mumkin:
```shell
python linux-telegram-call.py
```

### [Windows versiyasi](./Windows-telegram-call)
- Avvalo windows uchun Wireshark ni o'rnatib olasiz :
https://www.wireshark.org/download.html

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
- Keyin kerakli kutubxonalarini install qilish mumkin:
```shell
pip3 install -r requirements.txt
```
- Va tayyor kodni ishga tushurishingiz mumkin:
```shell
python win-tg-call.py
```

## Mualliflik huquqi

Muallif: [uztermin](https://github.com/uztermin)  
Litsenziya: Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)

Barcha foydalanishda mualliflik huquqi saqlanadi va sizning foydalanishingizda yuqoridagi litsenziya matni ko‘rsatilishi kerak.
