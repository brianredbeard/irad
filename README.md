# irad
a PoC ESP32 radio which only plays https://somafm.com/live.pls

WIFI credentials are set via the following [environment variables](https://github.com/brianredbeard/irad/blob/bcaa5c41629720c9737da86640d278f1e3799ba8/platformio.ini#L14-L15):

  - `WIFI_SSID`
  - `WIFI_PASSWORD`

Since this is a [PlatformIO](https://docs.platformio.org/en/latest/) project it should be easy to build:

```bash
$ pio run -t upload --upload-port /dev/ttyXXXX
```

This is no replacement for the PlatformIO documentation.
