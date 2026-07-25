# Call Me Cafe — เว็บแนะนำเมนู

เว็บ static (HTML/CSS + รูปใน `assets/`) แนะนำเมนูข้าวกล่อง/เบรคของร้าน Call Me Cafe

## Public URL
https://callmecafe.pages.dev/  (Cloudflare Pages · โปรเจกต์ `callmecafe`)

## แก้เนื้อหา
แก้ `index.html` / `style.css` / รูปใน `assets/` ในโฟลเดอร์นี้ได้เลย

## Redeploy (หลังแก้ไข)
```bash
cd "/Users/phoom/Desktop/Work/Callme/site"
npx wrangler pages deploy . --project-name=callmecafe --commit-dirty=true --branch=main
```
> ล็อกอิน Cloudflare ครั้งแรกด้วย `npx wrangler login` (บัญชี phoomdetuypornworng@gmail.com) — ล็อกอินไว้แล้ว

## หมายเหตุ
- ไม่ใช้ ngrok เพราะ ngrok ฟรีมี URL public ได้แค่ 1 อัน ซึ่ง n8n ใช้โดเมน elvira-rampant-eliseo.ngrok-free.dev อยู่
- รูปต้นฉบับความละเอียดเต็มอยู่ที่ `../Menu/` และ `../S__39444484.jpg` (รูปในเว็บย่อขนาดแล้วเพื่อโหลดเร็ว)
