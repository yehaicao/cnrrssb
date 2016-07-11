# China Font Awesome Ridiculously Responsive Social Sharing Buttons
[![](http://www.wordpressleaf.com/logo.png)](http://www.wordpressleaf.com/)
<br/><br/> 
<a href="http://www.wordpressleaf.com/2016_24.html"><img align="right" src="http://kurtnoble.com/labs/rrssb/media/rrssb-preview.png" width="248" height="auto"/></a>
CNRRSSB 是在 RRSSB 上修改而来。增加了国内的社交网络，改用了font-awesome 字体图标，你可以在这里看到改用字体图标的实例。 [**这里**](http://www.wordpressleaf.com) 

除去以上的改动，其他的都保留了RRSSB风格和文件。

你可以访问原来[**rrssb**](https://github.com/kni-labs/rrssb)项目。

<img src="http://kurtnoble.com/labs/rrssb/media/rrssb-preview.gif" width="100%" height="auto"/>



## 演示地址
> [**观看演示**](http://www.wordpressleaf.com/2016_24.html)

## 使用步骤
1) 在网页头部加载css样式。注意要加载font-awesome的CSS样式，在这之前要将FONT文件夹复制到静态文件夹中，与CSS文件夹同级:

```html
<link rel="stylesheet" href="css/font-awesome.min.css?ver=4.4.0'" />
<link rel="stylesheet" href="css/rrssb.css" />

```

2) 复制任意的 `.rrssb-buttons` 列表到所需的位置:

```html
<!-- 按钮从这里开始. 复制 div到你的文档. -->
<div class="entry-share" >
	<ul class="cnrrssb-buttons cnrrssb-1" style="-webkit-padding-start: 0px;">
		<li class="cnrrssb-weibo" >
			<a target="_blank" rel="nofollow" href="http://v.t.sina.com.cn/share/share.php?appkey=3036462609&url=http://www.wordpressleaf.com/2016_24.html&title=开源：WordPress国内社交网络分享按钮CNRRSSB源码下载&pic=http://www.wordpressleaf.com/wp-content/uploads/2016/05/wordpress-life_rrssb_chineseshare_20160608-700x350.jpg&searchPic=true" class="popup" >
				<span class="cnrrssb-icon">
					<i class="fa fa-weibo"></i>

				</span>
				<span class="cnrrssb-text">新浪微博</span>
			</a>
		</li>

		<li class="cnrrssb-qqstar"  >

			<a target="_blank" rel="nofollow" href="http://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey?url=http://www.wordpressleaf.com/2016_24.html&title=开源：WordPress国内社交网络分享按钮CNRRSSB源码下载&desc=&summary=国外的RRSSB开源的社交分享源码与codilight-lite搭配起来蛮好看的，可惜的是它只能支持国外的社交网络媒体，...&site=&pics=http://www.wordpressleaf.com/wp-content/uploads/2016/05/wordpress-life_rrssb_chineseshare_20160608-700x350.jpg" class="popup">
				<span class="cnrrssb-icon">

					<i class="fa fa-star"></i>

				</span>
				<span class="cnrrssb-text">QQ空间</span>
			</a>
		</li>
		<li class="cnrrssb-ttweibo">
			<a target="_blank" rel="nofollow" href="http://share.v.t.qq.com/index.php?c=share&a=index&title=开源：WordPress国内社交网络分享按钮CNRRSSB源码下载&url=http://www.wordpressleaf.com/2016_24.html&appkey=801497376&site=&pic=http://www.wordpressleaf.com/wp-content/uploads/2016/05/wordpress-life_rrssb_chineseshare_20160608-700x350.jpg" class="popup">
				<span class="cnrrssb-icon">
					<i class="fa fa-tencent-weibo"></i>

				</span>
				<span class="cnrrssb-text">腾讯微博</span>
			</a></li>
			<li class="cnrrssb-qq" >
				<a target="_blank" rel="nofollow" href="http://connect.qq.com/widget/shareqq/index.html?url=http://www.wordpressleaf.com/2016_24.html&title=开源：WordPress国内社交网络分享按钮CNRRSSB源码下载&desc=&summary=国外的RRSSB开源的社交分享源码与codilight-lite搭配起来蛮好看的，可惜的是它只能支持国外的社交网络媒体，...&site=baidu&pics=http://www.wordpressleaf.com/wp-content/uploads/2016/05/wordpress-life_rrssb_chineseshare_20160608-700x350.jpg">
					<span class="cnrrssb-icon">
						<i class="fa fa-qq"></i>

					</span>
					<span class="cnrrssb-text">QQ好友</span>
				</a>
			</li>
			<li class="cnrrssb-weixin" >
				<a target="_blank" rel="nofollow" class="jiathis_button_weixin" href="javascript:void(0);" onclick="js_method()">
					<span class="cnrrssb-icon">
						<i class="fa fa-weixin"></i>

					</span>
					<span class="cnrrssb-text">微信</span>
				</a>
			</li>
			<li class="cnrrssb-renren small" >
				<a target="_blank" rel="nofollow" href="http://widget.renren.com/dialog/share?resourceUrl=http://www.wordpressleaf.com/2016_24.html&srcUrl=http://www.wordpressleaf.com/2016_24.html&title=开源：WordPress国内社交网络分享按钮CNRRSSB源码下载&description=国外的RRSSB开源的社交分享源码与codilight-lite搭配起来蛮好看的，可惜的是它只能支持国外的社交网络媒体，...&pic=http://www.wordpressleaf.com/wp-content/uploads/2016/05/wordpress-life_rrssb_chineseshare_20160608-700x350.jpg" class="popup">
					<span class="cnrrssb-icon">
						<i class="fa fa-renren"></i>

					</span>
					<span class="cnrrssb-text">人人网</span>
				</a>
			</li>
			<li class="cnrrssb-github small" >
				<a target="_blank" rel="nofollow" href="https://github.com/yehaicao/cnrrssb" class="popup">
					<span class="cnrrssb-icon">
						<i class="fa fa-github"></i>

					</span>
					<span class="cnrrssb-text">github</span>
				</a>
			</li>
			<li class="cnrrssb-reddit small" >
				<a target="_blank" rel="nofollow" class="jiathis" href="javascript:void(0);" onclick="js_method()" title="更多">
					
					<span class="cnrrssb-icon">
						<i class="fa fa-share-alt"></i>


					</span>
					<span class="cnrrssb-text">更多</span>
				</a>
			</li>
			<li class="cnrrssb-email small" >
				<a target="_blank" rel="nofollow" href="mailto:?subject=开源：WordPress国内社交网络分享按钮CNRRSSB源码下载&body=http://www.wordpressleaf.com/2016_24.html">
					<span class="cnrrssb-icon">
						<i class="fa fa-envelope"></i>

					</span>
					<span class="cnrrssb-text">Email</span>
				</a>
			</li>
		</ul>
</div>
<!-- 按钮代码结束 -->
```
- 这些 `<li>` 代码，你可以在 index.html 示例中找到。 其他的注意事项同 rrssb ，你可以看下面的英文文档，我就不翻译了。
- Only copy the `<li>`s of the buttons you want (index.html has examples of all available types).
- Adding a class of `popup` to the anchor tag for each share button will make the share dialog open in a popup, rather than a new window. (Good for Facebook, Twitter, Google Plus, etc.)
- Buttons will automatically flow to the size of the ul `rrssb-buttons`. If fixed sized buttons are needed, nest `rrssb-buttons` in a fixed-width container.
- Each sharing URL requires various parameters that allow you to pass through messaging in the sharing dialog. A useful tool for URI escaping any messaging that needs to pass through the share URL can be found [**here**](http://meyerweb.com/eric/tools/dencoder/).
- Alternatively, all share metadata and links can be configured [using Javascript](#javascript)

3) 在你的网页上加上javascript文件，它们都在js的文件内。你也可以使用jQuery CDN。另外微信二维码使用了jiathis来生成，所以你也需要加载jia.js。

```html

  <script src="js/jquery.js"></script>
  <script src="js/cnrrssb.js"></script>
  <script type="text/javascript" src="http://v3.jiathis.com/code/jia.js?uid=1" charset="utf-8"></script>
```

<a name="javascript"></a>

这段的意思是你可以在网页源码中动态初始化一些参数，然后rrssb.js会自动给你生成 <a> 标签的href，很方便。当然cnrrssb.js也能一样给你生成，我在原有的基础上加上了微博、QQ空间、QQ、人人网的代码。

**Optional: Configure URL and share text with javascript:**<br/> Instead of editing each `href` by hand, you can call some Javascript to set the URLs on each social button automatically.

Note: to support users who have disabled Javascript, you still need to edit the `href`s by hand.

Paste the following before the closing body tag, after the scripts you added in the last section:

```html
<script type="text/javascript">

jQuery(document).ready(function ($) {

  $('.rrssb-buttons').rrssb({
    // required:
    title: 'This is the email subject and/or tweet text',
    url: 'http://kurtnoble.com/labs/rrssb/',

    // optional:
    description: 'Longer description used with some providers',
    emailBody: 'Usually email body is just the description + url, but you can customize it if you want'
  });
});
</script>
```

以下都是RRSSB的说明，我是在它上面修改的，所以就保留了。要注意的是CNRRSSB支持的字体图标font-awesome，而不是SVG。主要是我使用的时候，自己懒的做SVG，然后国内的设计SVG没有找到，所以就用了字体图标。你也可以自己制作SVG。


## Other install options:

Service     | Link
:---------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
npm         | `npm install rrssb`
bower       | `bower install rrssb`
Rails *     | [**Rails Setup by @rimkashox**](http://www.simplehacks.com/web-dev/how-to-use-rrssb-with-rails/)
Wordpress * | [**https://wordpress.org/plugins/rrssb/**](https://wordpress.org/plugins/rrssb/)<br>[**https://wordpress.org/plugins/wpsso-rrssb/**](https://wordpress.org/plugins/wpsso-rrssb/)<br>[**https://wordpress.org/plugins/rrssb-for-wp/**](https://wordpress.org/plugins/rrssb-for-wp/)
Drupal *    | [**Drupal Install Instructions**](https://drupal.org/project/rrssb)
CDN *       | [**OSSCDN by MaxCDN**](http://osscdn.com/#/rrssb)

<small>* Managed by 3rd parties. Please contact project hosts for support.</small>

## Support
Currently tested between [**140px**](https://www.dropbox.com/s/2k6lcebg2887ge3/Screenshot%202014-02-18%2009.45.45.png) and [**15,465px**](https://www.dropbox.com/s/1juq03011lixk3r/Screenshot%202014-02-18%2009.43.57.png) on current versions of Chrome 33, Safari 7.0.2, Firefox 27, Opera 20, and IE9+.

Requires [**SVG**](http://caniuse.com/svg)

## Contributing
Thanks for helping! Pull requests are welcomed.

### Build setup:
- Make sure [gulp](http://gulpjs.com/) is installed globally: `npm install -g gulp` (May require `sudo`.)
- run `npm install` to install the dependencies for this project.
- run `gulp` to create a local server at `localhost:3000` and watch for file changes.

## About
RRSSB is a [**KNI Labs freebie**](http://kurtnoble.com/) crafted by [**@dbox**](http://www.twitter.com/dbox) and [**@joshuatuscan**](http://www.twitter.com/joshuatuscan).
