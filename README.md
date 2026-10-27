# Vent & Let Go (ปล่อยวางทุกความรู้สึก)

เว็บแอปพลิเคชันแบบ Single File (HTML + Tailwind CSS + Vanilla JavaScript) สำหรับพิมพ์ระบายความรู้สึก ปลดปล่อยความเครียด และความกังวล โดยเน้นบรรยากาศที่สงบ มินิมอล พร้อมการตอบสนองทางสายตาและเสียงบำบัดที่นุ่มนวล

![Vent & Let Go Preview](https://img.shields.io/badge/Status-Complete-emerald)
![Privacy](https://img.shields.io/badge/Privacy-100%25%20Zero--Storage-blue)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero%20(Single%20File)-purple)

---

## ✨ จุดเด่นและฟังก์ชันการทำงาน (Features)

1. **ธีมบรรยากาศลุ่มลึกและผ่อนคลาย (Calm Midnight Theme):**
   - โทนสีมืดสบายตา (Deep Dark & Ambient Glow) พร้อมแอนิเมชันแสงออโรร่าพัลส์เบาๆ
   - ฟอนต์ *Prompt* โปร่งสบายตา อ่านง่าย
   - หน้าจอสะอาดตา ปราศจากสิ่งรบกวน โฟกัสเฉพาะการระบายความรู้สึก

2. **เอฟเฟกต์การเลือนหายของตัวหนังสือ (Text Dissolve & Mist Effect):**
   - เมื่อหยุดพิมพ์ ข้อความจะค่อยๆ เบลอจางและสลายตัวไปในความมืด พร้อมปล่อยละอองดาวลอยสู่เบื้องบน
   - ปรับความเร็วในการสลายตัวได้ 3 ระดับ (เร็ว 1.2s / ปกติ 2.8s / ช้า 6.0s)
   - เลือกรูปแบบการสลายตัวได้ 3 สไตล์:
     - ✨ **ละอองดาว (Stardust):** โทนสีม่วง-ฟ้าคราม
     - 🔥 **ประกายไฟมอดดับ (Burning Embers):** สะเก็ดไฟอบอุ่นมอดลงในความมืด
     - 🌫️ **สายหมอก (Gentle Mist):** กลุ่มควันลอยฟุ้งกระจาย
   - ปุ่ม **"ปล่อยวางทันที (Let it go)"** สำหรับสลายข้อความทั้งหมดในพริบตา

3. **เสียงเคาะแป้นพิมพ์ ASMR บำบัด (ASMR Tactile Typing Audio):**
   - สร้างเสียงตอบสนองแบบ Real-time ด้วย **Web Audio API** (ไม่ต้องใช้ไฟล์เสียงภายนอก)
   - มี 3 สไตล์เสียง:
     - 🎶 **กระดิ่งคาลิมบา (Kalimba):** เดินตัวโน้ต Pentatonic อ่อนหวาน
     - 💧 **หยดน้ำ (Water Droplet):** เสียงหยดน้ำกระทบผิวน้ำแผ่วเบา
     - 🪵 **เคาะไม้ (Soft Wood):** เสียงเคาะไม้อบอุ่น

4. **เสียงบรรยากาศผ่อนคลาย (Ambient Soundscapes):**
   - **คลื่นความถี่ 432Hz Drone:** คลื่นเสียงสมาธิลึกช่วยปรับคลื่นสมอง
   - **เสียงฝนโปรยปราย (Soft Rain):** เสียงฝนตกสังเคราะห์ผ่าน Filter ช่วยกลบเสียงรบกวนภายนอก
   - **Dissolve Chime:** เสียงกระดิ่งความถี่ 528Hz สั้นๆ เมื่อปล่อยวางสำเร็จ

5. **วงแหวนนำฝึกจังหวะการหายใจ (Box Breathing Guide 4-4-4-4):**
   - วงแหวนเรืองแสงขยาย-หดตัวตามจังหวะ *หายใจเข้า (4s) $\rightarrow$ กลั้นไว้ (4s) $\rightarrow$ ผ่อนออก (4s) $\rightarrow$ พัก (4s)*

6. **จุดประกายความคิด (Mindful Reflection Prompts):**
   - ปุ่มสุ่มคำถามชวนทบทวนตัวเอง เพื่อเป็นจุดเริ่มต้นสำหรับระบายความในใจ

7. **โหมด Zen เต็มจอ (Zen Fullscreen Mode):**
   - ซ่อน UI ทั้งหมด เหลือเพียงความว่างเปล่าและตัวหนังสือ

8. **ความเป็นส่วนตัว 100% (100% Private & Ephemeral):**
   - ไม่มีการบันทึกข้อมูลลงฐานข้อมูล, LocalStorage หรือส่งข้อมูลผ่านระบบเครือข่ายใดๆ ทั้งสิ้น ทุกตัวอักษรจะระเหยหายไปในความว่างเปล่า

---

## 🚀 วิธีการใช้งาน (Getting Started)

เนื่องจากเป็นแอปพลิเคชันแบบ **Single-file Web App** คุณสามารถเปิดใช้งานได้ทันทีโดยไม่ต้องติดตั้งหรือรันเซิร์ฟเวอร์:

1. Clone repository นี้:
   ```bash
   git clone git@github.com:nisshin61/vent-and-let-go.git
   ```
2. ดับเบิลคลิกเปิดไฟล์ `index.html` บนเว็บบราวเซอร์ใดก็ได้ (Chrome, Safari, Edge, Firefox)

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)
- **HTML5 & Vanilla JavaScript**
- **Tailwind CSS** (via CDN)
- **HTML5 Canvas** (Dynamic Particle Engine)
- **Web Audio API** (Procedural Sound Synthesizer)
