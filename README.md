Automated Faculty Timetable Scheduler
🚀 Project Overview
The Automated Faculty Timetable Scheduler is a Java-based console application that generates and manages weekly class timetables for multiple courses, while automatically handling faculty absences and ensuring balanced workload distribution among faculty members.
It simplifies the tedious process of manual timetable creation, offering smart faculty allocation based on subject expertise and availability.

🏗️ Project Features
Automatic Timetable Generation: Random and intelligent allocation of classes across 5 working days and 8 daily time slots.

Faculty Specialization Mapping: Faculty are assigned only the subjects they are qualified to teach.

Dynamic Absence Handling: If a faculty is absent, the system automatically reschedules their classes with available, qualified staff.

Faculty Workload Management: Tracks and balances the number of classes assigned to each faculty member.

Realistic Daily Structure: Includes 7 academic periods and 1 lunch break ("8U" – 8 Units per day).

📜 How It Works
Initialize courses, subjects, faculty details, and empty timetables.

Generate timetables by allocating subjects and teachers for each course, balancing workload.

Handle Absences by reassigning affected sessions to other available faculty.

Display timetables neatly by course and by day, along with faculty workloads and absence records.

🛠️ Technologies Used
Programming Language: Java

Development Environment: IntelliJ IDEA / Eclipse

Libraries: Core Java (Collections, Maps, Lists)

🔥 Outcomes
Fully functional console-based timetable manager for academic institutions.

Reduces human error and saves administrative time.

Provides a scalable foundation for future upgrades like:

JavaFX GUI Interface

Spring Boot Web Version

Export to PDF/CSV functionality

Notification system for faculty updates

📈 Future Enhancements
Integration with database systems (MySQL/PostgreSQL) for dynamic data storage.

GUI development using JavaFX for a better user experience.

Export options to download generated timetables.

Login system for admin/faculty view access.

✨ Thank you for exploring the Automated Timetable Scheduler!
