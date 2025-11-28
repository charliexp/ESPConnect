# Changelog

## 1.0.3
- Skipping partition table read for ESP8266 (not supported)
- Improved flash size messaging: when detection fails, the UI now shows “Flash size not detected” instead of a vague “Unknown”
- Code refactoring

## 1.0.2
- Fix LittleFS no detected ([issue #10](https://github.com/thelastoutpostworkshop/ESPConnect/issues/10)) Many thanks to Jason2866 for the PR.
- Add delayed connection progress dialog (shows after 1s during connect) to improve user feedback.

## 1.0.1
- Fix octal flash size detection (map 0x30–0x3F RDID capacity codes when OCTAL feature present).
