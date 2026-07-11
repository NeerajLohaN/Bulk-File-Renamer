# 📂 Bulk File Renamer

## Project Overview

The **Bulk File Renamer** is a Microsoft Power Automate Desktop (PAD) automation that renames multiple files in a folder using sequential numbering while preserving the original file extensions.

This project demonstrates the use of variables, loops, file manipulation, and text formatting in Power Automate Desktop.

---

## Business Problem

Many organizations receive hundreds of files from scanners, cameras, vendors, or other systems.

Renaming these files manually is:
- Time consuming
- Error prone
- Repetitive

This automation performs the renaming in seconds.

---

## Solution

The automation performs the following steps:

1. Read all files from a folder.
2. Initialize a counter.
3. Loop through each file.
4. Extract the file extension.
5. Convert the counter into text.
6. Add leading zeros (001, 002, 003...).
7. Generate a new filename.
8. Rename the file.
9. Increase the counter.

---

## Workflow

```text
Start
   │
   ▼
Get Files in Folder
   │
   ▼
Initialize Counter
   │
   ▼
For Each File
   │
   ├── Get File Extension
   ├── Format Counter
   ├── Create New File Name
   ├── Rename File
   └── Increase Counter
   │
   ▼
End
```

---

## Technologies Used

- Microsoft Power Automate Desktop
- Windows File System

---

## Power Automate Concepts

- Variables
- Lists
- Loops
- File Actions
- String Manipulation
- Number Formatting

---

## Screenshots

### Flow

(Add flow screenshot here)

### Before

(Add before screenshot here)

### After

(Add after screenshot here)

---

## Example

### Before

```
IMG001.jpg
IMG002.jpg
IMG003.jpg
```

### After

```

Vacation_001.jpg
Vacation_002.jpg
Vacation_003.jpg
```

---

## Skills Demonstrated

- Desktop Automation
- File Automation
- Process Automation
- Sequential File Processing
- Variable Handling
- Looping
- RPA Development

---

## Future Enhancements

- Folder Selection Dialog
- Custom Prefix
- Custom Start Number
- Extension Filter
- Logging
- Error Handling
- User Interface

---

## Author

**Neeraj Lohan**

Learning Microsoft Power Automate Desktop and preparing for the **Microsoft Certified: Power Automate RPA Developer Associate (PL-500)** certification.
