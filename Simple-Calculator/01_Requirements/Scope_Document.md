# Scope Document: Simple Calculator

## Project Name
Simple Calculator

## 1.1 วัตถุประสงค์หลักของระบบ (Project Objective)
สร้างเครื่องคิดเลขพื้นฐานที่รันบนเว็บ (Single Page Web App) เพื่อให้ผู้ใช้สามารถทำการคำนวณพื้นฐาน ได้แก่ บวก (+), ลบ (-), คูณ (*), หาร (/) ได้อย่างถูกต้องและปลอดภัย (เช่น จัดการกรณีหารด้วยศูนย์) พร้อม UI ที่ใช้งานง่ายสำหรับการกดปุ่มและการใช้งานด้วยคีย์บอร์ด

## 1.2 ขอบเขตการทำงาน (Scope Definition) 
เพื่อป้องกัน Scope Creep และให้งานสำเร็จตามเป้าหมาย  ขอบเขตการทำงานถูกกำหนดดังนี้:

## In-scope
- การรับ input ผ่านปุ่มบนหน้าจอและคีย์บอร์ด
- การคำนวณ Operation พื้นฐาน: +, -, ×, ÷
- การรองรับจำนวนเต็มและทศนิยม
- ปุ่ม Clear (C), Backspace (⌫), Equals (=)
- การแสดงผลการคำนวณแบบเรียลไทม์ (แสดง expression ปัจจุบันและผลเมื่อกด =)
- การจัดการข้อผิดพลาดพื้นฐาน (เช่น หารด้วยศูนย์, input ไม่ถูกต้อง)
- Responsive layout พื้นฐานสำหรับ desktop และ mobile

## Out-of-scope
- การคำนวณที่ซับซ้อน (เช่น trigonometry, exponent, log)
- ประวัติการคำนวณ (history) หรือเก็บข้อมูล
- การทำเครื่องคิดเลขแบบ scientific functions
- ระบบ login หรือ multi-user
- การเชื่อมต่อ backend หรือฐานข้อมูล

## Non-functional Requirements
- หน้าโหลดเร็ว (< 2s ในเครือข่ายปกติ)
- รองรับ modern browsers (Chrome, Edge, Firefox)
- โค้ดอ่านง่ายและมี README อธิบายการรัน
