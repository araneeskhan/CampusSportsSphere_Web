# 🏆 Campus Sports Sphere - Inventory Management System

## Administrative Module (Phase 1)

### Overview
Welcome to **Campus Sports Sphere** - a comprehensive inventory management system designed specifically for university sports departments. This innovative platform streamlines the reservation and management of athletic equipment, creating a seamless experience for both administrators and users.

With our intuitive interface, students and faculty can easily browse and reserve equipment ranging from footballs and tennis rackets to cricket bats and beyond, while administrators maintain complete control over inventory and usage analytics.

### ✨ Core Features

#### User Authentication
- Secure Firebase Authentication system
- Role-based access control for administrators and users
- Personalized dashboards based on user type

#### Equipment Management
- Complete CRUD operations for sports equipment inventory
- Real-time availability updates via Firebase Firestore
- Equipment categorization and search functionality
- Equipment condition tracking and maintenance scheduling

#### Reservation System
- Intuitive equipment reservation workflow
- Automated confirmation and reminder notifications
- Visual calendar for reservation timeline management

#### Analytics & Reporting
- Customized report generation in PDF and CSV formats
- Equipment utilization metrics and insights
- Historical reservation data tracking
- Export capabilities for administrative purposes

### 🛠️ Technical Architecture

**Frontend**: React.js with Material UI components  
**Backend**: Node.js with Express framework  
**Database**: Firebase Firestore for real-time data management  
**Authentication**: Firebase Authentication services  
**Hosting**: Firebase Hosting platform

### 📋 Setup Guide

#### Prerequisites
- Node.js (v14+)
- npm or yarn package manager
- Firebase account access
- Git version control

#### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/araneeskhan/CampusSportsSphere
   ```

2. **Install dependencies**
   ```bash
   # Backend setup
   cd backend
   npm install

   # Frontend setup
   cd ../frontend
   npm install
   ```

3. **Firebase Configuration**
   - Create or use an existing Firebase project
   - Enable Authentication and Firestore services
   - Add your Firebase configuration to `firebaseConfig.js`

4. **Launch development environment**
   ```bash
   # Start backend server
   cd backend
   node index.js

   # Start frontend application
   cd ../frontend
   npm start
   ```

Your application will be running at [http://localhost:3000](http://localhost:3000)

### 👨‍💼 Administrator Functions

As an administrator, you'll have access to:
- Complete inventory management tools
- User account oversight and management
- Reservation approval workflows
- System configuration settings
- Comprehensive analytics dashboard
- Report generation capabilities


