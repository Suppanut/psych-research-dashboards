# Psychological Research Practices, Psychometric Scales & Faculty Works Portal

> ⚠️ **ข้อควรทราบ (AI Disclaimer):** ระบบ ข้อมูล และแดชบอร์ดทั้งหมดในพอร์ทัลนี้สร้างและประมวลผลโดย AI อัตโนมัติ ซึ่งอาจมีความคลาดเคลื่อนหรือข้อผิดพลาดได้ กรุณาตรวจสอบกับเอกสารต้นฉบับก่อนนำไปอ้างอิง (All pipelines, classifications, and dashboards in this portal were built by AI, and AI can make mistakes — please verify against original sources.)

เว็บไซต์รวม 4 Interactive Dashboards สำหรับวิเคราะห์แนวปฏิบัติการวิจัยทางจิตวิทยาและสังคมศาสตร์ คลังมาตรวัด และผลงานวิชาการคณาจารย์คณะจิตวิทยา จุฬาลงกรณ์มหาวิทยาลัย:

1. **[Psychological Research Practices & Statistical Methods Analytics Dashboard (N = 52,849)](./psych_research_practices_dashboard.html)**
   - เปรียบเทียบแนวปฏิบัติการวิจัยและสถิติวิเคราะห์จากงานวิจัย 52,849 เรื่อง (APA Core Journals 1995–2025, PLOS ONE, Frontiers in Psychology, BMC Psychology, วารสารไทยในฐานข้อมูล TCI กลุ่ม 1 และวิทยานิพนธ์จิตวิทยา จุฬาฯ)
2. **[คลังมาตรวัดทางจิตวิทยา จุฬาลงกรณ์มหาวิทยาลัย (N = 768 วิทยานิพนธ์ | 2,534 มาตรวัด)](./chula_psych_scales_corpus_dashboard.html)**
   - ระบบสืบค้นมาตรวัดและเครื่องมือวิจัยทางจิตวิทยาจากวิทยานิพนธ์ระดับบัณฑิตศึกษา คณะจิตวิทยา จุฬาลงกรณ์มหาวิทยาลัย (พ.ศ. 2542–2568) พร้อมข้อมูลความเที่ยง (Cronbach's α) องค์ประกอบย่อย ตัวเปิดดู/ดาวน์โหลด JSON และลิงก์ PDF ฉบับเต็ม (Chula Digiverse)
3. **[ผลงานวิชาการ บทความวิจัย และวิทยานิพนธ์คณาจารย์ คณะจิตวิทยา จุฬาฯ (N = 1,415 ผลงาน | 35 ท่าน)](./chula_faculty_works_dashboard.html)**
   - ฐานข้อมูลผลงานของคณาจารย์ประจำปัจจุบัน 35 ท่าน ครอบคลุมบทความวิจัย Scopus/TCI/OA (709 เรื่อง) และวิทยานิพนธ์ (706 เล่ม) พร้อมสายสัมพันธ์อาจารย์ที่ปรึกษา–ศิษย์ ลิงก์ DOI/OA PDF บนเว็บ และตัวส่งออก CSV/JSON
4. **[แดชบอร์ดวิจัยไทย TCI กลุ่ม 1 สาขาสังคมศาสตร์ & คณะจิตวิทยา จุฬาฯ (N = 49,345 บทความ | 147 วารสาร)](./tci1_social_sciences_dashboard.html)**
   - วิเคราะห์แนวโน้มระยะยาว (ค.ศ. 2003–2025) ของวารสาร TCI กลุ่ม 1 สาขาสังคมศาสตร์ทั้ง 147 วารสาร พร้อมหน้าเปรียบเทียบเฉพาะสำหรับคณะจิตวิทยา จุฬาลงกรณ์มหาวิทยาลัย และระบบสืบค้นบทความทั้ง 49,345 เรื่อง

## โครงสร้างไฟล์ในโฟลเดอร์เว็บ (`docs/`)
- `index.html` — หน้าแรก (Portal Landing Page พร้อมระบบซิงค์ตัวเลขสถิติอัตโนมัติ)
- `psych_research_practices_dashboard.html` — แดชบอร์ดวิเคราะห์แนวปฏิบัติการวิจัยและสถิติ (N = 52,849)
- `tci1_social_sciences_dashboard.html` — แดชบอร์ดวิจัยไทย TCI กลุ่ม 1 สาขาสังคมศาสตร์ & คณะจิตวิทยา จุฬาฯ (N = 49,345)
- `chula_psych_scales_corpus_dashboard.html` — แดชบอร์ดคลังมาตรวัดทางจิตวิทยา จุฬาฯ (N = 768 วิทยานิพนธ์ | 2,534 มาตรวัด)
- `chula_faculty_works_dashboard.html` — แดชบอร์ดผลงานวิชาการคณาจารย์ คณะจิตวิทยา จุฬาฯ (N = 1,415 ผลงาน | 35 ท่าน)
- `LICENSE` — สัญญาอนุญาตการใช้งาน (MIT License & CC BY 4.0)
- `.nojekyll` — ไฟล์กำหนดให้ GitHub Pages เสิร์ฟไฟล์ Static HTML โดยตรง

## สัญญาอนุญาต (License)
ผลงานนี้เผยแพร่ภายใต้สัญญาอนุญาต **[MIT License](./LICENSE)** (สำหรับโค้ดเว็บแอปพลิเคชัน) และ **[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)** (เฉพาะฐานข้อมูลสังเคราะห์ การจัดหมวดหมู่ และเนื้อหาการวิเคราะห์ของผู้จัดทำ ส่วนบทคัดย่อและเอกสารต้นฉบับเป็นลิขสิทธิ์ของผู้ประพันธ์และสำนักพิมพ์ต้นสังกัด)
