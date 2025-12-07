作者：118電機乙 E24146296 林聖祐
程式檔案名稱：
1. hw4.java
2. Player.java
3. Card.java
4. Tank.java
5. Assassin.java
6. Shooter.java
7. Priest.java 
使用說明：
編譯與執行-
1. 開啟終端機 (Terminal / CMD)，切換至檔案所在目錄。
2. 編譯指令：javac *.java
3. 執行指令：java hw4 player_info.txt playground.txt
遊戲操作-
1. 佈局階段
   - 放置卡牌：輸入 "put [卡牌名稱] [位置]"
     範例：put Tank 2 (位置僅限 1, 2, 3)
   - 顯示遊戲資訊：輸入 "show game status"
   - 結束佈局：輸入 "end layout stage"
2. 存檔與下一回合：
   - 每回合結束時，輸入 "Y" 可存檔並離開。
   - 輸入 "N" 則進入下一回合。
程式額外功能：
在攻擊邏輯中加入了機率爆擊系統。卡牌攻擊時有10%機會觸發2倍傷害的爆擊，並會顯示提示訊息。