#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##นางสาวนภารัตน์ ฐิติกรโกวิท 57030180
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

##ขั้นเตรียมการทดลอง
1). สร้าง Project ตั้งชื่อเป็น Lab5 เพื่อทดลองการใช้งานคำสั่ง Console.WriteLine()
ลำดับขั้นการทดลอง
(หมายเหตุ ในรูปประกอบที่มี namespace เป็น Lab4 รบกวนแก้เป็น Lab5 ด้วยครับ)
2). ทดลองเรื่องจำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

 2.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic1.png)

  2.2). รันโปรแกรม และบันทึกผลที่ได้


จากการทดลอง เมื่อพิมพ์โค้ดตามข้างต้นแล้วรัน จะมีหน้าต่างสีดำขึ้นมาแสดงคำว่า This is text 1. เว้นบรรทัด  This is text 2. เว้นบรรทัด  This is text 3. เว้นบรรทัด Press any key continue. . . ซึ่งรูปแบบการแสดงผลของประโยคเหมือนกับแลป4 ดังภาพ

![](https://github.com/NAPHARAT/LAB-05/blob/master/img/Capture1.JPG)


2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้


จากการทดลอง เมื่อพิมพ์โค้ดตามข้างต้นแล้วรัน จะมีหน้าต่างสีดำขึ้นมาแสดงคำว่า 3 and 6 ซึ่งตัวเลขในวงเล็บปีกกาทำหน้าที่เป็นพ้อยเตอร์ชี้ไปยังตำแหน่งที่ 0 และ 1 คือเลข 3 และ 6 ตามลำดับ ดังภาพ


![](https://github.com/NAPHARAT/LAB-05/blob/master/img/Capture2.JPG)



###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร


เครื่องปีกกาครอบ มีลักษณะการใช้งาน คือ ใส่ตัวเลขตำแหน่งที่ต้องการชี้ไปยังข้อมูล เพื่อให้แสดงผลออกมา


###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย


จากการทดลองเมื่อใช้เลขกระโดด สามารถใช้งานพ้อยเตอร์ได้โดยจะกระโดดข้ามข้อมูลตัวที่ 1 ไป ดังรูป

![]()
 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้


จากการทดลอง เมื่อพิมพ์โค้ดตามข้างต้นแล้วรัน พบว่า มีการแสดงผลตัวเลข 6, 3 and 6 ตามพ้อยเตอร์ในโค้ด {1} , {0} and {1} ดังภาพ

![](https://github.com/NAPHARAT/LAB-05/blob/master/img/Capture3.1.JPG)

![](https://github.com/NAPHARAT/LAB-05/blob/master/img/Capture3.2.JPG)

3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้

จากการทดลอง เมื่อพิมพ์โค้ดตามข้างต้นแล้วรัน พบว่า บรรทัดที่ 1 และ 2 แสดงผลที่พิมพ์ในโค้ด แต่บรรทัดที่ 3 ลงมาจะมีการแสดงเลขที่ 1 เลขเดียว แต่มีตำแหน่งพิกัด (X,Y) ต่างกัน ดังภาพ 

![](https://github.com/NAPHARAT/LAB-05/blob/master/img/Capture5.JPG)

###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร


การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีการใช้งานโดยการกำหนดจุดพิกัดโดยใส่ตัวเลข (X,Y) ให้ตำแหน่งที่ต้องการแสดงผลนั้้น 

4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้


จากการทดลอง พบว่ามีการแสดงผลเลข 123456789 ในรูปแบบที่แตกต่างกัน ดังภาพ
  
 ![](https://github.com/NAPHARAT/LAB-05/blob/master/img/Capture6.JPG) 

5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้


จากการทดลอง พบว่ามีการแสดงผลเลข 123456789 ในรูปแบบที่แตกต่างกัน ดังภาพ
  
 ![](https://github.com/NAPHARAT/LAB-05/blob/master/img/Capture5.2.JPG)


6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้
  
  
  จากการทดลอง พบว่ามีการแสดงผลเลข 123456789 ในรูปแบบที่แตกต่างกัน ดังภาพ
  
  ![](https://github.com/NAPHARAT/LAB-05/blob/master/img/Capture6.2.JPG)
  

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
```


จากการทดลอง output ของโค้ดแสดงดังภาพ

![](https://github.com/NAPHARAT/LAB-05/blob/master/img/Capture7.JPG)
