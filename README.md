## Hi there 👋

<!--
**AnnTaiwan/AnnTaiwan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### 姓名: 周安  
### 目前就讀於: 國立中山大學資訊工程學系大四  
### 以下說明幾個Repositories的內容，第2到第5個是大學修課，課堂上的專案:  
1. **Graduate-Project** : 畢業專題<<AI生成語音辨識的應用>> <<Developing an application about detecting AI generated voice>>中我負責的程式碼。
  當今詐騙頻傳，有心人士常使用 AI 生成語音撥打詐騙電話，專題成果為成功實作出一
  個嵌入式系統能夠收音並辨識錄製到的語音為真實語音或是 AI 生成語音，進而防止語
  音詐騙，開發了中英文語音的生成語音辨識應用。需要自行生成中文語音資料，來補足
  中文資料較缺乏的情況。時頻譜圖是用來當作模型的輸入資料，因此過程中實作了 C++
  版本的將音檔繪製成時頻譜圖做法，是為了在硬體上能夠縮短繪製時間。還需要自行設
  計 PyTorch CNN 模型，學習調整模型架構。最終需要將模型映射至硬體加速器上，使硬
  體能夠做模型的 AI 推論，就能夠利用此硬體來連接麥克風，做實際的收音與發揮邊緣
  計算的能力，將辨識結果以 LINE 通知使用者。也將此模型設計成一個網頁和 LINE Bot
  聊天室讓使用者上傳音檔去做辨識，開發出更多元的應用方式。
  **flask-ngrok-ml**: 為網頁設計的程式碼
  **Vitis-ai-on-ubuntu**: 為在ubuntu上利用vitis-ai的各種操作，包含了模型的量化、訓練、編譯，產生最終適合KV260開發版的xmodel，將此xmodel放到硬體上去執行AI推論。 
2. **Assembly_language_Final_Project** - *組合語言與微處理機實驗*
  本專題以 ADXL345 加速度模組來實作一個計步器，並設計一個計算步
  數的有效演算法， 使本計步器能夠模擬真實的走路情況，並結合紅外線感測器、聲音感測器當作感
  測系統，感知周遭情況，而 LED 燈泡、蜂鳴器當作預警系統。為了視覺化數據，藉由 ESP32 上傳相
  關數據到 IDEAS CHAIN，去觀察數據，了解步行的趨勢。 鎖定視障者為主要客群，期望能幫助提
  升使用者的運動安全，減少因使用者未注意而發生意外的情況。期望為視障者社群提供更多福祉，
  並進一步增強他們的運動體驗。
3. **computer_network** - *電腦網路*
  實作了網路封包的傳遞，建立了 client 與 server 端架構，實現了 three-way handshake、DNS 
  query，並在 server 端進行數學式的計算和完整的檔案傳輸給 client。此專案還模擬了 TCP 中的擁塞
  控制機制，包括 slow start、congestion avoidance、fast recovery，並模擬了 packet loss、delayed ACKs 
  以及 fast retransmit 機制。
4. **Compiler-class** - *編譯器製作*
  在這個專案中，我利用 Lex 實作了一個 Pascal Scanner，負責從 Pascal 程式碼中掃描並識別出
  reserved word、運算符號、數字、字元符號、字串、變數等 tokens。再透過 Yacc 實作 Pascal Parser，
  將這些掃描到的 tokens 按照語法規則進行解析，構建語法樹，並檢查 Pascal 程式碼是否符合語法規
  範。這個專案的目的是建立一個可以對 Pascal 程式語言進行基本詞法與語法分析的編譯器前端。
5. **SOPC** - *SOPC 設計實務及 FPGA 系統整合設計-用 Verilog 實作矩陣乘法加速器*
  用 Verilog 完成矩陣乘法加速器的 RTL 設計，並通過 Synthesis 和 Implementation，最終將電路上
  板到 ZedBoard 上做計算。此設計是在 ZedBoard 上實作 16 bits 整數的矩陣乘法，並建立 AXI slave IP，
  使用 AXI-Lite 協定讓 CPU 和記憶體之間做溝通，透過讀取記憶體內的數值並送進撰寫的矩陣乘法
  加速器中，乘完後的矩陣數值為 32 bits 整數。使用 SDK 用 C 語言控制
  資料的讀寫，並使矩陣乘法硬體進行計算。
