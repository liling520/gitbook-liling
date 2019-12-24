# 第五步

<p>&nbsp;</p>
<h3><a id="user-content-step-3-creating-a-new-branch" class="anchor" href="https://github.com/cubeton/git101/blob/master/TurtorialInfo/Tutorial.md#step-3-creating-a-new-branch" aria-hidden="true"></a>创建一个新分支</h3>
<p>现在你已经做了一个新的提交，让我们尝试&nbsp;一些更高级的东西。</p>
<p>假设你想创建一个新功能，但担心在开发&nbsp;该功能时对主项目进行更改。 这就是 <strong><a href="https://git-scm.com/book/en/v1/Git-Branching-What-a-Branch-Is" target="_blank">git分支</a>&nbsp;</strong>的作用。&nbsp;</p>
<p>分支允许你在项目的“状态”之间来回移动。例如，如果要向网站添加新页面，可以仅为该页面创建新分支，&nbsp;而不影响&nbsp;项目的主要部分。 完成页面后，你可以&nbsp;<a href="http://git-scm.com/docs/git-merge" target="_blank"><strong>合并</strong></a> 更改从你的分支到主分支中。 当你创建一个新的分支时，&nbsp;<span>Git&nbsp;</span><span>会跟踪这个分支的提交，所以它知道所有文件背后的历史。&nbsp;</span></p>
<p>假设你在主分支机构并且想要创建一个新分支来开发你的网页。 下面是你要做的：运行<strong> <a href="http://git-scm.com/docs/git-checkout" target="_blank"><code>git checkout -b &lt;my branch name&gt;</code></a></strong>.这个命令将自动创建一个新的分支，然后对其“检查出来”，这意味着git会将你移动到主分支之外的那个分支。</p>
<p>运行上述命令后，&nbsp;你可以使用该 <strong><a href="http://git-scm.com/docs/git-branch" target="_blank"><code>git branch</code></a></strong> 命令确认你的分支已创建：</p>
<p>
<script src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/fa25a25f322a2cd5f405.js.下载"></script><link rel="stylesheet" href="./An Intro to Git and GitHub for Beginners (Tutorial)_files/gist-embed-4ac6018bcc05457cde2f66d2e7299d11.css"></p><div id="gist26277733" class="gist">

<div class="gist-file">
  <div class="gist-data">
    <div class="js-gist-file-update-container js-task-list-container file-box">

 <div id="file-gitbranch-md-readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><div class="highlight highlight-source-shell"><pre>mnelson:myproject mnelson$ git branch
  master
<span class="pl-k">*</span> my-new-branch</pre></div>
</article>
</div>

  </div>
</div>

 </div>
  <div class="gist-meta">
    <a href="https://gist.github.com/cubeton/fa25a25f322a2cd5f405/raw/81033788d288adeffe260bd724ab2699b29e3e35/gitbranch.md" style="float:right">view raw</a>
    <a href="https://gist.github.com/cubeton/fa25a25f322a2cd5f405#file-gitbranch-md">gitbranch.md</a>
    hosted with ❤ by <a href="https://github.com/">GitHub</a>
  </div>
</div>

</div>

<p></p>
<p>旁边带星号的分支名称指示在给定时间指向哪个分支。&nbsp;</p>
<p>现在，如果你切换回主分支并进行更多提交，你的新分支不会看到任何这些更改，直到你将这些更改 <a href="http://git-scm.com/docs/git-merge" target="_blank"><strong>合并</strong></a> 到新分支当中。</p>
<p>&nbsp;</p>

