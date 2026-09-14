Teaching Media Hub
==================

โครงสร้าง
---------
index.html
media-list.js
media/
  example-media.html

วิธีเพิ่มสื่อใหม่
-----------------
1. นำไฟล์ HTML ไปใส่ในโฟลเดอร์ media/
   ตัวอย่าง:
   media/walking-bass.html

2. เปิด media-list.js แล้วเพิ่มรายการ:

{
  id: "walking-bass",
  title: "Walking Bass Visual Lab",
  file: "media/walking-bass.html",
  category: "Jazz",
  description: "สื่อสาธิตแนว Walking Bass",
  icon: "🎸"
}

3. Save แล้วเปิด index.html ผ่าน Web Server หรือ GitHub Pages

หมายเหตุ
--------
ถ้า HTML บางไฟล์มีระบบที่ป้องกันการทำงานภายใน iframe
สามารถใช้ปุ่ม "เปิดแท็บใหม่" ที่แถบด้านบนได้
