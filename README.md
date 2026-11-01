# VeriBoxPack Software Update & Release Distribution 🚀

คลังเผยแพร่ข้อมูลการอัปเดตและไฟล์ตัวติดตั้งสำหรับ **VeriBoxPack** (Smart Parcel Packing Video & Evidence System)

---

## ระบบการอัปเดต (How Update Works)

โปรแกรม VeriBoxPack มีระบบตรวจสอบอัปเดตอัตโนมัติ 2 ช่องทาง:

### 1. ตรวจสอบผ่านไฟล์ `version.json` (วิธีหลัก - รวดเร็วและเสถียรที่สุด)
เมื่อต้องการปล่อยเวอร์ชันใหม่ ให้แก้ไขข้อมูลในไฟล์ `version.json` บน branch `main` ของคลังนี้:
```json
{
  "version": "1.0.1",
  "title": "VeriBoxPack v1.0.1 (Mandatory Security Update)",
  "changelog": "• ปรับปรุงระบบบันทึกวิดีโอและความเสถียรของกล้อง USB\n• ปรับปรุงระบบสำรองข้อมูลขึ้น Google Drive\n• อัปเดตแพตช์ความปลอดภัยล่าสุด",
  "downloadUrl": "https://github.com/megapoomz0001-collab/VeriBoxPackUPDATE/releases/download/v1.0.1/VeriBoxPack_Setup_v1.0.1.exe",
  "isMandatory": true
}
```

### 2. ตรวจสอบผ่าน GitHub Releases
เมื่อสร้าง Release ใหม่บนคลัง `VeriBoxPackUPDATE` พร้อมแนบไฟล์ตัวติดตั้ง `.exe` (เช่น `VeriBoxPack_Setup_v1.0.1.exe`) ระบบของลูกค้าจะดึงเวอร์ชันล่าสุดมาแจ้งเตือนและบังคับอัปเดตอัตโนมัติ

---

**คลังซอร์สโค้ดหลัก:** [https://github.com/megapoomz0001-collab/VeriBoxPack](https://github.com/megapoomz0001-collab/VeriBoxPack)
