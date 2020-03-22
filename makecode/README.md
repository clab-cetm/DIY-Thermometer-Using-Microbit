# Micro:bit 韌體

這篇文章說明如何將工作坊所需的韌體燒錄至 micro:bit 開發板上。所有的韌體皆使用 [Microsoft MakeCode for micro:bit](https://makecode.microbit.org/) 開發，附檔名為 .hex。


## 檔案說明

此目錄內有四個主要檔案：

* microbit-mlx90614`-cal`-blocks.pdf
* microbit-mlx90614`-cal`.hex
* microbit-mlx90614`-nocal`-blocks.pdf
* microbit-mlx90614`-nocal`.hex

其中 .hex 是 micro:bit 的韌體，你可以透過 usb 傳輸線將這些 .hex 檔傳入 micro:bit 中，即完成軟體燒錄工作。

目前工作坊提供兩種 .hex 檔，microbit-mlx90614-cal.hex 以及 microbit-mlx90614-nocal.hex。差別在於檔名標示 `-cal` 的代表具有校正功能。檔名為 `-nocal` 的代表沒有校正功能。

需不需要使用校正功能，端看 MLX90614 感測器的精度和誤差值而定。韌體可以隨時替換，你可以隨時根據你的需求選擇燒錄哪一種韌體。.pdf 檔則是對應 .hex 檔的程式積木圖。


## 如何燒錄韌體

事實上，所謂的「燒錄韌體」的工作，對 micro:bit 而言，就像把檔案複製到 USB 隨身碟一樣簡單。

首先使用 micro usb 連接 micro:bit 和你的電腦。你應該會發現一旦 micro:bit 接上電腦，micro:bit 立刻被電腦認定為一支 USB 隨身碟。如果你使用 windows 系統，開啟檔案總管會發現系統多了一個 MICROBIT 的磁碟機。

現在，選擇一個 .hex 韌體檔案，將 .hex 檔案複製到標示 MICROBIT 的磁碟機。micro:bit 就會自動接受韌體、燒錄、然後重新啟動並運作你的程式。


![](images/program-win.gif)


## 參考資料

想快速認識 micro:bit 嗎？請參考《[十分鐘了解 Micro:bit](10-minute-microbit-guide.md)》的工作坊手冊。

~ END ~