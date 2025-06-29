# 📸 วิธีการใส่รูปใน ThaiID App

## รูปที่ต้องใส่:

### 1. **profile.jpg** - รูปโปรไฟล์

- **ขนาด:** 50x50 pixels
- **รูปแบบ:** .jpg, .png, .webp
- **คำอธิบาย:** รูปโปรไฟล์ที่แสดงด้านบนซ้าย

### 2. **id-photo.jpg** - รูปบัตรประชาชน

- **ขนาด:** 100x120 pixels (อัตราส่วน 4:5)
- **รูปแบบ:** .jpg, .png
- **คำอธิบาย:** รูปที่แสดงบนบัตรประชาชน

### 3. **gov-logo.png** - โลโก้ราชการ

- **ขนาด:** 40x40 pixels
- **รูปแบบ:** .png (แนะนำ)
- **คำอธิบาย:** โลโก้ราชการที่แสดงบนบัตร

## 📋 วิธีการใส่รูป:

1. **วางไฟล์รูป** ในโฟลเดอร์ `images/` นี้
2. **ตั้งชื่อไฟล์** ให้ตรงตามที่ระบุ
3. **รีเฟรช** หน้าเว็บ
4. หากไม่มีรูป จะแสดง placeholder แทน

## 🔧 การปรับแต่ง:

หากต้องการเปลี่ยนชื่อไฟล์ สามารถแก้ใน `index.html`:

```html
<!-- ตัวอย่าง -->
<img src="images/my-photo.jpg" alt="Profile" />
```

## 💡 เทคนิคเพิ่มเติม:

- **Base64:** แปลงรูปเป็น Base64 แล้วใส่ในโค้ด
- **Online URL:** ใช้ลิงก์รูปจากเว็บอื่น
- **Drag & Drop:** สร้าง feature อัปโหลดรูป
