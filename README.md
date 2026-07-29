# CPE17 Autorun Killer

#### Original autorun malware protection - Free for non-commercial use

###### Download
[Download Link](https://github.com/chackco/autorun_killer_pub/raw/refs/heads/main/CPE17AutorunKiller_2.6.0.202607292315.exe)

###### Program Features

* โปรแกรมป้องกันไวรัส นี้สร้างขึ้นเพื่อแก้ไขปัญหาต่างๆ ที่เกิดขึ้นจากการกระทำของไวรัสที่ใช้ Flash หรือ Thumb Drive หรือ เป็นหลัก ซึ่งต้องใช้ควบคู่กับ Antivirus Software
* เป็น โปรแกรมที่ป้องกันปัญหาที่ต้นเหตุ โดยบล็อกการทำงานของ AutoRun จากทุกทาง ทั้ง ไดรฟ์ถอดเปลี่ยนได้ทุกแบบ ไดรฟ์ CD/DVD หรือ เน็ตเวิร์กไดรฟ์ก็ตาม
* โปรแกรมป้องกันไวรัสนี้ ถูกพัฒนาและเขียนขึ้นด้วยภาษา C++ แท้ มีขนาดเล็ก กว่า 1MB ทำงานรวดเร็ว และใช้งานได้ทันที
* ไม่กินทรัพยากรมากนัก (Computer Resources) สามารถใช้ได้แม้แต่เครื่องที่ความเร็วช้าก็ตาม
* ดับเบิ้ลคลิกเพียงครั้งเดียว โปรแกรมก็พร้อมจะทำงานทันที ไม่ต้องติดตั้งให้เสียเวลา
* สามารถเปลี่ยนแปลง Option ได้ง่ายๆ โดย เลือกให้ลบอัตโนมัติ มีเสียงเตือนหรือไม่ แสดงหน้าจอผลลัพธ์หรือไม่, จะตรวจ CD/DVD หรือไม่
* โปรแกรมป้องกันไวรัส สามารถแก้ไขปัญหาต่างๆ ที่ถูกไวรัสปิดทิ้งไป เช่น RegEdit, Task Manager, Folder Option, CMD, Find และการกระทำต่างๆ รวมทั้ง Title Bar ของ IE
* สามารถปิด AutoRun แบบถาวร อัตโนมัติ เพื่อไม่ให้เกิดปัญหาขึ้นอีก
* ป้องกันแบบถาวร ไม่ต้องอัพเดตฐานข้อมูลไวรัส (Virus Definitions) อยู่บ่อยๆ
* เพิ่มการทำงานพิเศษ สำหรับเครื่องที่ติดไวรัสไปแล้ว โดยมีฟังก์ชันพยายามฆ่าและลบไวรัส (Process Killer)
* สามารถตั้งให้ตรวจสอบ และลบไฟล์ที่เป็นรูปแบบของไวรัส เช่น ชื่อเดียวกับโฟลเดอร์ หรือไวรัสที่ Copy ตัวเองซ้ำ โดยอัตโนมัติได้
* ตรวจสอบ Image File Execution Option และ WinLogon กรณีถูกไวรัสพยายามฝังตัว
* ตรวจสอบ Schedule task และ WMI เพือค้นหาไวรัสที่พยายามแฝงตัวอยู่
* ตรวจสอบ Cached autorun เพื่อป้องกันการติดเชื้อซ้ำจาก cache หลังจากลบไฟล์ autorun.inf
* เพิ่มการแสดงรายการ Auto Start ทั้ง Registry, Start up folder และ Schedule task และสามารถสั่งลบได้
* เพิ่มฟีเจอร์ ลบไฟล์ขยะ และ ไฟล์แคชของ browser
* สามารถ Update DB ทั้งรายการ Whitelist และรายการ Process อันตรายจากอินเตอร์เน็ต
* มีระบบตรวจสอบ version ใหม่ และนำทางไปดาวน์โหลด version ใหม่ได้อัตโนมัติ
* ใช้เป็นตัว เปิด/ปิด ถาด CD/DVD ได้ด้วย
* รองรับระบบลงทะเบียนใบอนุญาต (License Registration System) ผ่าน Hardware ID
* รองรับการสลับ Theme Dark/Light และสลับเมนูภาษาไทย/อังกฤษ
* โปรแกรมป้องกันไวรัส CPE17 นี้สามารถใช้ได้กับ Vista/ 7 / 8 /10/ 11 (กรุณารันด้วยสิทธิ Administrator เพื่อใช้งานฟังก์ชั่นสำคัญ)
* เมื่อรันครั้งแรก ให้กด Register เพื่อลงทะเบียนการใช้งาน (Free สำหรับบุคคลทั่วไป)

-------------------------

### Core Protection & Malware Mitigation
*   **Companion Security:** Designed primarily to neutralize threats originating from USB Flash/Thumb drives. It acts as a specialized second layer of defense and should be used alongside your primary Antivirus software.
*   **Vector Blocking:** Prevents infections at the source by comprehensively blocking AutoRun execution across all vectors, including removable drives, CD/DVDs, and network drives.
*   **AutoRun Eradication:** Automatically and permanently disables AutoRun functionality to prevent recurring infections.
*   **Heuristic / Behavior-Based Detection:** Provides permanent protection without relying on frequent virus definition updates. It automatically detects and deletes files exhibiting malware behavior, such as executables disguising themselves as folders or self-replicating files.
*   **Active Process Killer:** Includes specialized routines for already-infected machines to forcefully terminate and eradicate active malware processes.
*   **Cache Sanitization:** Inspects cached AutoRun data to prevent reinfection from the system cache after the primary `autorun.inf` file has been deleted.

### System Repair & Deep Scanning
*   **OS Feature Restoration:** Repairs and restores critical Windows utilities often disabled by malware, including RegEdit, Task Manager, Folder Options, CMD, Search functions, and hijacked Internet Explorer Title Bars.
*   **Persistence Mechanism Auditing:** Scans deep system hooks often abused by malware to maintain persistence, like Image File Execution Options, WinLogon, WMI, Scheduled Tasks
*   **Auto-Start Management:** Provides visibility and removal capabilities for startup entries across the Registry, Startup folders, and Scheduled Tasks.

### Performance & System Utilities
*   **Ultra-Lightweight & Portable:** Written in native C++ with a footprint of less than 1MB. It consumes minimal system resources, making it highly efficient even on low-specification hardware.
*   **Zero-Installation:** Runs immediately upon double-clicking (portable executable). 
*   **Junk Cleanup:** Built-in utility to clear system junk files and browser caches.
*   **Hardware Control:** Includes a quick-access toggle to open/close CD/DVD trays.

### Configuration & Administration
*   **Customizable Operations:** Easy-to-toggle options for automatic deletion, audio alerts, result displays, and optical drive scanning.
*   **Cloud Database Updates:** Allows on-demand updates for whitelists and known malicious process databases.
*   **Automated Version Control:** Built-in system to check for and route you to the latest software updates.
*   **Secure Licensing:** Utilizes a secure license registration system based on Hardware ID binding.
*   **Modern UI:** Supports switching between Dark and Light themes, as well as English and Thai localizations.
*   **Broad Compatibility:** Fully functional on Windows Vista, 7, 8, 10, and 11. *(Note: Must be executed with Administrator privileges for core system modifications to work).*
*   **Registration:** Upon first launch, click 'Register' to activate the software (Free for personal use).