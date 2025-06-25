# 🚀 วิธี Deploy Photo Viewer ไปยัง Custom Domain

## 📁 ไฟล์ที่ต้อง Upload:

```
your-website/
├── index.html          (3.8KB)
└── images/
    └── FONTNEWEDIT.jpg  (1MB)
```

## 🌟 Web Hosting ที่แนะนำ (ฟรี):

### 1. **GitHub Pages** (ฟรี)

- สร้าง GitHub Repository
- Upload ไฟล์ทั้งหมด
- เปิด GitHub Pages
- URL: `https://username.github.io/repo-name`

### 2. **Vercel** (ฟรี)

```bash
# ติดตั้ง Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

### 3. **Netlify** (ฟรี)

- ลาก Drop โฟลเดอร์ไปที่ netlify.com
- หรือใช้ Netlify CLI

### 4. **Firebase Hosting** (ฟรี)

```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```

## 🔧 การตั้งค่า Custom Domain:

### สำหรับ GitHub Pages:

1. ไปที่ Repository Settings
2. เลือก Pages
3. ใส่ Custom Domain: `yourdomain.com`
4. ตั้ง DNS Record:
   ```
   Type: CNAME
   Name: www
   Value: username.github.io
   ```

### สำหรับ Vercel:

1. ไปที่ Vercel Dashboard
2. เลือก Project → Settings → Domains
3. เพิ่ม Domain: `yourdomain.com`
4. ตั้ง DNS Record ตามที่แนะนำ

### สำหรับ Netlify:

1. ไปที่ Site Settings → Domain management
2. เพิ่ม Custom Domain
3. ตั้ง DNS Record:
   ```
   Type: CNAME
   Name: www
   Value: site-name.netlify.app
   ```

## 📱 ผลลัพธ์:

- **URL:** `https://yourdomain.com`
- **Speed:** เร็วกว่า ngrok
- **Uptime:** 99.9%
- **SSL:** มี HTTPS ให้อัตโนมัติ
- **Mobile:** เหมาะกับ iPhone ทุกรุ่น

## 💡 ข้อดี:

✅ ใช้ Domain ของตัวเอง
✅ ไม่มีค่าใช้จ่าย
✅ Loading เร็วกว่า
✅ ไม่ต้องเปิด Computer
✅ SSL Certificate ฟรี

## ⚡ Quick Start:

1. **สมัคร GitHub** (ถ้ายังไม่มี)
2. **สร้าง Repository** ชื่อ `photo-viewer`
3. **Upload ไฟล์** `index.html` และ `images/`
4. **เปิด GitHub Pages**
5. **ตั้งค่า Custom Domain**

คุณต้องการให้ช่วย deploy ไปที่ไหนเป็นพิเศษไหม?
