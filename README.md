# ITE-439 Labs

วิชา ITE-439 Mobile Application Development (Flutter) · ภาคเรียนที่ 2/2569

## ข้อมูลผู้เรียน

- **ชื่อ-สกุล**:
- **รหัสนักศึกษา**:
- **GitHub username**:

## รายการ Lab

ทำงานแต่ละ Lab ในโฟลเดอร์ของ Lab นั้นเท่านั้น (Lab ใหม่ให้สร้างโฟลเดอร์ใหม่ เช่น `L02`) และแก้ช่องสถานะเมื่อส่งแล้ว

| Lab | สัปดาห์ (ตามตารางเรียน) | หัวข้อ | โฟลเดอร์ | สถานะ |
| --- | --- | --- | --- | --- |
| L01 | 1 | ติดตั้งเครื่องมือและ Dart พื้นฐาน | [L01](L01/) | ยังไม่ส่ง |
| L02 | 2 | Dart OOP และ async | L02 | ยังไม่ส่ง |
| L03 | 4 | Widget และ layout | L03 | ยังไม่ส่ง |
| L04 | 5 | Form และ validation | L04 | ยังไม่ส่ง |
| L05 | 7 | List, model และค้นหา | L05 | ยังไม่ส่ง |
| L06 | 8 | Navigation และข้อมูลข้ามหน้า | L06 | ยังไม่ส่ง |
| L07 | 10 | State management | L07 | ยังไม่ส่ง |
| L08 | 11 | อ่าน REST API | L08 | ยังไม่ส่ง |
| L09 | 12 | JSON, Service และ CRUD | L09 | ยังไม่ส่ง |
| L10 | 13 | Local storage | L10 | ยังไม่ส่ง |
| L11 | 15 | Firebase Authentication | L11 | ยังไม่ส่ง |
| L12 | 16 | Firestore, สิทธิ์ และ APK | L12 | ยังไม่ส่ง |

## วิธีส่ง Lab ทุกครั้ง

1. ทำงานในโฟลเดอร์ของ Lab นั้น แล้วกรอก `README.md` ของ Lab ให้ครบ
2. ส่งขึ้น GitHub จากโฟลเดอร์นอกสุดของ repo:

   ```bash
   git add .
   git commit -m "L01: ทำข้อ 1-2 เสร็จ"
   git push
   ```

3. ส่งลิงก์ในไฟล์ **Excel ส่ง Lab** (Teams › ช่อง General › แท็บ "ส่ง Lab"):
   - ทุก Lab เพิ่ม 1 แถว: วันที่ · รหัสนักศึกษา · **GitHub username** (ใส่แค่ username เช่น `somchai-dev`) · เลือก Lab · วาง**ลิงก์ commit ล่าสุด**ของ Lab
   - ตัวอย่างลิงก์ commit: `https://github.com/somchai-dev/ite439-labs-6512345678/commit/a1b2c3d` (คัดลอกจากแถบที่อยู่ของเบราว์เซอร์ ไม่ใช่ลิงก์ที่ลงท้าย `.git`)
   - ไม่ต้องลงทะเบียน Repo
   - ช่องตรวจลิงก์ต้องขึ้น ✓ ถูกต้อง · **ไม่ต้องส่งใน Teams Assignments**

## กติกา

- repo ต้องเป็น **Public** อาจารย์จึงเปิดดูได้
- commit บ่อยๆ อย่างน้อย 3 ครั้งต่อ Lab ข้อความต้องบอกว่าทำอะไร (`update` หรือ `final` ไม่นับ) อาจารย์ดู commit history ตอนตรวจ
- ห้าม commit รหัสผ่าน token หรือ API key ลงใน repo
