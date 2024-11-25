# Custom VS Code Setup

This repository contains my customized setup for Visual Studio Code, including settings, custom CSS, and custom JavaScript. This setup allows you to achieve a personalized look and feel for your code editor, complete with styling tweaks and enhancements.

## Features
- **Custom CSS and JavaScript**: Modify the appearance and behavior of VS Code using your own CSS and JS files.
- **Catppuccin Dark Theme**: A beautiful dark theme for a cohesive aesthetic.
- **Easy Integration**: Simple steps to set up and start using.

## Prerequisites
Before using this setup, make sure you have the following:
1. **Visual Studio Code** installed on your machine.
2. The [**Custom CSS & JS Loader**](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) extension
3. The [**Catppuccin Dark Theme**](https://marketplace.visualstudio.com/items?itemName=Birdlinux.catppuccin-dark-theme) installed:

## Installation Steps
1. **Clone this Repository**
   Clone the repository to your local machine or download the files directly:
   ```bash
   git clone https://github.com/your-username/custom-vscode-setup.git
   ```
   
2. **Locate the Files**
   Note the paths to the `custom.css` and `custom.js` files in the repository.
   
4. **Update VS Code Settings**
   Open your `settings.json` file in VS Code and add the following lines, replacing `/path/to/your/custom` with the actual file paths:

  ```json
  // Custom Styling
  "vscode_custom_css.imports": [
    "file:///path/to/your/custom.css",
    "file:///path/to/your/custom.js"
  ],
  ```

4. **Enable Custom CSS and JS**
  After adding the files:
    - Restart VS Code.
    - Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P) and run the command `**Enable Custom CSS and JS**`.
  
5. **Set the Color Theme**
  In VS Code, go to `File > Preferences > Color Theme` and select **`Catppuccin Dark Theme`**.
  
6. **Reload VS Code**
    Restart VS Code one final time to apply the customizations.

## Important Notes
  - **File URLs:** Ensure the paths `settings.json` use `file:///` format and point to the correct file locations
  - **Custom CSS & JS not working:** Rerun the command `**Enable Custom CSS and JS**`

   
