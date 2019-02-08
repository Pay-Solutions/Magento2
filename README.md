# PaySolutions
Pay Solutions Payment Gateway for Magento2

# API
https://paysolutions.asia/developer

<br>

Credit Card Number: 4311 1510 0999 9993 (Available for Demo Account Only)
<br>CVV: 180
<br>Expiry Data: 12/20
<br>Credit Card Issuer: United Overseas Bank (Thai) Public Company Limited
<p>
  
# How to Install
1. Download Paysolution Package file
2. แตกไฟล์ และ Copy ไฟล์ทั้งหมดไปไว้ในโฟลเดอร์  app\code 
3. ทำการล้างแคชระบบด้วยคำสั่ง
php bin/magento cache:flush

4. สั่งให้อัพเกรดระบบ
php bin/magento setup:upgrade

5. สั่งรวมโค้ดระบบ
php -d memory_limit=-1 bin/magento setup:di:compile

6. สั่งดีพลอยโค้ด
php -d memory_limit=-1 bin/magento setup:static-content:deploy en_US th_TH -f

7. สั่ง reindex ข้อมูล
php -d memory_limit=-1 bin/magento indexer:reindex

8. สั่งล้างแคชการแสดงผล
php bin/magento cache:clean

9. login เข้าไปตั้งค่า Config PaySolution Module ใน Payment Method 
    

