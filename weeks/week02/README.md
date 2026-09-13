# Week 02：輸入輸出、變數、資料型態與基礎運算

本週完整練習變數、資料型態、`std::cin`、`std::cout`，並加入基本算術運算。

```cpp
std::string deviceName;
int channel;
std::cin >> deviceName >> channel;
std::cout << "Device: " << deviceName << '\n';
```

## 變數與資料型態

```cpp
int count = 12;             // 整數
long long population = 0;  // 較大的整數
double temperature = 26.5; // 有小數的數值
char level = 'A';           // 單一字元
std::string name = "Mina"; // 一段文字
```

型態也會影響運算：`7 / 2` 是整數除法，結果為 `3`；`7.0 / 2` 才是 `3.5`。

## 輸入、輸出與運算

`std::cin >> first >> second;` 依序讀取資料，空格與換行都能分隔輸入。`std::cout <<` 可串接固定文字、變數與運算結果。Judge 不需要「請輸入」等提示。

`+`、`-`、`*`、`/` 分別進行加減乘除；`%` 取得整數餘數；`=` 把右側結果指定給左側變數。用括號分組，例如 `(a + b + c) / 3.0`。

## 題目

每題的 `main.cpp` 都是空白檔案，請自行完成完整程式。依進度選題，不要求全部完成。

| 題目 | 難度 | 練習重點 |
|---|---|---|
| [01 設備連線資訊](problems/basic/01-connectionInfo/README.md) | 基礎 | 文字與整數 |
| [02 活動識別證](problems/basic/02-eventBadge/README.md) | 基礎 | 多個文字變數 |
| [03 庫存紀錄](problems/basic/03-inventoryRecord/README.md) | 基礎 | 精確輸出格式 |
| [04 整數運算報表](problems/basic/04-integerReport/README.md) | 基礎 | 加減乘除與餘數 |
| [05 三次量測平均](problems/basic/05-measurementAverage/README.md) | 基礎 | `double` 與平均值 |
| [06 字元狀態紀錄](problems/basic/06-statusRecord/README.md) | 基礎 | `char` 與 `string` |
| [07 指令回應](problems/advanced/07-commandResponse/README.md) | 進階 | 重複使用變數 |
| [08 執行時間換算](problems/advanced/08-durationConversion/README.md) | 進階 | 整除與餘數 |

完成後先跑範例，再更換輸入測試。Judge 不需要「請輸入」等提示文字。
