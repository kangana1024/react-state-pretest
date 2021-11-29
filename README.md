# State Test

## Install and Run

### npm

setup

```bash
> npm install
```

### yarn

```bash
> yarn
```

run

```bash
> npm run start
```

### yarn

```bash
> yarn start
```

## แบบทดสอบ

1. จากไฟล์ `src/components/input.js` สร้าง props ที่ component input เพื่อเปลี่ยนค่า state `email` เมื่อกดปุ่ม Save ด้วย function `setEmail` ในไฟล์ `src/App.js`

2. เมื่อทำการ set ค่า email เรียบร้อย ให้ set ค่า isSuccess เป็น true และนำค่า email ไปแสดงใน component ชื่อ `Success` ด้วย

3. เมื่อ click ปุ่ม `GO BACK` ทำการเปลี่ยนค่า state `email` เป็น `""` และ `isSuccess` เป็น `false`
