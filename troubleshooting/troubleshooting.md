# การแก้ปัญหา

## **ก่อนอื่นเลย**

ตรวจสอบให้แน่ใจว่าคุณได้ติดตั้ง[ "ส่วนเสริม"](https://github.com/PreMiD/PreMiD/wiki/Installation#extension) และ ["แอปพลิเคชัน"](https://github.com/PreMiD/PreMiD/wiki/Installation#application) ไว้แล้ว วิธีการติดตั้งสามารถคลิกได้ [ที่นี่](https://github.com/PreMiD/PreMiD/wiki/Installation)  
วิธีที่เห็นข้างล่างนี้คุณจะทำตามมันเลยก็ได้ หรือทำวิธีต่างจากที่เราไม่ได้ใส่ไว้ก็ได้

## Discord ไม่แสดง Presences

### ตรวจสอบให้แน่ใจว่า Discord "ไม่ได้"ทำงานในสถานะ Administrator \(Run As Administrator\)

มันสำคัญมาก Discord RPC จะไม่ทำงานถ้าคุณเปิดการทำงาน Discord ในฐานะ Administrator                                               \(ไม่ได้อ่านผิดหรอก มันต้องไม่ Run as Administrator ถึงจะทำงานได้\)

### ตรวจสอบให้แน่ใจว่าคุณติดตั้ง PreMiD เวอร์ชันล่าสุดแล้ว!

**คุณสามารถตรวจสอบได้โดยคลิกขวาที่ PreMiD 'ตรวจสอบการอัพเดท' \(Check for updates\) ในทาสก์บาร์**  
แอปจะบอกให้คุณรู้ว่ามีอัปเดตใหม่มาให้ดาวน์โหลด! แล้วคุณไม่ต้องกังวลเรื่อง "ส่วนเสริม" ตัวส่วนเสริมจะอัปเดตให้อัตโนมัติเอง!

{% hint style="info" %}
เวอร์ชันสำหรับผู้พัฒนาและเวอร์ชันที่ไม่ได้ลงตามที่เราสอนไว้ มันจะไม่อัปเดตอัตโนมัติ!
{% endhint %}

![Windows Taskbar](https://github.com/PreMiD/PreMiD/raw/master/wiki/assets/CheckForUpdates.png)

### ตรวจสอบให้แน่ใจว่าคุณได้เปิด Discord Rich Presence ในตั้งค่าแล้ว

![Discord Game Activity](https://github.com/PreMiD/PreMiD/raw/master/wiki/assets/GameActivity.png)

### รีเฟรชเว็บเพจ

คุณสามารถกด **F5/Str+G** หรือ **CMD+R** บนคีย์บอร์ดของคุณแทนที่จะไปหาปุ่ม Refresh

### เริ่มต้นเบราว์เซอร์ใหม่อีกครั้ง

**Alt+F4** มันก็ทำงานได้เจ๋งเหมือนกันลองกดดูสิ \(มันชัดเจนเลยว่าคุณจำเป็นต้องเปิดเบราว์เซอร์ขึ้นมาใหม่\)

### ปิดการทำงานส่วนเสริมของคุณทั้งหมด

ลองปิดส่วนเสริมของคุณทั้งหมด\(ยกเว้น PreMiD\)แล้วลองดูว่ามันใช้งานได้ไหม  
ถ้าได้ ลองค่อย ๆ เปิดส่วนเสริมของคุณทีละตัวแล้วแจ้งเราว่าส่วนเสริมตัวไหนมันพังการทำงานของ PreMiD!

### เริ่มต้น PreMiD ใหม่อีกครั้ง \(แอปพลิเคชัน\)

![Windows Taskbar](https://github.com/PreMiD/PreMiD/raw/master/wiki/assets/Quit.png)

หลังจากคุณก็เปิด PreMiD ขึ้นมาใหม่

### เริ่มต้นหรือรีโหลด Discord ใหม่อีกครั้ง

กด **Strg+R** หรือ **CMD+R** บนคีย์บอร์ดของคุณหรือรีสตาร์ท Discord

### รีสตาร์ทคอมพิวเตอร์ของคุณ

ผมว่าคุณคงรู้ว่ารีสตาร์ทคอมพิวเตอร์มันทำยังไงนะ !

### ติดตั้ง PreMiD ใหม่อีกครั้ง

บางครั้งมันเกิดปัญหาที่ไฟล์ขณะติดตั้ง... ขั้นตอนการติดตั้งคลิก [ที่นี่](https://github.com/PreMiD/PreMiD/wiki/Installation).

### วิธีการลบแบบอัตโนมือ \(Manual\)

{% tabs %}
{% tab title="Windows" %}
1. ไปที่ `C:\Users\USER\AppData\Local` แล้วลบโฟลเดอร์ `premid`
2. ไปที่ `C:\Users\USER\AppData\Roaming` แล้วลบโฟลเดอร์ `PreMiD`
{% endtab %}

{% tab title="Mac OS" %}
ไปที่`YOURDISK:/users/USER/~Library/Application Support` แล้วลบโฟลเดอร์ `PreMiD`
{% endtab %}
{% endtabs %}

ถาม Staff ที่ [Discord ของเรา](https://discord.gg/WvfVZ8T) ถ้าขั้นตอนทั้งหมดใช้งานไม่ได้ผลเลย  
 ไปที่เว็บไซต์ [วิกิ](https://wiki.premid.app/) เพื่อดูวิธีแบบละเอียด

## วิธีเหล่านี้ไม่สามารถแก้ปัญหาได้

คุณสามารถ:

* ไปที่ [วิกิ](https://wiki.premid.app/)
* [แจ้งปัญหา](https://github.com/PreMiD/PreMiD/issues/new/choose)ที่ [GitHub](https://github.com/PreMiD/PreMiD)
* ถาม Staff ใน [\#support](https://discord.gg/WvfVZ8T) บน Discord ของเรา

  


