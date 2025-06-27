# custom-homepage
Kett - a custom homepage made to resemble a linux distro UI

![Image](https://github.com/user-attachments/assets/fce048df-5185-48ef-961c-cd173f694688)

This is a custom homepage I decided to create for myself. It was designed to look like a UI from a linux distro and operate like a CLI application using a custom terminal.

Instructions on how to use:
- download the html file
- run
- type into the terminal provided
Terminal (displays input/output)
Command line (allows for command input)

Current features: 
(Note: A help command is included so new users can see the features and their commands)
1. bookmark manager

![Image](https://github.com/user-attachments/assets/580b7e55-f030-4627-a369-6bb726c649d2)

2. color selector for all UI components

![Image](https://github.com/user-attachments/assets/c53808a4-2567-426c-bde0-0ca7727ebed3)

3. tool selector
   - allows users to link to to specific tools they would like to use - similar to bookmarks(only a separate feature because I want to add other .html files to this project in the future)

![Image](https://github.com/user-attachments/assets/19ad6f46-c4b2-45ee-b128-50ced60a912d)

4. google search
5. config system for saving/sharing all bookmarks, customizations, tools/settings

![Image](https://github.com/user-attachments/assets/23c8ede2-24fd-4629-b709-27ab0bfd745f)

6. preset themes

7. grid view
   - puts terminals into a grid for better terminal alignment

![Image](https://github.com/user-attachments/assets/d187e76d-ea13-461a-91c6-7ac848dfa724)

![Image](https://github.com/user-attachments/assets/592fd29f-6dc7-43b0-9fe2-33ca2625306f)


8. free view
   - allows users to turn off the grid and freely move terminals around in any way

![Image](https://github.com/user-attachments/assets/af2f5f2e-6c94-4166-b75d-29ad152682ab)

Current commands:

General
- help - Show available commands
- clear - Clear active terminal
- split - Create new terminal
- close - Close active terminal
  
Window(terminal) Management
- grid on - Enable grid layout
- grid off - Disable grid for free movement
- grid status - Show current grid mode
  
Customization
- color list - Show available color options
- theme list - Show available themes
- theme save [name] - Save current theme
- theme set [name] - Apply a theme
- config edit - Edit configuration
- config export - Export configuration
- config import - Import configuration
  
Utilities
- search [query] - Search on Google
- bookmarks - Show saved bookmarks
- tools - Show available tools
