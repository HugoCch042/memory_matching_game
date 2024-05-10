## memory_matching_game

### 1. HTML結構

- 創建網頁標題為 "memory_matching_game"
- 在網頁中添加主要區塊，包含16/(4x4)個可點擊的網格
- 在頁腳部分顯示遊戲狀態信息

### 2. CSS樣式

- 為所有元素設定字體為 Arial
- 為網格設定灰色背景和點擊指示符
- 網格區塊居中顯示，每個網格項目均勻分布
- 設定重新開始的按鈕
### 3. Javascript邏輯

- 初始化：設定點擊次數從 0 開始
    - 當遊戲開始時隨機編配網格
    - 初次點
    - 
- 檢查獲勝者：
    - 所有配對相同，會標記為獲勝者
- 遊戲結束：
    - 當出現所有網格被點擊後，顯示結果（you win）
    - 提供重新開始遊戲(restart the game)的選項
    - 遊戲重新開始時將重新洗牌

### 4. 添加進階功能，例如：

- 實現一個得分追蹤器，記錄兩名玩家的勝利、失敗和平局次數。
- 添加一個AI對手。從製作一個隨機移動的簡單AI開始，然後嘗試創建一個使用策略的更精密的AI。
- 透過添加動畫或聲音效果來改善用戶介面。
- 添加一個讓玩家選擇他們想要的是 "X" 或 "O" 的功能。
- 加入多人遊戲功能，允許用戶在不同的裝置上相互對戰。
