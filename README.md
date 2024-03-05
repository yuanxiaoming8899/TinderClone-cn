<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tinder_android_app_clone</font></font></h1><a id="user-content-tinder_android_app_clone" class="anchor-element" aria-label="永久链接：Tinder_android_app_clone" href="#tinder_android_app_clone"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">▷ 创建一个像tinder这样的Android应用程序</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">▷ 完整视频教程播放列表：</font></font><a href="https://www.youtube.com/playlist?list=PLxabZQCAe5fio9dm1Vd0peIY6HLfo5MCf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.youtube.com/playlist? list=PLxabZQCAe5fio9dm1Vd0peIY6HLfo5MCf</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">▷ 本项目使用的工具：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安卓工作室；</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Firebase：*实时数据库*身份验证</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">刷卡；</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">▷ 在这个项目中，我们完成了：</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
1 - SwipeCards 实施；</font></font><br></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">▷ 如果您有任何问题请询问，我会尽力回答每个问题，甚至在必要时查看您的代码。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PS：如果您要下载完整的项目，请使用您的 on firebase API，项目中的 API 将不会得到维护，并且应用程序可能无法运行。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实施指南</font></font></h1><a id="user-content-implementation-guide" class="anchor-element" aria-label="永久链接：实施指南" href="#implementation-guide"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1 - 项目</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
1 - 在您的 android studio 中打开项目；</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
2 - ！！！重要！！！</font><font style="vertical-align: inherit;">更改包名称。</font><font style="vertical-align: inherit;">您可以在此处查看如何执行此操作（</font></font><a href="https://stackoverflow.com/questions/16804093/android-studio-rename-package" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://stackoverflow.com/questions/16804093/android-studio-rename-package</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font><br></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2 - Firebase 面板</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
1 - 创建 Firebase 项目 ( </font></font><a href="https://console.firebase.google.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://console.firebase.google.com/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ); </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
2 - 按照说明将文件 google-service.json 导入到您的项目中；</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
3 - 转到 Firebase -&gt; 注册并使用电子邮件激活登录/注册</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
4 - 转到 Firebase -&gt; 存储并激活它；</font></font><br></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！！！完毕！！！</font></font></strong></p>
</article></div>
