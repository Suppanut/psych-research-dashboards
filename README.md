# Psychological Research Practices & Psychometric Scales Analytics Portal

เว็บไซต์รวม 2 Interactive Dashboards สำหรับวิเคราะห์แนวปฏิบัติการวิจัยทางจิตวิทยาและคลังมาตรวัดทางจิตวิทยา:

1. **[Psychological Research Practices & Statistical Methods Analytics Dashboard (N = 42,605)](./psych_research_practices_dashboard.html)**
   - เปรียบเทียบแนวปฏิบัติการวิจัยและสถิติวิเคราะห์จากงานวิจัย 42,605 เรื่อง (APA Core Journals 1995–2025, PLOS ONE, Frontiers in Psychology, BMC Psychology, วารสารไทยในฐานข้อมูล TCI กลุ่ม 1 และวิทยานิพนธ์จิตวิทยา จุฬาฯ)
2. **[คลังมาตรวัดทางจิตวิทยา จุฬาลงกรณ์มหาวิทยาลัย (N = 768 วิทยานิพนธ์ | 2,534 มาตรวัด)](./chula_psych_scales_corpus_dashboard.html)**
   - ระบบสืบค้นมาตรวัดและเครื่องมือวิจัยทางจิตวิทยาจากวิทยานิพนธ์ระดับบัณฑิตศึกษา คณะจิตวิทยา จุฬาลงกรณ์มหาวิทยาลัย (พ.ศ. 2542–2568) พร้อมข้อมูลความเที่ยง (Cronbach's α) องค์ประกอบย่อย ตัวเปิดดู/ดาวน์โหลด JSON และลิงก์ PDF ฉบับเต็ม (Chula Digiverse)

## โครงสร้างไฟล์ในโฟลเดอร์เว็บ (`docs/`)
- `index.html` — หน้าแรก (Portal Landing Page)
- `psych_research_practices_dashboard.html` — แดชบอร์ดวิเคราะห์แนวปฏิบัติการวิจัยและสถิติ (N = 42,605)
- `chula_psych_scales_corpus_dashboard.html` — แดชบอร์ดคลังมาตรวัดทางจิตวิทยา จุฬาฯ (N = 768 วิทยานิพนธ์ | 2,534 มาตรวัด)
- `.nojekyll` — ไฟล์กำหนดให้ GitHub Pages เสิร์ฟไฟล์ Static HTML โดยตรง
