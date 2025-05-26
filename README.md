# 🚂 Train Booking System

A robust and user-friendly console-based train ticket booking system implemented in Java. This project demonstrates the practical application of object-oriented programming, database management, and software engineering principles.

## ✨ Features

- 🔐 **Secure Authentication**
  - User registration and login
  - Password hashing
  - Session management
  - Role-based access control

- 🎫 **Ticket Management**
  - Train search by route
  - Real-time seat availability
  - Seat selection
  - Booking confirmation
  - Booking history
  - Cancellation processing

- 🚉 **Train Information**
  - Comprehensive train details
  - Route information
  - Schedule management
  - Seat layout display

- 🔒 **Security Features**
  - Encrypted password storage
  - Secure session handling
  - Input validation
  - Error handling

## 🛠️ Technical Stack

- **Language:** Java 11
- **Build Tool:** Gradle
- **Database:** Local file-based storage
- **Testing:** JUnit, Mockito
- **Logging:** SLF4J, Logback

## 📋 Prerequisites

- Java JDK 11 or higher
- Gradle 7.0 or higher
- Git

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/train-booking-system.git
   ```

2. **Navigate to project directory**
   ```bash
   cd train-booking-system
   ```

3. **Build the project**
   ```bash
   ./gradlew build
   ```

4. **Run the application**
   ```bash
   ./gradlew run
   ```

## 💻 Usage

1. **User Registration**
   - Create a new account
   - Set up secure password

2. **Train Search**
   - Enter source station
   - Enter destination station
   - View available trains

3. **Booking Process**
   - Select preferred train
   - Choose available seat
   - Confirm booking

4. **Booking Management**
   - View booking history
   - Cancel bookings
   - Check seat status

## 🏗️ Project Structure
train-booking-system/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── ticket/
│ │ │ └── booking/
│ │ │ ├── entities/
│ │ │ ├── service/
│ │ │ ├── util/
│ │ │ └── App.java
│ │ └── resources/
│ └── test/
└── build.gradle
