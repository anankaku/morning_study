# 2026-10-30 晨間快訊來源

本期回顧 2026 年預印本，並非今日新發表，也不視為已通過同儕審查。

Mhd Hussein Murtada, Z. Faidon Brotzakis, Michele Vendruscolo. “MD-LLM-2: A Transferable Language Model of Molecular Dynamics with Physical Conditioning and Explicit Path Probabilities.” arXiv:2610.10879v1 (2026-10-07).

[作者預印本](https://arxiv.org/abs/2610.10879v1)
[公開全文](https://arxiv.org/html/2610.10879v1)
[DOI](https://doi.org/10.48550/arXiv.2610.10879)

## 查核與界線

- 摘要及第 1 節：模型根據序列、溫度與構形歷史生成離散結構符號序列。正規化的逐步條件機率讓模型內的符號路徑機率可直接計算；這不等於真實物理路徑機率已正確。
- 第 2.3 節及第 3 節：所報告蛋白質測試中，加入歷史構形減少整體骨架漂移。作者同時討論動力學記憶與抑制累積生成誤差兩種解釋，尚未將它們完全分離。
- 第 3 節限制：蛋白質模型只生成骨架座標，生成軌跡的時間尺度尚未對分子動力學校準。動力學測試限於小分子兩個能谷間的短時間首次通過機率，不能推廣為蛋白質速率已驗證。

## 複習提示

關鍵詞：條件機率、歷史資訊、時間尺度。
回想題：能算出路徑機率，就代表時間尺度正確嗎？
答案：不一定。機率可計算是模型的性質；物理時間尺度與轉移速率仍須獨立對照驗證。

日期採 America/New_York。口播約 45–50 秒僅為估計，實際依語音、速度與停頓而異。
