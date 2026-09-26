# ข้อมูลสำหรับรัน Notebooks บน Google Colab

ข้อมูล CSV อยู่ใน [data_for_github](https://drive.google.com/drive/folders/1ssVrUcY4TiYee9T2B0pwgr5SwvPp_lAq) รวม **22 ไฟล์ ประมาณ 9.08 GB** ไม่ต้องนำข้อมูลเหล่านี้ขึ้น GitHub

ไฟล์ทั้งหมดวางในโฟลเดอร์นี้โดยตรง ไม่มีโฟลเดอร์ย่อย Notebook ดาวน์โหลดเฉพาะข้อมูลที่ใช้ ไม่ได้ดาวน์โหลดทั้ง 22 ไฟล์ทุกครั้ง

## รายการข้อมูล

| ไฟล์ใน data_for_github | Notebook ที่ใช้ | ขนาด MiB |
| --- | :---: | ---: |
| [07_lower10_project_budget_2567.csv](https://drive.google.com/file/d/1YQpAhUcghJ9gM6eIC6qBZGe6WcVuKyWR/view) | 01 | 0.00 |
| [07_lower10_project_budget_2568.csv](https://drive.google.com/file/d/1aNYIMOH7Da8VvVhXI1XQigBYRNWk9IHj/view) | 01 | 0.00 |
| [07_lower10_project_budget_2569.csv](https://drive.google.com/file/d/1tU1V9n2ysJmXxvmnm_SPz7n7Bhbz2B5_/view) | 01 | 0.00 |
| [07_top10_project_budget_2567.csv](https://drive.google.com/file/d/1bkMYSpLM4UKivKCHe7S8Dsho0BaLgCdJ/view) | 01 | 0.01 |
| [07_top10_project_budget_2568.csv](https://drive.google.com/file/d/1xsItnomfe9q4A9NYJ5U_lR0764mZMEE4/view) | 01 | 0.01 |
| [07_top10_project_budget_2569.csv](https://drive.google.com/file/d/1ZwOBFVQkTRAnazjoeXzr3jkpSGFl2bkI/view) | 01 | 0.01 |
| [2569-egp-contract-1.csv](https://drive.google.com/file/d/1ygmuKsvVjNpjfg0k94Olcuox8efDP3cY/view) | 02, 03, 04 | 587.08 |
| [2569-egp-contract-2.csv](https://drive.google.com/file/d/1DUAh8zAtUUV4Hm2yRplCryUOQDFb3Ad8/view) | 02, 03, 04 | 516.98 |
| [2569-egp-contract-3.csv](https://drive.google.com/file/d/1fD_6GqtIY7LUempYqId0qIEldcJd2moM/view) | 02, 03, 04 | 504.68 |
| [2569-egp-contract-4.csv](https://drive.google.com/file/d/19C4Ak8XNMvm2IBsr7TVpfexZE_1WBke5/view) | 02, 03, 04 | 502.33 |
| [2569-egp-contract-5.csv](https://drive.google.com/file/d/1nsV7vqF8Um-QWKX_Q-kEQq6Z1BFDbK_y/view) | 02, 03, 04 | 497.68 |
| [2569-egp-contract-6.csv](https://drive.google.com/file/d/1-0zhDZjF2chjeXuPoSVGQWNYtp8fVIzt/view) | 02, 03, 04 | 498.48 |
| [2569-egp-contract-7.csv](https://drive.google.com/file/d/1gl9sx_1ve-n7e9M_mQaj0A7mMnk2P0yb/view) | 02, 03, 04 | 493.49 |
| [2569-egp-contract-8.csv](https://drive.google.com/file/d/1z0icf65DY2e7WPmc_qV5PPLdUVyT1wdR/view) | 02, 03, 04 | 434.48 |
| [construction_contract_review_indicators_2569.csv](https://drive.google.com/file/d/1nYgjub4kfLTyX_9gnz3dM2GZWUM67wRJ/view) | 05, 06 | 236.14 |
| [construction_contract_supplier_study_scope_2569.csv](https://drive.google.com/file/d/1dXH9N4ukZAabRQwl9nkQ-KidB1e80ZAh/view) | 05 | 232.04 |
| [agency_supplier_dependence_2569.csv](https://drive.google.com/file/d/1IcOigDI8HdPjC2JqnYiNbQz1_6S23qxl/view) | 05 | 0.02 |
| [priority_review_contracts_2569.csv](https://drive.google.com/file/d/1prDQwSgkNCFqarTx0rkFuQK12Q5J2MT_/view) | 05 | 0.10 |
| [project_overview_2567.csv](https://drive.google.com/file/d/1hEr6tXWRBgEM-uK0dOEKvzIhBdKzHtnx/view) | 01 | 1607.38 |
| [project_overview_2568.csv](https://drive.google.com/file/d/1WVh1etQtH45AemJE4J7mBCDOOT9QmQff/view) | 01 | 1381.36 |
| [project_overview_2569.csv](https://drive.google.com/file/d/1h3Oah1ARYenycAJnLa1DTefzjMryQuJ5/view) | 01 | 1170.84 |
| [repeated_near_500k_agency_supplier_2569.csv](https://drive.google.com/file/d/10fT6PqZbBa5mS4GEHHEOf8_qIeASToQk/view) | 05 | 0.35 |

| Notebook | การอ่านข้อมูลและวิธีเดิมที่คงไว้ |
| --- | --- |
| 01 | ใช้ overview + top 10 + lower 10 ของปีที่เลือก; เปลี่ยน `YEAR` ได้เป็น 2567–2569 |
| 02 | อ่าน CSV ต้นทาง 8 ไฟล์ เรียงชื่อตามเดิม กรอง `จ้างก่อสร้าง` และรักษาแถวสัญญาทั้งหมด |
| 03 | ใช้ผลเตรียมของสูตร Notebook 02 วิเคราะห์ระดับโครงการและผู้รับจ้างตามเดิม |
| 04 | ใช้สูตรข้อมูลของ Notebook 02–03; โค้ดรุ่นนี้วิเคราะห์ระดับโครงการ/หน่วยงานย่อย รวมตัวชี้วัดด้านราคาและการเกิดซ้ำ |
| 05 | อ่าน snapshot ผลวิเคราะห์ระดับสัญญา–ผู้รับจ้างจาก Drive ห้าไฟล์โดยตรง ไม่ใช้ผลลัพธ์ Notebook 04 รุ่นที่อยู่ในโฟลเดอร์นี้มาสร้างแทน |
| 06 | อ่าน snapshot review indicators และคำนวณ Pattern 2 ใหม่ตามสูตรเดิมในไฟล์: ขั้นต่ำ 10 รายการและสัดส่วนจำนวน/มูลค่าอย่างน้อย 75%; คงยอดควบคุมเดิมไว้ |

## วิธีใช้

1. เปิด Notebook ที่ต้องการผ่านลิงก์ **Open in Colab** ใน [คู่มือ Notebook](notebook/README.md)
2. เลือก **Runtime → Run all** ไม่ต้อง Mount Google Drive ส่วนตัวและไม่ต้องตั้งโฟลเดอร์บันทึกผล
3. กราฟและ DataFrame แสดงภายใน Notebook ไฟล์ข้อมูล ฟอนต์ แผนที่ และไฟล์พักจะอยู่ในพื้นที่ชั่วคราวของ Colab
4. เซลล์สุดท้ายเรียก `cleanup_runtime()` เพื่อลบไฟล์พักและปิดรูป โดยเก็บ DataFrame ผลวิเคราะห์ไว้ หากหยุดกลางทางสามารถเรียกฟังก์ชันนี้เองได้
5. หากต้องรันใหม่ทั้งชุด ให้เริ่มจาก setup อีกครั้งเพื่อสร้างพื้นที่พักใหม่ หาก RAM สูง แนะนำ Restart runtime ก่อน Run all


