# Modification on autoGPT for Chinese users
基于autogpt非常小的修改，使得中国用户可以调用谷歌

主要的原因是原版的[autoGPT](https://github.com/Torantulino/Auto-GPT)中`google_official_search`使用了build建立链接，而这个函数没法走代理，我改成了reuqest。

## 安装

只需要在./scripts 里面替换同名文件，并且将该文件的`yourproxy`改成你的代理。

## 注意

本人没有任何爬虫经验，非科班出身，瞎写的代理，比较丑陋望见谅。

And this code only suits for Chinese users who can't connect Google even after they have finished all the steps mentioned in section [Google API Keys Configuration](https://github.com/Torantulino/Auto-GPT) in autoGPT.
