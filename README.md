# 🏥 Doctor Dashboard

The **Doctor Dashboard** is a comprehensive React-based web application designed for hospitals and healthcare professionals. It provides doctors with a centralized system to manage their schedules, qualifications, attendance, and leave requests efficiently.


## 📌 Features

### 🔹 Core Modules

- **Doctor Dashboard** (`DoctorDashboard.jsx`)
  - Quick overview with key statistics (total patients, today's appointments, completed cases)
  - Important messages and announcements display
  - Upcoming appointments list with detailed patient information
  
- **Onboarding** (`Onboarding.jsx`)
  - New doctor registration with comprehensive form
  - Personal details, contact information, and availability management
  - Custom timing configuration
  - Automatic unique **Doctor ID** generation

- **Doctor Qualifications** (`DoctorQualifications.jsx`)
  - Complete qualification management system
  - Track specializations, degrees, universities
  - Experience and certification records
  - Research work documentation

- **Leave & Attendance** (`LeaveAttendance.jsx`)
  - Interactive monthly attendance calendar view
  - Present/absent day tracking
  - Leave application system with reasons and date selection
  - Additional details and comments support

- **Leave Status** (`LeaveStatus.jsx`)
  - Real-time leave application status tracking
  - Status indicators (Approved/Pending/Rejected)
  - Detailed approval information display

- **About Us** (`AboutUs.jsx`)
  - Hospital information and branding
  - Mission statement and organizational values
  - Contact and location details

### 🔹 Navigation Components

- **Navbar** (`Navbar.jsx`)
  - Hospital branding and logo
  - Quick access to About Us section
  - User authentication controls (Logout)

- **Sidebar** (`Sidebar.jsx`)
  - Intuitive navigation menu
  - Access to all modules: Dashboard, Onboarding, Qualifications, Attendance, Leave Status
  - Responsive design for mobile and desktop

## 🛠️ Tech Stack

- **Frontend Framework**: React.js
- **Routing**: React Router DOM
- **Icons**: React Icons (`react-icons/fa`)
- **Date Management**: `date-fns` library
- **Styling**: CSS3 with modular stylesheets
- **State Management**: React Hooks (useState, useEffect)

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14.0 or higher)
- npm or yarn package manager
- Git

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/anishbhujbal7/doctor_dashboard.git
   cd doctor-dashboard
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start Development Server**
   ```bash
   npm start
   ```

4. **Open in Browser**
   
   Navigate to: `http://localhost:3000`

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build` folder.

## 📂 Project Structure

```
doctor-dashboard/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Sidebar.jsx
│   │   ├── DoctorDashboard.jsx
│   │   ├── Onboarding.jsx
│   │   ├── DoctorQualifications.jsx
│   │   ├── LeaveAttendance.jsx
│   │   ├── LeaveStatus.jsx
│   │   └── AboutUs.jsx
│   ├── styles/
│   │   ├── Navbar.css
│   │   ├── Sidebar.css
│   │   ├── Dashboard.css
│   │   └── [other CSS files]
│   ├── App.js
│   ├── index.js
│   └── App.css
├── package.json
├── README.md
└── .gitignore
```

## 🎯 Usage

### For Hospital Administrators
1. Use the **Onboarding** module to register new doctors
2. Monitor doctor attendance through the **Leave & Attendance** system
3. Review and approve leave applications via **Leave Status**

### For Doctors
1. Access your personalized **Dashboard** for daily overview
2. Update **Qualifications** and professional information
3. Submit **Leave Applications** and track their status
4. View **Attendance** history and patterns

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the root directory:

```env
REACT_APP_API_URL=your_backend_api_url
REACT_APP_HOSPITAL_NAME=Your Hospital Name
```

### Customization
- Update hospital branding in `src/components/Navbar.jsx`
- Modify color schemes in CSS files
- Configure default working hours in `src/components/Onboarding.jsx`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ✅ Future Roadmap

### Phase 1 - Backend Integration
- [ ] REST API integration for real patient data
- [ ] Database connectivity for persistent storage
- [ ] User authentication and session management

### Phase 2 - Enhanced Features
- [ ] Role-based access control (Admin, Doctor, Nurse)
- [ ] Real-time notifications for appointments
- [ ] Email integration for leave approvals
- [ ] Mobile app development

### Phase 3 - Analytics & Reporting
- [ ] Interactive charts and dashboards
- [ ] Performance analytics
- [ ] Attendance reports and insights
- [ ] Patient management statistics

### Phase 4 - Advanced Features
- [ ] Video consultation integration
- [ ] Appointment scheduling system
- [ ] Document management system
- [ ] Multi-language support

## 🐛 Known Issues

- Calendar view may not display correctly on very small screens
- Leave application form needs validation improvements
- Performance optimization needed for large datasets

## 💬 Support

For support and questions:
- Create an issue in the GitHub repository
- Email: [anishbhujbal11@gmai.com]


## 👨‍⚕️ Author

**Anish Bhujbal**
- GitHub: [@anishbhujbal7](https://github.com/anishbhujbal7)


---

*Developed as part of a comprehensive hospital management system project to streamline healthcare administration and improve doctor workflow efficiency.*

## ⭐ Show Your Support

If this project helped you, please consider giving it a star on GitHub!

---

**Last Updated**: August 2025
