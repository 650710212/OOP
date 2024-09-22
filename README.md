# OOP
# การเปรียบเทียบการเขียนโปรแกรมเชิงวัตถุ (OOP) ใน Java, C++, และ Python

เอกสารนี้เปรียบเทียบความเหมือนและความแตกต่างของการเขียนโปรแกรมเชิงวัตถุ (OOP) โดยใช้ **Java**, **C++**, และ **Python**

## ตาราง: การเปรียบเทียบ OOP ใน Java, C++, และ Python

| **คุณลักษณะ**            | **Java**                                                  | **C++**                                                  | **Python**                                               |
|---------------------------|------------------------------------------------------------|----------------------------------------------------------|----------------------------------------------------------|
| **การประกาศคลาส**         | ใช้คีย์เวิร์ด `class`                                      | ใช้คีย์เวิร์ด `class`                                    | ใช้คีย์เวิร์ด `class`                                    |
| **การประกาศสมาชิกของคลาส**| ต้องกำหนดชนิดข้อมูลทุกครั้ง (`int`, `String`, ฯลฯ)            | ต้องกำหนดชนิดข้อมูลทุกครั้ง (`int`, `float`, ฯลฯ)        | ไม่ต้องกำหนดชนิดข้อมูล (ใช้ไดนามิกไทป์)                 |
| **การสืบทอด (Inheritance)** | ใช้คีย์เวิร์ด `extends`                                    | ใช้ `:` เพื่อกำหนดคลาสแม่                                  | ใช้ `:` เพื่อกำหนดคลาสแม่                                |
| **Multiple Inheritance**   | ไม่รองรับ                                                  | รองรับ (ผ่านการใช้ Virtual Base Class เพื่อแก้ไขปัญหา Diamond Problem) | รองรับโดยตรง                                             |
| **การปิดกั้นข้อมูล (Encapsulation)** | ใช้ `private`, `protected`, `public` เพื่อกำหนดการเข้าถึงข้อมูล | ใช้ `private`, `protected`, `public`                      | ไม่มีการกำหนดชัดเจน แต่ใช้ `_` และ `__` เพื่อระบุระดับการเข้าถึง |
| **การทำ Polymorphism**     | รองรับผ่าน Interface และ Overriding                        | รองรับทั้ง Overloading และ Overriding                     | รองรับผ่านการ Overriding และ Duck Typing                 |
| **การจัดการหน่วยความจำ**  | มี Garbage Collection ในตัว                                 | ต้องจัดการหน่วยความจำเอง (ด้วยการใช้ `delete` หรือ `free`) | มี Garbage Collection ในตัว                              |
| **Abstract Class และ Interface** | ใช้ Abstract Class และ Interface                      | มี Abstract Class แต่ไม่มีคีย์เวิร์ด `interface` โดยตรง      | ไม่มี Abstract Class โดยตรง แต่สามารถใช้โมดูล `abc`       |
| **การเข้าถึงสมาชิกของคลาส**| ใช้ `.` เพื่อเข้าถึง                                      | ใช้ `.` เพื่อเข้าถึง                                     | ใช้ `.` เพื่อเข้าถึง                                     |
| **Constructor และ Destructor** | มี constructor แต่ไม่มี destructor (ใช้ garbage collector) | มี constructor และ destructor (`~ClassName()`)             | มี constructor (`__init__`) แต่ไม่มี destructor (ใช้ garbage collector) |
| **การจัดการ Exception**    | ใช้ `try`, `catch`, `finally`                               | ใช้ `try`, `catch`, `finally`                             | ใช้ `try`, `except`, `finally`                           |

