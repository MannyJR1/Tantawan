| Test Cases: Meeting Room Booking System                      |                                                                                  |
|--------------------------------------------------------------|----------------------------------------------------------------------------------|
|                                                              |                                                                                  |
| Document information                                         |                                                                                  |
| System under test                                            |                                                                                  |
| Author                                                       |                                                                                  |
| Date written                                                 |                                                                                  |
| Document version                                             |                                                                                  |
| Requirements from the exercise                               |                                                                                  |
| R1                                                           | ระบบต้องรับคะแนนชนิดจำนวนเต็ม (int) ผ่านเมธอด gradeOf(int score) และส่งคืนเกรดชนิด String |
| R2                                                           | เมื่อคะแนนอยู่ระหว่าง 80–100 ระบบต้องคืนค่า "A"                                          |
| R3                                                           | เมื่อคะแนนอยู่ระหว่าง 75–79 ระบบต้องคืนค่า "B+"                                          |
| R4                                                           | เมื่อคะแนนอยู่ระหว่าง 70–74 ระบบต้องคืนค่า "B"                                           |
| R5                                                           | เมื่อคะแนนอยู่ระหว่าง 65–69 ระบบต้องคืนค่า "C+"                                          |
| R6                                                           | เมื่อคะแนนอยู่ระหว่าง 60–64 ระบบต้องคืนค่า "C"                                           |
| R7                                                           | เมื่อคะแนนอยู่ระหว่าง 55–59 ระบบต้องคืนค่า "D+"                                          |
| R8                                                           | เมื่อคะแนนอยู่ระหว่าง 50–54 ระบบต้องคืนค่า                                               |
| R9                                                           | เมื่อคะแนนอยู่ระหว่าง 0–49 ระบบต้องคืนค่า "F"                                            |
| R10                                                          | เมื่อคะแนนต่ำกว่า 0 ระบบต้องโยน IllegalArgumentException                               |
| R11                                                          | เมื่อคะแนนสูงกว่า 100 ระบบต้องโยน IllegalArgumentException                            |
| R12                                                          | ระบบต้องคำนวณเกรดได้ถูกต้องทั้งค่าขอบเขตล่างและขอบเขตบนของแต่ละช่วงคะแนน                    |
| R13                                                          | ระบบต้องใช้ JUnit 4.13.2 สำหรับการทดสอบ                                              |
| R14                                                          | ระบบต้องได้รับการพัฒนาด้วยกระบวนการ TDD ตามขั้นตอน RED, GREEN และ REFACTOR              |
| R15                                                          | หลังจาก Refactor แล้ว Test Case ทั้งหมดต้องผ่านการทดสอบ                                |
|                                                              |                                                                                  |
| Design assumptions (to be confirmed with the exercise owner) |                                                                                  |
| Slot size                                                    |                                                                                  |
| Opening hours                                                |                                                                                  |
| Test data                                                    |                                                                                  |
| Cancellation deadline                                        |                                                                                  |
| 2-hour limit                                                 |                                                                                  |
| Performance threshold                                        |                                                                                  |
| Overlap rule                                                 |                                                                                  |
| How to use the TestCases sheet                               |                                                                                  |
| 1                                                            |                                                                                  |
| 2                                                            |                                                                                  |
| 3                                                            |                                                                                  |
| Column definitions                                           |                                                                                  |
| TC ID                                                        |                                                                                  |
| Req ID                                                       |                                                                                  |
| Type                                                         |                                                                                  |
| Preconditions                                                |                                                                                  |
| Test Data                                                    |                                                                                  |
| Test Steps                                                   |                                                                                  |
| Expected Result                                              |                                                                                  |
| Priority                                                     |                                                                                  |
