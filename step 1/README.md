# 第一步

<h3>创建本地git存储库&nbsp;</h3>
<p>使用git在本地机器上创建新项目时，首先要创建一个新&nbsp;<strong><a href="https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository" target="_blank">存储库</a>&nbsp;</strong>(或者通常是'<strong>repo</strong>').&nbsp;</p>
<p>要使用git，我们将使用终端。如果您对终端和基本命令没有太多经验，请查看 <a href="http://mac.appstorm.net/how-to/utilities-how-to/how-to-use-terminal-the-basics/" target="_blank">本教程</a>&nbsp;(尤其是“导航文件系统”和“移动”部分).</p>
<p>首先，打开终端并使用<code>cd</code> (更改目录) 命令移动到要将项目放置在本地计算机上的位置.例如，如果桌面上有“项目”文件夹，则可以执行以下操作：</p>
<p>
<script src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/67a84eb876984f0b5785.js.下载"></script><link rel="stylesheet" href="./An Intro to Git and GitHub for Beginners (Tutorial)_files/gist-embed-4ac6018bcc05457cde2f66d2e7299d11.css"></p><div id="gist26245466" class="gist">

<div class="gist-file">
  <div class="gist-data">
    <div class="js-gist-file-update-container js-task-list-container file-box">

  <div id="file-terminalcd-md" class="file">
  <div id="file-terminalcd-md-readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><div class="highlight highlight-source-shell"><pre>mnelson:Desktop mnelson$ <span class="pl-c1">cd</span> <span class="pl-k">~</span>/Desktop
mnelson:Desktop mnelson$ mkdir myproject
mnelson:Desktop mnelson$ <span class="pl-c1">cd</span> myproject/</pre></div>
</article>
  </div> 
</div>

<div>  
<div class="gist-meta">
    <a href="https://gist.github.com/cubeton/67a84eb876984f0b5785/raw/d4560016d742865c1fd68d97fcff1feb557d5e19/terminalcd.md" style="float:right">view raw</a>
    <a href="https://gist.github.com/cubeton/67a84eb876984f0b5785#file-terminalcd-md">terminalcd.md</a>
    hosted with ❤ by <a href="https://github.com/">GitHub</a>
    </div> 
</div>

<p></p>
<p>&nbsp;</p>
<p>要在文件夹的根目录中初始化git存储库，请运行 <span style="font-family: &#39;courier new&#39;, courier;"><strong><a href="http://git-scm.com/docs/git-init" target="_blank">git init</a>&nbsp;</strong><span style="font-family: arial, helvetica, sans-serif;">命令:</span></span>&nbsp;&nbsp;</p>
<script src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/89793ba1bc947f64658e.js.下载"></script><link rel="stylesheet" href="./An Intro to Git and GitHub for Beginners (Tutorial)_files/gist-embed-4ac6018bcc05457cde2f66d2e7299d11.css"><div id="gist26245638" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gitinit-md" class="file">

  <div id="file-gitinit-md-readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><div class="highlight highlight-source-shell"><pre>mnelson:myproject mnelson$ git init
Initialized empty Git repository <span class="pl-k">in</span> /Users/mnelson/Desktop/myproject/.git/</pre></div>
</article>
  </div>

      </div>
      <div class="gist-meta">
        <a href="https://gist.github.com/cubeton/89793ba1bc947f64658e/raw/f3dba1dd72fda5eeb98b761338aedfc310d29d54/gitinit.md" style="float:right">view raw</a>
        <a href="https://gist.github.com/cubeton/89793ba1bc947f64658e#file-gitinit-md">gitinit.md</a>
        hosted with ❤ by <a href="https://github.com/">GitHub</a>
      </div>
    </div>
</div>