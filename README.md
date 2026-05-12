# REGISTER

A JavaFX-based desktop application for managing student course registration and enrollment.

## Overview

REGISTER is a comprehensive student course registration system built with Java and JavaFX. This project provides a graphical user interface for managing students, courses, and course enrollments with persistent data storage using SQLite databases.

**Language Composition:**
- Java: 78.8%
- CSS: 21.2%

## Features

- **Student Management**: Add, view, and manage student information
- **Course Management**: Browse and manage available courses
- **Course Registration**: Register students for courses with real-time database updates
- **Persistent Storage**: SQLite database backend for reliable data persistence
- **Modern UI**: JavaFX-based graphical interface with Bootstrap styling
- **Form Validation**: Integrated form validation for data integrity

## Tech Stack

### Core Framework
- **JavaFX**: Modern Java GUI framework (v21.0.6)
- **Maven**: Build automation and dependency management
- **Java 21**: Latest Java LTS version

### Key Dependencies
- **SQLite JDBC**: Database driver for SQLite
- **Jackson**: JSON processing
- **Logback**: Logging framework
- **ControlsFX**: Extended JavaFX controls
- **BootstrapFX**: Bootstrap styling for JavaFX
- **ValidatorFX**: Form validation library
- **JUnit 5**: Testing framework

## Project Structure

```
REGISTER/
├── src/                   # Source code
│   ├── main/
│   │   ├── java/        # Java application code
│   │   └── resources/   # FXML layouts and CSS stylesheets
│   └── test/            # Unit tests
├── .mvn/                # Maven wrapper configuration
├── target/              # Compiled output (build artifacts)
├── pom.xml              # Maven project configuration
├── mvnw                 # Maven wrapper (Unix/Linux)
├── mvnw.cmd             # Maven wrapper (Windows)
├── students.db          # SQLite database for student data
├── courses.db           # SQLite database for course data
└── README.md            # This file
```

## Getting Started

### Prerequisites
- Java 21 or higher
- Maven 3.6+

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Haileab33/REGISTER.git
   cd REGISTER
   ```

2. **Build the project:**
   ```bash
   # Using Maven wrapper (Unix/Linux)
   ./mvnw clean install
   
   # Or using Maven wrapper (Windows)
   mvnw.cmd clean install
   ```

3. **Run the application:**
   ```bash
   # Using Maven wrapper
   ./mvnw clean javafx:run
   ```

## Database

The application uses two SQLite databases:
- **students.db**: Stores student information
- **courses.db**: Stores course information

These databases are automatically initialized on first run.

## Development

### Building
```bash
./mvnw clean package
```

### Running Tests
```bash
./mvnw test
```

### Development Mode
```bash
./mvnw clean javafx:run
```

## Maven Configuration

- **Java Version**: 21
- **Source Encoding**: UTF-8
- **Compiler**: Apache Maven Compiler Plugin v3.13.0
- **JavaFX Plugin**: Maven JavaFX plugin v0.0.8

## Project Metadata

- **Artifact ID**: Register
- **Group ID**: com.example
- **Version**: 1.0-SNAPSHOT
- **Main Class**: `com.example.register.HelloApplication`

## Fork Information

This is a fork of [Group-Git-Repositories/REGISTER](https://github.com/Group-Git-Repositories/REGISTER)

## License

No specific license is defined. Check the original repository for licensing information.

## Contributing

To contribute to this project:
1. Create a feature branch
2. Make your changes
3. Test your modifications
4. Submit a pull request

## Support

For issues, questions, or suggestions, please open an issue in the repository.

---

**Created**: May 2026  
**Repository**: https://github.com/Haileab33/REGISTER
