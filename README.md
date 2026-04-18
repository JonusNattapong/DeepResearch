# BANGSEARCH OS (v1.2.0)

![BANGSEARCH OS - Autonomous Swarm Intelligence](https://raw.githubusercontent.com/JonusNattapong/DeepResearch/main/assets/title.png)

> **Welcome to BANGSEARCH OS v1.2.0**
> **Autonomous Intelligence & Deep Strategic Technical Research**
> แพลตฟอร์มสืบสวนข้อมูลเชิงลึกและวิเคราะห์ Codebase ระดับสูงด้วย Autonomous Swarm Agents

---

## ภาพรวมระบบ

DEEP RESEARCH OS คือแพลตฟอร์มสืบสวนข้อมูลที่ออกแบบมาเพื่อภารกิจที่ซับซ้อน ไม่ว่าจะเป็นการวิเคราะห์ Software Architecture การวิจัยตลาดเชิงลึก หรือการรวบรวมข่าวกรองจากแหล่งข้อมูลเปิด (OSINT) โดยใช้ระบบ Swarm Agents ที่ทำงานประสานกัน

---

## คุณสมบัติใหม่ใน v1.2.0 (The Swarm Update)

### 1. Parallel Research Engine
ระบบสามารถประมวลผล Sub-Agents หลายตัวพร้อมกัน:
- **Concurrent Execution**: ค้นหาข้อมูลจาก Google, Wikipedia และ ArXiv พร้อมกันในหนึ่ง Turn
- **High Throughput**: ประมวลผลข้อมูลปริมาณมากได้เร็วกว่าระบบ Sequential ปกติ

### 2. Autonomous Swarm Delegation (Friend Agents)
Agent ตัวหลักสามารถมอบหมายงานให้โมเดลอื่นจัดการ:
- **Task Delegation**: หากโมเดลหลัก (เช่น GPT-4o-mini) เจอภารกิจที่เกินขีดจำกัด สามารถส่ง Sub-task ให้โมเดลเฉพาะทาง เช่น Claude 3.5 หรือ Gemini 1.5 ช่วยจัดการได้
- **Cross-Provider Synergy**: รวมจุดเด่นของแต่ละค่าย (OpenAI/Anthropic/Google/KiloCode) มาทำงานร่วมกัน

### 3. Multimodal Vision Capabilities
รองรับการวิเคราะห์ข้อมูลผ่านภาพ:
- **Autonomous Screenshotting**: ถ่ายภาพหน้าจอกราฟ ชาร์ต หรือ UI ที่ซับซ้อนมาวิเคราะห์โดยอัตโนมัติ
- **Vision Analysis**: ใช้เครื่องมือ vision_analyze เพื่อตีความข้อมูลจากรูปภาพและนำมาประกอบในรายงาน

### 4. Advanced Browser Interaction
- **Autonomous Action**: Agent สามารถ Click, Type และ Scroll หน้าเว็บเพื่อหาข้อมูลเชิงลึก
- **Dynamic Exploration**: รองรับ SPA และเว็บไซต์ที่มีการโต้ตอบซับซ้อน

---

## โหมดการทำงาน

### Global Intelligence Mission
โหมดสำหรับการวิจัยหัวข้ออิสระ โดยระบบจะทำหน้าที่เป็น Lead Investigative Analyst เพื่อสร้างรายงาน Deep Intelligence Dossier พร้อมแหล่งอ้างอิงที่ตรวจสอบได้จริง

### Strategic Code Analysis
- วิเคราะห์ Codebase จาก GitHub หรือ Local Path
- สังเคราะห์เป็น Technical Blueprint สำหรับนักพัฒนาหรือ Coder AI
- ตรวจสอบ Data Flow และโครงสร้างสถาปัตยกรรมเชิงลึก

---

## อินเทอร์เฟซ

### Intelligence Command Center (Web)
- Bento UI Layout ที่เน้นความชัดเจนและทันสมัย
- Live Swarm Streaming แสดงความเคลื่อนไหวของ Agent แบบ Real-time

### Hacker-Grade TUI (Terminal)
- สไตล์ Operating System ที่ให้ข้อมูลสถานะการทำงานอย่างละเอียด
- แสดงการทำงานระดับเครื่องมือ (Tool Logs) เช่น [Delegation] หรือ [Browser]

---

## การตั้งค่า

ระบบรองรับ Auto-Discovery Keys โดยจะเลือกผู้ให้บริการที่พร้อมใช้งานที่สุดโดยอัตโนมัติ

```env
# ตั้งค่าผ่านเมนู [*] Configure ใน TUI
OPENAI_API_KEY=...
ANTHROPIC_API_KEY=...
GEMINI_API_KEY=...
KILOCODE_API_KEY=...
GITHUB_TOKEN=...
```

---

## เริ่มปฏิบัติภารกิจ

```bash
npm start
```

**DEEP RESEARCH OS** — Intelligence at Scale, Autonomy without Limits.
