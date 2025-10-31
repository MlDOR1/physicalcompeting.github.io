# 📄 คู่มือด่วน - หน้าโปสเตอร์

## 🎯 วิธีใช้ง่ายๆ ใน 3 ขั้นตอน

### ขั้นตอนที่ 1: เตรียมไฟล์โปสเตอร์
บันทึกโปสเตอร์ A1 ของคุณเป็น:
- **JPG** หรือ **PNG** (แนะนำ ⭐)
- หรือ **PDF**

### ขั้นตอนที่ 2: วางไฟล์ในโฟลเดอร์
```
project/
└── images/
    └── poster-a1.jpg  ← วางไฟล์ตรงนี้
```

### ขั้นตอนที่ 3: แก้ไขโค้ด
เปิดไฟล์ `poster.html` ด้วย Text Editor

**หาบรรทัดนี้ (ประมาณบรรทัด 105-106):**
```html
<!-- Method 1: Use an image file -->
<!-- <img src="images/poster-a1.jpg" alt="Project Poster" class="poster-image"> -->
```

**ลบ `<!--` และ `-->` ออก:**
```html
<!-- Method 1: Use an image file -->
<img src="images/poster-a1.jpg" alt="Project Poster" class="poster-image">
```

**หาบรรทัดนี้ (ประมาณบรรทัด 111):**
```html
<!-- Placeholder - Remove this when you add your actual content -->
<div class="poster-placeholder">
```

**เพิ่ม `<!--` ข้างหน้า และ `-->` ข้างหลัง (หรือลบทิ้งเลย):**
```html
<!-- Placeholder - Remove this when you add your actual content
<div class="poster-placeholder">
    ...ทั้งหมดจนถึง...
</div>
-->
```

---

## ✅ เสร็จแล้ว!

เปิดไฟล์ `poster.html` ด้วยเบราเซอร์ → โปสเตอร์ของคุณจะแสดงผล!

---

## 🎮 วิธีใช้งาน

### ปุ่มลัด:
- กด **F** = เข้า/ออก Fullscreen
- กด **ESC** = ออกจาก Fullscreen

### ปุ่มบนจอ:
- ปุ่ม **⛶** มุมล่างขวา = Toggle Fullscreen

---

## 🔧 แก้ปัญหาเร็ว

### โปสเตอร์ไม่แสดง?
1. เช็คว่าไฟล์ชื่อ `poster-a1.jpg` อยู่ในโฟลเดอร์ `images/`
2. ลบ `<!--` และ `-->` หรือยัง?
3. Refresh หน้าเว็บ (กด Ctrl+Shift+R)

### ชื่อไฟล์ต่างจากตัวอย่าง?
แก้ไขชื่อในโค้ด:
```html
<img src="images/ชื่อไฟล์ของคุณ.jpg" alt="Project Poster" class="poster-image">
```

---

## 📌 ไฟล์ที่เกี่ยวข้อง

- `poster.html` - หน้าแสดงโปสเตอร์
- `images/poster-a1.jpg` - ไฟล์โปสเตอร์ของคุณ
- `style.css` - สไตล์ (ไม่ต้องแก้)

---

## 💡 เคล็ดลับ

✅ ใช้รูปภาพคุณภาพสูง (1920x1080 หรือสูงกว่า)  
✅ บีบอัดรูปก่อนใช้ (TinyPNG.com)  
✅ ทดสอบบนโปรเจคเตอร์ก่อนนำเสนอจริง  
✅ เตรียมไฟล์ backup ไว้ใน USB  

---

**พร้อมนำเสนอแล้ว!** 🎉
