# 🚀 Space Door Airlock Portal (太空艙門入口)

電影級擬真科幻太空艙氣密門驗證入口系統。採用純前端技術（HTML5、CSS3、Web Audio API 與 Canvas 粒子系統）打造，具備沉浸式工業裝甲艙門、天花板實體全息投影投射儀、減壓氣爆白霧與 8K 太陽系深空全景（地球、月球、火星）。

---

## 🌟 特色功能 (Key Features)

1. **電影級工業裝甲氣密門 (Heavy Armor Blast Door)**：
   - 外部固定重型裝甲門框（Outer Bulkhead Frame）與內部雙扇滑動門（Inner Sliding Leaves）分層運作。
   - 驗證成功時，僅內部八角形門扇向兩側平穩滑入門框收納凹槽中，外部門框維持固定不動。
   - 門扇完全開啟後，鏡頭視角平滑向前推進（Camera Dolly-In）穿過氣密門洞直入深空，呈現最極致的真實機械邏輯。

2. **真實天花板全息投影機構 (Retractable Overhead Projector)**：
   - 天花板實體發光投影鏡頭（Emitter Head），投射出錐形散射體積光束（Volumetric Light Cone）。
   - **嚴格符合機械邏輯**：驗證通過後，全息投影 HUD 自動消散，投影機組 100% 垂直縮回天花板收納槽中。

3. **科幻互動認證 HUD (Cybernetic Hologram Access)**：
   - 懸浮全息認證面板，支援帳號密碼輸入、鍵盤 `Enter` 快速驗證。
   - 提供「快速帶入授權憑證」與「錯誤憑證測試」按鈕。
   - 門頂狀態指示燈：認證失敗時警報紅燈急促閃爍（Strobe）；認證成功時綠燈閃爍（Strobe）。

4. **8K 深空銀河全景與天體科技鎖定 (Celestial Target Reticles)**：
   - 艙門開啟推進深空視野後，直面浩瀚宇宙（地球、月球、火星）。
   - **月球互動鎖定**：滑鼠懸停至月球即展現科技感閃爍直角框線與雷達掃描刀，上方浮現「**案件管理系統**」科技標籤。
   - **地球互動鎖定**：滑鼠懸停至地球亦呈現科技感閃爍框線與掃描光束，上方浮現「**報告產生器**」科技標籤。
   - 具備 Web Audio 程序化鎖定聲效與懸停反饋。

5. **物理氣爆白霧與音效系統 (Steam Jets & Web Audio API)**：
   - 採用 HTML5 Canvas 即時動態模擬氣密閥減壓白霧噴射（Decompression Steam Burst）。
   - 內建純 Web Audio API 程序化科幻音效（高低頻氣密洩壓嘶嘶聲、全息操作音、授權成功音律與報警音），無需依賴外部音頻文件。

---

## 🔑 預設登入憑證 (Credentials)

您可以在全息介面中直接輸入，或點擊介面上的「**帶入授權憑證**」按鈕：

| 欄位 (Field) | 認證資料 (Value) | 說明 (Note) |
| :--- | :--- | :--- |
| **帳號 (Security ID)** | `commander` | 指揮官特權身分 (Operator ID) |
| **密碼 (Passcode)** | `earth-2026` | 艙門通行授權金鑰 |

> 💡 **測試提醒**：
> - 輸入正確帳密或按「**帶入授權憑證**」後按 Enter，艙門將解鎖並自動全開。
> - 若點選「**帶入錯誤憑證**」進行驗證，上方警報燈將呈現高頻閃爍並發出警報音。
> - 艙門全開後，視窗底部會浮現「**⟲ 重新關閉並鎖定艙門**」按鈕，點擊後艙門回闔，天花板投影儀會再度降下投射。

---

## 📁 檔案結構 (File Structure)

```text
space_door/
├── index.html            # 完整單頁應用（含 HTML結構、CSS3動畫、Web Audio 與 Canvas）
├── assets/
│   ├── scifi_door.jpg    # 8K 工業級科幻裝甲艙門貼圖 (左右對開)
│   ├── deep_space.jpg    # 8K 深空背景（地球、月球、火星與銀河）
│   └── three.min.js      # 本地依賴庫備份
└── README.md             # 專案說明文件
```

---

## 💻 快速開始 (Quick Start)

本專案無需任何 Node.js 建置工具或後端伺服器，直接使用瀏覽器即可開啟：

1. **複製專案**：
   ```bash
   git clone https://github.com/taichi16/space_door.git
   cd space_door
   ```

2. **直接執行**：
   - 在 macOS 上：
     ```bash
     open index.html
     ```
   - 或直接將 `index.html` 拖曳至任一主流瀏覽器（Chrome、Edge、Safari、Firefox）即可體驗電影級開門效果。
