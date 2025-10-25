 📁 File Handling Utility - Java

A comprehensive Java utility for advanced file operations with robust error handling and multiple file format support.

 🚀 Features
- Create & Write Files - Efficient file creation with overwrite protection
- Read Files - Fast file reading with buffered streams
- Append Content - Seamless content addition without data loss
- File Metadata - Size, creation date, and permissions info
- Error Handling - Comprehensive exception management

💻 Tech Stack
- Java 8+
- NIO Package for enhanced performance
- Buffered I/O operations

 📸 Demo Output
 
  🛠 Usage
java
// Write file
FileHandler.writeToFile("data.txt", "Hello World!");

// Read file  
FileHandler.readFile("data.txt");

// Append to file
FileHandler.appendToFile("data.txt", "\nNew content!");
