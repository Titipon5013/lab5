# lab5
- (2)
![image](https://github.com/user-attachments/assets/6e062ea6-12b2-4a13-ac87-bc073328cfdf)

- cd (folder name) (เข้าไปที่ directory ของ folder name)
- cd . (directory อยู่ที่เดิม home/time)
- cd .. (directory กลับไปที่ home)
- cd ~ (directory กลับไปที่ home/time)
- cd / (directory กลับไปที่เริ่มต้น /)
- cd $ (ไม่ได้ตั้ง variable ไว้เลยไม่ขึ้น)
- pwd (ระบุตำแหน่งของ directory)
- mkdir (name) (สร้าง folder)



- 3.1&3.2
  ![image](https://github.com/user-attachments/assets/c9a0f39e-7cd4-480e-83df-f5ff63c8ad94)


- 3.3
  
  ![image](https://github.com/user-attachments/assets/142e2449-1b10-40cd-a1e7-994519491833)

  - ls (ใช้เพื่อแสดงไฟล์ทั้งหมดภายใน folder หรือการใช่คำสั่ง list)
  - ls -alt:

  - -a: แสดงไฟล์ทั้งหมด รวมถึงไฟล์ซ่อน
  - -l: แสดงรายละเอียดไฟล์ (สิทธิ์, เจ้าของ, ขนาด, วันที่)
  - -t: เรียงลำดับตามวันที่แก้ไขล่าสุด (ใหม่สุดอยู่บนสุด)
  - ls แสดงรายการธรรมดา ส่วน ls -alt แสดงรายละเอียดไฟล์ทั้งหมด เรียงตามการแก้ไขล่าสุด.


- 3.4

  ![image](https://github.com/user-attachments/assets/6c196e44-f65b-47ae-87fb-810f07474cf1)

  - mv (เปลี่ยนชื่อไฟล์)

- 3.5

  ![image](https://github.com/user-attachments/assets/6b6d3f6c-4e2b-4a1d-831f-8479cd6db1d3)

  - ls -lh
  - แสดงรายการไฟล์/โฟลเดอร์ในรูปแบบอ่านง่าย 
  - ขนาดไฟล์แสดงเป็น KB, MB, GB แทนการใช้หน่วยเป็นไบต์
  - du -h 
  - แสดงขนาดพื้นที่ดิสก์ที่ไฟล์/โฟลเดอร์ใช้จริง 
  - ใช้ดูขนาดรวมของโฟลเดอร์ทั้งหมด
 

- 3.7-3.10

  ![image](https://github.com/user-attachments/assets/12ee6f3f-99e6-4798-882d-174aa42abd5f)
  
  ![image](https://github.com/user-attachments/assets/b8a176e0-7af4-486d-9f96-3083a7079e0d)

  - chmod 400 คือคำสั่งเปลี่ยนสิทธิ์การเข้าถึงไฟล์หรือโฟลเดอร์ในระบบ Unix/Linux โดยให้สิทธิ์เฉพาะผู้เป็นเจ้าของไฟล์ในการ อ่าน (read) ไฟล์เท่านั้น
  - rm (remove)

- 4.1

  ![image](https://github.com/user-attachments/assets/ecc136dd-846c-4f47-b548-4675f5a2be27)

  ![image](https://github.com/user-attachments/assets/d92543b7-b4c0-4401-9978-4eeed951edb2)

  - cat (ย่อมาจาก concatenate) เป็นคำสั่งในระบบ Unix/Linux ที่ใช้สำหรับจัดการไฟล์ข้อความ เช่น การดูเนื้อหาของไฟล์ รวมไฟล์ และสร้างไฟล์ใหม่


- 4.2
  
  ![image](https://github.com/user-attachments/assets/ffce123e-bcfd-4050-a1f5-9d8fddf5553f)

  - head และ tail เป็นคำสั่งในระบบ Unix/Linux ที่ใช้สำหรับดูเนื้อหาบางส่วนของไฟล์ข้อความ:

  - head ใช้แสดง บรรทัดแรกๆ ของไฟล์ (ค่าเริ่มต้นคือ 10 บรรทัดแรก)
  - tail ใช้แสดง บรรทัดท้ายๆ ของไฟล์ (ค่าเริ่มต้นคือ 10 บรรทัดท้าย)

- 4.3
  
  ![image](https://github.com/user-attachments/assets/04b47291-21c0-42cb-a3e6-19840074aba3)

  - wc (ย่อมาจาก Word Count) เป็นคำสั่งใน Unix/Linux ที่ใช้สำหรับนับข้อมูลในไฟล์ข้อความ เช่น บรรทัด (lines), คำ (words), และอักขระ (characters/bytes)
 
- 4.4
  
  ![image](https://github.com/user-attachments/assets/1667c9e4-acb8-4a57-93aa-582580d5a6ff)

  - -l คือเอาเฉพาะ line

- 5.2

  ![image](https://github.com/user-attachments/assets/c9f5f361-9fba-4cc3-967e-3a0aa76bd23c)

  - echo $PATH แสดงค่าของตัวแปร PATH ซึ่งเป็นรายการของไดเรกทอรีที่แยกด้วย : ที่ Shell จะค้นหาไฟล์คำสั่งหรือโปรแกรม
 
- 5.3

  ![image](https://github.com/user-attachments/assets/0d5687ed-fbec-42a1-9c3a-5c3de2754bfd)

  - man which
  - which: which ใช้สำหรับค้นหา absolute path ของคำสั่งหรือโปรแกรมที่อยู่ในระบบ โดยอ้างอิงจากตัวแปร PATH
 
- 5.4 & 5.5

  ![image](https://github.com/user-attachments/assets/d607a830-9507-426b-82d2-ce373eca1b4f)

  - which ls: ใช้ตรวจสอบว่าไฟล์คำสั่ง ls (list files) อยู่ใน directory
  - which man: ใช้ตรวจสอบว่าไฟล์คำสั่ง man (manual pages) อยู่ใน directory

- 6.1
  
  ![image](https://github.com/user-attachments/assets/6ab88c5e-e53f-40d0-88ca-b28ce8f38b24)

  - ifconfig คือคำสั่งในระบบปฏิบัติการ Linux หรือ Unix ที่ใช้สำหรับดูและปรับแต่งการตั้งค่าของเครือข่าย เช่น การแสดงข้อมูลของ IP address, network interfaces, หรือการตั้งค่าอื่นๆ ที่เกี่ยวข้องกับการเชื่อมต่อเครือข่าย.

- 6.2

  ![image](https://github.com/user-attachments/assets/b98f5b6c-073e-4728-8eea-ddb762288051)

  - nslookup www.google.com ใช้สำหรับตรวจสอบข้อมูล DNS (Domain Name System) ของโดเมน www.google.com โดยจะคืนค่า IP address ที่เชื่อมโยงกับโดเมนนั้น ๆ

- 6.3

  ![image](https://github.com/user-attachments/assets/88dd919d-848e-4b4c-b353-ece7b3033970)

  - ping www.google.com ใช้สำหรับทดสอบการเชื่อมต่อเครือข่ายระหว่างคอมพิวเตอร์ของคุณกับเซิร์ฟเวอร์ของ www.google.com โดยการส่งแพ็กเก็ตข้อมูลไปยังเซิร์ฟเวอร์นั้น และรอรับการตอบกลับ
  - ผลลัพธ์ของคำสั่ง ping จะบอกเวลาในการรับส่งข้อมูล (latency) หรือเวลาที่ใช้ในการส่งแพ็กเก็ตข้อมูลจากคอมพิวเตอร์ของคุณไปยังเซิร์ฟเวอร์และกลับมา


  ![image](https://github.com/user-attachments/assets/3248f30a-10ed-4a3b-9d38-0d185c0b2c16)

  - traceroute คือเครื่องมือที่ใช้ในการตรวจสอบเส้นทางการส่งข้อมูลระหว่างคอมพิวเตอร์ของคุณกับปลายทาง (เช่น เซิร์ฟเวอร์ หรือเว็บไซต์) โดยแสดงเส้นทางที่แพ็กเก็ตข้อมูลเดินทางผ่านในเครือข่าย

- 6.4
  
  ![image](https://github.com/user-attachments/assets/91c6d38b-542a-4931-8baf-e8dec7b219d6)

  - netstat -n ใช้ในการแสดงสถานะการเชื่อมต่อเครือข่ายบนเครื่องคอมพิวเตอร์ของคุณ โดยแสดงหมายเลข IP และพอร์ตที่เชื่อมต่ออยู่ในรูปแบบตัวเลข

- 7.1

   ![image](https://github.com/user-attachments/assets/b9727adf-8b32-451b-92da-538bb7fbdfd2)

  - top ในระบบปฏิบัติการ Linux ใช้สำหรับแสดงข้อมูลเกี่ยวกับกระบวนการ (processes) ที่กำลังทำงานอยู่ในระบบ โดยแสดงรายละเอียดของการใช้ทรัพยากรต่างๆ เช่น CPU, หน่วยความจำ (RAM), และการใช้งานของโปรเซสต่างๆ ในเวลาจริง

- 7.2

  ![image](https://github.com/user-attachments/assets/d4d6874c-c20a-473f-996b-7bf3848d1ebb)

  - htop คือเครื่องมือที่ใช้ในการแสดงข้อมูลเกี่ยวกับกระบวนการ (processes) ในระบบปฏิบัติการ Linux แบบกราฟิก (ตัวอักษร) ที่ดีกว่า top ในหลายๆ ด้าน เช่น ความสะดวกในการใช้งานและความสามารถในการโต้ตอบ

  
    
 
    

    

  
  





  

  



  
  
