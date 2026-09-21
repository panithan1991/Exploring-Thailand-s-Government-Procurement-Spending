# Notebooks สำหรับ Google Colab

**ดูผลโดยไม่ต้องรัน:** Notebook ทั้งหกมีรูปและตารางจากไฟล์ที่ผู้จัดทำรันบน Colab ฝังไว้แล้ว รวม 24 รูป โดยคงโค้ดเดิมตามแนวทาง `jupyter-notebooks` ไฟล์ 01 มีผลถึงตาราง Top/Lower 10 เท่านั้น ส่วนแผนที่รายจังหวัดและการวิเคราะห์ช่วงท้ายยังไม่มีรูปบันทึกไว้ ไฟล์ 02–06 มีเลขลำดับการรันครบทุกเซลล์และไม่พบ output ชนิด error ในไฟล์ที่ส่งมา

เปิดไฟล์ที่ต้องการแล้วเลือก **Runtime → Run all** แนะนำแยก Runtime ของแต่ละ Notebook เพื่อไม่สะสมข้อมูลใหญ่ใน RAM

| Notebook | เนื้อหา | เปิดรัน |
| --- | --- | --- |
| [01_overview_plot.ipynb](01_overview_plot.ipynb) | ภาพรวมการจัดซื้อจัดจ้าง | [Open in Colab](https://colab.research.google.com/github/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/notebook/01_overview_plot.ipynb) |
| [02_construction_data_preparation_2569.ipynb](02_construction_data_preparation_2569.ipynb) | เตรียมข้อมูลก่อสร้าง | [Open in Colab](https://colab.research.google.com/github/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/notebook/02_construction_data_preparation_2569.ipynb) |
| [03_construction_eda_2569.ipynb](03_construction_eda_2569.ipynb) | สำรวจข้อมูลก่อสร้าง | [Open in Colab](https://colab.research.google.com/github/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/notebook/03_construction_eda_2569.ipynb) |
| [04_construction_review_indicators_2569.ipynb](04_construction_review_indicators_2569.ipynb) | ตรวจตัวชี้วัดระดับโครงการ | [Open in Colab](https://colab.research.google.com/github/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/notebook/04_construction_review_indicators_2569.ipynb) |
| [05_construction_storytelling_visuals_2569.ipynb](05_construction_storytelling_visuals_2569.ipynb) | กราฟเล่าเรื่องจาก snapshot ของ Pae | [Open in Colab](https://colab.research.google.com/github/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/notebook/05_construction_storytelling_visuals_2569.ipynb) |
| [06_top_entities_longlat_maps_2569.ipynb](06_top_entities_longlat_maps_2569.ipynb) | แผนที่หน่วยงานและผู้รับจ้าง | [Open in Colab](https://colab.research.google.com/github/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/notebook/06_top_entities_longlat_maps_2569.ipynb) |

ข้อมูลอยู่ใน [Google Drive: data_for_github](https://drive.google.com/drive/folders/1ssVrUcY4TiYee9T2B0pwgr5SwvPp_lAq) ดู [รายการไฟล์และข้อกำหนดการแชร์](../DATA_FILES.md) ก่อนรัน ลิงก์ Colab ใช้ได้หลังอัปโหลดไฟล์เวอร์ชันนี้ไว้ในโฟลเดอร์ `notebook/` บน branch `main` ของ repository

- แสดงกราฟและตารางใน Notebook ไม่มีการส่งออก CSV/PNG/SVG ไปยัง Drive ของผู้อ่าน
- ดาวน์โหลดข้อมูลเฉพาะที่จำเป็นลงพื้นที่ชั่วคราวและลบเมื่อจบ Notebook ไม่มีการบังคับ Mount Drive
- Notebook 01 เลือกปี 2567–2569 ผ่าน `YEAR`; Notebook 02–06 คงปี 2569 และสูตรเดิม
- Notebook 02–04 สร้างข้อมูลเตรียมที่ขาดด้วยขั้นตอนเดิมใน Runtime จึงใช้เวลาอ่านต้นทางประมาณ 4.23 GB
- Notebook 05–06 ใช้ snapshot ระดับสัญญา–ผู้รับจ้างคนละรุ่นกับวิธีคำนวณของ Notebook 04 ที่ให้มา รายละเอียดอยู่ใน DATA_FILES.md
- Notebook 06 คงเกณฑ์ 75% และการตรวจยอดควบคุมเดิม หากไม่ผ่านต้องตรวจรุ่นข้อมูลก่อนเปลี่ยนเกณฑ์

ตรวจ syntax/nbformat และทดสอบขั้นตอนรับส่งข้อมูลด้วยข้อมูลจำลองแล้ว ยังไม่ได้ Run all ข้อมูลจริงครบทุก Notebook หรือยืนยันภาพใหม่ เจ้าของข้อมูลต้องเปิดสิทธิ์ **Anyone with the link → Viewer** ก่อนผู้ชมทั่วไปใช้การดาวน์โหลดอัตโนมัติได้

เมื่อนำขึ้น GitHub ให้อัปโหลด Notebook ทั้งหกไฟล์ พร้อม `DATA_FILES.md`, `data_manifest.json` และคู่มือนี้ ส่วน CSV เก็บไว้ใน Drive เท่านั้น
