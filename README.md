# Grey Hack Scripts
A collection of scripts made for [Grey Hack](https://store.steampowered.com/app/605230/Grey_Hack/).

## Scripts
- `CoreKit` - Core utilities and helpers. Used by most scripts (except PrepKit itself).
- `PrepKit` - Hybrid C-style preprocessor for GreyScript. Required to compile the other scripts.

    ![SCREENSHOT](/screenshots/prepkit.png?raw=true "PrepKit")
- `AirKit` - Quickly finds and connects to a vulnerable WiFi network.

    ![SCREENSHOT](/screenshots/airkit.png?raw=true "AirKit")
- `AirScan` - Scans the network (or target IP address) and provides extensive information (open ports and used libraries for each, number of available accounts, etc.).

    ![SCREENSHOT](/screenshots/airscan.png?raw=true "AirScan")

## Installation
All scripts are intended to be compiled with `PrepKit`.

1. Compile `PrepKit.src` (e.g., into /bin) using the in-game code editor.
2. Then use it to compile other scripts. Example:
    ```shell
    prepkit AirKit.src -o /bin
    ```

## Resources
- [GreyScript API Documentation](https://documentation.greyscript.org)
