
在前公司时候，开发的一套字体图标

使用方式大概有两种：
1.直接使用字体图标对应的编码(我们不建议，这样做，因为这个我们需要记住编码；而且看代码时候，不能知道这个图标的含义)

 	<i class="icon iconfont">&#xe670;</i>
                    <div class="name">下载</div>
                    <div class="code">&amp;#xe670;</div>
                    <div class="fontclass">.xiazai</div>
      </li>



2.通过伪类：（建议用这个，不用记忆，看代码时，也能知道图标意思）

<i class="icon iconfont icon-xiazai"></i>
                    <div class="name">下载</div>
                    <div class="code">&amp;#xe670;</div>
                    <div class="fontclass">.xiazai</div>
                </li>

这里有一篇文章 http://shuizhongyue.blog.51cto.com/7439523/1720896
是我在项目实践中 关于css sprite 和字体图标的苦恼和思考
