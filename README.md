# Thai Drive Privacy Policy

**Effective date:** 7 November 2026

This policy covers version 3.0 of the Thai Drive apps for iPhone and iPad: "Thailand Driver License" (English) and "สอบใบขับขี่ ไทยไดรฟ์" (Thai). Thai Drive is an independent study app. It is not affiliated with the Department of Land Transport.

[Read the previous policy for earlier versions](https://github.com/artypeace/ThaiDrive/blob/3e9f890b1de063a00cabd535f697eeaef1037143/README.md).

## What stays on your device

Your practice answers, saved questions, exam appointment, office details, checklists, app settings and sign-scan history are stored on your device. Exam reminders are scheduled on the device. Thai Drive has no user accounts. You can clear study statistics in Settings and delete scans in AI Helper history. Deleting the app removes its local data.

## Sign recognition

Sign recognition is optional. You can allow AI sharing during the welcome tour or when you first use an AI feature. When you scan a sign, the photo is reduced in size and sent over HTTPS through our Supabase backend to OpenAI, which identifies the sign. The photo and result are saved in your history on your device. Our backend does not keep the photo. You can withdraw permission under Settings → Privacy and data. Thai Drive will ask again before sharing data for AI analysis.

Please photograph only the road sign and avoid faces, number plates or other personal details.

## Study explanations

When you confirm an AI explanation, the app sends the question identifier and the number of the option you chose to our backend. OpenAI receives the question, your chosen option, the correct option and any reviewed rule available. It does not receive your Apple purchase proof.

Practice question lookup from a photo takes place on your device. When you choose AI analysis after allowing AI sharing, the app sends a reduced copy of the photo through our Supabase backend to OpenAI. Include only the question, its choices and any diagram. Our backend keeps a hash of the submitted image and the completed AI answer for repeat requests. It does not save the photo.

## Purchases and AI usage

Apple processes payments. We do not receive your card details. The app uses StoreKit to check Premium purchases. For study explanations, our backend uses a pseudonymous Apple app transaction identifier to enforce usage limits and save completed explanations for reuse. This also applies to free explanations. Records of previously issued explanation credits and related purchase events may be retained.

## Support and question reports

If you report a question, the app prepares a draft with the question and its reference number, app version, your chosen reason and any comment you add. You choose whether to send it. If you email support, we receive the information you send and your email address so we can respond.

## Limiting abuse

The sign-recognition service keeps a keyed hash of your network address and a short-lived request count to limit abuse. The service removes records older than one hour when it processes another scan.

## Service providers

- **Apple** processes purchases and app distribution.
- **Supabase** hosts our backend functions and may keep service logs.
- **OpenAI** processes photos and explanation requests. We send these requests with storage turned off. OpenAI may retain abuse-monitoring logs under its [API data policy](https://developers.openai.com/api/docs/guides/your-data). The default is up to 30 days, with exceptions described in that policy.

We do not sell your data.

## Ads and tracking

Thai Drive 3.0 shows no ads and does not contain advertising SDKs. It does not track you across other companies' apps or websites.

## Children

Thai Drive is designed for people preparing for a driving licence and is not directed at children.

## Your choices and requests

You can decline AI uploads and still use the practice questions. To ask about your data or request deletion of server records, email thaidriveapp@gmail.com. Because we have no accounts, we may ask for a purchase receipt or similar detail to find the record.

## Changes

We will update this page when these practices change and revise the effective date above.

## Contact

thaidriveapp@gmail.com

---

# นโยบายความเป็นส่วนตัวของ Thai Drive

**วันที่มีผลบังคับใช้:** 7 พฤศจิกายน 2569

นโยบายนี้ครอบคลุมแอป Thai Drive เวอร์ชัน 3.0 สำหรับ iPhone และ iPad ทั้งเวอร์ชันภาษาอังกฤษ "Thailand Driver License" และเวอร์ชันภาษาไทย "สอบใบขับขี่ ไทยไดรฟ์" Thai Drive เป็นแอปเตรียมสอบอิสระ ไม่ได้สังกัดกรมการขนส่งทางบก

[อ่านนโยบายเดิมสำหรับแอปเวอร์ชันก่อนหน้า](https://github.com/artypeace/ThaiDrive/blob/3e9f890b1de063a00cabd535f697eeaef1037143/README.md).

## ข้อมูลที่อยู่ในอุปกรณ์ของคุณ

คำตอบที่ฝึก คำถามที่บันทึกไว้ เวลานัดสอบ ข้อมูลสำนักงาน รายการเตรียมเอกสาร การตั้งค่าแอป และประวัติการสแกนป้ายจะเก็บไว้ในอุปกรณ์ของคุณ การแจ้งเตือนวันสอบตั้งค่าบนอุปกรณ์ Thai Drive ไม่มีระบบบัญชีผู้ใช้ คุณล้างสถิติการเรียนได้ในการตั้งค่า และลบการสแกนได้ในประวัติของผู้ช่วย AI การลบแอปจะลบข้อมูลที่แอปเก็บไว้ในอุปกรณ์

## การสแกนป้ายจราจร

การสแกนป้ายเป็นตัวเลือกเสริม คุณอนุญาตให้แชร์ข้อมูลกับ AI ได้ในหน้าแนะนำหรือเมื่อใช้ฟีเจอร์ AI ครั้งแรก เมื่อคุณสแกนป้าย รูปจะถูกลดขนาดและส่งผ่าน HTTPS ผ่านเซิร์ฟเวอร์ Supabase ของเราไปยัง OpenAI เพื่อระบุป้าย รูปและผลลัพธ์จะบันทึกในประวัติบนอุปกรณ์ของคุณ เซิร์ฟเวอร์ของเราไม่เก็บรูปนั้นไว้ คุณถอนความยินยอมได้ที่ การตั้งค่า → ความเป็นส่วนตัวและข้อมูล แอปจะขออนุญาตอีกครั้งก่อนส่งข้อมูลให้ AI

โปรดถ่ายเฉพาะป้ายจราจร และหลีกเลี่ยงใบหน้า ป้ายทะเบียนรถ หรือข้อมูลส่วนบุคคลอื่น

## คำอธิบายข้อสอบ

เมื่อคุณยืนยันให้ AI อธิบายคำตอบ แอปจะส่งรหัสคำถามและหมายเลขตัวเลือกที่คุณตอบไปยังเซิร์ฟเวอร์ของเรา OpenAI จะได้รับโจทย์ ตัวเลือกที่คุณตอบ ตัวเลือกที่ถูกต้อง และกฎที่ตรวจสอบแล้วหากมี โดยไม่ได้รับหลักฐานการซื้อจาก Apple

การค้นหาโจทย์ฝึกจากรูปทำงานในอุปกรณ์ของคุณ เมื่อเลือกให้ AI วิเคราะห์หลังจากอนุญาตให้แชร์ข้อมูลแล้ว แอปจะส่งรูปที่ลดขนาดแล้วผ่านเซิร์ฟเวอร์ Supabase ของเราไปยัง OpenAI โปรดให้มีเฉพาะโจทย์ ตัวเลือก และภาพประกอบ เซิร์ฟเวอร์ของเราบันทึกค่าแฮชของรูปและคำตอบที่ AI สร้างไว้สำหรับคำขอซ้ำ โดยไม่บันทึกรูป

## การซื้อและการใช้งาน AI

Apple ดำเนินการชำระเงิน เราไม่ได้รับข้อมูลบัตรของคุณ แอปใช้ StoreKit เพื่อตรวจสอบสิทธิ์พรีเมียม สำหรับคำอธิบายข้อสอบ เซิร์ฟเวอร์ใช้รหัสธุรกรรมแอปจาก Apple ที่ไม่แสดงชื่อเพื่อจำกัดจำนวนครั้งและบันทึกคำอธิบายที่สร้างแล้วไว้ใช้ซ้ำ รวมถึงคำอธิบายฟรี เราอาจเก็บข้อมูลเครดิตที่เคยได้รับและรายการซื้อที่เกี่ยวข้องไว้

## การติดต่อและแจ้งปัญหาข้อสอบ

เมื่อคุณแจ้งปัญหา แอปจะเตรียมแบบร่างที่มีคำถาม รหัสข้อสอบ เวอร์ชันแอป เหตุผลที่เลือก และความคิดเห็นที่คุณเพิ่ม คุณเป็นผู้เลือกว่าจะส่งหรือไม่ หากติดต่อเราทางอีเมล เราจะได้รับข้อมูลที่คุณส่งและที่อยู่อีเมลเพื่อใช้ตอบกลับ

## การป้องกันการใช้งานในทางที่ผิด

บริการสแกนป้ายจะเก็บค่าแฮชแบบใช้กุญแจของที่อยู่เครือข่ายและตัวนับคำขอชั่วคราวเพื่อป้องกันการใช้งานในทางที่ผิด ระบบจะลบบันทึกที่มีอายุเกินหนึ่งชั่วโมงเมื่อประมวลผลการสแกนครั้งถัดไป

## ผู้ให้บริการ

- **Apple** ดำเนินการเรื่องการซื้อและการเผยแพร่แอป
- **Supabase** ให้บริการฟังก์ชันเซิร์ฟเวอร์ และอาจเก็บบันทึกการให้บริการ
- **OpenAI** ประมวลผลรูปและคำขอคำอธิบาย เราส่งคำขอโดยปิดการจัดเก็บ OpenAI อาจเก็บบันทึกเพื่อตรวจสอบการใช้งานในทางที่ผิดตาม[นโยบายข้อมูล API](https://developers.openai.com/api/docs/guides/your-data) โดยปกติเก็บไว้สูงสุด 30 วัน และมีข้อยกเว้นตามนโยบายดังกล่าว

เราไม่ขายข้อมูลของคุณ

## โฆษณาและการติดตาม

Thai Drive 3.0 ไม่แสดงโฆษณาและไม่มี SDK โฆษณา และไม่ติดตามคุณข้ามแอปหรือเว็บไซต์ของบริษัทอื่น

## เด็ก

Thai Drive ออกแบบมาสำหรับผู้ที่เตรียมสอบใบขับขี่ และไม่ได้มุ่งเป้าไปที่เด็ก

## ทางเลือกและคำขอของคุณ

คุณปฏิเสธการอัปโหลดไปยัง AI และยังใช้คำถามฝึกได้ หากต้องการสอบถามเกี่ยวกับข้อมูลหรือขอลบข้อมูลบนเซิร์ฟเวอร์ โปรดส่งอีเมลถึง thaidriveapp@gmail.com เนื่องจากแอปไม่มีระบบบัญชี เราอาจขอใบเสร็จการซื้อหรือรายละเอียดที่คล้ายกันเพื่อค้นหาข้อมูล

## การเปลี่ยนแปลง

เราจะปรับปรุงหน้านี้และวันที่มีผลบังคับใช้ด้านบนเมื่อแนวทางเหล่านี้เปลี่ยนแปลง

## ติดต่อ

thaidriveapp@gmail.com
