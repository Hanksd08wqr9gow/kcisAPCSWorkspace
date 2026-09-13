# 07 指令回應

- 難度：進階

終端機收到操作人員代號、指令名稱與工作編號後，要輸出兩行回應。工作編號會使用兩次。

## 輸入格式

輸入操作人員代號、指令名稱及整數工作編號；字串不含空白。

## 輸出格式

```text
[工作編號] 指令名稱 accepted
Operator 操作人員代號 is handling job 工作編號.
```

## 資料範圍

字串長度為 1～20；工作編號為 1～1000000。

## 範例輸入

```text
OP7 calibrate 302
```

## 範例輸出

```text
[302] calibrate accepted
Operator OP7 is handling job 302.
```
