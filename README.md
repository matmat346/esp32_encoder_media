- You should revert the esp32 board in your Arduino to version 2.0.11. link: https://github.com/espressif/arduino-esp32/releases/tag/2.0.11
- This only applies if version 2.0.11 cannot be downloaded in Arduino.
  After downloading the "esp32-2.0.11.zip" file, access this path (Win + R): " C:\Users\<username>\AppData\Local\Arduino15\packages\esp32\hardware\esp32 " ->
-> Delete the existing folder (which is the current esp32 version, e.g., 3.3.6). After deleting it, extract the 2.0.11 file and rename it from "esp32-2.0.11" to "2.0.11". If you are currently using Arduino, close and reopen it. Note: If you see a board update prompt, ignore it.
- The library used in the project is ESP32-BLE-Keyboard by T-vK. link:    https://github.com/T-vK/ESP32-BLE-Keyboard
- It's best to use an encoder module to avoid erratic volume control when adjusting the volume using the encoder knob.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Nên chuyển board esp32 trong arduino về phiên bản 2.0.11.  link: https://github.com/espressif/arduino-esp32/releases/tag/2.0.11
- Chỉ áp dụng nếu không thể tải phiên bản 2.0.11 trong arduino:
  Khi tải file "esp32-2.0.11.zip" về thì hãy truy cập vào đường dẫn này (Win + R): " C:\Users\<username>\AppData\Local\Arduino15\packages\esp32\hardware\esp32 " ->
-> Xóa thư hiện hiện có (là bản esp32 đang dùng ví dụ: 3.3.6)  sau khi xóa hãy giải nén file 2.0.11 và đổi tên file "esp32-2.0.11" thành "2.0.11" nếu bạn đang mở arduino thì hãy thoát ra và vào lại . lưu ý nếu thấy hiện cập nhật board thì hãy bỏ qua

- Thư viên được sử dụng trong dự án : ESP32-BLE-Keyboard của T-vK. link:  https://github.com/T-vK/ESP32-BLE-Keyboard
- Nên dùng module encoder để không bị loạn khi tăng giảm âm lượng khi vặn encoder
