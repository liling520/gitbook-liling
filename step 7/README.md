# 第七步

<h3><a id="user-content-step-6-pushing-a-branch-to-the-github" class="anchor" href="https://github.com/cubeton/git101/blob/master/TurtorialInfo/Tutorial.md#step-6-pushing-a-branch-to-the-github" aria-hidden="true"></a>将分支推送到GitHub</h3>
<p>现在，我们将分支中的提交<strong>推送</strong>到新的GitHub仓库。这使其他人可以看到你所做的更改。 如果它们是由仓库拥有者同意的，则可以将其更改合并到主分支中。</p>
<p>要将更改推送到GitHub上的新分支，你需要运行&nbsp;<code><strong><a href="http://git-scm.com/docs/git-push" target="_blank">git push</a> origin yourbranchname</strong>.<span style="font-family: arial, helvetica, sans-serif;">&nbsp;</span></code>``GitHub将在远程仓库上自动为你创建分支：&nbsp;</p>
<script src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/bf8274609c344b6d0e70.js.下载"></script><link rel="stylesheet" href="./An Intro to Git and GitHub for Beginners (Tutorial)_files/gist-embed-4ac6018bcc05457cde2f66d2e7299d11.css"><div id="gist26278368" class="gist">

<div class="gist-file">
  <div class="gist-data">
    <div class="js-gist-file-update-container js-task-list-container file-box">

 <div id="file-addnewbranchgithub-md-readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><div class="highlight highlight-source-shell"><pre>mnelson:myproject mnelson$ git push origin my-new-branch
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 313 bytes <span class="pl-k">|</span> 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/cubeton/mynewrepository.git
 <span class="pl-k">*</span> [new branch]      my-new-branch -<span class="pl-k">&gt;</span> my-new-branch</pre></div>
</article>
  </div>

</div>
</div>

</div>
  <div class="gist-meta">
    <a href="https://gist.github.com/cubeton/bf8274609c344b6d0e70/raw/4764e740cac9a48eefad341d9e34ceb09f89b73f/addnewbranchgithub.md" style="float:right">view raw</a>
    <a href="https://gist.github.com/cubeton/bf8274609c344b6d0e70#file-addnewbranchgithub-md">addnewbranchgithub.md</a>
    hosted with ❤ by <a href="https://github.com/">GitHub</a>
  </div>
</div>

</div>

<p>你可能想知道上面命令中“origin”一词的含义。当你将远程仓库克隆到本地计算机时，git为你创建了一个<strong>别名</strong>。在几乎所有情况下，此别名都称为<a href="https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes" target="_blank"><strong>origin</strong></a> 。它实质上是远程仓库URL的简写。 因此，要将更改推送到远程仓库，可以使用以下命令：<strong> <code>git push git@github.com:git/git.git yourbranchname</code></strong> 或者<strong><code>git push origin yourbranchname</code></strong></p>
<p>（如果这是你第一次在本地使用GitHub，则可能会提示你使用GitHub用户名和密码登录。）</p>
<p>如果刷新GitHub页面，你会看到注释，说你的名字的分支刚刚被推送到仓库中。 你也可以单击”branches“链接以查看此处列出的分支。</p>
<p><a href="https://cloud.githubusercontent.com/assets/5241432/9189475/da30eb86-3fb6-11e5-934f-ca596a2cac69.png" target="_blank"><img alt="Git_101_Screenshot2.png" src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/Git_101_Screenshot2.webp" title="Git_101_Screenshot2.png" data-constrained="true" style="width: 1600px; display: block; margin-left: auto; margin-right: auto;" width="869" height="183" srcset="https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot2.png?width=435&amp;height=92&amp;name=Git_101_Screenshot2.png 435w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot2.png?width=869&amp;height=183&amp;name=Git_101_Screenshot2.png 869w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot2.png?width=1304&amp;height=275&amp;name=Git_101_Screenshot2.png 1304w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot2.png?width=1738&amp;height=366&amp;name=Git_101_Screenshot2.png 1738w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot2.png?width=2173&amp;height=458&amp;name=Git_101_Screenshot2.png 2173w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot2.png?width=2607&amp;height=549&amp;name=Git_101_Screenshot2.png 2607w" sizes="(max-width: 869px) 100vw, 869px"></a></p>
<p>现在，单击上方屏幕截屏中的绿色按钮。 我们将提出<strong>发送请求</strong>！</p>
<p>&nbsp;</p>

