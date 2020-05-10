# lshort-thaitrans

This is a Thai translation of the book, "The Not So Short Introduction
to LaTeX2e", version "5.06, June 20, 2016" by Tobias Oetiker.

นี่คือ หนังสือ The Not So Short Introduction to LaTeX2e version 5.06
ที่ถูกเขียนเสร็จเมื่อ วันที่ 20 มิถุนายน ค.ศ. 2016 โดย คุณ Tobias Oetiker ฉบับภาษาไทย
ที่ถูกแปลโดย [shebang.tech](https://shebang.tech)

# โครงสร้างไฟล์

- orig/ : ต้นฉบับหนังสือภาษาอังกฤษ
- orig/lshort-5.0.6/ : source code ของต้นฉบับหนังสือภาษาอังกฤษที่ copy มาจาก
  release v5.0.6 บน [github ของ คุณ Tobias Oetike](https://github.com/oetiker/lshort)
- orig/lshort-5.0.6.pdf : ต้นฉบับหนังสือภาษาอังกฤษในฟอร์แมต pdf ที่ดาวน์โหลดมาจาก
  [โฮมเพจของผู้เขียน](https://tobi.oetiker.ch/lshort/) เมื่อวันที่ 17 ตุลาคม ค.ศ.
  2017 และได้ทำการ rename ไฟล์จาก lshort.pdf เป็น lshort-5.0.6.pdf
  เพื่อประโยชน์ในการอ้างอิงเวอร์ชั่นของหนังสือในอนาคต
- src/ : งานแปลหนังสือเล่มนี้ของเรา
- src/lshort-5.0.6.pdf : งานแปลหนังสือเล่มนี้ของเราในรูปแบบ PDf พร้อมใช้
  อ่านได้เลย

# วิธีสร้างหนังสือแปลในฟอร์แมตแบบ pdf

หากท่านใช้ Debian ให้ติดตั้งแพกเกจดังนี้:

- xelatex
- fonts-thai-tlwg

แล้วท่านสามารถสร้างไฟล์ pdf ได้ด้วยการใช้คำสั่ง `xelatex lshort.tex` จำนวน 3 ครั้ง
ก็จะได้ไฟล์ lshort.pdf ออกมา

# ลิขสิทธิ์

ต้นฉบับหนังสือภาษาอังกฤษใช้ license แบบ [GNU General Public License v2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
ในขณะที่ งานแปลหนังสือเป็นภาษาไทยเล่มนี้ใช้ license แบบ [GNU General Public
License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)

# หมายเหตุ

เนื่องด้วยผู้แปลมีความเชี่ยวชาญในการใช้งาน LaTeX ต่ำมาก จึงไม่อาจใช้ LaTeX
สร้างหนังสือออกมาได้สวยงามเหมือนที่ผู้เขียนได้ทำไว้ อย่างไรก็ตาม
ผู้แปลได้พยายามจัดวางโครงสร้างของไฟล์ต่างๆให้คล้ายคลึงกับที่ผู้เขียนได้วางไว้ให้มากที่สุด
(เท่าที่ความรู้ของผู้แปลจะอำนวย) เผื่อว่าวันหนึ่งจะมีผู้ใจดีที่มีความเชี่ยวชาญเกี่ยวกับ LaTeX
มาช่วยตบแต่งให้สวยงามขึ้น จึงต้องกราบขออภัยมา ณ ที่นี้
