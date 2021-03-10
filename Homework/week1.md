# 第一週課堂筆記

## 課堂教材
[系統程式](http://programmermedia.org/root/%E9%99%B3%E9%8D%BE%E8%AA%A0/%E8%AA%B2%E7%A8%8B/%E7%B3%BB%E7%B5%B1%E7%A8%8B%E5%BC%8F/README.md)  
[程式人媒體](http://programmermedia.org/root/%E7%A8%8B%E5%BC%8F%E4%BA%BA%E5%AA%92%E9%AB%94/) 

## CPU分類
* HACK CPU : 上學期計算及結構所設計CPU，非市場上常見CPU。
* x86 : 目前最常見的架構。
* ARM : 目前最新一代MAC的CPU已經改用此架構(課堂中不會探討此CPU)。
* RISC-V : 開放原始碼的CPU(開放原始碼：指令集開放，使用指令不會被收取費用)。

## 環境安裝檢測

```
pengbowei@pengbaiweideMacBook-Pro 00-hello % gcc
clang: error: no input files
pengbowei@pengbaiweideMacBook-Pro 00-hello % gcc hello.c -o hello
pengbowei@pengbaiweideMacBook-Pro 00-hello % ./hello
hello!
```