# Custom Homepage

A browser Homepage with two different styles and some extras:

1. Linux-inspired Homepage CLI-style interaction using a custom terminal interface
2. Basic Homepage with a modern-looking interface
3. Extras - notes tool, colorscheme generator, scheduler

## CLI App

![Main Interface](https://github.com/user-attachments/assets/fce048df-5185-48ef-961c-cd173f694688)

## Basic App

![Basic Interface](https://github.com/user-attachments/assets/0a826aa4-7972-43c5-8570-a9c59290c36f)
![List view](https://github.com/user-attachments/assets/40eff55b-ac5b-4dbd-af38-22ccf0ffbc3d)


---

## Getting Started

### Basic Usage:
1. Download the HTML files
2. Open it in your browser
3. Interact through the terminal interface

### Interface Components:

1. CLI APP
- Terminal Display (shows input/output)
- Command Line (for command input)

2. Basic App
- Bookmark sections
- Clock
- Search bar for google

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
## Added second extra tool - Color picker

![Color Picker](https://github.com/user-attachments/assets/6b7153a7-c6f1-4206-a1f1-da29abf2ddad)

This tool allows you to generate and adjust color schemes and it shows you a preview of them in real time.

### Color Scheme tool - features

Action buttons:
 - Undo (previous theme)
 - Redo

Add colors:
 - 5 Extra colors added
 - The user can add more colors if needed

![Add Colors](https://github.com/user-attachments/assets/2730dbd5-6c82-4961-9bf1-cf9f58887764)

![Color Change Menu](https://github.com/user-attachments/assets/77ae4cee-af9b-4b75-802e-e1bafa195acf)

Color options:
 - Monochromatic
 - Analogous
 - Complementary
 - Triadic

![Color Options Dropdown](https://github.com/user-attachments/assets/9093792b-013f-4c85-822c-5186858fac27)

Theme options:
 - Light
 - Dark

Export(config) options:
 - Copy CSS
 - Copy JSON
 - Copy URL

![Export options](https://github.com/user-attachments/assets/78be7b06-b906-47f2-93d0-2c3a51c021c7)

## Third extra tool - Schedule Tool

## Scheduler

### Features

### People:
![People Section](https://github.com/user-attachments/assets/8c61b66e-5822-4c59-a807-3c594ffa854f)
 - allows user to create multiple profiles
 - each profile can be used for different schedules (e.g. school profile, gym profile, work profile)
 - each profile has its own schedules and tasks

### Templates:
![Templates Section](https://github.com/user-attachments/assets/37a172c8-8d6f-40f2-b45c-0aefbe855139)
 - allows the user to create templates for tasks
 - each template can be edited and deleted
 - allows the user to set a time, name, description for repeated tasks and load those tasks in the app

### Calendar:
![Calendar Section](https://github.com/user-attachments/assets/293512fd-22f4-426d-b8b2-dcb98400ddf1)
 - different views
 - year view - shows all months, days, weeks in the current year, the user can switch between years
 - month view - shows all months and days
 - week view - shows this week and every scheduled event, allows the user to create and edit tasks
 - day view - shows the tasks in the day, allows the user to create and edit tasks

### Settings:
![Settings section](https://github.com/user-attachments/assets/a35d7f4f-8ab5-4217-b72a-13e1852706b4)
 - Date format - different date formats such as DD-MM-YY, YY-MM-DD
 - Hour format - 24h or 12h (AM, PM) format
 - Notification - built in notifications to remind user about tasks

### Color options: 
![Color options section](https://github.com/user-attachments/assets/e6a9ab4d-cc30-4541-b162-2f5dc9be1f90)
- Allows the user to change all colors used in the tool

### Config:
![Configs option](https://github.com/user-attachments/assets/19abd328-e5a7-4eaa-862a-8f7745cac5d1)
 - Allows the user to save, edit, export and import configs
