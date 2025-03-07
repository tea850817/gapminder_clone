# 練習專案一：兩百個國家、兩百年、四分鐘

## 簡介

這個專案復刻了 [Hans Rosling's 200 Countries, 200 Years, 4 Minutes](https://www.youtube.com/watch?v=jbkSRLYSojo) 資料視覺化，使用`pandas`和`sqlite3`建立資料庫(create_gapminder_db.py)，利用`matplotlib`進行概念驗證(proof_of_concept.py)，最後以`plotly.express`做出成品(plot_with_px.py)

## 如何重現

- 安裝 [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main)
- 依據`environment.yml`建立環境

```shell
conda env create -f environment.yml`
```

- 建立一個gapminder_clone資料夾
- 將`data/`資料夾中四個CSV檔案放在工作目錄中`data/`資料夾
- 啟動環境並執行`python create_gapminder_db.py` 就能在`data/`資料夾中建立`gapminder.db`
- 啟動環境並執行`python plot_with_px.py`就能生成`gapminder_clone.html`