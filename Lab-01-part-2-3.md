# Lab-01 Part 2~3 คำสั่ง Console.Write() และ Console.WriteLine()

## 2. การใช้เมดธอด Console.Write()

### 2.1 การใช้เมดธอด Console.Write()
👉 แก้ไขโปรแกรม ให้เป็นดังด้านล่างนี้

```csharp
Console.Write("Hello");
Console.Write("Hello");
```

➢ รันโปรแกรมและบันทึกผล
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/9f62405d-3774-4df2-94e2-e34f8f60c20d)


❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย
เเสดงผล  hello hello แบบเว้นบรรทัด

### 2.2 การใช้เมดธอด Console.Write() ร่วมกับ  `Environment.NewLine`

`Environment.NewLine` เป็นค่าคงที่ที่ถูกนิยามในภาษา C# เพื่อใช้สำหรับการส่งอักขระขึ้นบรรทัดใหม่ไปยัง console

👉 แก้ไขโปรแกรม ให้เป็นดังด้านล่างนี้

```csharp
Console.Write("Hello" + Environment.NewLine);
Console.Write("Hello" + Environment.NewLine);
```

➢ รันโปรแกรมและบันทึกผล
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/ae27ff96-f504-4da4-b988-cf7c08533bd0)


❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย
เสดงผล  hello hello แบบเว้นบรรทัด

## 3. เมดธอด Console.WriteLine()

`Console.WriteLine()` เป็นคำสั่งที่เทียบเท่ากับการใช้  `Console.Write` ร่วมกับ  `Environment.NewLine` ทำให้ประหยัดเวลาในการเขียนโปรแกรม
👉 แก้โปรแกรมในเมดธอด Main() ให้เป็นดังต่อไปนี้

```csharp
Console.WriteLine("Hello");
```

➢ รันโปรแกรมและบันทึกผล
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/4cad05a3-4c79-4832-85d5-f64f570dd3d7)


👉 แก้ไขโปรแกรม ให้เป็นดังรูปด้านล่างนี้

```csharp
Console.Write("Hello, ");
Console.WriteLine("World!");
```

➢ รันโปรแกรมและบันทึกผล
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/b6b149d2-6417-4325-8751-9342a708e42d)

❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย
เป็น เนื่องจากแสดงผล ตรงตามภาพการรันโปรเเกรม

❔ จงอธิบายความแตกต่างระหว่างคำสั่ง Console.Write() และ Console.WriteLine()
Console.Write()ไม่ขึ้นบรรทัดใหม่หลังเเสดงผล ส่วน Console.WriteLine ขึ้นบรรทัดใหม่ลังเเสดงผล

## [4. จำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()](./Lab-01-part-4.md)
