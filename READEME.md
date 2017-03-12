# 倒數計時牌
You can count down on me!

## Run
```
  git clone https://github.com/katrina376/count-down-on-me.git
  cd count-down-on-me
  python3 -m http.server 5566 # 或是任何你用來跑 server 的指令
```

## Usage
在瀏覽器輸入以下網址：
```
  http://localhost:5566/t=<時間全長(分鐘)>&f=<第一次警告時間(分鐘)>&s=<第二次警告時間(分鐘)>
```
畫面顯示倒數時間剩餘分鐘數。  
時間全長（t）預設為 60 分鐘。  
第一次警告時間（f）預設為 5 分鐘，會提前 5 秒鐘警告，警告時背景顏色會變成綠色。  
第二次警告時間（s）預設為 1 分鐘，會提前 5 秒鐘警告，警告時背景顏色會變成橘色。  
結束時會提前 5 秒鐘警告，背景顏色會變成紅色。  
最後字樣會變為「時間到」。  

## License
MIT

## Memo
1. 可以直接連上 https://katrina376.github.io/count-down-on-me/ 使用
2. 只測過電腦版的 Safari 跟 Chrome
