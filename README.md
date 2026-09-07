# TTB AI Agent Day

ในการฝึกอบรมนี้ พลจะพาพวกเราสร้าง ใน Microsoft Copilot Studio ตั้งแต่กำหนดโจทย์ เพิ่ม Knowledge สร้าง Agent Flow ไปจนถึงทดสอบและเผยแพร่ Agent กันครับ

> **ข้อมูลสำหรับการอบรม:** ชื่อบุคคล เหตุการณ์ ขั้นตอน และข้อมูลบริการทั้งหมดในชุดนี้เป็นข้อมูลสมมติ ไม่ใช่นโยบาย กระบวนการ หรือ SLA จริงของ ttb ห้ามใช้ข้อมูลลูกค้า ข้อมูลส่วนบุคคล หรือข้อมูลภายในจริงในการอบรม

## ก่อนเริ่ม

- มีประสบการณ์ใช้งาน Microsoft 365 และ Chatbot เบื้องต้น
- มีบัญชีที่เข้าใช้ Microsoft Copilot Studio ได้
- มี Developer หรือ Trial Environment ของ Microsoft Power Platform ที่มี Dataverse พร้อมใช้งาน
- ผู้ดูแลเปิด Dataverse search สำหรับการใช้ไฟล์เป็น Knowledge
- สำหรับการ Publish ต้องมี license และ Copilot Credits/capacity ตามที่องค์กรกำหนด; Trial อย่างเดียวอาจสร้างและทดสอบได้แต่ไม่รับรองว่าสามารถ Publish
- Optional Extension สำหรับ email ต้องใช้ Office 365 Outlook connector ที่องค์กรอนุญาต

## แบบฝึกหัด

1. [สร้าง Agent ตัวแรก](./exercises/exercise-01-create-agent/README.md)
2. [เพิ่ม Knowledge และทดสอบคำตอบ](./exercises/exercise-02-add-knowledge/README.md)
3. [สร้าง Agent Flow สำหรับสรุปคำขอบริการ](./exercises/exercise-03-add-agent-flow/README.md)
4. [ทดสอบ Responsible AI และ Publish](./exercises/exercise-04-publish-and-review/README.md)

## ไฟล์ประกอบ

- [ดาวน์โหลดไฟล์ประกอบทั้งหมด](./downloads/ttb-ai-agent-day-sample-files.zip)
- [คู่มือคำขอบริการจำลอง](./files/ttb-service-request-guide.docx)
- [ชุดทดสอบ](./files/service-request-test-cases.md)
- [รายการตรวจความพร้อมของ Agent](./files/agent-readiness-checklist.md)

## ขอบเขต

แบบฝึกหัดนี้ใช้ Copilot Studio standard harness และครอบคลุมเฉพาะ Agent, Instructions, Knowledge, Agent Flow, Tool, การทดสอบ, Authentication และ Teams and Microsoft 365 Copilot channel ไม่ครอบคลุม custom Topic, Prompt node, REST API, MCP, custom connector, production deployment หรือการส่ง Agent เข้าสู่ Agent Store ของทั้งองค์กร

## เอกสารอ้างอิง

- [Upload files as a knowledge source](https://learn.microsoft.com/microsoft-copilot-studio/knowledge-add-file-upload)
- [Create an agent flow as a tool](https://learn.microsoft.com/microsoft-copilot-studio/advanced-flow-create)
- [Add an agent flow as a tool to an agent](https://learn.microsoft.com/microsoft-copilot-studio/flow-agent)
- [Configure user authentication](https://learn.microsoft.com/microsoft-copilot-studio/configuration-end-user-authentication)
- [Connect an agent to Teams and Microsoft 365 Copilot](https://learn.microsoft.com/microsoft-copilot-studio/publication-add-bot-to-microsoft-teams)
- [Copilot Studio billing and licensing FAQ](https://learn.microsoft.com/microsoft-copilot-studio/faq-billing-licensing)
