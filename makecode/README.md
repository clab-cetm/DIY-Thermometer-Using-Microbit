
# Micro:bit 軟體

這篇文章說明如何將工作坊所需的軟體更新至 micro:bit 開發板上。所有的軟體皆使用 [Microsoft MakeCode for micro:bit](https://makecode.microbit.org/) 開發，附檔名為 .hex。


## 程式邏輯說明

將感測器靠近額頭約 1~2 公分，按下 micro:bit 左邊的 A 鍵即可顯示量測到的溫度。

右邊的 B 鍵用來顯示溫度校正值，預設為 0，即不需要校正。


## 檔案說明

software 目錄內有幾個 .hex 檔。它就是 micro:bit 的軟體，你可以透過 usb 傳輸線將這些 .hex 檔傳入 micro:bit 中，即完成軟體更新工作。所有的軟體可以隨時替換，你可以隨時根據你的需求選擇更新哪一種軟體。詳細說明請看 [software 目錄內的 README.md](software/)


## 如何更新軟體

事實上，所謂的「更新軟體」的工作，對 micro:bit 而言，就像把檔案複製到 USB 隨身碟一樣簡單。

首先使用 micro usb 連接 micro:bit 和你的電腦。你應該會發現一旦 micro:bit 接上電腦，micro:bit 立刻被電腦認定為一支 USB 隨身碟。如果你使用 windows 系統，開啟檔案總管會發現系統多了一個 MICROBIT 的磁碟機。

現在，選擇一個 .hex 軟體檔案，將 .hex 檔案複製到標示 MICROBIT 的磁碟機。micro:bit 就會自動接受軟體、更新、然後重新啟動並運作你的程式。


![](images/program-win.gif)


## 參考資料

想快速認識 micro:bit 嗎？請參考《[十分鐘了解 Micro:bit](docs/10-minute-microbit-guide.md)》的工作坊手冊。


~ END ~
