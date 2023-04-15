# Modification on autoGPT for Chinese user
基于autogpt非常小的修改，使得中国用户可以调用谷歌

主要的原因是原版的[autoGPT](https://github.com/Torantulino/Auto-GPT)中`google_official_search`使用了build建立链接，而这个函数没法走代理，我改成了reuqest。
