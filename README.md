# 🌌 NebulaTrade AI – เทรดอัจฉริยะข้ามกาแล็กซี

NebulaTrade AI คือระบบ AI เทรดคริปโตแบบมัลติเอเจนต์ที่ออกแบบมาเพื่อทดสอบและใช้งาน AI หลายตัวในการวิเคราะห์เหรียญมีม, Futures, Sentiment และปัจจัยด้านเวลา โดยมี Dashboard UI สำหรับการติดตามการตัดสินใจของ AI แต่ละตัวแบบเรียลไทม์

---

## 🚀 Features (MVP Version)

- 🧠 AI 3 ตัวแรก:
  - `AstroSniper` วิเคราะห์เหรียญมีมจากเทรนด์และ Volume
  - `FOMIND` วิเคราะห์ Sentiment จากข่าว/โซเชียล
  - `ChronoX` วิเคราะห์จังหวะการเทรดตาม Pattern

- 📈 Dashboard UI แสดงผลการวิเคราะห์และตัดสินใจของ AI
- 🔁 ซ้อมเทรด (Backtest) + รันเทรดจริงผ่าน Binance Futures (Testnet)
- 📊 ระบบจัดเก็บ Log การเทรดลงฐานข้อมูล (MongoDB)
- 🔍 AI Rookie รุ่นฝึกหัด 3 ตัว พร้อมระบบเรตติ้ง

---

## 🧱 โครงสร้างโปรเจกต์

nebula-trade-ai/
├── backend/
│ ├── main.py # FastAPI backend
│ ├── ai_agents/ # AI แต่ละตัว
│ ├── db/models.py # MongoDB models
│ └── services/binance_client.py
├── frontend/
│ ├── index.html # Dashboard UI
│ └── app.js
├── .env # API keys
├── requirements.txt
└── README.md
