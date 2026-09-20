<a id="top"></a>

<div align="center">

# Exploring Thailand's Government Procurement Spending

### การสำรวจการใช้จ่ายภาครัฐไทยผ่านข้อมูลการจัดซื้อจัดจ้าง

<br>

![Fiscal Years](https://img.shields.io/badge/FISCAL%20YEARS-2567--2569-2A9D8F?style=for-the-badge&labelColor=0B1F3A)
![Public Data](https://img.shields.io/badge/DATA-PUBLIC%20PROCUREMENT-2A9D8F?style=for-the-badge&labelColor=0B1F3A)
![Analysis](https://img.shields.io/badge/ANALYSIS-EDA-2A9D8F?style=for-the-badge&labelColor=0B1F3A)
![Visualization](https://img.shields.io/badge/VISUALIZATION-SVG-2A9D8F?style=for-the-badge&labelColor=0B1F3A)

<br>

**การสำรวจโครงสร้าง แนวโน้ม และการกระจายตัวของการจัดซื้อจัดจ้างภาครัฐไทย**  
**จากข้อมูลปีงบประมาณ พ.ศ. 2567–2569**

<br>

[Project Overview](https://github.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/README.md#project-overview) ·
[Executive Summary](https://github.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/README.md#executive-summary) ·
[Analysis](https://github.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/README.md#contents) ·
[Data Source](https://github.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/README.md#data-source)

</div>

---

<a id="data-source"></a>

## แหล่งข้อมูล (Data Source)

ข้อมูลที่ใช้ในการศึกษานี้มาจาก

**Thailand Government Spending**  
**ระบบข้อมูลการใช้จ่ายภาครัฐ**

[https://govspending.data.go.th/](https://govspending.data.go.th/)

ขอขอบคุณหน่วยงานผู้ดูแล **ระบบข้อมูลการใช้จ่ายภาครัฐ (Thailand Government Spending)** สำหรับการรวบรวมและเผยแพร่ข้อมูลการจัดซื้อจัดจ้างภาครัฐ ซึ่งเป็นประโยชน์ต่อการศึกษาและการวิเคราะห์ข้อมูลสาธารณะ

ผู้จัดทำได้นำข้อมูลดังกล่าวมาตรวจสอบโครงสร้าง ทำความสะอาด และวิเคราะห์เพิ่มเติมตามวัตถุประสงค์ของการศึกษา

**การใช้และตีความข้อมูล:** เนื้อหาและข้อสรุปในโครงการนี้เป็นผลการวิเคราะห์ของผู้จัดทำเพื่อวัตถุประสงค์ทางการศึกษา ไม่ใช่ข้อสรุปอย่างเป็นทางการของหน่วยงานเจ้าของข้อมูล

**ที่มาของภาพและกราฟ:** [Exploring Thailand's Government Procurement Spending](https://github.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending)

---

<a id="contents"></a>

## สารบัญ (Contents)

| Section | หัวข้อการวิเคราะห์ |
| :---: | --- |
| **Data** | [แหล่งข้อมูล (Data Source)](#data-source) |
| **01** | [01 — ภาพรวมสัญญาจัดซื้อจัดจ้างภาครัฐ (Overview Contract)](#overview-contract) |
| **01.1** | [01.1 โครงสร้างวงเงินตามหมวดภารกิจ](#section-1-1) |
| **01.2** | [01.2 การจัดซื้อจัดจ้างจำแนกตามประเภทโครงการ](#section-2) |
| **01.3** | [01.3 ข้อค้นพบสำคัญ](#executive-summary) |


---

<a id="overview-contract"></a>
<a id="project-overview"></a>

## 01 — ภาพรวมสัญญาจัดซื้อจัดจ้างภาครัฐ (Overview Contract)

> **วัตถุประสงค์:** นำเสนอภาพรวมการจัดซื้อจัดจ้างภาครัฐ และอธิบายเหตุผลในการเลือกงานจ้างก่อสร้างเป็นขอบเขตการวิเคราะห์เชิงลึก

ข้อมูลการจัดซื้อจัดจ้างภาครัฐแต่ละปีประกอบด้วยโครงการหลายล้านรายการ ทั้งการซื้อ การจ้างบริการ การก่อสร้าง การเช่า และงานวิชาชีพเฉพาะด้าน การศึกษานี้จึงเริ่มจากโครงสร้างภาพรวม 2 มิติ ได้แก่ **การจัดสรรวงเงินตามหมวดภารกิจ** และ **จำนวนกับมูลค่าของโครงการแต่ละประเภท** จากนั้นจึงกำหนดขอบเขตการวิเคราะห์ไปที่งานจ้างก่อสร้าง

> **ขอบเขตข้อมูล:** ข้อมูลปีงบประมาณ 2569 ครอบคลุมถึงวันที่ **30 กรกฎาคม 2569** และยังไม่ครบทั้งปีงบประมาณ การเปรียบเทียบกับปี 2567–2568 จึงต้องพิจารณาความแตกต่างของช่วงเวลาประกอบ

---

<a id="section-1-1"></a>

### 01.1 โครงสร้างวงเงินตามหมวดภารกิจ

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![วงเงินตามหมวดภารกิจ ปี 2567](figure/1_2567.svg)](figure/1_2567.svg) | [![วงเงินตามหมวดภารกิจ ปี 2568](figure/1_2568.svg)](figure/1_2568.svg) | [![วงเงินตามหมวดภารกิจ ปี 2569](figure/1_2569.svg)](figure/1_2569.svg) |

<p align="center"><em>รูปที่ 1–3 วงเงินงบประมาณรวมจำแนกตามหมวดภารกิจ (คลิกที่ภาพเพื่อดูขนาดเต็ม)</em></p>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="figure/1_2567.svg">
    <img src="figure/1_2567.svg" width="92%" alt="วงเงินงบประมาณรวมตามหมวดภารกิจ ปีงบประมาณ 2567">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="figure/1_2568.svg">
    <img src="figure/1_2568.svg" width="92%" alt="วงเงินงบประมาณรวมตามหมวดภารกิจ ปีงบประมาณ 2568">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="figure/1_2569.svg">
    <img src="figure/1_2569.svg" width="92%" alt="วงเงินงบประมาณรวมตามหมวดภารกิจ ปีงบประมาณ 2569">
  </a>
</p>

</details>

ตลอดช่วงปีงบประมาณ 2567–2569 หมวด **การเศรษฐกิจ** ได้รับวงเงินสูงที่สุด คิดเป็น 33.4%, 39.7% และ 36.3% ของวงเงินรวมตามลำดับ รองลงมาคือ **การบริหารทั่วไปของรัฐ** และ **การสาธารณสุข** ทั้งสามหมวดรวมกันมีสัดส่วนประมาณ 75–80% ของวงเงินในแต่ละปี แสดงให้เห็นว่าวงเงินส่วนใหญ่กระจุกอยู่ในภารกิจหลักไม่กี่หมวด

การจำแนกตามหมวดภารกิจแสดงทิศทางการใช้จ่ายในภาพรวม แต่ยังไม่แสดงว่าวงเงินดังกล่าวดำเนินการผ่านโครงการประเภทใด ส่วนถัดไปจึงพิจารณาจำนวนโครงการ วงเงินรวม และวงเงินเฉลี่ยแยกตามประเภทโครงการ

> **หมายเหตุ:** หมวดภารกิจในกราฟจัดทำขึ้นเพื่อการวิเคราะห์ โดยพิจารณาจากสังกัด ชื่อหน่วยงาน และเกณฑ์คำสำคัญที่ผู้จัดทำกำหนด จึงไม่ใช่รหัสจำแนกงบประมาณอย่างเป็นทางการ

<a id="section-2"></a>

### 01.2 การจัดซื้อจัดจ้างจำแนกตามประเภทโครงการ

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![ประเภทโครงการ ปี 2567](figure/2_2567.svg)](figure/2_2567.svg) | [![ประเภทโครงการ ปี 2568](figure/2_2568.svg)](figure/2_2568.svg) | [![ประเภทโครงการ ปี 2569](figure/2_2569.svg)](figure/2_2569.svg) |

<p align="center"><em>รูปที่ 4–6 จำนวนโครงการ วงเงินรวม และวงเงินเฉลี่ย จำแนกตามประเภทโครงการ (คลิกที่ภาพเพื่อดูขนาดเต็ม)</em></p>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="figure/2_2567.svg">
    <img src="figure/2_2567.svg" width="92%" alt="ตารางสรุปข้อมูลตามประเภทโครงการ ปีงบประมาณ 2567">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="figure/2_2568.svg">
    <img src="figure/2_2568.svg" width="92%" alt="ตารางสรุปข้อมูลตามประเภทโครงการ ปีงบประมาณ 2568">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="figure/2_2569.svg">
    <img src="figure/2_2569.svg" width="92%" alt="ตารางสรุปข้อมูลตามประเภทโครงการ ปีงบประมาณ 2569">
  </a>
</p>

</details>

<a id="executive-summary"></a>

### 01.3 ข้อค้นพบสำคัญ

ผลการจำแนกพบว่า **ประเภทโครงการที่มีจำนวนมากที่สุด ไม่ใช่ประเภทเดียวกับที่มีวงเงินรวมสูงที่สุด**

- โครงการประเภท **ซื้อ** มีจำนวนมากที่สุดในทุกปี ระหว่าง 2.47–3.43 ล้านโครงการ
- โครงการ **จ้างทำของ/จ้างเหมาบริการ** อยู่ในลำดับถัดมา ระหว่าง 1.23–1.63 ล้านโครงการ
- **งานจ้างก่อสร้าง** มีจำนวน 178,978–302,830 โครงการ แต่มีวงเงินรวมสูงที่สุดในทุกปีที่ศึกษา

| ปีงบประมาณ | จำนวนโครงการก่อสร้าง | สัดส่วนจำนวนโครงการทั้งหมด | วงเงินก่อสร้างรวม | สัดส่วนวงเงินทั้งหมด | วงเงินเฉลี่ยต่อโครงการ |
| :---: | ---: | ---: | ---: | ---: | ---: |
| **2567** | 302,830 | 5.58% | 522.68 พันล้านบาท | 42.04% | 1.73 ล้านบาท |
| **2568** | 292,437 | 6.28% | 672.09 พันล้านบาท | 49.34% | 2.30 ล้านบาท |
| **2569*** | 178,978 | 4.55% | 475.93 พันล้านบาท | 40.57% | 2.66 ล้านบาท |

งานจ้างก่อสร้างมีสัดส่วนเพียง 4.55–6.28% ของจำนวนโครงการทั้งหมด แต่คิดเป็น 40.57–49.34% ของวงเงินรวม ความแตกต่างระหว่างสัดส่วนจำนวนโครงการกับสัดส่วนวงเงินเป็นเหตุผลหลักที่เลือกงานจ้างก่อสร้างมาวิเคราะห์ต่อ

---





---

<div align="center">

![Python](https://img.shields.io/badge/PYTHON-DATA%20ANALYSIS-0B1F3A?style=for-the-badge)
![Pandas](https://img.shields.io/badge/PANDAS-DATA%20PROCESSING-176B70?style=for-the-badge)
![EDA](https://img.shields.io/badge/EDA-EXPLORATORY%20ANALYSIS-2A9D8F?style=for-the-badge)
![SVG](https://img.shields.io/badge/SVG-DATA%20VISUALIZATION-176B70?style=for-the-badge)

<br><br>

### Thailand Government Procurement Spending Analysis

การวิเคราะห์ข้อมูลการจัดซื้อจัดจ้างภาครัฐของประเทศไทย  
ปีงบประมาณ พ.ศ. 2567–2569

<br>

**Data Source**

Thailand Government Spending  
[https://govspending.data.go.th/](https://govspending.data.go.th/)

<br>

`Data Preprocessing` · `Data Cleaning` · `Exploratory Data Analysis` · `Data Visualization`

<br>

<sub>
โครงการนี้จัดทำขึ้นเพื่อวัตถุประสงค์ด้านการศึกษาและการวิเคราะห์ข้อมูล
</sub>

<br><br>

[**กลับสู่ด้านบน**](https://github.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/blob/main/README.md#top)

</div>
