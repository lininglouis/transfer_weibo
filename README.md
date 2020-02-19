# 微博收藏和个人原创微博转移

* 如何使用python和selenium将自己收藏微博和原创微博的链接导出来，并转移到自己的新号当中 
收藏的微博link导出和转移.ipynb
* 如何导出自己的原创微博
原创微博导出.ipynb


# 环境python3
* jupyter notebook   
* selenium 这是一个自动化工具。就是可以自动模拟用户对微博的翻页、点击、滚动网页等动作
* lxml 这是网页的解析工具。我们获取到网页之后需要通过lxml去获取网页中的链接或者文本信息。 selenium库中也有自己的网页html解析防范，但是试用过还是lxml更强大一些
```
pip install notebook
pip install selenium
pip install lxml
```
