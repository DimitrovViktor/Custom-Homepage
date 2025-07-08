# Custom Homepage - Kett

A Linux-inspired browser homepage with CLI-style interaction using a custom terminal interface.

![Main Interface](https://github.com/user-attachments/assets/fce048df-5185-48ef-961c-cd173f694688)

---

## Getting Started

### Basic Usage:
1. Download the HTML file
2. Open it in your browser
3. Interact through the terminal interface

### Interface Components:
- Terminal Display (shows input/output)
- Command Line (for command input)

---

## Key Features

### 1. Bookmark Manager
![Bookmark Demo](https://github.com/user-attachments/assets/580b7e55-f030-4627-a369-6bb726c649d2)

### 2. UI Color Customization
![Color Customization](https://github.com/user-attachments/assets/c53808a4-2567-426c-bde0-0ca7727ebed3)

### 3. Tool Selector
![Tool Selector](https://github.com/user-attachments/assets/19ad6f46-c4b2-45ee-b128-50ced60a912d)

### 4. Configuration System
![Config System](https://github.com/user-attachments/assets/23c8ede2-24fd-4629-b709-27ab0bfd745f)

### 5. Layout Modes
- **Grid View**  
  ![Grid View](https://github.com/user-attachments/assets/d187e76d-ea13-461a-91c6-7ac848dfa724)
  ![Grid View](https://github.com/user-attachments/assets/592fd29f-6dc7-43b0-9fe2-33ca2625306f)
  
- **Free Movement Mode**  
  ![Free View](https://github.com/user-attachments/assets/af2f5f2e-6c94-4166-b75d-29ad152682ab)

### Additional Features:
- Google search integration
- Theme presets
- Config import/export
- Github commit checker

---

## Command Reference

### General Commands
| Command | Description                  |
|---------|------------------------------|
| help    | Show available commands      |
| clear   | Clear active terminal        |
| split   | Create new terminal          |
| close   | Close active terminal        |

### Window Management
| Command         | Description                          |
|-----------------|--------------------------------------|
| grid on         | Enable grid layout                   |
| grid off        | Disable grid for free movement       |
| grid status     | Show current grid mode               |

### Customization
| Command               | Description                      |
|-----------------------|----------------------------------|
| color list            | Show available color options     |
| theme list            | Show available themes            |
| theme save [name]     | Save current theme               |
| theme set [name]      | Apply a saved theme              |
| config edit           | Edit configuration               |
| config export         | Export configuration             |
| config import         | Import configuration             |

### Utilities
| Command       | Description                          |
|---------------|--------------------------------------|
| search        | Search Google (search [query])       |
| bookmarks     | Show saved bookmarks                 |
| tools         | Show available tools                 |

---

I suggest always starting with 'help' to see available commands.

---

## Added extra tool - Notes tool
![Notes Tool](https://github.com/user-attachments/assets/75b1ad68-0ecc-4ccf-b47f-1cb18dc4235d)
### Notes tool - features

Note cards:
 - Category
 - Title
 - Content
 - Start/Deadline dates
 - Status (manual progress tracking)
 - Color (for sorting)

![Note Creation](https://github.com/user-attachments/assets/dba5026a-6cdc-4504-810a-6be25820a1d9)

Filters Section (can be hidden):
![Filters](https://github.com/user-attachments/assets/32f3a0f1-db54-4d46-8fc5-402d91c1d0d5)
 - Date
 - Status
   
### Notes tool - configuration

Config:
 - Works the same as the one in homepage

Categories:
 - Can be added through config

Visual customization:
 - Background can be changed through config
 - Color picker just like in homepage

---
### New tool - Color picker

![Color Picker](https://github.com/user-attachments/assets/51836b0c-c607-491c-a5e6-4c212e7ef45b)
