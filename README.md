<!-- @format -->

# flutter_apps

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Class 26/6

**widget** คือส่วนประกอบหลักที่ใช้ในการสร้าง UI โดยจะแบ่งออกเป็นสองประเภทหลักคือ Stateless widget และ Stateful widget

1. **Stateless Widget [stl]** เป็น widget ที่ไม่มีการจดจำสถานะการทำงาน ใช้สำหรับ UI ที่ไม่เปลี่ยนแปลงตัวอย่างเช่น Text, Icon, และ Container ที่ไม่มีการเปลี่ยนแปลงหลังจากสร้างขึ้นมาแล้ว
2. **Stateful Widget [stf]** เป็น widget ที่มีการจดจำสถานะการทำงาน ใช้สำหรับ UI ที่เปลี่ยนแปลงได้ เช่น ปุ่มที่สามารถคลิกเพื่อเปลี่ยนสถานะ หรือ text field ที่สามารถกรอกข้อมูลได้ Stateful widget จะประกอบด้วยสองส่วนคือ ตัว widget เองและ State ที่บันทึกสถานะ

**scaffold** เป็น widget ที่ใช้ในการสร้างโครงสร้างพื้นฐานของหน้าจอใน Flutter มันมีคุณสมบัติต่าง ๆ เช่น `AppBar`, `Drawer`, `BottomNavigationBar`, และ `FloatingActionButton` ที่ช่วยในการจัดการและสร้างเลย์เอาต์ของแอปพลิเคชันได้ง่ายขึ้น
