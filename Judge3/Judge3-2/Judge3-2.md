# 上機考Judge 3-2 
### 故事背景
>玩橋牌手氣不是很好的瑩瑩，最近決定轉往21點發展，可是他又怕他的手氣會衰到連玩21點都輸到脫褲，你可以幫他製作一個21點模擬器嗎?

### 題目
21點規則:由莊家發牌(自行生成)，一開始只有1張，之後看要不要繼續叫牌，如果要的話莊家繼續發牌，可持續叫到過5關為止(手牌超過5張且點數加起來不超過21)。除了J,Q,K點數的是0.5外，其他牌都是跟牌面上的點數一樣。最後比手牌上的點數誰多，誰就贏了。但前面都是廢話，因為瑩瑩只需要模擬器，所以你只要做1個可以幫他練習21點的程式就好了，不須比較輸贏，知道自己已經贏或輸就可以自己跳出去了。

#### 輸入
```
Y or N
```

#### 輸出
```
沒爆掉:Your score is 總點數.
爆掉:You are loser.
```

### 範例
![](http://i.imgur.com/xU5SHfU.jpg)

♥HINT:請用浮點數處理總和
