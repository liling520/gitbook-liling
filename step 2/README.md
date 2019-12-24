# 第二步

<h3>&nbsp;</h3>
<h3><a id="user-content-step-4-adding-a-new-file-to-the-repo" class="anchor" href="https://github.com/cubeton/git101/blob/master/TurtorialInfo/Tutorial.md#step-4-adding-a-new-file-to-the-repo" aria-hidden="true"></a>向repo添加新文件</h3>
<p>继续使用你喜欢的任何文本编辑器或运行<span style="font-family: &#39;courier new&#39;, courier;">&nbsp;<a href="http://linux.die.net/man/1/touch" target="_blank">touch</a></span> 命令将新文件添加到项目中.</p>
<p>一旦你在包含git repo的文件夹中添加或修改了文件，git就会发现在repo中已经进行了更改。但是，git不会正式跟踪文件（也就是说，将其置于提交中-我们将在下面详细讨论提交），除非你明确告诉它。</p>
<p>
<script src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/2d8f224bede4c2dde86b.js.下载"></script><link rel="stylesheet" href="./An Intro to Git and GitHub for Beginners (Tutorial)_files/gist-embed-4ac6018bcc05457cde2f66d2e7299d11.css"></p><div id="gist26245712" class="gist">

<div class="gist-file">
  <div class="gist-data">
    <div class="js-gist-file-update-container js-task-list-container file-box">

  <div id="file-addfile-md-readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><div class="highlight highlight-source-shell"><pre>mnelson:myproject mnelson$ touch mnelson.txt
mnelson:myproject mnelson$ ls
mnelson.txt</pre></div>
</article>
  </div>

  </div>
</div>

  </div>
<div class="gist-meta">
    <a href="https://gist.github.com/cubeton/2d8f224bede4c2dde86b/raw/b865e27cc4715b3a3a4a5839e77ab232ff1b31f9/addfile.md" style="float:right">view raw</a>
    <a href="https://gist.github.com/cubeton/2d8f224bede4c2dde86b#file-addfile-md">addfile.md</a>
    hosted with ❤ by <a href="https://github.com/">GitHub</a>
  </div>

</div>

<p></p>
<p>&nbsp;</p>
<p>创建新文件后，你可以使用该 <a href="http://git-scm.com/docs/git-status" target="_blank"><strong><code>git status</code></strong></a> 命令查看git知道哪些文件存在。</p>
<p>
<script src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/02e849bbffcbea1e9a61.js.下载"></script><link rel="stylesheet" href="./An Intro to Git and GitHub for Beginners (Tutorial)_files/gist-embed-4ac6018bcc05457cde2f66d2e7299d11.css"></p><div id="gist26245727" class="gist">

<div class="gist-file">
  <div class="gist-data">
    <div class="js-gist-file-update-container js-task-list-container file-box">

  <div id="file-gitstatus-md-readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><div class="highlight highlight-source-shell"><pre>mnelson:myproject mnelson$ git status
On branch master

Initial commit

Untracked files:
  (use <span class="pl-s"><span class="pl-pds">"</span>git add &lt;file&gt;...<span class="pl-pds">"</span></span> to include <span class="pl-k">in</span> what will be committed)

mnelson.txt

nothing added to commit but untracked files present (use <span class="pl-s"><span class="pl-pds">"</span>git add<span class="pl-pds">"</span></span> to track)</pre></div>
</article>
  </div>

  </div>
</div>

</div>
  <div class="gist-meta">
    <a href="https://gist.github.com/cubeton/02e849bbffcbea1e9a61/raw/71c93139666a8a4e06795f53c9aec5db95e6019a/gitstatus.md" style="float:right">view raw</a>
    <a href="https://gist.github.com/cubeton/02e849bbffcbea1e9a61#file-gitstatus-md">gitstatus.md</a>
    hosted with ❤ by <a href="https://github.com/">GitHub</a>
  </div>
</div>

</div>

<p></p>
<p>这基本上是说, "嘿, 我们注意到你创建了一个名为mnelson.txt的新文件，但除非你使用'<code>git add' </code>命令，否则我们不会对它做任何事情。"</p>
<p>&nbsp;</p>

