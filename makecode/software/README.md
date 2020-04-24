Language: [中文](#檔案說明)、[English](#file-description)

---

# 檔案說明

## 額溫槍最終版本

* microbit-mlx90614-nocal_v2_en.hex -- (English Version)
* microbit-mlx90614-nocal_v2.hex -- (中文版本)

此次額溫槍工作坊的最終軟體程式版本。此版本會在量測後持續顯示溫度資訊，直到使用者按下右邊的 B 鍵後才會離開顯示模式，適用於感測器與溫度顯示不在同一側的裝置設計（因為你可能要翻過來看溫度）。


## 快速測試版本

* microbit-mlx90614_test.hex -- 快速測試模組是否正常運作

這是最極簡的偵測溫度程式，上電後會每隔一秒讀取並顯示偵測溫度。幫便讓你快速測試感溫模組是否運作正常。


## 其它實驗/測試版本

* microbit-mlx90614-cal.hex -- 使用按鍵進行校正 (實驗版本)

提供使用按鍵進行 runtime 溫度校正的功能。同時按下 A 鍵和 B 鍵，可以進入校正模式，在校正模式下，按 A 或 B 鍵調整校正溫度要增加或減少，確定校正溫度後，再次同時按下 A 鍵和 B 鍵即可。

請注意，由於 microbit 沒有儲存裝置可以記憶你的校正值，所以每次重新上電後都需要重新校正。

* microbit-mlx90614-nocal_v1.hex -- 跟 v2 的差別是，按下 A 鍵偵測後，溫度只顯示一次

這個版本與工作坊所使用的 v2 的版本類似。主要差異在 v1 會在量測後僅顯示一次溫度，適合感測器和溫度顯示在同一側的裝置設計。

---

# File Description

## Forehead thermometer final version

* microbit-mlx90614-nocal_v2_en.hex -- (English Version)
* microbit-mlx90614-nocal_v2.hex -- (Chinese Version)

The final version is what we use in workshop. This version will continue to display the temperature information after measurement and it will not leave the display mode until presses the B button on the right. The behavior is design for the device which sensor and display are not on the same side (because you may have to turn over to see temperature information).


## Quick test version

* microbit-mlx90614_test.hex -- quick test module is working properly

This is the most simple temperature detection program. After power on, it will read temperature and display it every second. This program can help you quickly test whether the temperature sensing module is working properly.


## Other experimental/test version

* microbit-mlx90614-cal.hex -- use buttons to do calibration (experimental version)

Use buttons to do temperature correction during the runtime. Press the A key and B key at the same time to enter the calibration mode. In the calibration mode, press the A or B key to adjust the temperature to increase or decrease. Press the A key and the B key again to exit the calibration mode.

Please note that microbit has no storage device to store your calibration values. You need to recalibrate each time when device power on.

* microbit-mlx90614-nocal_v1.hex -- The difference with v2 is that after pressing the A key to detect, the temperature only display once.

This version is similar to the v2 version which we used in the workshop. The main difference is that v1 will only display the temperature once after measurement. The behavior is design for the device which sensor and display are in the same side.
