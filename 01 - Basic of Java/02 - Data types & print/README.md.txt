Data type
1.Primitive Data type
- Integer (เก็บได้ตั้งแต่ -2,147,483,648 จนถึง 2,147,483,647)
วิธีปริ้น int
System.out.println(เลขที่ต้องการ);
Example
System.out.println(10);
System.out.println(-10);
System.out.println(10+10);
Output
10
-10
20

- Long (จำนวนเต็มที่ยาวมากๆ (ยาวกว่า int))
วิธีปริ้น long
System.out.println(1000000000000000000l);
Output
1000000000000000000

จุดสังเกต
- ถ้าตัวเลขไม่เยอะมากใช้ int ปริ้นธรรมดาเลย
- ถ้าตัวเลขเยอะมากๆให้ใช้ long โดยใส่ l ข้างหลังเลขเสมอ

- Float (เก็บข้อมูลแบบ 32 บิต)(เก็บข้อมูลได้น้อยกว่า double แต่ใช้พื้นที่น้อยกว่า)
วิธีปริ้น int
System.out.println(เลขที่ต้องการ);
Example
System.out.println(10.5f);
System.out.println(-10.5f);
System.out.println(10.5f+10.5f);
Output
10.5
-10.5
21

- Double (เก็บข้อมูลแบบ 64 บิต) (เก็บข้ิอมูลได้เยอะกว่า float แต่ใช้พื้นที่มากกว่า)
วิธีปริ้น int
System.out.println(เลขที่ต้องการ);
Example
System.out.println(10.5);
System.out.println(-10.5);
System.out.println(10.5+10.5);
Output
10.5
-10.5
21

วิธีสังเกต
- ถ้า float ต้องใส่ f ข้างหลังตัวเลขเสมอ ไม่งั้น Java จะคิดว่าเป็น double
- double พิมพ์ทศนิยมธรรมดาเฉยๆ ไม่ต้องใส่อะไรเพิ่มเติม

- Boolean (ข้อมูงเชิงตรรก)
วิธีปริ้น boolean
System.out.println(ค่่าความจริง);
Example
System.out.println(true);
System.out.println(false);
Output
true
false

- Character (ตัวอักษร)
ถ้าเป็นอักขระตัวเดียว ให้ใช้ single quote ครอบไว้แล้วรันเลย (ใส่มากกว่า 1 ตัวไม่ได้) (เลขก็ใส่ได้แต่ใส่ได้แค่ตัวเดียว)
System.out.println('a');
System.out.println('7');
Output
a
7

2.Reference Data type (ข้อมูลที่ custom เองได้)
- String (ข้อความ)
วิธีปริ้น string
System.out.println("Hello World");
Output
Hello World

จุดสังเกต
- character ใส่ single quote ในคำสั่ง print และต้องมีแค่ตัวเดียว (ตัวอักษร / ตัวเลข) เท่านั้น
- string ใส่ double quote ในคำสั่ง print



