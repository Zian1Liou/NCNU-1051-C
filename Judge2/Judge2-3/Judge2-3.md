# 上機考 Judge 2-3
### 故事背景
>糖果城裡面有好多香蕉衛兵，泡泡糖公主都給了他們一個衛兵編號，進出城門都需要驗證，但是衛兵編號沒有固定長度，讓負責檢驗的身分的阿郡和老皮每次都花費好多時間，你能不能幫他寫一支可以一直輸入驗證的程式呢?
### 題目
>先輸入衛兵編號長度，一個一個數字輸入編號，經過驗證成功則印出 real ，驗證失敗則印出 fasle 。

驗證規則： 
- 當「驗證碼」等於「檢查碼」時，代表身分正確
- 第一碼為「檢查碼」
- 「驗證碼」: 自檢查碼後 ( 即第二碼 ) 開始，乘以 1，第三碼乘以 2，第四碼乘以 3 ...... 第 n 碼乘以 n-1 相加之總和的個位數。例如1 2 3 5 7，總和為 2x1 + 3x2 + 5x3 + 7x4 = 51。此總和的個位數為 1，驗證碼就是 1 

- - 程式需可以一直輸入不中斷 

### 輸出範例
```
5
0 1 1 1 1
real
8
2 1 6 1 2 5 7 8
fasle

```