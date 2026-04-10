# SentinelShield-Advanced-Intrusion-Detection-Web-Protection-System-Practical-Work-Documentation
This project demonstrates password vulnerabilities using brute-force and dictionary attacks. It shows how weak passwords can be cracked and explains mitigation techniques like password hashing and strong password policies.
1. Project Overview

SentinelShield is a beginner-level cybersecurity project designed to demonstrate the fundamentals of intrusion detection and web application protection. The system monitors user inputs, detects suspicious patterns (such as SQL injection attempts), and logs activities using a file-based storage system.

This project focuses on building a foundational understanding of security mechanisms without using complex databases or frameworks, making it ideal for beginners.

2. Objectives
To understand basic concepts of web security
To detect and prevent SQL Injection attacks
To implement a simple Intrusion Detection System (IDS)
To log and monitor suspicious activities using the file system
To gain hands-on experience in secure coding practices
3. Key Features
✅ Input validation and sanitization
✅ Detection of malicious patterns (e.g., SQL keywords like SELECT, DROP, etc.)
✅ File-based logging system (no database used)
✅ Basic authentication system
✅ Alert generation for suspicious inputs
✅ Lightweight and beginner-friendly implementation
4. Technologies Used
Programming Language: Python / PHP (based on your implementation)
Frontend: HTML, CSS
Backend: Basic scripting (Flask / PHP)
Storage: File system (text files for logs)
5. System Architecture

The system works in the following steps:

User enters input (login form / input field)
Input is passed through validation filters
System checks for suspicious patterns
If detected:
Logs the activity in a file
Blocks or flags the request
If safe:
Processes normally
6. Working Principle

SentinelShield uses pattern matching techniques to detect attacks:

Matches user input against predefined malicious keywords
Uses conditional logic to identify unusual patterns
Logs all suspicious activities for monitoring

Example:

Input: ' OR 1=1 --
Detected as: SQL Injection
Action: Blocked and Logged
7. File-Based Logging System

Instead of using a database, the system stores logs in files:

logs.txt – Stores suspicious activity
users.txt – Stores login credentials

This approach helps beginners understand:

Data handling
Security risks of improper storage
Importance of encryption (future improvement)
8. Limitations
❌ Not suitable for production use
❌ Limited detection (pattern-based only)
❌ No encryption for stored data
❌ Can be bypassed by advanced attacks
9. Future Enhancements
🔒 Implement database with hashing (bcrypt)
🤖 Add machine learning-based anomaly detection
🌐 Deploy as a web application
📊 Add real-time dashboard monitoring
🔐 Implement role-based authentication
10. Learning Outcomes
Basics of cybersecurity and intrusion detection
Understanding of SQL injection attacks
Importance of input validation
Experience with file handling and logging
Improved problem-solving and secure coding skills
11. Project Resources & Links
🎥 Project Explanation Video
https://1drv.ms/v/c/9e26cf78b0c1a310/IQAXnIJhBrhPQ6do1FU1VY4ZAZDIxOI9liqmpJC2Q9nBr8A?e=VVxEQx
🙏 Thanksgiving Video (Unified Mentor)
https://1drv.ms/v/c/9e26cf78b0c1a310/IQD_4O0N1hgZT5HJsMyb5FG5ATAM9x_23uVsZ1dy4lihUVo?e=okpNu2
SOURCE CODE LINK(ZIP FILE):https://1drv.ms/u/c/9e26cf78b0c1a310/IQA3-vOmbfn4Qp2-OQffQqEVAdrkjCI1fwIZokLD-YByb4M?e=mdCH7m
PROJECT REPORT:https://1drv.ms/w/c/9e26cf78b0c1a310/IQCUGfUS3rCjQb2OYhH_6ADPAX3f7ZZ9TRGUQpTkv6GiGkc?e=m6Sh3H
