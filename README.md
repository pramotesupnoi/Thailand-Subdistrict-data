# Thailand-Subdistrict-data
ฐานข้อมูล ตำบล อำเภอ จังหวัด ในประเทศไทย

### รูปแบบของข้อมูล
- JSON
- CSV
- XML
- MySQL Command

### โครงสร้างตาราง
#### ข้อมูล ภูมิภาค (region) 
- region_id -> รหัสภูมิภาค
- region_th -> ชื่อภาษาไทย 
- region_en -> ชื่อภาษาอังกฤษ  
รวมทั้งสิ้น 6 ภูมิภาค

#### ข้อมูล จังหวัด (province) 
- province_id -> รหัสจังหวัด
- province_th -> ชื่อภาษาไทย 
- province_en -> ชื่อภาษาอังกฤษ
- region_id -> รหัสภูมิภาค  
รวมทั้งสิ้น 77 จังหวัด

#### ข้อมูล อำเภอ (district) 
- district_id -> รหัสอำเภอ
- district_th -> ชื่อภาษาไทย 
- district_en -> ชื่อภาษาอังกฤษ
- province_id -> รหัสจังหวัด  
รวมทั้งสิ้น 928 อำเภอ

#### ข้อมูล ตำบล (subdistrict) 
- subdistrict_id -> รหัสตำบล
- subdistrict_th -> ชื่อภาษาไทย 
- subdistrict_en -> ชื่อภาษาอังกฤษ
- latitude -> ละติจูด
- lontitude -> ลองติจูด
- postcode -> รหัสไปรษณีย์
- district_id -> รหัสอำเภอ  
รวมทั้งสิ้น 7375 ตำบล (มีข้อมูลตำแหน่งที่ตั้ง 7311 รายการ มีข้อมูลรหัสไปรษณีย์ 6764 รายการ)

### Data Source  
[data.go.th](https://data.go.th)  
Last update : 09/22/2018
