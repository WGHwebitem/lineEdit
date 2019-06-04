1、图片的居中：在img标签的父元素的div中的css:display: flex; justify-content: center;align-items: center;
2、给中文加拼音的标签：<ruby>今 天<rp>(</rp><rt>jin tian</rt><rp>)</rp></ruby>

一、rel=”alternate”;（a、area、link标签上）
	1、 表示链接有替换内容（可实现换肤效果）
	2、 还可以用来定义用来替换的页面
	eg:media响应处理，小于640像素时候，告诉用户或者设备（或搜索引擎），还有移动站页面
	<link rel="alternate" media="only screen and (max-width: 640px)" href="css页面" />
	
	二、rel=”dns-prefetch”只能作用在<link>元素上，作用是DNS预读取，可以提高页面资源加载速度
	
	三、rel=”help”;提示进行帮助说明（a、area、form或link标签上）
	eg:CSS转义<a href="" title="这个用在什么地方？" rel="help">鼠标移上提示tile的内容</a>
	
	四、rel=”icon”（link允许）
	<link rel="icon" type="image/png" href="image/choose.png" sizes="16x16">
	
	五、rel=”modulepreload”预加载原生模块脚本
	<link rel="modulepreload" href="super-critical-stuff.mjs">
	
	六、rel=”nofollow”可让网站站长告诉搜索引擎“不要跟踪此网页上的链接”或“不要跟踪此特定链接”。
	
	七、rel=”noopener”这是一个很重要的且常用的rel属性值，与安全相关。
	
	八、rel=”prefetch”表示预获取，通常是一些静态资源（link允许）
	
	九、rel=”preload”表示预加载。告诉浏览器这些资源你先帮我加载，之后我要使用（link允许）
	
	十、rel=”prerender”prerender表示预渲染。告知浏览器在背后先默默渲染页面（link允许）
	
	十一、rel=”stylesheet” 指向样式表资源（link允许）
	
	十二、rel=”tag”（表示指向表述当前文档标签的链接）因此SEO会更加精准，质量更高。
	

