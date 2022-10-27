# Metaverse for Smart Factory Contest 2022
Repository นี้เป็นการเผยแพร่ผลงานการแข่งขัน [Metaverse for Smart Factory Contest 2022](https://smartfactory.hcilab.net/contest/metaverse2022/) ซึ่งผู้เข้าร่วมการแข่งขันยินยอมให้เผยแพร่ Source Code ทั้งหมดหรือบางส่วนของโปรแกรมจำลองการทำงาน (Simulation) โดยเป็น Source Code ส่วนการเชื่อมต่อระหว่างโปรแกรมจำลองการทำงาน (Simulation) และ TeleSorting System  มีวัตถุประสงค์เผยแพร่เพื่อให้นำไปใช้ในการศึกษา โดยมิได้อนุญาตให้นำไปใช้เชิงพาณิชย์ใด ๆ ทั้งสิ้น 

## ชื่อผลงาน โรงงานคัดแยกผลไม้อัจฉริยะ (Smart fruit sorting factory)
### ที่มาและความสำคัญ
ปัจจุบันเกษตรกรไทยรายย่อยประสบปัญหารายได้จากการขายสินค้าทางการเกษตรตกต่ำลงในขณะที่ต้นทุนการผลิตสูงขึ้น บางรายไม่มีแหล่งรับซื้อสินค้าที่มั่นคง ทำให้สินค้าบางส่วนเกิดการเน่าเสีย และในขณะเดียวกันผู้บริโภคที่เป็นผู้ประกอบการก็ประสบปัญหาในการจัดหาวัตถุดิบไม่เพียงพอต่อกำลังการผลิตหรือวัตถุดิบไม่ได้คุณภาพตามความต้องการส่วนผู้บริโภครายย่อยก็ประสบปัญหาการเข้าถึงสินค้าทางเกษตรที่สดใหม่กลุ่มของพวกเราจึงวางแผนออกแบบพัฒนาโรงงานคัดแยกผลไม้อัจฉริยะเพื่อช่วยเพิ่มโอกาสให้เกษตรกรหรือผู้ขายสินค้าด้านการเกษตรสามารถเพิ่มช่องทางการจำหน่ายและช่วยให้เข้าถึงผู้บริโภคได้ในวงกว้างมากขึ้น ช่วยให้ผู้บริโภคสามารถเข้าถึงสินค้าการเกษตรท้องถิ่นที่สดใหม่และช่วยให้ผู้ประกอบการที่ต้องการหาแหล่งวัตถุดิบเพื่อใช้ในการผลิตหรือแปรรูปสามารถเข้าถึงแหล่งวัตถุดิบเหล่านั้นได้ในวงกว้างมากขึ้น ลดความสูญเสียสินค้าเนื่องจาการเน่าเสียโดยการนำเทคโนโลยีที่มีการเชื่อมโยงระหว่างระบบอัตโนมัติและโลกเสมือนจริงเข้ามาพัฒนาระบบของโรงงานตั้งแต่การรับสินค้าจากเกษตรกรและการรับคำซื้อจากผู้บริโภคผ่านgoogle sheet รวบรวมข้อมูลให้กับโรงงานนอกจากนี้ยังเชื่อมโยงและสั่งงานข้อมูลขึ้นผ่านระบบiotรวมไปถึงจำลองและปรับปรุงกระบวนการคัดแยกด้วยdigital twin ตลอดจนการนำเอาARมาช่วยสนับสนุนในการซ่อมบำรุงโรงงานและแสดงผลข้อมูล
### วัตถุประสงค์
1. เพื่อเพิ่มโอกาสให้เกษตรกรหรือผู้ขายสินค้าด้านการเกษตรสามารถเพิ่มช่องทางการจำหน่าย
2. เพื่อให้ผู้บริโภคสามารถเข้าถึงสินค้าการเกษตรท้องถิ่นที่สดใหม่ที่มีคุณภาพและตรงตามความต้องการ
3. เพื่อให้ผู้ประกอบการที่ต้องการหาแหล่งวัตถุดิบที่ใช้ในการผลิตหรือแปรรูปสามารถเข้าถึงแหล่งวัตถุดิบเหล่านั้นได้อย่างเพียงพอและตรงตามความต้องการ
4. เพื่อให้ระบบภายในโรงงานมีประสิทธิภาพสูงขึ้นเนื่องจากมีการนำเทคโนโลยีเข้ามาใช้ในโรงงานทำให้กระบวนคัดแยกสามารถปรับเปลี่ยนให้เหมาะสมกับประเภทของสินค้า
### ประโยชน์ที่ได้รับ
1. เกษตรกรหรือผู้ขายสินค้าด้านการเกษตรสามารถเพิ่มช่องทางการจำหน่ายและมีรายได้ที่มากขึ้น
2. ผู้บริโภคสามารถเข้าถึงสินค้าการเกษตรท้องถิ่นที่สดใหม่ที่มีคุณภาพและตรงตามความต้องการ
3. ผู้ประกอบการที่ต้องการหาแหล่งวัตถุดิบที่ใช้ในการผลิตหรือแปรรูปสามารถเข้าถึงแหล่งวัตถุดิบเหล่านั้นได้อย่างเพียงพอและตรงตามความต้องการ
4. ลดการสูญเสียสินค้าทางการเกษตรจากการเน่าเสียเนื่องจากโรงงานมีการนำเทคโนโลยีเข้ามาใช้ทำให้กระบวนคัดแยกเป็นไปอย่างมีประสิทธิภาพ
### ภาพรวมระบบ
โรงงานคัดแยกผลไม้อัจฉริยะจะนำเอาผลไม้ที่รับมาจากเกษตรกรมาเข้าสู่กระบวนการคัดแยกตามเกรดที่ลูกค้าต้องการ โดยผ่านกระบวนการคัดแยก โดยตัวข้อมูลต่างๆในโรงงานจะใช้ IOT เป็นจุดเชื่อมโยงในการจัดเก็บข้อมูลเเละส่งข้อมูลขึ้นcloudเพื่อใช้ในการวิเคราะห์ เเละใช้ARในการเเสดงผลข้อมูลการทำงานและการซ่อมแซมของเครื่องจักรเเละมีระบบsimulationในการจำลองระบบของกระบวนการคัดแยกเพื่อเข้าถึงกระบวนการคัดแยกได้สะดวกรวดเร็ว จำลองและปรับปรุงกระบวนการคัดแยกด้วยdigital twinอีกทั้งยังสามารถคาดการณ์และรับมือปัญหาที่อาจเกิดขึ้นได้ในอนาคตได้

![Screenshot (826)](https://user-images.githubusercontent.com/114386015/194271160-4c0bdded-8746-425e-8120-a94338a00964.png)

### คลิปสาธิตผลงาน
https://youtu.be/txzhI6dqTlM

## รายชื่อสมาชิกทีม AUTO101
1. คันธารัตน์ บุตรดามา
2. ญาณภัทร อุ่ยวัฒนา
3. ณัฐธพล ตันสำโรง
4. กิตตินันท์ ศรีธนานุวัฒน์
5. ชมพูนุท ศิริกุลพิสุทธิ์
6. กิตติกานต์ จิตต์รุ่งเรืองสุข 
### ช่องทางการติดต่อ
Email: 63010246@kmitl.ac.th
