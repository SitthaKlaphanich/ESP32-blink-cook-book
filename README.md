# ESP32-blink-cook-book

## 1.ESP-IDF Example

เลือก blink หลังจากนั้นกด Create project

![image](https://github.com/user-attachments/assets/d3bc51ed-03b0-4e78-b9c9-d1dfb2c8f651)

## 2.แก้ไข File 

กำหนดขาให้ไฟ LED กระพริบ 

![image](https://github.com/user-attachments/assets/6829dae0-9e25-4fa7-872a-bcd26e20f899)

## 3.กำหนดตั้งค่า

ไปที่ ESP-IDF: SDK configuration editor (menuconfig) เพื่อตั้งค่าการใช้งานสำหรับโปรเจกต์ blink ตรวจสอบการตั้งค่าในส่วนที่เรียกว่า "Example Configuration" เพื่อกำหนดค่า GPIO 

![image](https://github.com/user-attachments/assets/0d68b2c6-12cc-40fa-bcc5-7e8414aecf4f)

หรือสามารถกำหนดขาเองได้ตามที่กำหนดได้ตามรูปภาพ

![image](https://github.com/user-attachments/assets/c4c18ad1-7e82-490c-9a02-27b15fe25529)


## 4.Build โปรเจค
 
ไฟ led ติดดับตามขาที่กำหนด

![image](https://github.com/user-attachments/assets/bac6aac8-f798-4eb9-8044-c088942cc30e)

![ae25a475-0e64-4592-8fb8-9f88327c33ba](https://github.com/user-attachments/assets/412bf173-2df6-40b0-860d-d1c7dadc817e)

## 5.สรุป

BLINK LED สามารถกำหนดเองผ่าน code หรือ ESP-IDF: SDK configuration editor ได้เพื่อให้ไฟ LED สามารถติดดับได้ตามที่กำหนด
