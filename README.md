credit : [picoCTF - The Numbers](https://play.picoctf.org/practice/challenge/68)

![image](https://github.com/user-attachments/assets/255404ea-631a-4c91-b306-29be6fb00b2e)

## Description
The [numbers](https://jupiter.challenges.picoctf.org/static/f209a32253affb6f547a585649ba4fda/the_numbers.png)... what do they mean?

## hint 
The flag is in the format PICOCTF{}

## Solution
เมื่อ Click Download รูปภาพมาดู 

<img width="387" alt="the_numbers (1)" src="https://github.com/user-attachments/assets/046c813a-c60a-486f-905d-c53b5511986a" />

จะเห็นได้ว่ามีตัวเลข ซึ่งนั่นคือ Flag ที่เราต้องการ พอสังเกตดูแล้วตัวเลขมันเหมือน Letter Number Cipher หรือรหัสตัวอักษรเป็นตัวเลข (หรือ A1Z26 เป็นการแทนที่ตัวอักษรแต่ละตัวด้วยตำแหน่งตัวเลข เช่น A=1 B=2 Z=26)

***
16 9 3 15 3 20 6 { 20 8 5 14 21 13 2 5 18 19 13 1 19 15 14 }
***
เราจะถอดรหัสเลขบนภาพ โดยการนำตัวเลขที่ให้มาในภาพ ไป Decode ด้วยรหัส A1Z26 จะได้ Flag 

แนะนำให้ใช้เว็บ CyberChef

![image](https://github.com/user-attachments/assets/d8a003b3-5a02-4ac2-aae8-d2e68e32233e)

เราก็จะหา Flag เจอแล้ว!
