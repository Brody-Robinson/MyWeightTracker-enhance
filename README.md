#  Enhanced WeightTracker Project

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android%20Studio-blue" alt="Platform">
  <img src="https://img.shields.io/badge/Database-SQLite-brightgreen" alt="Database">
  <img src="https://img.shields.io/badge/Programming%20Language-Java-orange" alt="Programming Language">
</p>

**Enhanced WeightTracker** is an improved version of the original WeightTracker app, bringing enhancements in security, performance, and user experience. This application allows users to record their weight daily, manage their profiles, and receive notifications when they achieve their weight goals.

---

## 🚀 New Features
- **Enhanced Security**: Improved security features including encryption and better data protection.
- **Optimized Database Queries**: Faster data retrieval and storage with optimized SQL queries.
- **Improved User Experience**: Refined UI and UX for a smoother user experience.

## 💡 Artifact Description

The **WeightTracker** application was developed in Android Studio and serves as a practical tool for users to monitor their daily weight. The app allows users to:
- **Record Weight Daily**: Users can log their weight each day and track their progress.
- **Manage Profiles**: Users can manage their profiles, set or change their goal weight, and update their personal information.
- **Receive Notifications**: Users receive congratulatory notifications when they reach their goal weight, enhancing user engagement.

### 📈 Key Enhancements
- **Database Management**: Added foreign key constraints to ensure data integrity and improve the relational database schema.
- **CRUD Operations**: Updated CRUD operations in `DBHelper.java` to handle complex data interactions and maintain data integrity.
- **User Management**: Enhanced user authentication and profile management features.
- **Notifications**: Integrated Android’s notification system to provide feedback and encouragement to users.

## 🛠️ Technology Stack
- **Platform**: Android Studio
- **Database**: SQLite
- **Programming Language**: Java

## 🎯 Justification for Inclusion in ePortfolio

This artifact was selected for my ePortfolio because it demonstrates:
- **Practical Application**: The ability to build a functional Android app focused on user experience and data integrity.
- **Advanced Database Management**: Skills in managing relational databases and ensuring data integrity through foreign key constraints.
- **User-Centered Design**: Proficiency in user interface design and providing an engaging user experience.
- **Notification Handling**: Experience in utilizing Android’s notification system to enhance user engagement.

## 🔧 Improvements Included

### 🗃️ DBHelper.java
- Added `userId` as a foreign key in the `weightEntry` table to maintain relational integrity.
- Updated the `onUpgrade` method to handle schema changes and the addition of the foreign key without data loss.
- Modified methods to work with `userId` for adding and retrieving weight entries.

### 👤 UserSessionManager.java
- Introduced a new key `KEY_USER_ID` to store and retrieve the user's ID.
- Updated `createUserSession` and `getUserId` methods to handle the user ID effectively.

### 📊 WeightEntry.java
- Added a new field `userId` to represent the foreign key in the `weightEntry` table.
- Updated constructors to include `userId` for consistent data management.

## 🎓 Meeting Course Objectives

- **Course Objectives Met**: Yes, the enhancements achieved the objectives of improving database schema design and ensuring data integrity, which were key learning goals in Module One.
- **Outcome-Coverage Plans**: No significant updates are required; the enhancements align with the planned objectives. However, continuous improvement may include further optimizations or additional features based on user feedback.

## 📝 Reflection on the Enhancement Process

### What Was Learned:
- **Database Integrity**: Learned the importance of foreign key constraints in maintaining data integrity and preventing orphaned records.
- **Schema Management**: Gained experience in managing database schema changes and implementing upgrade strategies.
- **CRUD Operations**: Improved skills in updating CRUD operations to handle relational data properly.

### Challenges Faced:
- **Foreign Key Constraints**: Overcame issues related to ensuring foreign key support in SQLite and updating the schema without data loss.
- **Database Upgrades**: Managed the complexity of implementing a database upgrade strategy while maintaining existing user data and functionality.

Enhancing and modifying this artifact provided valuable insights into advanced database management and application development, resulting in a more robust and reliable software solution.

## 📥 Installation

To run this project on your local machine:
1. Clone the repository: `git clone https://github.com/Brody-Robinson/MyWeightTracker-enhance.git`
2. Open the project in Android Studio.
3. Build and run the project on an Android emulator or device.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or would like to contribute, please create an issue or submit a pull request.

---

<p align="center">
  <img src="https://img.shields.io/github/stars/Brody-Robinson/MyWeightTracker-enhance?style=social" alt="GitHub Stars">
  <img src="https://img.shields.io/github/forks/Brody-Robinson/MyWeightTracker-enhance?style=social" alt="GitHub Forks">
</p>
