# Java Project Scanner

## Overview
Java Project Scanner is a Python-based tool designed to analyze Java projects. It extracts and analyzes various components of Java code, including classes, methods, API endpoints, message queues, database queries, and security vulnerabilities.

## Features
- **Extract Java Classes & Methods**: Analyze class structure, method signatures, inheritance, and parameters.
- **Track Function Calls & Dependencies**: Identify interdependencies between classes, services, and functions.
- **Extract API Endpoints & Services**: Detect Spring Boot API endpoints, including annotations like `@RequestMapping` and `@GetMapping`.
- **Analyze JMS & Message Queues**: Extract message-based communication patterns, including JMS and Kafka usage.
- **Identify Database Queries**: Detect SQL queries inside Java services and repositories.
- **Find Security Issues**: Scan for hardcoded credentials, SQL injection risks, and bad authentication patterns.

## Project Structure
```
java-project-scanner
├── src
│   ├── main.py
│   ├── analyzers
│   │   ├── class_analyzer.py
│   │   ├── function_analyzer.py
│   │   ├── api_analyzer.py
│   │   ├── message_queue_analyzer.py
│   │   ├── database_analyzer.py
│   │   └── security_analyzer.py
│   └── utils
│       └── helper.py
├── requirements.txt
├── setup.py
└── README.md
```

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/java-project-scanner.git
   ```
2. Navigate to the project directory:
   ```
   cd java-project-scanner
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
To run the Java Project Scanner, execute the following command:
```
python src/main.py <path_to_java_project>
```
Replace `<path_to_java_project>` with the path to the Java project you wish to analyze.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.