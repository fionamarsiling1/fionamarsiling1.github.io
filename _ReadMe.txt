﻿==============================================================================================
選單的選項，儲存在 menu.txt 中，變數說明如下：

ModeFlag=0&              <---- 0 代表使用教學模式，1 代表使用測驗模式
&MenuTotal=2&            <---- 單元數目，2 代表兩個單元
&F1=chtest.txt&          <---- F1 是第一個單元的文字檔檔名，例如：chtest.txt
&N1=這是中文測試單元&    <---- N1 是第一個單元的名稱(中文或英文皆可)，例如：這是中文測試單元
&F2=entest.txt&          <---- F2 是第二個單元的文字檔檔名，例如：entest.txt
&N2=這是英文測試單元&    <---- N1 是第二個單元的名稱(中文或英文皆可)，例如：這是英文測試單元
&okflag=1                <---- 照例，這是我程式中的變數，請勿更動


==============================================================================================
這裡以範例檔案中的第一個單元檔 chtest.txt 的內容，介紹其中的變數如下：

QTotal=4&                <---- 本單元的句子數目，4 代表有 4 個句子
&BombTimeExtra=1&        <---- 本單元的遊戲模式炸彈時間額外增加 1 個係數，數字越大增加越多(1 ~ 10)
&QFont=標楷體&           <---- 本單元指定的字型，請根據作業系統的可用字型作為設定

&Q1S=今天/我/和/小牛/去看/一場/電影&           <---- Q1 代表第1句，句子以 / 符號切斷
&A1=1234567/1432567/2341567/4321567/2134567/4132567&   <---- 可能答案順序的組合
&Q2S=他的/哥哥/想買/一間/房子&                 <---- Q2 代表第2句，句子以 / 符號切斷
&A2=12345/23415&                               <---- 可能答案順序的組合
&Q3S=姐姐/很想/成為/有名的/歌星&               <---- Q3 代表第3句，句子以 / 符號切斷
&Q4S=教/育/噗/浪/客&                           <---- Q4 代表第4句，句子以 / 符號切斷

&okflag=1                <---- 照例，這是我程式中的變數，請勿更動

===============================================================================================
PS:

單元的文字檔檔名，可以任意命名，但不可以用中文檔名，因為 Flash 不太能讀到中文檔名。


這裡文字檔案格式我都用 utf-8 ，並非 Big5。


每句最多可以切分成 10 個字組，每個字組的字母數或單字數並未設限，若太長的字串，系統將自動計算
縮小字的大小，但是縮小的下限是10點，因此字串的總長度其實有上限，請在出題時斟酌字數與長度。

選擇較瘦的字型，有助於改善字串的總長度問題。

===============================================================================================
