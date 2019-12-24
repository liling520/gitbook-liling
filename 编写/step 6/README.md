# 第六步

<h3>在 GitHub上创建新的仓库</h3>
<p>如果你只想在本地跟踪代码，则无需使用GitHub。 但是，如果你想与团队合作，则可以使用GitHub协同修改项目代码。</p>
<p>&nbsp;</p>
<p>如果要在GitHub上创建新的仓库，请登录并转到GitHub主页。 你会看到一个绿色的“+ New repository ”按钮：&nbsp;</p>
<p><img src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/Git_101_Screenshot1-2.webp" alt="Git_101_Screenshot1-2.png" title="Git_101_Screenshot1-2.png" data-constrained="true" style="width: 671px; float: left;" width="671" height="141" srcset="https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot1-2.png?width=336&amp;height=71&amp;name=Git_101_Screenshot1-2.png 336w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot1-2.png?width=671&amp;height=141&amp;name=Git_101_Screenshot1-2.png 671w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot1-2.png?width=1007&amp;height=212&amp;name=Git_101_Screenshot1-2.png 1007w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot1-2.png?width=1342&amp;height=282&amp;name=Git_101_Screenshot1-2.png 1342w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot1-2.png?width=1678&amp;height=353&amp;name=Git_101_Screenshot1-2.png 1678w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot1-2.png?width=2013&amp;height=423&amp;name=Git_101_Screenshot1-2.png 2013w" sizes="(max-width: 671px) 100vw, 671px"></p>

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

<p>单击按钮后，GitHub将要求你命名仓库并提供简短描述：</p>
<p><img src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/Git_101_Screenshot_2-1.webp" alt="Git_101_Screenshot_2-1.png" title="Git_101_Screenshot_2-1.png" data-constrained="true" style="width: 671px; float: left;" width="671" height="418" srcset="https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot_2-1.png?width=336&amp;height=209&amp;name=Git_101_Screenshot_2-1.png 336w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot_2-1.png?width=671&amp;height=418&amp;name=Git_101_Screenshot_2-1.png 671w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot_2-1.png?width=1007&amp;height=627&amp;name=Git_101_Screenshot_2-1.png 1007w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot_2-1.png?width=1342&amp;height=836&amp;name=Git_101_Screenshot_2-1.png 1342w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot_2-1.png?width=1678&amp;height=1045&amp;name=Git_101_Screenshot_2-1.png 1678w, https://product.hubspot.com/hs-fs/hubfs/Git_101_Screenshot_2-1.png?width=2013&amp;height=1254&amp;name=Git_101_Screenshot_2-1.png 2013w" sizes="(max-width: 869px) 100vw,869px"></p>

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>




<p>填写完信息后，请按“Create repository”按钮以创建新的仓库。</p>
<p>GitHub会询问你是否要从头开始创建新的仓库，或者是否要添加在本地创建的仓库。 在这种情况下，由于我们已经在本地创建了新的仓库，因此我们希望将其推送到GitHub上，因此请遵循 <strong>“....或从命令行推送现有仓库”</strong>&nbsp;部分：&nbsp;</p>
<h3>
<script src="./An Intro to Git and GitHub for Beginners (Tutorial)_files/3a2616c44e35ca68a6b0.js.下载"></script><link rel="stylesheet" href="./An Intro to Git and GitHub for Beginners (Tutorial)_files/gist-embed-4ac6018bcc05457cde2f66d2e7299d11.css"><div id="gist26278153" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-addgithub-md" class="file">
  <div id="file-addgithub-md-readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><div class="highlight highlight-source-shell"><pre>mnelson:myproject mnelson$ git remote add origin https://github.com/cubeton/mynewrepository.git
mnelson:myproject mnelson$ git push -u origin master
Counting objects: 3, done.
Writing objects: 100% (3/3), 263 bytes <span class="pl-k">|</span> 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/cubeton/mynewrepository.git
 <span class="pl-k">*</span> [new branch]      master -<span class="pl-k">&gt;</span> master
Branch master <span class="pl-c1">set</span> up to track remote branch master from origin.</pre></div>
</article>
  </div>

 </div>
</div>

 </div>
  <div class="gist-meta">
    <a href="https://gist.github.com/cubeton/3a2616c44e35ca68a6b0/raw/41e5758cfdbd7db8a1659c1adaba9346680097f9/addgithub.md" style="float:right">view raw</a>
    <a href="https://gist.github.com/cubeton/3a2616c44e35ca68a6b0#file-addgithub-md">addgithub.md</a>
    hosted with ❤ by <a href="https://github.com/">GitHub</a>
  </div>
</div>

</div>

</h3>

<p>（由于你的GitHub用户名和仓库名称不同，因此你需要将第一个命令行中的URL更改为本节中GitHub列出的内容）&nbsp;</p>
<p>&nbsp;</p>