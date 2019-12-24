# 第十步

<h3><a id="user-content-step-9-almost-done-time-to-get-your-changes-on-github-back-to-your-computer" class="anchor" href="https://github.com/cubeton/git101/blob/master/TurtorialInfo/Tutorial.md#step-9-almost-done-time-to-get-your-changes-on-github-back-to-your-computer" aria-hidden="true"></a>在GitHub上更改回到您的计算机</h3>
<p>现在，GitHub上的回购看起来与你在本地机器上的回购略有不同。例如，你在分支中进行的并且合并到主分支的提交在本地计算机的主分支中不存在。</p>
<p>为了获得你或其他人在GitHub上合并的最新更改，请使用该 <code><strong>git pull origin master&nbsp;</strong></code>命令（在处理master分支时）。</p>
<p>
<script src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/48b5c726b496d50c3975.js.下载"></script><link rel="stylesheet" href="./An Intro to Git and GitHub for Beginners (Tutorial)_files/gist-embed-4ac6018bcc05457cde2f66d2e7299d11.css"></p><div id="gist26279024" class="gist">

<div class="gist-file">
  <div class="gist-data">
    <div class="js-gist-file-update-container js-task-list-container file-box">

  <div id="file-pulloriginmaster-md" class="file">

  <div id="file-pulloriginmaster-md-readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><div class="highlight highlight-source-shell"><pre>mnelson:myproject mnelson$ git pull origin master
remote: Counting objects: 1, done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), done.
From https://github.com/cubeton/mynewrepository
 <span class="pl-k">*</span> branch            master     -<span class="pl-k">&gt;</span> FETCH_HEAD
   b345d9a..5381b7c  master     -<span class="pl-k">&gt;</span> origin/master
Merge made by the <span class="pl-s"><span class="pl-pds">'</span>recursive<span class="pl-pds">'</span></span> strategy.
 mnelson.txt <span class="pl-k">|</span> 1 +
 1 file changed, 1 insertion(+)</pre></div>
</article>
  </div>

  <div class="gist-meta">
    <a href="https://gist.github.com/cubeton/48b5c726b496d50c3975/raw/fe2c68e0988c467fd218587e2397552076355b52/pulloriginmaster.md" style="float:right">view raw</a>
    <a href="https://gist.github.com/cubeton/48b5c726b496d50c3975#file-pulloriginmaster-md">pulloriginmaster.md</a>
    hosted with ❤ by <a href="https://github.com/">GitHub</a>
  </div>
<p></p>
<p>这将显示已更改的所有文件及其更改方式。</p>
<p>现在我们可以 <a href="http://git-scm.com/docs/git-log" target="_blank"><strong><code>git log</code></strong></a> 再次使用该命令查看所有新提交。</p>
<p>（你可能需要将分支切换回主分支。你可以使用该<code><strong>git checkout master</strong>&nbsp;</code>命令执行此操作。）</p>
<p>
<script src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/48f55c5a237cd8e1a238.js.下载"></script><link rel="stylesheet" href="./An Intro to Git and GitHub for Beginners (Tutorial)_files/gist-embed-4ac6018bcc05457cde2f66d2e7299d11.css"></p><div id="gist26346090" class="gist">

    <div class="js-gist-file-update-container js-task-list-container file-box">

  <div id="file-gitlogaftermerge-md-readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><div class="highlight highlight-source-shell"><pre>mnelson:myproject mnelson$ git log
commit 3e270876db0e5ffd3e9bfc5edede89b64b83812c
Merge: 4f1cb17 5381b7c
Author: Meghan Nelson <span class="pl-k">&lt;</span>mnelson@hubspot.com<span class="pl-k">&gt;</span>
Date:   Fri Sep 11 17:48:11 2015 -0400

  <div id="file-gitlogaftermerge-md-readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><div class="highlight highlight-source-shell"><pre>mnelson:myproject mnelson$ git log
commit 3e270876db0e5ffd3e9bfc5edede89b64b83812c
Merge: 4f1cb17 5381b7c
Author: Meghan Nelson <span class="pl-k">&lt;</span>mnelson@hubspot.com<span class="pl-k">&gt;</span>
Date:   Fri Sep 11 17:48:11 2015 -0400

```
Merge branch <span class="pl-s"><span class="pl-pds">'</span>master<span class="pl-pds">'</span></span> of https://github.com/cubeton/mynewrepository
```

commit 4f1cb1798b6e6890da797f98383e6337df577c2a
Author: Meghan Nelson <span class="pl-k">&lt;</span>mnelson@hubspot.com<span class="pl-k">&gt;</span>
Date:   Fri Sep 11 17:48:00 2015 -0400



```
added a new file
```

commit 5381b7c53212ca92151c743b4ed7dde07d9be3ce
Merge: b345d9a 1e8dc08
Author: Meghan Nelson <span class="pl-k">&lt;</span>meghan@meghan.net<span class="pl-k">&gt;</span>
Date:   Fri Sep 11 17:43:22 2015 -0400



```
Merge pull request <span class="pl-c"><span class="pl-c">#</span>2 from cubeton/my-newbranch</span>

Added some more text to my file
```

commit 1e8dc0830b4db8c93efd80479ea886264768520c
Author: Meghan Nelson <span class="pl-k">&lt;</span>mnelson@hubspot.com<span class="pl-k">&gt;</span>
Date:   Fri Sep 11 17:06:05 2015 -0400



```
Added some more text to my file
```

commit b345d9a25353037afdeaa9fcaf9f330effd157f1
Author: Meghan Nelson <span class="pl-k">&lt;</span>mnelson@hubspot.com<span class="pl-k">&gt;</span>
Date:   Thu Sep 10 17:42:15 2015 -0400



```
This is my first commit<span class="pl-k">!</span></pre></div>
```

</article>
  </div>

  </div>
</div>



```
  </div>
  <div class="gist-meta">
    <a href="https://gist.github.com/cubeton/48f55c5a237cd8e1a238/raw/3e31113a073b9bdec16800407d718b631dd0f587/gitlogaftermerge.md" style="float:right">view raw</a>
    <a href="https://gist.github.com/cubeton/48f55c5a237cd8e1a238#file-gitlogaftermerge-md">gitlogaftermerge.md</a>
    hosted with ❤ by <a href="https://github.com/">GitHub</a>
  </div>
</div>
```

</div>