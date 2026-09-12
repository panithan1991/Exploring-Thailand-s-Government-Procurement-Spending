<div align="center">

# Exploring Thailand's Government Procurement Spending

### การสำรวจการใช้จ่ายภาครัฐไทยผ่านข้อมูลการจัดซื้อจัดจ้าง

<br>

![Fiscal Years](https://img.shields.io/badge/FISCAL%20YEARS-2567--2569-C9A227?style=for-the-badge&labelColor=0B1F3A)
![Data](https://img.shields.io/badge/DATA-PUBLIC%20PROCUREMENT-C9A227?style=for-the-badge&labelColor=0B1F3A)
![Visualization](https://img.shields.io/badge/VISUALIZATION-SVG-C9A227?style=for-the-badge&labelColor=0B1F3A)

<br>

**สำรวจโครงสร้าง แนวโน้ม และการกระจายตัวของการจัดซื้อจัดจ้างภาครัฐไทย  
ผ่านการวิเคราะห์ข้อมูลปีงบประมาณ 2567–2569**

</div>

---

## Project Overview

โครงการนี้จัดทำขึ้นเพื่อสำรวจและนำเสนอภาพรวมของ **ข้อมูลการจัดซื้อจัดจ้างภาครัฐของประเทศไทย** ในมิติต่าง ๆ โดยใช้กระบวนการวิเคราะห์ข้อมูลตั้งแต่การเตรียมข้อมูล การตรวจสอบและทำความสะอาดข้อมูล การวิเคราะห์เชิงสำรวจ ตลอดจนการจัดทำกราฟและภาพประกอบเพื่อสื่อสารผลการวิเคราะห์

<div align="center">

**Raw Data → Data Preprocessing → Data Cleaning → Exploratory Data Analysis → Data Visualization**

</div>

### Procurement at a Glance

| ปีงบประมาณ | จำนวนโครงการ | วงเงินงบประมาณรวม | ราคาที่ตกลงซื้อ/จ้าง |
| :---: | ---: | ---: | ---: |
| **2567** | **5,428,289 โครงการ** | **1,243,189.99 ล้านบาท** | **94.25%** ของวงเงิน |
| **2568** | **4,658,738 โครงการ** | **1,362,057.24 ล้านบาท** | **94.26%** ของวงเงิน |
| **2569*** | **3,935,690 โครงการ** | **1,173,086.06 ล้านบาท** | **94.91%** ของวงเงิน |

> **ข้อมูลปีงบประมาณ 2569 เป็นข้อมูล ณ วันที่ 30 กรกฎาคม 2569 และยังไม่ครอบคลุมตลอดทั้งปีงบประมาณ**

---

## Data Source

โครงการนี้ใช้ข้อมูลจาก **ระบบข้อมูลการใช้จ่ายภาครัฐ (Thailand Government Spending)** ซึ่งเผยแพร่ผ่านเว็บไซต์

**https://govspending.data.go.th/**

ขอขอบคุณหน่วยงานผู้ดูแลระบบข้อมูลการใช้จ่ายภาครัฐ ที่ได้รวบรวมและเผยแพร่ข้อมูลด้านการจัดซื้อจัดจ้างภาครัฐ เพื่อสนับสนุนการนำข้อมูลไปใช้ประโยชน์ในการศึกษา การวิเคราะห์ และการพัฒนางานด้านข้อมูล

> **หมายเหตุเกี่ยวกับการใช้ข้อมูล**  
> ผลการวิเคราะห์ การตีความ และการนำเสนอในโครงการนี้จัดทำขึ้นเพื่อวัตถุประสงค์ด้านการศึกษา โดยเป็นผลงานของผู้จัดทำ และไม่ถือเป็นผลการวิเคราะห์หรือข้อสรุปอย่างเป็นทางการของหน่วยงานเจ้าของข้อมูล

---

## Contents

1. [ภาพรวมการจัดซื้อจัดจ้างภาครัฐ](#section-1)
   - [วงเงินงบประมาณรวมจำแนกตามหมวดภารกิจ](#section-1-1)
2. [โครงการที่มีวงเงินงบประมาณสูงสุดและต่ำสุด](#section-2)
3. [การจัดซื้อจัดจ้างจำแนกตามประเภทโครงการ](#section-3)
4. [วงเงินงบประมาณรวมจำแนกตามจังหวัด](#section-4)
   - [การกระจายวงเงินงบประมาณรวมรายจังหวัด](#section-4-1)
5. [ความสัมพันธ์ระหว่างจำนวนโครงการและวงเงินรวมรายจังหวัด](#section-5)
6. [หน่วยงานที่มีวงเงินงบประมาณรวมสูงสุด](#section-6)
7. [การกระจายวงเงินงบประมาณต่อโครงการ](#section-7)

---

<a id="section-1"></a>

![SECTION 01](https://img.shields.io/badge/SECTION-01-C9A227?style=for-the-badge&labelColor=0B1F3A)

## 1. ภาพรวมการจัดซื้อจัดจ้างภาครัฐ ปีงบประมาณ 2567–2569

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![ภาพรวมปี 2567](figures/1_2567.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/1_2567.svg) | [![ภาพรวมปี 2568](figures/1_2568.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/1_2568.svg) | [![ภาพรวมปี 2569](figures/1_2569.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/1_2569.svg) |

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/1_2567.svg">
    <img src="figures/1_2567.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/1_2568.svg">
    <img src="figures/1_2568.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/1_2569.svg">
    <img src="figures/1_2569.svg" width="90%">
  </a>
</p>

<p align="center">
  <i>ข้อมูล ณ วันที่ 30 กรกฎาคม 2569</i>
</p>

</details>

*ข้อมูลปีงบประมาณ 2569 ณ วันที่ 30 กรกฎาคม 2569*

### การวิเคราะห์

เมื่อเปรียบเทียบภาพรวมทั้งสามปี ปีงบประมาณ **2567** มีจำนวนโครงการสูงที่สุดที่ **5,428,289 โครงการ** ขณะที่ปีงบประมาณ **2568** มีวงเงินงบประมาณรวมสูงที่สุดที่ **1,362,057.24 ล้านบาท**

สำหรับปีงบประมาณ **2569** มีข้อมูลจำนวน **3,935,690 โครงการ** คิดเป็นวงเงินรวม **1,173,086.06 ล้านบาท** อย่างไรก็ตาม ข้อมูลดังกล่าวเป็นข้อมูล ณ วันที่ 30 กรกฎาคม 2569 จึงยังไม่ครอบคลุมตลอดทั้งปีงบประมาณ

ราคาที่ตกลงซื้อหรือจ้างเมื่อเทียบกับวงเงินงบประมาณรวมอยู่ในระดับใกล้เคียงกันทั้งสามปี โดยคิดเป็น **94.25%** ในปี 2567, **94.26%** ในปี 2568 และ **94.91%** ในปี 2569

ส่วนต่างระหว่างวงเงินงบประมาณกับราคาที่ตกลงซื้อหรือจ้างอยู่ที่ **71,536.16 ล้านบาท**, **78,141.58 ล้านบาท** และ **59,682.68 ล้านบาท** ตามลำดับ

> **ข้อค้นพบสำคัญ**  
> ปี 2567 มีจำนวนโครงการมากที่สุด ขณะที่ปี 2568 มีวงเงินงบประมาณรวมสูงที่สุดในช่วงข้อมูลที่นำมาวิเคราะห์

<br>

<a id="section-1-1"></a>

![ANALYSIS 01.1](https://img.shields.io/badge/ANALYSIS-01.1-C9A227?style=flat-square&labelColor=0B1F3A)

### 1.1 วงเงินงบประมาณรวมจำแนกตามหมวดภารกิจ ปีงบประมาณ 2567–2569

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![วงเงินตามหมวดภารกิจ ปี 2567](figures/2_2567.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/2_2567.svg) | [![วงเงินตามหมวดภารกิจ ปี 2568](figures/2_2568.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/2_2568.svg) | [![วงเงินตามหมวดภารกิจ ปี 2569](figures/2_2569.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/2_2569.svg) |

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/2_2567.svg">
    <img src="figures/2_2567.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/2_2568.svg">
    <img src="figures/2_2568.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/2_2569.svg">
    <img src="figures/2_2569.svg" width="90%">
  </a>
</p>

<p align="center">
  <i>ข้อมูล ณ วันที่ 30 กรกฎาคม 2569</i>
</p>

</details>

*ข้อมูลปีงบประมาณ 2569 ณ วันที่ 30 กรกฎาคม 2569*

#### การวิเคราะห์

เมื่อพิจารณาวงเงินงบประมาณตามหมวดภารกิจ พบว่า **การเศรษฐกิจ** เป็นหมวดที่มีวงเงินสูงที่สุดอย่างต่อเนื่องทั้งสามปี โดยมีวงเงิน **415.82 พันล้านบาท (33.4%)** ในปี 2567 เพิ่มขึ้นเป็น **540.27 พันล้านบาท (39.7%)** ในปี 2568 และอยู่ที่ **425.70 พันล้านบาท (36.3%)** ในปี 2569

**การบริหารทั่วไปของรัฐ** เป็นหมวดที่มีสัดส่วนสูงในลำดับถัดมา คิดเป็น **28.7%**, **27.1%** และ **26.2%** ตามลำดับ ขณะที่ **การสาธารณสุข** มีสัดส่วนอยู่ในช่วงประมาณ **12.9–14.9%** ของวงเงินรวมในแต่ละปี

สำหรับหมวด **การศึกษา** มีวงเงิน **108.07 พันล้านบาท** ในปี 2567, **90.84 พันล้านบาท** ในปี 2568 และ **112.92 พันล้านบาท** ในปี 2569

ภาพรวมสะท้อนให้เห็นว่า **การเศรษฐกิจ การบริหารทั่วไปของรัฐ และการสาธารณสุข** เป็นกลุ่มภารกิจหลักที่มีสัดส่วนวงเงินสูงเมื่อเทียบกับหมวดอื่นอย่างต่อเนื่อง

> **ข้อควรพิจารณา**  
> การแบ่งหมวดภารกิจในส่วนนี้เป็นการจัดกลุ่มเชิงวิเคราะห์จากสังกัดและชื่อหน่วยงานด้วยกฎคำสำคัญ เพื่อใช้สำหรับการนำเสนอภาพรวม และไม่ใช่รหัสจำแนกงบประมาณอย่างเป็นทางการ

---

<a id="section-2"></a>

![SECTION 02](https://img.shields.io/badge/SECTION-02-C9A227?style=for-the-badge&labelColor=0B1F3A)

## 2. โครงการที่มีวงเงินงบประมาณสูงสุดและต่ำสุด ปีงบประมาณ 2567–2569

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![โครงการวงเงินสูงสุดและต่ำสุด ปี 2567](figures/3_2567.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/3_2567.svg) | [![โครงการวงเงินสูงสุดและต่ำสุด ปี 2568](figures/3_2568.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/3_2568.svg) | [![โครงการวงเงินสูงสุดและต่ำสุด ปี 2569](figures/3_2569.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/3_2569.svg) |

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/3_2567.svg">
    <img src="figures/3_2567.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/3_2568.svg">
    <img src="figures/3_2568.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/3_2569.svg">
    <img src="figures/3_2569.svg" width="90%">
  </a>
</p>

<p align="center">
  <i>ข้อมูล ณ วันที่ 30 กรกฎาคม 2569</i>
</p>

</details>

*ข้อมูลปีงบประมาณ 2569 ณ วันที่ 30 กรกฎาคม 2569*

### การวิเคราะห์

ข้อมูลสะท้อนให้เห็นถึงความแตกต่างของขนาดโครงการจัดซื้อจัดจ้างอย่างชัดเจน โดยโครงการที่มีวงเงินสูงสุดในปีงบประมาณ **2567** มีมูลค่า **18,740 ล้านบาท** และเพิ่มขึ้นเป็น **28,759 ล้านบาท** ในปี 2568 ซึ่งเป็นวงเงินสูงที่สุดในช่วงข้อมูลที่นำมาศึกษา

สำหรับปี 2569 โครงการที่มีวงเงินสูงสุดอยู่ที่ **15,355.60 ล้านบาท**

โครงการในกลุ่มวงเงินสูงส่วนใหญ่เกี่ยวข้องกับ **การพัฒนาโครงสร้างพื้นฐาน ระบบขนส่ง สาธารณูปโภค งานก่อสร้าง รวมถึงการจัดหาระบบหรืออุปกรณ์ขนาดใหญ่**

ในทางตรงกันข้าม โครงการที่มีวงเงินต่ำสุดมีมูลค่าเพียงหลักสิบถึงหลักร้อยบาท โดยส่วนใหญ่เป็นการจัดซื้อหรือจัดจ้างรายการขนาดเล็ก เช่น อาหารเสริม (นม) วัสดุ น้ำมันเชื้อเพลิง และงานบริการทั่วไป

> **ข้อค้นพบสำคัญ**  
> ข้อมูลการจัดซื้อจัดจ้างภาครัฐมีช่วงของวงเงินต่อโครงการกว้างมาก ตั้งแต่รายการมูลค่าหลักสิบบาทไปจนถึงโครงการขนาดใหญ่ระดับหมื่นล้านบาท

---

<a id="section-3"></a>

![SECTION 03](https://img.shields.io/badge/SECTION-03-C9A227?style=for-the-badge&labelColor=0B1F3A)

## 3. การจัดซื้อจัดจ้างจำแนกตามประเภทโครงการ ปีงบประมาณ 2567–2569

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![ประเภทโครงการ ปี 2567](figures/4_2567.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/4_2567.svg) | [![ประเภทโครงการ ปี 2568](figures/4_2568.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/4_2568.svg) | [![ประเภทโครงการ ปี 2569](figures/4_2569.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/4_2569.svg) |

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/4_2567.svg">
    <img src="figures/4_2567.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/4_2568.svg">
    <img src="figures/4_2568.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/4_2569.svg">
    <img src="figures/4_2569.svg" width="90%">
  </a>
</p>

<p align="center">
  <i>ข้อมูล ณ วันที่ 30 กรกฎาคม 2569</i>
</p>

</details>

*ข้อมูลปีงบประมาณ 2569 ณ วันที่ 30 กรกฎาคม 2569*

### การวิเคราะห์

เมื่อจำแนกตามประเภทโครงการ พบว่า **การซื้อ** เป็นประเภทที่มีจำนวนโครงการมากที่สุดในทุกปี โดยมีจำนวน **3,433,701 โครงการ** ในปี 2567, **2,923,243 โครงการ** ในปี 2568 และ **2,474,411 โครงการ** ในปี 2569

อย่างไรก็ตาม หากพิจารณาด้านวงเงินรวม **การจ้างก่อสร้าง** เป็นประเภทที่มีวงเงินสูงที่สุด โดยมีวงเงินประมาณ **522.68 พันล้านบาท** ในปี 2567 เพิ่มขึ้นเป็น **672.09 พันล้านบาท** ในปี 2568 และอยู่ที่ประมาณ **475.93 พันล้านบาท** ในปี 2569

สำหรับวงเงินเฉลี่ยต่อโครงการ กลุ่ม **จ้างที่ปรึกษา** และ **จ้างควบคุมงาน** มีค่าเฉลี่ยค่อนข้างสูง โดยในปี 2569 มีวงเงินเฉลี่ยประมาณ **9.31 ล้านบาท** และ **9.30 ล้านบาทต่อโครงการ** ตามลำดับ

> **ข้อค้นพบสำคัญ**  
> ประเภทโครงการที่มีจำนวนมากที่สุดไม่จำเป็นต้องเป็นประเภทที่มีวงเงินรวมสูงที่สุด เนื่องจากขนาดและลักษณะของโครงการมีความแตกต่างกัน

---

<a id="section-4"></a>

![SECTION 04](https://img.shields.io/badge/SECTION-04-C9A227?style=for-the-badge&labelColor=0B1F3A)

## 4. วงเงินงบประมาณรวมจำแนกตามจังหวัด ปีงบประมาณ 2567–2569

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![วงเงินงบประมาณตามจังหวัด ปี 2567](figures/5_2567.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/5_2567.svg) | [![วงเงินงบประมาณตามจังหวัด ปี 2568](figures/5_2568.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/5_2568.svg) | [![วงเงินงบประมาณตามจังหวัด ปี 2569](figures/5_2569.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/5_2569.svg) |

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/5_2567.svg">
    <img src="figures/5_2567.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/5_2568.svg">
    <img src="figures/5_2568.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/5_2569.svg">
    <img src="figures/5_2569.svg" width="90%">
  </a>
</p>

<p align="center">
  <i>ข้อมูล ณ วันที่ 30 กรกฎาคม 2569</i>
</p>

</details>

*ข้อมูลปีงบประมาณ 2569 ณ วันที่ 30 กรกฎาคม 2569*

### การวิเคราะห์

**กรุงเทพมหานคร** มีวงเงินงบประมาณรวมสูงที่สุดในทั้งสามปีอย่างชัดเจน โดยมีวงเงินประมาณ **332.10 พันล้านบาท** ในปี 2567 เพิ่มขึ้นเป็น **542.08 พันล้านบาท** ในปี 2568 และอยู่ที่ **488.54 พันล้านบาท** ในปี 2569

สำหรับจังหวัดในลำดับถัดมา อันดับมีการเปลี่ยนแปลงในแต่ละปี โดยปี 2567 **ชลบุรี** มีวงเงินรวมสูงเป็นอันดับ 2 ที่ประมาณ **40.72 พันล้านบาท** ปี 2568 เป็น **นครราชสีมา** ที่ประมาณ **33.61 พันล้านบาท** และปี 2569 เป็น **นนทบุรี** ที่ประมาณ **32.91 พันล้านบาท**

ขณะที่ **สมุทรสงคราม** มีวงเงินรวมอยู่ในระดับต่ำที่สุดของทั้งสามปี โดยอยู่ที่ประมาณ **2.17 พันล้านบาท**, **1.99 พันล้านบาท** และ **2.12 พันล้านบาท** ตามลำดับ

> **ข้อค้นพบสำคัญ**  
> กรุงเทพมหานครมีวงเงินรวมสูงกว่าจังหวัดอื่นอย่างเด่นชัด ขณะที่อันดับของจังหวัดในกลุ่มรองลงมามีการเปลี่ยนแปลงในแต่ละปี

<br>

<a id="section-4-1"></a>

![ANALYSIS 04.1](https://img.shields.io/badge/ANALYSIS-04.1-C9A227?style=flat-square&labelColor=0B1F3A)

### 4.1 การกระจายวงเงินงบประมาณรวมรายจังหวัด ปีงบประมาณ 2567–2569

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![แผนที่วงเงินรายจังหวัด ปี 2567](figures/6_2567.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/6_2567.svg) | [![แผนที่วงเงินรายจังหวัด ปี 2568](figures/6_2568.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/6_2568.svg) | [![แผนที่วงเงินรายจังหวัด ปี 2569](figures/6_2569.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/6_2569.svg) |

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/6_2567.svg">
    <img src="figures/6_2567.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/6_2568.svg">
    <img src="figures/6_2568.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/6_2569.svg">
    <img src="figures/6_2569.svg" width="90%">
  </a>
</p>

<p align="center">
  <i>ข้อมูล ณ วันที่ 30 กรกฎาคม 2569</i>
</p>

</details>

*ข้อมูลปีงบประมาณ 2569 ณ วันที่ 30 กรกฎาคม 2569*

#### การวิเคราะห์

แผนที่แสดงการกระจายของวงเงินงบประมาณรวมในระดับจังหวัด โดยพื้นที่ที่มีสีเข้มกว่าสะท้อนถึงวงเงินรวมที่สูงกว่า

กรุงเทพมหานครถูกแยกออกจากการคำนวณสเกลสี เนื่องจากมีวงเงินสูงกว่าจังหวัดอื่นอย่างชัดเจน จึงนำจังหวัดอันดับ 2–77 มาใช้ในการเปรียบเทียบ เพื่อให้เห็นความแตกต่างของวงเงินระหว่างพื้นที่ได้ชัดเจนยิ่งขึ้น

ในปี **2567** จังหวัดที่มีวงเงินสูงเด่นในแต่ละภูมิภาค ได้แก่ **ชลบุรี นนทบุรี นครราชสีมา เชียงใหม่ สงขลา และกาญจนบุรี**

ปี **2568** จังหวัดที่มีวงเงินสูงในแต่ละภูมิภาค ได้แก่ **นครราชสีมา นนทบุรี ชลบุรี เชียงใหม่ สงขลา และราชบุรี**

ส่วนปี **2569** จังหวัดที่มีวงเงินสูงเด่น ได้แก่ **นนทบุรี ชลบุรี เชียงใหม่ นครราชสีมา สงขลา และราชบุรี**

เมื่อพิจารณาภาพรวมทั้งสามปี จังหวัดที่ปรากฏเป็นพื้นที่วงเงินสูงอย่างต่อเนื่อง ได้แก่ **นนทบุรี ชลบุรี เชียงใหม่ นครราชสีมา และสงขลา**

> **ข้อค้นพบสำคัญ**  
> รูปแบบการกระจายของวงเงินสะท้อนให้เห็นกลุ่มจังหวัดศูนย์กลางของแต่ละภูมิภาคที่มีวงเงินจัดซื้อจัดจ้างอยู่ในระดับสูงอย่างต่อเนื่อง

---

<a id="section-5"></a>

![SECTION 05](https://img.shields.io/badge/SECTION-05-C9A227?style=for-the-badge&labelColor=0B1F3A)

## 5. ความสัมพันธ์ระหว่างจำนวนโครงการและวงเงินรวมรายจังหวัด ปีงบประมาณ 2567–2569

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![ความสัมพันธ์รายจังหวัด ปี 2567](figures/7_2567.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/7_2567.svg) | [![ความสัมพันธ์รายจังหวัด ปี 2568](figures/7_2568.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/7_2568.svg) | [![ความสัมพันธ์รายจังหวัด ปี 2569](figures/7_2569.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/7_2569.svg) |

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/7_2567.svg">
    <img src="figures/7_2567.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/7_2568.svg">
    <img src="figures/7_2568.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/7_2569.svg">
    <img src="figures/7_2569.svg" width="90%">
  </a>
</p>

<p align="center">
  <i>ข้อมูล ณ วันที่ 30 กรกฎาคม 2569</i>
</p>

</details>

*ข้อมูลปีงบประมาณ 2569 ณ วันที่ 30 กรกฎาคม 2569*

### การวิเคราะห์

กราฟแสดงแนวโน้มว่า **จำนวนโครงการและวงเงินรวมรายจังหวัดมีความสัมพันธ์ไปในทิศทางเดียวกัน** กล่าวคือ จังหวัดที่มีจำนวนโครงการมากมักมีวงเงินรวมสูงตามไปด้วย

การกระจายของข้อมูลบนกราฟ Log–Log มีแนวโน้มจากด้านล่างซ้ายไปยังด้านบนขวา ซึ่งสะท้อนความสัมพันธ์เชิงบวกระหว่างตัวแปรทั้งสอง

**กรุงเทพมหานคร** เป็นจุดที่โดดเด่นที่สุดในทุกปี เนื่องจากมีทั้งจำนวนโครงการและวงเงินรวมสูงกว่าจังหวัดอื่นอย่างชัดเจน

อย่างไรก็ตาม ยังพบจังหวัดบางแห่งที่อยู่ห่างจากแนวโน้มโดยรวม กล่าวคือ แม้จะมีจำนวนโครงการใกล้เคียงกัน แต่กลับมีวงเงินรวมแตกต่างกันค่อนข้างมาก

> **ข้อค้นพบสำคัญ**  
> จำนวนโครงการมีความสัมพันธ์กับวงเงินรวมในระดับหนึ่ง แต่ไม่สามารถใช้อธิบายระดับวงเงินของแต่ละจังหวัดได้ทั้งหมด เนื่องจากขนาดวงเงินต่อโครงการมีความแตกต่างกัน

> **หมายเหตุ**  
> กราฟใช้มาตราส่วนลอการิทึม (Log Scale) เพื่อให้สามารถแสดงข้อมูลที่มีช่วงค่ากว้างได้ชัดเจนยิ่งขึ้น

---

<a id="section-6"></a>

![SECTION 06](https://img.shields.io/badge/SECTION-06-C9A227?style=for-the-badge&labelColor=0B1F3A)

## 6. หน่วยงานที่มีวงเงินงบประมาณรวมสูงสุด ปีงบประมาณ 2567–2569

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![หน่วยงานวงเงินสูงสุด ปี 2567](figures/8_2567.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/8_2567.svg) | [![หน่วยงานวงเงินสูงสุด ปี 2568](figures/8_2568.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/8_2568.svg) | [![หน่วยงานวงเงินสูงสุด ปี 2569](figures/8_2569.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/8_2569.svg) |

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/8_2567.svg">
    <img src="figures/8_2567.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/8_2568.svg">
    <img src="figures/8_2568.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/8_2569.svg">
    <img src="figures/8_2569.svg" width="90%">
  </a>
</p>

<p align="center">
  <i>ข้อมูล ณ วันที่ 30 กรกฎาคม 2569</i>
</p>

</details>

*ข้อมูลปีงบประมาณ 2569 ณ วันที่ 30 กรกฎาคม 2569*

### การวิเคราะห์

**กรมทางหลวง** เป็นหน่วยงานที่มีวงเงินงบประมาณรวมสูงที่สุดในทั้งสามปี โดยมีวงเงินประมาณ **109.26 พันล้านบาท** ในปี 2567 เพิ่มขึ้นเป็น **188.24 พันล้านบาท** ในปี 2568 และอยู่ที่ **107.31 พันล้านบาท** ในปี 2569

**กรมชลประทาน** อยู่ในอันดับ 2 อย่างต่อเนื่อง โดยมีวงเงินประมาณ **58.12 พันล้านบาท**, **88.67 พันล้านบาท** และ **92.57 พันล้านบาท** ตามลำดับ

หน่วยงานในกลุ่มที่มีวงเงินสูงส่วนใหญ่เกี่ยวข้องกับ **โครงสร้างพื้นฐาน การคมนาคม สาธารณูปโภค และงานก่อสร้าง** เช่น กรมทางหลวงชนบท การไฟฟ้าส่วนภูมิภาค กรมโยธาธิการและผังเมือง กรุงเทพมหานคร และการประปาส่วนภูมิภาค

เมื่อพิจารณาจำนวนโครงการควบคู่กับวงเงินรวม พบว่าแต่ละหน่วยงานมีลักษณะแตกต่างกันอย่างชัดเจน บางหน่วยงานมีจำนวนโครงการไม่สูงมาก แต่มีโครงการที่มีวงเงินเฉลี่ยสูง

> **ข้อค้นพบสำคัญ**  
> จำนวนโครงการไม่ใช่ปัจจัยเดียวที่กำหนดระดับวงเงินรวมของหน่วยงาน เนื่องจากขนาดและมูลค่าของแต่ละโครงการแตกต่างกัน

---

<a id="section-7"></a>

![SECTION 07](https://img.shields.io/badge/SECTION-07-C9A227?style=for-the-badge&labelColor=0B1F3A)

## 7. การกระจายวงเงินงบประมาณต่อโครงการ ปีงบประมาณ 2567–2569

| ปีงบประมาณ 2567 | ปีงบประมาณ 2568 | ปีงบประมาณ 2569* |
| :---: | :---: | :---: |
| [![การกระจายวงเงินต่อโครงการ ปี 2567](figures/9_2567.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/9_2567.svg) | [![การกระจายวงเงินต่อโครงการ ปี 2568](figures/9_2568.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/9_2568.svg) | [![การกระจายวงเงินต่อโครงการ ปี 2569](figures/9_2569.svg)](https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/9_2569.svg) |

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2567</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/9_2567.svg">
    <img src="figures/9_2567.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2568</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/9_2568.svg">
    <img src="figures/9_2568.svg" width="90%">
  </a>
</p>

</details>

<details>
<summary><b>ดูภาพขยาย — ปีงบประมาณ 2569</b></summary>

<br>

<p align="center">
  <a href="https://raw.githubusercontent.com/panithan1991/Exploring-Thailand-s-Government-Procurement-Spending/main/figures/9_2569.svg">
    <img src="figures/9_2569.svg" width="90%">
  </a>
</p>

<p align="center">
  <i>ข้อมูล ณ วันที่ 30 กรกฎาคม 2569</i>
</p>

</details>

*ข้อมูลปีงบประมาณ 2569 ณ วันที่ 30 กรกฎาคม 2569*

### การวิเคราะห์

การกระจายของวงเงินต่อโครงการในทั้งสามปีมีรูปแบบใกล้เคียงกัน โดยโครงการส่วนใหญ่กระจุกตัวอยู่ในกลุ่มวงเงินระดับต่ำถึงปานกลาง ขณะที่มีโครงการจำนวนไม่มากที่มีวงเงินสูงมาก

ค่าเฉลี่ยของวงเงินต่อโครงการสูงกว่าค่ามัธยฐานอย่างชัดเจน โดยปี 2567 มีค่ามัธยฐาน **20,650 บาท** เทียบกับค่าเฉลี่ย **229,021 บาท**

ปี 2568 มีค่ามัธยฐาน **20,794 บาท** และค่าเฉลี่ย **292,366 บาท** ขณะที่ปี 2569 มีค่ามัธยฐาน **20,144 บาท** และค่าเฉลี่ย **298,064 บาท**

ความแตกต่างระหว่างค่าเฉลี่ยและค่ามัธยฐานสะท้อนให้เห็นว่า การกระจายของวงเงินมีลักษณะ **เบ้ไปทางขวา (Right-skewed)** เนื่องจากมีโครงการวงเงินสูงจำนวนหนึ่งที่ดึงค่าเฉลี่ยให้สูงขึ้น

สำหรับช่วงวงเงินที่มีจำนวนโครงการมากที่สุด พบว่า ปี 2567 มี **647,806 โครงการ** ปี 2568 มี **570,423 โครงการ** และปี 2569 มี **461,564 โครงการ**

> **ข้อค้นพบสำคัญ**  
> โครงการส่วนใหญ่มีวงเงินไม่สูงมาก แต่มีโครงการขนาดใหญ่จำนวนหนึ่งที่ทำให้ค่าเฉลี่ยของวงเงินต่อโครงการสูงกว่าค่ามัธยฐานอย่างมาก

> **หมายเหตุ**  
> กราฟใช้มาตราส่วนลอการิทึม (Log Scale) ทั้งแกนวงเงินและแกนจำนวนโครงการ เพื่อให้เห็นรูปแบบการกระจายของข้อมูลได้ชัดเจนยิ่งขึ้น

---

<div align="center">

### Thailand Government Procurement Spending Analysis

ข้อมูลจาก  
**Thailand Government Spending**

https://govspending.data.go.th/

<br>

![Data Analysis](https://img.shields.io/badge/DATA-ANALYSIS-0B1F3A?style=flat-square)
![EDA](https://img.shields.io/badge/EXPLORATORY-DATA%20ANALYSIS-C9A227?style=flat-square)
![Visualization](https://img.shields.io/badge/DATA-VISUALIZATION-0B1F3A?style=flat-square)

</div>


