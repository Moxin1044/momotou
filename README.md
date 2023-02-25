# 摸摸头
使用Python快速制作一个摸摸头的GIF图片。

# 使用
你需要先Pip下来momotou
```python
pip install momotou
```
假如国内源有些没有同步，你可以尝试更新频繁的清华源或者官方源。
```python
https://pypi.tuna.tsinghua.edu.cn/simple
https://pypi.python.org/simple/
```

```python
from momotou import momotou


momotou("abc.png", "save.gif")
```
你只需要导入这个包，然后给定一个需要摸摸头的图片路径，再给一个保存路径，就可以帮你摸摸头啦！

# 成功案例
1.青少年CTF机器人