# วิธีปรับ Yulgang เปิดได้หลายจอ (Low CPU) โดย แมวหมวย (NVIDIA) 
## หมายเหตุ
เนื่องจาก Yulgang เป็นเกมที่ถูกสร้างมานานมากแล้ว ทำให้ Nvidia ไม่สามารถตรวจจับได้ว่าต้องประมวลกราฟฟิก ตัวเกมจึงไปใช้งาน CPU ประมวลผลแทน ทำให้เมื่อเราเปิดเกมเล่นปกติ ตัวเกมจะใช้งาน CPU ค่อนข้างมาก

วันนี้เราจะมาสอนวิธีทำให้ ตัวเกมไปใช้งาน GPU แทน และปรับให้ตัวเกมใช้ FPS ที่ 20-30 (ต่ำสุด)\
วิธีนี้จะเหมาะกับตี้ฟาร์มหาของ ที่ไม่ได้อยู่หน้าจอเกม โดยเน้นเปิดทิ้งซะมากกว่า

![](https://i.imgur.com/YXXICVk.png)

## คำเตือน
หากคุณปรับตามวิธีนี้ เกมของคุณจะรู้สึกไม่ลื่นไหล และรู้สึกกระตุกนิ๊ด ๆ เนื่องจากตัวเกมจะทำงานที่ 20 FPS
## วิธีทำ
1. เข้าไปที่ โฟลเดอร์ที่เราติดตั้งเกม เช่น C:\Playpark
2. คัดลอกข้อมลของ Yulgang ไปไว้ที่อื่น หรือจะไว้ที่เดียวกันก็ได้ ก็จะได้แบบนี้ โดยโฟลเดอร์ด้านล่างคือตัวเกมอีกตัวที่เราคัดลอกมาและถูกเปลี่ยนชื่อเป็น Yulgang - 20fps (ใช้เวลาซักพักกว่าจะคัดลอกเสร็จ)\
   ![](https://i.imgur.com/50Yj8IK.png)
   
3. โหลด [GEFORCE EXPERIENCE คลิก](https://www.nvidia.com/en-us/geforce/geforce-experience/download/)
4. ติดตั้งให้เรียบร้อย
5. เปิดโปรแกรม\
   ![](https://i.imgur.com/Z3z5jf6.png)

6. เมื่เปิดโปรแกรมา จะเจอหน้าจอให้เข้าสู่ระบบ
7. สามารถเลือกสมัครหรือ Login in with Facebook หรือ Login in with Google
8.  ถ้าเลือกสมัครให้คลิกที่นี่\
   ![](https://i.imgur.com/JbBFcz7.png)

9. กรอกข้อมูลสมัครให้เรียบร้อย
10. หลังจากสมัครแล้ว คุณจำเป็นต้องยืนยันอีเมลด้วย เข้าอีเมลที่สมัครไว้เพื่อยืนยัน
11. หลังจากนั้น เข้าสู่ระบบตามไอดีที่สมัครไว้ จะพบหน้าจอหลัก คลิกที่ DRIVERS\
    ![](https://i.imgur.com/fHdULKU.png)

12. คลิกที่ CHECK FOR UPDATES\
    ![](https://i.imgur.com/SD93YBa.png)

13. หากมีให้อัปเดต ก็กด DOWNLOAD และกด EXPESS INSTALL แล้วกดติดตั้งให้เรียบร้อย
14. มาที่หน้าจอ คลิกขวาเลือก NVIDIA Control Panel\
    ![](https://i.imgur.com/8s9p62J.png)

15. เลือกที่เมนูด้านซ้าย Manage 3D Settings
16. เลือกที่ Tab Program Settings แล้วเลือก Add\
    ![](https://i.imgur.com/PWu7nWm.png)

17. คลิกที่ Browse... แล้วเลือกไฟล์ YGOnline.exe ที่อยู่ใน Playpark\Yulgang - 20fps\client\ (ใน Yulgang โฟลเดอร์ใหม่ที่เรา Copy มา)\
    ![](https://i.imgur.com/3XXwylP.png)

    ![](https://i.imgur.com/4lIbAPr.png)

18. หลังจากนั้นให้ตั้งค่าตามนี้\
    ![](https://i.imgur.com/bVpwMlV.png)

    ![](https://i.imgur.com/8nHMNWp.png)

    ![](https://i.imgur.com/RlcZeqS.png)

19. โดยการตั้งค่าตรงนี้จะสำคัญมาก คุณสามารถเลือกตั้งค่าได้โดยค่าที่เหมาะสมคือ 20-30 แนะนำ 20 เพื่อให้ CPU ต่ำที่สุด (ลองทดสอบด้วยตัวเอง ต้องออกเกมทุกครั้งที่ตั้งค่านี้)\
    ![](https://i.imgur.com/RcH8mgV.png)

20. หลังจากนั้นกดที่ปุ่ม Apply ด้านล่างขวา\
    ![](https://i.imgur.com/Uc0c1Ka.png)

21. หลังจากนั้นตอนเข้าเกมให้คุณเข้าเกมจากไฟล์ launcher.exe ใน โฟลเดอร์ Yulgang - 20fps แทน
22. คุณสามารถทำให้เข้าเกมง่าย ๆ ผ่านหน้าจอด้วยวิธีนี้ คลิกขวาที่ไฟล์ launcher.exe เลือก Send to แล้วเลือก Desktop (create shortcut)\
    ![](https://i.imgur.com/qrmKzfe.png)
23. สำคัญมาก หากคุณตั้งไว้ 20 fps คุณจะรู้สึกกระตุกนิ๊ด ๆ หรืออาจจะมากในความรู้สึกของคุณ หากไม่พอใจเราแนะนำ 30 fps ขึ้นไป แต่ตัวเกมจะใช้งาน CPU เพิ่มขึ้น
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
