__คำถาม__ 

1.1  int บน ESP32 ใช้กี่ไบต์?
     ตอบ  int บน ESP32 ใช้ 4 ไบต์

1.2 จากผลลัพธ์ นักศึกษาสังเกตเห็นอะไรเมื่อค่าเกินขอบเขตของ int บน ESP32? 
    ตอบ ค่าเกินขอบเขตจะเกิด Overflow/Underflow ค่าจะวนกลับ


__คำถาม__


2.1 float และ double บน ESP32 ใช้กี่ไบต์ตามลำดับ?
  ตอบ float 4 ไบต์, double 8 ไบต์

2.2 นักศึกษาสังเกตเห็นความแตกต่างของความแม่นยำระหว่าง float และ double อย่างไร? สถานการณ์ใดที่คุณควรเลือกใช้ double แทน float?
    ตอบ double แม่นกว่าถึง 15 ตำแหน่ง ใช้เมื่อความแม่นยำสูง


__คำถาม__

3.1 char ใช้กี่ไบต์? ค่าตัวเลข (ASCII value) มีความสัมพันธ์กับอักขระอย่างไร?
    ตอบ char ใช้ 1 ไบต์ ค่า ASCII แทนอักขระ


__คำถาม__

4.1 bool ใช้กี่ไบต์? true และ false ถูกแสดงผลเป็นค่าใดบน Serial Monitor?
    ตอบ bool ใช้ 1 ไบต์ true=1, false=0


__คำถาม__

5.1 ชนิดข้อมูลจำนวนเต็มแต่ละชนิด (long, long long, unsigned int, unsigned long, unsigned long long) ใช้กี่ไบต์บน ESP32?
    ตอบ long, unsigned int, unsigned long ใช้ 4 ไบต์; long long, unsigned long long ใช้ 8 ไบต์

5.2 บน ESP32, long มีขอบเขตเท่ากับ int หรือไม่? ชนิดข้อมูลใดที่คุณจะใช้หากต้องการเก็บค่าจำนวนเต็มบวกที่ใหญ่ที่สุด?
    ตอบ long เท่ากับ int; ใช้ unsigned long long เก็บจำนวนเต็มบวกใหญ่สุด


__คำถาม__

6.1 byte ใช้กี่ไบต์? เมื่อ myByte ถูกกำหนดให้เป็น 256 ผลลัพธ์ที่ได้คืออะไร และเพราะเหตุใด?
    ตอบ byte ใช้ 1 ไบต์; กำหนด 256 จะเป็น 0 เพราะวนรอบ


__คำถาม__ 

7.1 ทำไม 10 / 3.0 (เมื่อตัวหารเป็น float หรือ double) ถึงได้ผลลัพธ์เป็นทศนิยม แต่เมื่อตัวหารถูกแปลงเป็น int แล้วผลลัพธ์เป็นจำนวนเต็ม?
   ตอบ byte ใช้ 1 ไบต์; กำหนด 256 จะเป็น 0 เพราะวนรอบ


__คำถาม__ 

8.1 นักศึกษาจะใช้การทำ Type Casting ในสถานการณ์ใดบ้างในการเขียนโปรแกรม?
    ตอบ ใช้แปลงชนิดข้อมูล เช่น float→int, char→int, int→float
