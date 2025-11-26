# Ticket-Based Task Management System

A comprehensive mobile application for task and ticket management built with React Native and Expo, designed with role-based access control and following industry best practices for issue tracking and resolution workflows.

## 🚀 Features

### Core Functionality

- **Authentication System**: Secure login with role-based access (Administrator & Developer)
- **Dashboard Analytics**: Real-time ticket statistics and performance indicators
- **Ticket Management**: Advanced filtering, search, and categorization
- **Workflow Management**: Complete ticket lifecycle (Open → In Progress → Resolved → Closed)
- **File Attachments**: Support for screenshots and document uploads
- **Activity Logging**: Comprehensive tracking of all ticket modifications
- **Push Notifications**: Real-time alerts for ticket assignments and updates

### Key Features Breakdown

#### 📊 Dashboard Analytics

- Total tickets overview
- Open/In Progress/Resolved ticket counts
- Personal ticket assignments
- Interactive data visualization (pie charts)

#### 🎫 Ticket Management

- Create tickets with categories (Bug, Feature, Improvement)
- Set severity levels (Low, Medium, High, Critical)
- Assign tickets to developers
- Status-based filtering and search functionality

#### 👥 Role-Based Access Control

**Administrator Privileges:**

- View and manage all tickets
- Create and assign tickets
- Verify and close resolved tickets

**Developer Capabilities:**

- View assigned tickets only
- Update ticket status
- Add comments and attachments
- Upload resolution evidence

## 🛠️ Technical Stack

### Frontend

- **Framework**: React Native with Expo
- **Navigation**: Expo Router (file-based routing)
- **State Management**: React Context / Redux Toolkit
- **UI Components**: NativeBase / React Native Elements

### Backend & Storage

- **Authentication**: JWT tokens with secure storage
- **Database**: Local SQLite / Async Storage
- **File Management**: expo-image-picker, expo-camera
- **Notifications**: expo-notifications

### Performance Optimizations

- FlatList with memoization
- Infinite scrolling and pagination
- Optimized image handling
- Efficient state management

## 📋 Prerequisites

- Node.js (v18 or higher)
- npm or pnpm package manager
- Expo CLI
- Android Studio (for Android development)
- Xcode (for iOS development - macOS only)

## 🚀 Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/ticket-based-task-management.git
   cd ticket-based-task-management
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   pnpm install
   ```

3. **Start the development server**

   ```bash
   npx expo start
   ```

4. **Run the application**
   - **Android**: Press `a` to open Android emulator
   - **iOS**: Press `i` to open iOS simulator
   - **Web**: Press `w` to open in browser
   - **Expo Go**: Scan QR code with Expo Go app

## 📁 Project Structure

```
ticket-based-task-management/
├── app/                    # Main application screens
│   ├── (auth)/            # Authentication screens
│   ├── (tabs)/            # Tab navigation screens
│   └── _layout.tsx        # Root layout
├── components/            # Reusable UI components
├── constants/             # App constants and configurations
├── hooks/                 # Custom React hooks
├── store/                 # State management
├── utils/                 # Utility functions
├── assets/                # Static assets (images, fonts)
└── docs/                  # Documentation
```

## 🔧 Development Commands

```bash
# Start development server
npx expo start

# Start with tunnel (for network access)
npx expo start --tunnel

# Clear cache
npx expo start --clear

# Install dependencies
npm install

# Run linting
npm run lint

# Build for production
npx expo build
```

## 📱 Platform Support

- ✅ Android
- ✅ iOS
- ✅ Web (limited features)

## 🔐 Security Features

- Secure token storage using Expo SecureStore
- Role-based access validation
- Data encryption for sensitive information
- Safe file upload handling

## 📚 Documentation

For detailed application specifications and feature breakdown, please refer to:

- [Application Summary](docs/APP_SUMMARY.md) - Complete feature documentation

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support and questions:

- Create an issue in the GitHub repository
- Contact the development team
- Check the documentation for common troubleshooting

---

**Note**: This application was developed as a final project for Mobile Programming course at Universitas Muhammadiyah Pekalongan.
