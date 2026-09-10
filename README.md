# TTB AI Agent Day

ในการฝึกอบรมนี้ พลจะพาพวกเราสร้าง Agent สามรูปแบบใน Microsoft Copilot Studio ตั้งแต่สร้าง Agent, เพิ่ม Knowledge ให้ตอบจากเอกสาร ไปจนถึงเรียก Agent flow เพื่อช่วยทำงานซ้ำซ้อน แล้วปิดท้ายด้วยการทดสอบและ Publish ตัว Agent นะครับ

> **ข้อมูลสำหรับการอบรม:** ชื่อบุคคล ผู้สมัคร เหตุการณ์ vendor ราคา นโยบาย และข้อมูลสินเชื่อทั้งหมดในชุดนี้เป็นข้อมูลสมมติ ไม่ใช่นโยบาย กระบวนการ เกณฑ์อนุมัติ หรือข้อเสนอจริงของ ttb ห้ามใช้ข้อมูลลูกค้า ข้อมูลส่วนบุคคล หรือข้อมูลภายในจริงในการอบรม

## ก่อนเริ่ม

- มีประสบการณ์ใช้งาน Microsoft 365 และ Chatbot เบื้องต้น
- มีบัญชีที่เข้าใช้ Microsoft Copilot Studio ได้
- มี Developer หรือ Trial Environment ของ Microsoft Power Platform ที่มี Dataverse พร้อมใช้งาน
- ผู้ดูแลเปิด Dataverse search สำหรับการใช้ไฟล์เป็น Knowledge
- ผู้เรียนสามารถเริ่มแบบฝึกหัดที่ 1, 2 หรือ 3 แยกกันได้
- สำหรับการ Publish ต้องมี license และ Copilot Credits/capacity ตามที่องค์กรกำหนด; Trial อย่างเดียวอาจสร้างและทดสอบได้แต่ไม่รับรองว่าสามารถ Publish
- การส่ง email จริงเป็นเพียง Instructor demonstration เมื่อผู้สอนยืนยันความพร้อมของ Outlook connector และนโยบาย Environment

## แบบฝึกหัด

1. [สร้าง Vendor Comparison Assistant](./exercises/exercise-01-create-agent/README.md)
2. [สร้าง Loan Application Policy Assistant ด้วย Knowledge และ RAG](./exercises/exercise-02-add-knowledge/README.md)
3. [สร้าง Customer Follow-up Assistant ด้วย Agent flow](./exercises/exercise-03-add-agent-flow/README.md)
4. [ทดสอบ Responsible AI และ Publish Customer Follow-up Assistant](./exercises/exercise-04-publish-and-review/README.md)

## ไฟล์ประกอบ

- [ดาวน์โหลดไฟล์ประกอบทั้งหมด](./downloads/ttb-ai-agent-day-sample-files.zip)
- ข้อเสนอ Vendor จำลองสำหรับการฝึก
	- [ข้อเสนอ Vendor A](./files/fictional-vendor-a-scanner-proposal.pdf)
	- [ข้อเสนอ Vendor B](./files/fictional-vendor-b-scanner-proposal.pdf)
	- [ข้อเสนอ Vendor C](./files/fictional-vendor-c-scanner-proposal.pdf)
- [เฉลยข้อมูล Vendor สำหรับตรวจคำตอบ](./files/vendor-comparison-sample.md)
- [แนวทางข้อมูลประกอบการพิจารณาสินเชื่อจำลอง](./files/fictional-loan-consideration-guidelines.docx)
- [รายการเอกสารประกอบคำขอสินเชื่อจำลอง](./files/fictional-loan-required-documents.docx)
- [แนวทาง Review และ Escalation จำลอง](./files/fictional-loan-review-and-escalation.docx)
- [ชุดทดสอบ Agent](./files/service-request-test-cases.md)
- [รายการตรวจความพร้อมของ Agent](./files/agent-readiness-checklist.md)

## ขอบเขต

แบบฝึกหัดนี้ใช้ Copilot Studio standard harness และครอบคลุม Agent, Instructions, Knowledge, Agent flow, Tool, การทดสอบ, Authentication และ Teams and Microsoft 365 Copilot channel ไม่ครอบคลุม custom Topic, Prompt node, REST API, MCP, custom connector, automated loan decision, credit scoring, production deployment หรือการส่ง Agent เข้าสู่ Agent Store ของทั้งองค์กร

## เอกสารอ้างอิง

- [Create and delete agents](https://learn.microsoft.com/microsoft-copilot-studio/authoring-first-bot)
- [Upload files as a knowledge source](https://learn.microsoft.com/microsoft-copilot-studio/knowledge-add-file-upload)
- [Create an agent flow as a tool](https://learn.microsoft.com/microsoft-copilot-studio/advanced-flow-create)
- [Add an agent flow as a tool to an agent](https://learn.microsoft.com/microsoft-copilot-studio/flow-agent)
- [Configure user authentication](https://learn.microsoft.com/microsoft-copilot-studio/configuration-end-user-authentication)
- [Connect an agent to Teams and Microsoft 365 Copilot](https://learn.microsoft.com/microsoft-copilot-studio/publication-add-bot-to-microsoft-teams)
- [Copilot Studio billing and licensing FAQ](https://learn.microsoft.com/microsoft-copilot-studio/faq-billing-licensing)
