# AIFirst_word_emb


1. [下載詞向量](https://mega.nz/#!5LwDjZia!f77y-eWm90H3akg8mD9CqhOZ89NihirRKN4IT1SJ01Q)
(這份詞向量是用中央社新聞訓練的)

2. 安裝套件
jieba
```
(sudo) pip install jieba
或
(sudo) python3 -m pip install jieba
```

3. 執行
這份script用python3撰寫，用以下的指令都能執行。
如果因為某些限制只能用python2，要注意讀取詞向量時的編碼可能會有問題。(py3預設utf-8)
```
./inference_with_word_sim.py <詞向量檔名> <問題檔名>
python3 inference_with_word_sim.py <詞向量檔名> <問題檔名>
```
