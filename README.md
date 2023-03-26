# LaRoomyApi_Esp32
![](https://img.shields.io/badge/Platform-espressif32-002f3e)
![](https://img.shields.io/badge/Environment-PlatformIO-9cf)
![](https://img.shields.io/badge/Framework-Arduino-informational)
![](https://img.shields.io/github/last-commit/LaRoomy/LaRoomyApi_Esp32_PlatformIO)

This is the **LaRoomy Api** remote framework library. Implementing this library enables your Esp32 project to interact with the [LaRoomy App](https://www.laroomy.com). The library is written for the **espressif32** platform and is intended to be used with the **PlatformIO** embedded development platform or the arduino IDE.

The complete documentation for the library is provided on the [LaRoomy Api Website](https://api.laroomy.com/).
 
# How to use the Library

## Usage with PlatformIO

### Prerequisites

This library requires [Platform IO](https://platformio.org/platformio-ide) to be installed in [Visual Studio Code](https://code.visualstudio.com/).

- [Install Visual Studio Code](https://code.visualstudio.com/)
- [Install Platform IO for VS Code ](https://docs.platformio.org/en/latest/integration/ide/vscode.html#installation)


### Implementation

- Add the dependency to the **platformio.ini** file of your project:

```ini
lib_deps = https://github.com/LaRoomy/LaRoomyApi_Esp32_PlatformIO
```

- Include the repective header in your main project file

```c
#include <LaRoomyApi_Esp32.h>
```

- Now you can use the LaRoomy Api with the respective access operator

```cpp
LaRoomyApi.begin();
```

## Usage with Arduino IDE:

### Prerequisites

This library requires the Arduino IDE to be installed

- [Download and install Arduino IDE](https://support.arduino.cc/hc/en-us/articles/360019833020-Download-and-install-Arduino-IDE)

### Implementation

- Download this repository as .zip file (click on <>Code and select 'Download ZIP')
- Open the Arduino IDE
- Click on the 'Sketch' entry on the menu and select 'Include Library' > 'Add .ZIP Library'
- Select the downloaded .zip file and press OK
- When the library was successful installed, it can be used by clicking on 'Sketch' > 'Include Library' in the menu and select the LaRoomy Api library in the section for the contributed libraries
- Now you can use the LaRoomy Api with the respective access operator:

```cpp
LaRoomyApi.begin();
```

## Further Information

[Click here for detailed instructions on how to use the LaRoomyApi.](https://api.laroomy.com/p/laroomy-api-class.html)

