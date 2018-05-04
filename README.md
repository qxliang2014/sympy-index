# 将学习sympy库时记下的关键字制作成词云
- 文本是自己敲上去的，所以代码里没用到分词包以及词云包的一些分词功能。
- 代码实现参考了[WordCloud的github主页](https://github.com/amueller/word_cloud)，并尽量取简洁实用部分。
- 如果是中文文本则很可能会由于UTF8编码问题而无法显示，那么打开**wordcloud.py**，找到以下设置进行修改：
> FONT_PATH = os.environ.get("FONT_PATH", os.path.join(os.path.dirname(__file__), "DroidSansMono.ttf"))

更多的词云库参数和用法也可以在里面查看。
- 最后一个cell里的代码是想让读者可以对词云图片进行一些基本的交互操作（比如放大、拖动和保存等），需要导入额外安装的插件到notebook，
但是在github上不能正常生效，可能github还不支持这样的插件。
