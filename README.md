專案概述 (Project Overview)
這個專案是基於 Nordic nRF52 系列晶片開發的嵌入式系統應用。主要目的是實現一個藍牙低功耗 (BLE) 設備，用於智慧鞋墊的數據採集與傳輸。本程式碼包含了感測器資料讀取、BLE 連線管理及 UART 服務的實作。
主要功能 (Features)
✅ 藍牙連線： 支援 BLE Peripheral 模式，可與手機 App 連線。
📶 UART 服務： 實作 BLE UART (NUS) 服務，進行資料雙向傳輸。
🔋 低功耗設計： 優化 nRF52 功耗配置。
🔧 Keil C 環境： 使用 Keil uVision 進行開發與編譯。


使用技術 (Technologies Used)
技術/工具	版本/說明
Compiler/IDE	Keil MDK-ARM (uVision 5)
SDK	Nordic nRF5 SDK [v17.1.0]
Language	C 語言 (Embedded C)
Hardware	nRF52832 Development Kit


開始使用 (Getting Started)
Prerequisites (先決條件)
您需要安裝以下軟體：
Keil MDK-ARM
對應的 nRF5 SDK 版本
J-Link 或 ST-Link 除錯器 (Debugger)
編譯與燒錄 (Build and Flash)
開啟 ble_app_uart_pca10056_s140.uvprojx 檔案於 Keil uVision。
確保已選擇正確的目標設備 (Target Device)。
點擊 「Build」 按鈕編譯專案。
使用除錯器連接開發板，點擊 「Flash」 按鈕將程式燒錄到晶片中。


專案成果展示 (Demo & Results)
實際測試足壓影片
https://youtu.be/urFbbLQfJtk


貢獻 (Contributing)
歡迎提交 Pull requests 來改進此專案。


授權 (License)
本專案採用 [選擇您的 License，例如 MIT 或 Apache 2.0] 授權條款。


聯絡方式 (Contact)
作者： kamer71372(WeiJhe Huang)
Email： kamer71372@gmail.com
GitHub： github.com
