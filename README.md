

# dynamicWallpaper <a href="https://ibb.co/5n4wStY"><img src="https://i.ibb.co/5n4wStY/dynamic-Wallpaper-Icon.png" alt="dynamic-Wallpaper-Icon" border="0" width="40" height="40" style="vertical-align: right;"></a>

A simple application to manage your desktop wallpaper dynamically. 

**Built with**: Python, PySide6.

# 📄Overview
This software allows users to select images and defines specific times for each of them to be displayed as the system wallpaper. With this tool, users can personalize their desktop backgrounds by scheduling different images to appear at differents times throughout the day.

# 📋 Features 

- Easily customize your desktop background with your favorite images🖼️.
- Select three images from your computer🌅🌇🌃.
- Set specific time intervals for each image to be displayed as the wallpaper⏰.


# 📝 Notes

- **Antivirus False Positives⚠️**: Sometimes, the application may trigger antivirus alerts as it lacks a digital signature, causing it to be flagged as coming from an unknown source on the internet. Rest assured, this is a false positive. Tests were conducted on VirusTotal to verify the safety of the application, where it passed nearly all security scans without any issues. You can view the detailed scan results [here](https://www.virustotal.com/gui/file/cc46c26aced564ba7b0ee1a4b77309a918cc4345e2d6382e7aa953e8b901541d). If you encounter any warnings, please consider adding the application to your antivirus exception list.

- **Compatibility🖥️**: This software is designed for Windows and may not be compatible with Mac or Linux. It is recommended to use this application on a Windows environment for optimal perfomance and functionality.

- **Image Relocation 📂**: If an image is moved to a different directory after being set as wallpaper, the application will not recognize the new location and will revert to the default Windows wallpaper.

- **Default Wallpaper 🛠️**: When the current time does not match any of the specified times for the selected images, the application will use the default Windows wallpaper. If you want to change this wallpaper to a custom one, please navigate to the following folder in your file explorer: `%APPDATA%\dynamicWallpaper` and replace the image "defaultWallpaperWindows" with your image, using the same name "defaultWallpaperWindows", and in jpg format.

# 📊 Usage

1. **First Run**: Initially, you need to run the application (once done, it will automatically run after Windows boot). 
<img src="https://i.ibb.co/YTTxM3g/image.png" alt="image" border="0">
After that, it will appear in your system tray. Right-click on it and select "Change Wallpaper".
<img src="https://i.ibb.co/8mbRbTb/image.png" alt="image" border="0">

2. **Select Images**: After the window opens, click on "+ Add Wallpaper". 
<img src="https://i.ibb.co/7jJvhTS/image.png" alt="image" border="0">
You will then see three images that will transition as your wallpapers. To load your images, click on "Load File".
<img src="https://i.ibb.co/yhyJDfZ/image.png" alt="image" border="0">


3. **Set Time Intervals**: Each image has its own interval for when the wallpaper will appear, with the left time indicating the start and the right time indicating the end.
<img src="https://i.ibb.co/ns9sQBT/image.png" alt="image" border="0">

4. **Apply**: Click the "Apply" button to save your settings and update the wallpaper according to your schedule. 
<img src="https://i.ibb.co/wcbxMHf/image.png" alt="image" border="0">
Once the changes are made, they will automatically take effect and do not need to be changed again. Note that the update may take a moment.

