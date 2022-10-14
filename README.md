# DADS5001 Mini-project
NYPD Shooting Incident Data Historic 2006 - 2021

# Author
Thunpitcha Sattabun
6420422010

# Dataset
Source : https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8
Dataset : 25596 rows , 19 columns
Dataset Name : NYPD_Shootings_Historic
Agency Name	 : NYPD
Dataset Description	: List of every shooting incident that occurred in NYC  going back to 2013 through the end of the previous calendar year.
Dataset Keywords : Shooting, Crime, Law Enforcement, Public Safety, NYPD
Dataset Category : Public Safety


# Question 
1. ความสัมพันธ์ระหว่างช่วงเวลากับจำนวนที่เกิดเหตุการณ์กับเพศผู้บาดเจ็บ
2. คดีอาชญากรรมสู่คดีฆาตกรรม
3. สัดส่วนของเพศ ช่วงอายุ ของผู้ก่ออาชญากรรม
4. สถานที่เกิดเหตุที่เกิดเหตุ

# Issue
* ข้อมูลที่จัดเก็บมีการแก้ไขและปรับปรุงตลอดเวลาทำให้บาง column ข้อมูลขาดหายไปจำเป็นต้องใส่ค่า "Unknown/Not Available/Not Reported"
* INCIDENT_KEY column มีเหยื่อหลายคนที่เกี่ยวข้อง และจึงมีการสร้าง INCIDENT_KEY ที่ซ้ำกัน ในที่นี้ไม่มี primary key ทำไมต้องแปลงข้อมูลก่อนใส่กราฟ
* Visualization ยังทำไม่สามารถทำที่ต้องการได้ทั้งหมดเนื่องจากตัวข้อมูล จึงจำเป็นต้องแยกกราฟออกมา

# Visualization
![image](https://imgur.com/jvwe8NJ.jpg)
