# LE202

# Github  
# Repo 
## Markdown
Markdown คือ ใช้สำหรับการจัด Format ของ Plain Text บน Document และแปลงเป็น HTML บนเว็บต่างๆและมีนามสกุลไฟล์เป็น .md
### Headings ใช้ # เมื่อต้องการสร้างหัวเรื่อง
### Styling text ใช้ _ หรือ * สำหรับการระบุการเน้นข้อความตัวหนา ตัวเอียง หรือขีดทับในช่องความคิดเห็นและไฟล์ .md
### Quoting 
1.Quoting text , 2.Quoting code
### Links ใช้ [] แสดงข้อความที่เราต้องการคู่กันกับการใส่ลิงก์ในวงเล็บ()เพื่อทำการลิงก์
1.Section links , 2.Relative links
### Images การแทรกรูปภาพของ Markdown จะใช้ Syntax และเพิ่มเครื่องหมาย ! และใช้สูตรเดียวกับลิงก์
### Lists มี 3 ประเภท เป็นตัวหน้าข้อความ เช่น 1.) -* 2.) 1.2.3. 3.) วรรคเป็นบรรทัด
1.Nested lists , 2.Task lists
### Mentioning people and teams ใช้เมื่อต้องการพูดถึงบุคคลหรือทีมบน GitHub โดยพิมพ์ @ บวกชื่อผู้ใช้หรือชื่อทีม
### Referencing issues and pull requests ใช้เมื่อต้องการแสดงรายการปัญหาที่แนะนำและดึงคำขอภายในที่เก็บโดยพิมพ์ #
### Referencing external resources # หากมีการกำหนดค่าการอ้างอิงลิงก์อัตโนมัติที่กำหนดเองสำหรับที่เก็บ การอ้างอิงไปยังทรัพยากรภายนอก
### Uploading assets คุณสามารถอัปโหลดเนื้อหา เช่น รูปภาพ โดยการลากและวาง เลือกจากเบราว์เซอร์ไฟล์ หรือวาง
### Using emoji ใช้แทรกอิโมจิได้
### Paragraphs ใช้สำหรับขึ้นบรรทัดใหม่
### Footnotes ใช้สำหรับการเพิ่มเชิงอรรถในเนื้อหาโดยใช้ไวยากรณ์วงเล็บ()
### Hiding context with comments ใช้ ! เนื้อหาจะไม่ปรากฎใน Markdown ที่แสดงผล
### Ignoring Markdown formatting ใช้ Github ละเว้นการจัดรูปแบบ Markdown ได้โดยใช้ \ ก่อนอักขระ Markdown
### Disabiling Markdown rendering ใช้สำหรับทุกไฟล์ Markdown สามารถคลิกด้านบนของไฟล์เพื่อปิดใช้งานการเรนเดอร์ Markdown และดูแหล่งที่มาของไฟล์แทน

## ทบทวนความรู้เกี่ยวกับ ESP-01 microcontroller
### 1.digital คือ การรวมอุปกรณ์ทางอิเล็กทรอนิกส์ 
### 2.voltage คือ แรงดันไฟฟ้าเป็นความแตกต่างในพลังงานศักย์ไฟฟ้าระหว่างจุดสองจุดต่อหน่วยประจุไฟฟ้า
### 3.computer คือ คอมพิวเตอร์เป็นเครื่องจักรแบบสั่งการได้ที่ออกแบบมาเพื่อดำเนินแก้ปัญหาได้อย่างง่าย
### 4.internet คือ อินเตอร์เน็ตจะมีการเชื่อมต่อระหว่างเครือข่ายหลายๆเครือข่ายกันทั่วโลก
### 5.program lang คือ ภาษาที่ออกแบบโครงสร้างขึ้นเพื่อใช้ในการเขียนคำสั่งให้คอมพิวเตอร์ทำงาน
### 6.platformio คือ สิ่งที่ช่วยให้เราสามารถพัฒนาโปรแกรมได้
### 7.iotset1 คือ เป็นตัวรันคำสั่ง บราวเซอร์ที่เราต้องการให้มันอ่านข้อมูลแล้วเรารู้ผล

## การทดลองบน ESP-01 จำนวน 6 การทดลองต่อไปนี้
### การเขียนโปรแกรมเพื่อรันบนไมโครคอนโทรเลอร์ การทำให้สัญาณออกไป โดยใช้คำสั่งรันโปรแกรมคือ pio run -t upload
### การเขียนโปรแกรมค้นหาไวไฟ ต้องมีไวไฟสำหรับอัปโหลดโปรแกรม และโปรแกรมที่เขียนจะทำงานด้วยไวไฟ
### การเขียนโปรแกรมเอ้าพุทสัญญาณดิจิทัล จะมี 0n/0ff ดีเรต่อกับ power bank
### การเขียนโปรแกรมอนพุธสัญญาณดิจิทัล เมื่อได้รับเซนเซอร์ไฟจะค้าง
### การเขียนโปรแกรมเชื่อมต่อไวไฟและเว็บเซอร์เวอร์ สร้างเซิฟเวอร์ผ่านไวไฟจะได้ตัวเดิม
### การเขียนโปรแกรมสร้างไวไฟแอคเซสพอยด์ สร้างไวไฟเองเพื่อความส่วนตัว
