# File System Management Project in Java

This Java project provides a simple command-line interface for basic file system management operations. Users can navigate directories, create and delete directories/files, copy files, rename files, and display file content.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/FileSystemManagementJava.git
   cd FileSystemManagementJava
   ```

2. **Compile and Run:**
   ```bash
   javac Project.java
   java Project
   ```

## Usage

The program presents a command-line interface where users can enter various commands. Supported commands include:

- `dir`: Show the files in the current directory.
- `mkdir`: Create a new directory.
- `rmdir`: Delete a directory.
- `rm`: Delete a file.
- `copy`: Copy a file.
- `touch`: Create a new file.
- `ren`: Rename a file.
- `cat`: Display the content of a file.

To navigate between directories, use the `cd` command followed by the desired directory path.

Example:
```bash
D:/ > cd myfolder/
D:/myfolder > dir
file1.txt
file2.txt
D:/myfolder > cat file1.txt
Hello, this is the content of file1.txt.
D:/myfolder > exit
Good bye
```

## Features

- **Directory Operations:**
  - View files in the current directory (`dir`).
  - Create a new directory (`mkdir`).
  - Delete a directory and its contents (`rmdir`).

- **File Operations:**
  - Delete a file (`rm`).
  - Copy a file (`copy`).
  - Create a new file with content (`touch`).
  - Rename a file (`ren`).
  - Display the content of a file (`cat`).

- **Navigation:**
  - Change directory using `cd`.


