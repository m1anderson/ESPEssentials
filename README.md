# ESPEssentials

## What does it enable?
- Serial output (Baudrate: 115200)
- Wifi connection management using [WifiManager](https://github.com/tzapu/WiFiManager)
- Webserver including file upload and editing (Access via http://&lt;device-ip&gt;/edit)
- OTA update
- Web update (Access via http://&lt;device-ip&gt;/update)

## Usage
```cpp
#include <ESPEssentials.h>

void setup()
{
	initESPEssentials("Project Name");
}

void loop()
{
	handleESPEssentials();
}
```