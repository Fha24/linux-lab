# narumoncli

My Tool does one thing, and one thing well.


# Installation

If you don't use `pipsi`, you're missing out.
Here are [installation instructions](https://github.com/mitsuhiko/pipsi#readme).

Simply run:

    $ pipsi install .


# Usage

To use it:

    $ narumoncli --help

## ขั้นตอนการใช้งานโปรเจคนี้
1. ทำการ clone https://github.com/Fha24/linux-lab.git มาก่อน
2. พอ clone เสร็จแล้ว ก็เข้าไปในโปรเจคที่ clone มา
3. สิ่งที่ต้องติดตั้งก่อนใช้งานก็จะมี 1. pip install --user cookiecutter
pip install --user virtualenv 2. pip install --user click requests Pillow  3. pip install --user .  4. sudo pip install BeautifulSoup4 
4. หลังจากที่ติดตั้งเสร็จหมดทุกอย่างแล้วก็รันโปรแกรม โดยการทำงานของโปรแกรมนี้คือ จะไปดึงรูปภาพของซีรี่ย์เรื่องที่เราต้องการหามาแสดงให้เราดู โดยเราเลือกใช้เว็บ http://www.kseries.co/ ในการทำโปรเจคส่งในครั้งนี้ ถ้าเราต้องการ รูปภาพของซีรี่ย์เรื่องใดเราก็ใส่ชื่อเรื่องลงไป โดยต้องใส่ชื่อเรื่องให้ถูกต้องด้วยภาพถึงจะโชว์ขึ้นมา
5. ตัวอย่างการรันโปรแกรมคือ พิมพ์ว่า narumoncli doctors 2 
**หมายเหตุ docters 2 นี้ เป็นที่อยู่ url http://www.kseries.co/doctors-2/  เราจะเอาชื่อเรื่องตรงนั้นมาเขียนลงไปเพื่อใช้ในการค้นหารูปภาพซีรี่ย์ในเรื่องที่เราต้องการ  และต้องเป็นซีรี่ย์จากเว็บนี้เท่านั้นถึงจะสามารถดึงภาพได้**
##ถือเป็นอันเสร็จสิ้นสำหรับโปรเจคในครั้งนี้แล้วค่ะ ขอบคุณค่ะ  
