🏨 Hostel Management System
A comprehensive C++-based Hostel Management System with role-based access and functionality for Students, Wardens, Staff, and Visitors. This console application simulates real-world hostel operations such as room management, attendance tracking, mess billing, and visitor handling.

👤 System Roles & Permissions
🧑‍🎓 Student
Students can log in to:

📅 Display all meals
🍽️ View meals by day
✅ Mark attendance
👁️ View their attendance
💰 Calculate their bill
🚪 Exit
🛡️ Warden
Wardens have full control over the hostel system:

🏠 Add / Remove / Display Rooms
🎓 Add / Remove / Display Students
📆 View attendance records
🍛 View mess details / Update meals
🔍 Search Students / Staff
💸 Calculate student bills / Staff salary
🔑 Update Password
🧾 Allocate / De-allocate Rooms
🕵️‍♂️ Display Warden Info
👷‍♂️ Add / Remove Staff
👨‍👩‍👧‍👦 Add / Remove / Display Visitors
🛑 Exit
🚶 Visitor
Visitors can:

🔐 Log in to visit a specific student
📝 Add visitor entry (name, ID, contact, purpose, check-in/out date)
❌ Remove a visitor entry
📋 Display all visitor records
Rooms cannot be allocated to more than 3 students at once. All data is saved using simple file handling (e.g., student.txt, visitor.txt, room.txt).

📂 Features
File-based data storage (no external DB needed)
Role-based user interface
Room allocation & validation
Attendance and mess management
Visitor registration & tracking
Billing and salary computation
Modular and expandable design
🛠️ Technologies Used
Language: C++
File Handling: fstream
CLI Interface: Standard Console I/O
🚀 How to Run
-download zip file
-unzip it -run the cpp file
-see passwords anduseernames from the files
