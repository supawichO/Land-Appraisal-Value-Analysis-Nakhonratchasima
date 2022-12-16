# Land-Appraisal-Value-Analysis-Nakhonratchasima
โปรเจกต์การวิเคราะห์ราคาประเมินที่ดินจังหวัดนครราชสีมาปี พ.ศ. 2559-2562

### Objective 🎯
1. ภาพรวมของราคาประเมินที่ดินของแต่ละอำเภอในจังหวัดนครราชสีมา
2. ใช้โมเดลทางสถิติในการคำนวณความน่าจะเป็นของราคาประเมินที่ดิน
3. จัดทำ Visualization เพื่อหา insights ของข้อมูล

### Process 📊
1. ทำการ download ข้อมูลจากกรมธนารักษ์และดึงข้อมูลจาก pdf มาเป็น excel เพื่อล้างข้อมูลให้พร้อมใช้งาน
2. import ข้อมูลลง Python มาทำให้ข้อมูลเหมาะสมสำหรับการวิเคราะห์มากขึ้น
3. ทำ EDA เพื่อสำรวจข้อมูลมีจุดบกพร่อง หรือความผิดปกติอะไรหรือไม่ ทำการแก้ไข
4. จัดทำ data visualization ที่สามารถเห็นภาพรวมของข้อมูลได้
5. วิเคราะห์ข้อมูลด้วย probability และ statistical model

### Problems 🗣️
1. ลักษณะของข้อมูลที่เป็น pdf เวลา export มาทำให้ตัวอักษรคลาดเคลื่อนไปหลายจุด จึงเป็นส่วนที่ต้องใช้เวลาในการแก้ไข
2. การวิเคราะห์โดยการหาค่ากลางงทางสถิติโดยใช้ค่า mean นั้นจะเป็นการใช้เพื่อนำเสนอข้อมูลมากกว่าการวิเคราะห์ หากต้องวิเคราะห์จะใช้ค่า median เนื่องจากข้อมูลเป็น heavy-tailed