# 倒數計時牌
You can count down on me!

## Run
```
  $ git clone https://github.com/katrina376/count-down-on-me.git
  $ cd count-down-on-me
  $ python3 -m http.server 5566 # 或是任何你用來跑 server 的指令
```

## Usage
在瀏覽器輸入以下網址：
```
  http://localhost:5566/?total=<時間全長(分鐘)>&t1=<第一次警告時間(分鐘)>&t2=<第二次警告時間(分鐘)>
```
畫面顯示倒數時間剩餘分鐘數。

可使用參數如下：
1. `total`：時間全長。預設為 60 分鐘。  
2. `t1`：第一次警告時間。預設為 5 分鐘，會提前 5 秒鐘警告，警告時背景顏色會變成綠色。  
3. `t1_v`：第一次警告音效 Youtube 影片 UID，會提前 1 秒鐘開始載入。預設為空白字串。  
4. `t1_t`：第一次警告音效 Youtube 影片開始時間，會提前 1 秒鐘開始載入。預設為 0 秒。  
5. `t2`：第二次警告時間（s）預設為 1 分鐘，會提前 5 秒鐘警告，警告時背景顏色會變成橘色。  
6. `t2_v`：第二次警告音效 Youtube 影片 UID，會提前 1 秒鐘開始載入。預設為空白字串。  
7. `t2_t`：第二次警告音效 Youtube 影片開始時間，會提前 1 秒鐘開始載入。預設為 0 秒。
6. `end_v`：最後警告音效 Youtube 影片 UID，會提前 1 秒鐘開始載入。預設為空白字串。  
7. `end_t`：最後警告音效 Youtube 影片開始時間，會提前 1 秒鐘開始載入。預設為 0 秒。

時間結束時會提前 5 秒鐘警告，背景顏色會變成紅色。最後字樣會變為「時間到」。
Youtube 影片開始時間使用方式請參見：https://support.google.com/youtube/answer/171780?hl=zh-Hant

## License
MIT

## Memo
1. 可以直接連上 https://katrina376.github.io/count-down-on-me/ 使用
2. 只測過電腦版的 Safari 跟 Chrome
3. 有瀏覽器通知的功能，可以暫時切到其他視窗去做事

## Example
https://katrina376.github.io/count-down-on-me/?total=5&t1=2&t2=1&t1_v=7koJ6aILxo4&t2_v=K5lE0wTDdZc&t2_t=2s&end_v=LbY4MfcJOEw&end_t=25s
