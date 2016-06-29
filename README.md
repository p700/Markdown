>Markdown 语法研究

<h1>1级标题</h1>
<h2>2级标题</h2>
<h3>3级标题</h3>
<h4>4级标题</h4>
<h5>5级标题</h5>
<h6>6级标题</h6>
<blockquote>valign="top"   valign="middle"     valign=“bottom"
    <blockquote>align="left"   align="center"      align="center"</blockquote>
</blockquote>
复选框
- [x] 需求分析
- [x] 系统设计
- [x] 详细设计
- [ ] 编码
- [ ] 测试
- [ ] 交付    

136212068@qq.com 邮箱自动识别 <br>
<sup>上标</sup>&nbsp;&nbsp;<sub>下标</sub>&nbsp;&nbsp;<del>删除线</del> <br>
<i>斜体</i> <b>粗体</b>
<hr>
<blockquote>树枝
    <blockquote>树枝
        <blockquote>树枝</blockquote>
    </blockquote>
    <blockquote>树枝</blockquote>
</blockquote>

代码块 <a name="daima"></a><br>
<code>- (void)GETRequestWithUrl:(NSString *)urlStr parameters:(NSMutableDictionary *)parameters completionHandler:(completionHandler)completionHandler</code> <br>
<pre>- (void)GETRequestWithUrl:(NSString *)urlStr parameters:(NSMutableDictionary *)parameters completionHandler:(completionHandler)completionHandler</pre><br>
带高亮语法的代码块 <br>
``` objc
- (void)GETRequestWithUrl:(NSString *)urlStr parameters:(NSMutableDictionary *)parameters completionHandler:(completionHandler)completionHandler{
    printf("%s\n", a);
    }
```

<table>
    <tr>
        <th align="center">th</th>
        <th>th</th>
    </tr>
    <tr>
        <td>tdtdtdtdtdtdtdtdtd</td>
        <td>td</td>
    </tr>
    <tr>
        <td>td</td>
        <td>td</td>
    </tr>
</table>
<ul>
    <li>无序</li>
    <ul><li>1</li><li>2</li></ul>
    <li>有序</li>
    <ol>
        <li>1</li>
        <li>2</li>
    </ol>
</ul>
<dl>
   <dt>自定义列表</dt>
   <dd>用来计算的仪器</dd>
   <dt>显示器</dt>
   <dd>以视觉方式显示信息的装置</dd>
</dl>

<a href="http://p700.cn/">This link</a>  <br>
<img src="http://p700.cn/c/1.gif" width="130" /> <br>
<a href="#readme">回到顶部</a> <br>
<a href="#user-content-daima">去往代码块</a> <br>
表情 :bowtie