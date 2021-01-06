# SensitiveWordFiltering
敏感词过滤

word_filter.py
WordFilePath = 修改为存储的 wd.txt 所在位置

调用：
gfw = DFAFilter()
gfw.word_replace(word_string, "*")
