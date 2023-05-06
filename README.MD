# ESP32WebServerTemplate - Without TypeScript
ESP32WebServerTemplate is a template project for developing web server applications using ESP32 microcontroller and Arduino framework. It provides a simple and easy-to-use framework for building web applications.


---

## Instalation

### What do you need? 
- [Git](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [PlatformIO IDE](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide)
---

1. Use this template

2. Clone the repository

3. Set up PlatformIO config if you need

4. Configure WiFi in `src/main.cpp`
   ```c++
   const char *SSID = "";
   const char *PASSWORD = "";
   ```
---
## Upload files to board

1. Build Filesystem Image
   
   ![Build](/doc/build.png)

2. Upload Filesystem Image
   
   ![Build](/doc/upload.png)