# 💰 Expense Tracker

A comprehensive expense management application that helps you track your spending habits and visualize your financial data through interactive charts and analytics.

## 🌟 Features

### Core Functionality
- **💸 Expense Tracking**: Record and categorize your daily expenses with Java-based logic
- **📊 Data Visualization**: Interactive pie charts powered by chart dependencies
- **📅 Time-based Analysis**: View expenses on daily and monthly basis with local database queries
- **🏷️ Category Management**: Organize expenses by custom categories stored locally
- **💹 Financial Insights**: Get detailed analytics processed locally for complete privacy
- **🔒 Offline Operation**: Complete functionality without internet connection
- **⚡ Fast Performance**: Local database ensures quick data retrieval and chart rendering

### Visualization & Analytics
- **📈 Pie Charts**: Visual representation of expense distribution by category
- **📊 Daily Analysis**: Track daily spending trends and patterns
- **📅 Monthly Reports**: Comprehensive monthly expense summaries
- **🎯 Budget Insights**: Compare actual spending against budgets

## 🛠️ Technology Stack

- **Programming Language**: Java
- **UI/Layout**: XML
- **Database**: Local Database (SQLite/Room/Internal Storage)
- **Charts**: Pie Chart Dependencies/Library
- **Platform**: Android Application (Java-based)

## 🚀 Getting Started

### Prerequisites
- **Java Development Kit (JDK)** 8 or higher
- **Android Studio** (for Android development)
- **Android SDK** (if building Android app)
- **Git** for version control

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/prashant000000004/ExpenseTracker.git
   cd ExpenseTracker
   ```

2. **Open in IDE**
   - Open the project in **Android Studio** or your preferred Java IDE
   - Wait for Gradle sync to complete (if Android project)

3. **Configure Local Database**
   ```java
   // The app uses local database storage
   // No additional database setup required
   // Data is stored locally on device
   ```

4. **Build and Run**
   - **For Android Studio**:
     - Click "Run" button or press Shift + F10
     - Select target device/emulator
   - **For Java Application**:
     ```bash
     javac *.java
     java MainClass
     ```

5. **Install Dependencies**
   - Pie chart dependencies are included in the project
   - Sync project to download required libraries

## 📖 Usage

### Adding Expenses
1. Navigate to the "Add Expense" section
2. Enter the expense amount
3. Select or create a category
4. Add a description (optional)
5. Set the date
6. Save the expense

### Viewing Analytics
1. **Daily View**: 
   - Go to the Dashboard
   - Select "Daily" view to see today's expenses
   - View pie chart breakdown by category

2. **Monthly View**: 
   - Switch to "Monthly" view
   - Analyze spending patterns over the month
   - Compare different months

### Managing Categories
1. Create custom expense categories
2. Edit existing categories
3. View category-wise spending

## 📊 Features in Detail

### Pie Chart Analytics
- **Local Data Processing**: All data processed locally for privacy
- **Daily Breakdown**: Visual representation of daily expenses by category using pie charts
- **Monthly Overview**: Comprehensive monthly spending analysis with interactive charts
- **Offline Analytics**: No internet required - all calculations done locally
- **Color-coded Categories**: Easy identification of spending areas with distinct colors
- **Real-time Updates**: Charts update immediately when expenses are added/modified

### Local Database Features
- **SQLite Integration**: Fast and reliable local data storage
- **Data Persistence**: All expense data saved locally on device
- **No Internet Required**: Complete offline functionality
- **Quick Queries**: Optimized database queries for fast chart generation
- **Data Privacy**: All financial data remains on your device

### Expense Management
- **Quick Entry**: Fast expense logging with minimal clicks
- **Bulk Import**: Upload expenses from CSV files (if supported)
- **Search & Filter**: Find specific expenses quickly
- **Edit & Delete**: Modify or remove incorrect entries

## 🎨 Screenshots

#### Home & Add
<p align="center">
  <img src="https://github.com/prashant000000004/ExpenseTracker/blob/21e07966c2a53df1cb1e2dc921dc6a87dd63fc54/efirst.jpeg" width="200" alt="Home Screen">
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/prashant000000004/ExpenseTracker/blob/21e07966c2a53df1cb1e2dc921dc6a87dd63fc54/esecond.jpeg"width="200" alt="Add Screen">
</p>
<p align="center">
  <strong>Home Screen</strong>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <strong>Add Screen</strong>
</p>

#### Select Types,Expense Add and Pie Chart
<p align="center">
  <img src="https://github.com/prashant000000004/ExpenseTracker/blob/21e07966c2a53df1cb1e2dc921dc6a87dd63fc54/ethird.jpeg" width="200" alt="Select Types">
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/prashant000000004/ExpenseTracker/blob/21e07966c2a53df1cb1e2dc921dc6a87dd63fc54/efourth.jpeg"width="200" alt="Expense Add Screen">
   &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/prashant000000004/ExpenseTracker/blob/21e07966c2a53df1cb1e2dc921dc6a87dd63fc54/efifth.jpeg"width="200" alt="Pie Chart">
</p>
<p align="center">
  <strong>Select Types</strong>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <strong>Expense Add Screen</strong>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <strong>Pie Chart</strong>
</p>



## 🗂️ Project Structure

```
ExpenseTracker/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/              # Java source files
│   │   │   │   ├── activities/    # Activity classes
│   │   │   │   ├── adapters/      # RecyclerView adapters
│   │   │   │   ├── database/      # Local database classes
│   │   │   │   ├── models/        # Data models
│   │   │   │   └── utils/         # Utility classes
│   │   │   ├── res/
│   │   │   │   ├── layout/        # XML layout files
│   │   │   │   ├── values/        # Strings, colors, styles
│   │   │   │   ├── drawable/      # Images and icons
│   │   │   │   └── menu/          # Menu XML files
│   │   │   └── AndroidManifest.xml
│   │   └── test/                  # Test files
│   ├── build.gradle               # App-level build configuration
│   └── proguard-rules.pro
├── gradle/                        # Gradle wrapper files
├── build.gradle                   # Project-level build configuration
└── README.md
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

## 📝 License

This project is licensed under the [LICENSE](LICENSE) - see the LICENSE file for details.

## 🐛 Bug Reports & Feature Requests

If you encounter any bugs or have feature requests, please:
1. Check existing [Issues](https://github.com/prashant000000004/ExpenseTracker/issues)
2. Create a new issue with detailed information
3. Include steps to reproduce (for bugs)

## 👨‍💻 Author

**Prashant**
- GitHub: [@prashant000000004](https://github.com/prashant000000004)
- Email: [prshntydv6061@gmail.com]

## 🙏 Acknowledgments

- Thanks to all contributors
- Inspiration from personal finance management needs
- Community feedback and suggestions

## 📈 Roadmap

### Upcoming Features
- [ ] Mobile responsive design
- [ ] Expense categories customization
- [ ] Budget setting and tracking
- [ ] Export reports to PDF/Excel
- [ ] Multi-currency support
- [ ] Recurring expense management
- [ ] Data backup and sync

### Future Enhancements
- [ ] AI-powered expense categorization
- [ ] Integration with banking APIs
- [ ] Advanced reporting and analytics
- [ ] Mobile application
- [ ] Team/family expense sharing

## 🔧 Development

### Building the Project
```bash
# For Android Studio
./gradlew build

# For clean build
./gradlew clean build
```

### Running Tests
```bash
# Run unit tests
./gradlew test

# Run instrumented tests (Android)
./gradlew connectedAndroidTest
```

### Database Schema
```sql
-- Example table structure for local database
CREATE TABLE expenses (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    amount REAL NOT NULL,
    category TEXT NOT NULL,
    description TEXT,
    date TEXT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

CREATE TABLE categories (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    name TEXT UNIQUE NOT NULL,
    color TEXT
);
```

### Adding Pie Chart Dependencies
```gradle
// Add to app/build.gradle dependencies
implementation 'com.github.PhilJay:MPAndroidChart:v3.1.0'
// or your specific pie chart library
```

## 📞 Support

If you need help or have questions:
- 📧 Email: [prshntydv6061@gmail.com]
---

⭐ **Star this repository if you find it helpful!** ⭐

Made with ❤️ for better financial management
