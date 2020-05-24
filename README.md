# SchooMy
This is the board setting for SchooMy and SchooMyMini.
Forked from [MiniCore](https://github.com/MCUdude/MiniCore).

## How to install
#### Boards Manager Installation
This installation method requires Arduino IDE version 1.6.4 or greater.
* Open the Arduino IDE.
* Open the **File > Preferences** menu item.
* Enter the following URL in **Additional Boards Manager URLs**:

    ```
    https://mcudude.github.io/MiniCore/package_MCUdude_MiniCore_index.json
    ``` 

* Open the **Tools > Board > Boards Manager...** menu item.
* Wait for the platform indexes to finish downloading.
* Scroll down until you see the **MiniCore** entry and click on it.
* Click **Install**.
* After installation is complete close the **Boards Manager** window.
* **Note**: If you plan to use the *PB series, you need the latest version of the Arduino toolchain. This toolchain is available through IDE 1.8.6 or newer. Here's how you install/enable the toolchain:
  - Open the **Tools > Board > Boards Manager...** menu item.
  - Wait for the platform indexes to finish downloading.
  - The top is named **Arduino AVR boards**. Click on this item.
  - Make sure the latest version is installed and selected
  - Close the **Boards Manager** window.

#### Manual Installation
Click on the "Download ZIP" button in the upper right corner. Exctract the ZIP file, and move the extracted folder to the location "**~/Documents/Arduino/hardware**". Create the "hardware" folder if it doesn't exist.
Open Arduino IDE, and a new category in the boards menu called "SchooMy" will show up.

## Pinout
<img src="https://cherrychain.cc/board/SchooMy_PIN.png">
