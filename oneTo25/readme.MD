# game.html
- 利用迴圈產生25個button
  各自有自己的ID,Name...
- 但是button onclick問題多多..

# game.1.html
- 利用 function btnClick(i){...};
  傳入各自的 i 達到每個按鍵能產生各自的事件

# game.1.1.html
- 利用 btn-num (原始) 跟 btn-numC (點對數字了) 的切換
  來表示已經按成功的數字

# game.2.html
- 加了一個 Timer

# game.2.1.html
- 新增功能至三個按鈕
- 利用 Slide 功能收縮遊戲畫面

# game.3.html + stopwatch.1.js
- 針對 btn25 設定 EndGame 條件
  從1點到25的時候，Timer會停止在按下 btn25 的時候
- 目前還有個小bug -> 直接點25的時候會直接停止計時
- p.s. 記得要用 window.onload 不然找不到 btn25

# game.3.html + stopwatch.2.js
- 判斷 btn24 是否為 disabled 來當作是否 End Game 的依據

# config.xml
- 利用 https://build.phonegap.com/ 產生 Android App
- 簡單做了個 Icon 
- App 設定為全螢幕

# game3.1.html + stopwatch.2.js
- 移動div
- 添加背景
- 修改button樣式
- 新增 animate.css 
  讓點錯按鈕的時候會晃動

# game3.2.html
- 想用html2canvas來做遊戲的截圖，不過失敗了