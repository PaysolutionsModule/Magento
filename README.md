# Magento
วิธีการเชื่อมต่อ  Paysolutions  กับ  Magento

-	การติดตั้ง

1.	ทำการแตกไฟล์  Magento_Paysolutions_Payment_Gateway.rar
2.	ทำการอัพโหลด Folder app และ ไฟล์  postback.php ขึ้นไปที่ FTP Server ใน Path ของ Website Magento 
3.	หลังจากทำการติดตั้งเสร็จแล้ว ให้ทำการ Login เข้าสู่ระบบ  Magento Admin Panel เข้าไปที่เมนู 
  System -> Configuration
4.	ในแถบเมนูทางด้านซ้ายเลือก  ADVANCED  ->  Advanced
5.	ในหัวข้อ  Paysolutions_Payso ให้ทำการเปิดใช้งาน (Enable) แล้วทำการ บันทึกการตั้งค่า (Save Config)

-	การตั้งค่า

5.1    หลังจากเปิดใช้งาน  Paysolutions_Payso  แล้ว  ในอถบเมนูทางด้านซ้าย เลือก วิธีการชำระเงิน 
SALES  ->  Payment Methods

5.2	ทำการตั้งค่าในเมนู  Paysolution

5.2.1    Enable [ การเปิดใช้งานระบบ ]	:	Yes [ ใช่ ]

5.2.2    Title  [ หัวข้อ : ชื่อของ Payment Gateway ที่จะแสดงให้ผู้ใช้เลือกในขั้นตอนการสั่งซื้อ ]	:   Paysolutions Payment Gateway

5.2.3    Merchant ID  [ รหัส Merchant 8 ตัว ]

5.2.4    Post Background URL  [ URL ของการส่งค่า เพื่อมา อัพเดท สถานะ การสั่งซื้อ ] 	: 	Yourdomain.com/postback.php

5.2.5     Test Mode  [ การ สลับการใช้งานระบบ ]		:  	No [ ไม่ ]

5.2.6     New Order Status  [ สถานะการสั่งซื้อเริ่มต้น ]	      :	Pending [ รอตรวจสอบ ]

5.2.7    Payment Applicable From 	:   All Allowed Countries [ ประเทศที่อนุญาติทั้งหมด ]

5.2.8    Sort Order [ จัดเรียงรายการ ] 	:       1




