# User Manual - Simple Calculator

## Requirements
- Modern web browser (Chrome/Edge/Firefox)
- ไม่มี server required

## How to run locally
1. ดาวน์โหลดโฟลเดอร์ `Simple-Calculator`
2. เปิดไฟล์ index.html ด้วย browser (ดับเบิลคลิก หรือคลิกขวา -> Open with -> Browser)

## How to use
- กดตัวเลขเพื่อป้อนค่า
- กด + - × ÷ เพื่อเลือก operator
- กด . เพื่อใส่ทศนิยม
- กด = หรือ Enter เพื่อคำนวณ
- กด C เพื่อเคลียร์ทั้งหมด
- กด ⌫ (Backspace) เพื่อเอาตัวอักษรสุดท้ายออก
- รองรับการกดบนคีย์บอร์ด (0-9, + - * /, Enter, Backspace, Delete)

## Error handling
- หากพยายามหารด้วย 0 จะแสดงข้อความ "Error: Division by zero"
- หาก expression ไม่ถูกต้องจะแสดง "Error"

## Notes
- ผลลัพธ์ทศนิยมจะถูกปัดเพื่อหลีกเลี่ยงเลขยาวเกินไป (precision 12)