---
layout: post
title: "How To Build you Portfolio"
description: 'Innovate, Create, Repeat: My Project Journey'
image:
nav-menu: true
show_tile: false
order: 6
---
		
<p>Here you are looking for a easier way to build your portfolio…
Sweat no more!
This project has made it much easier to do it than you think.
Follow along with me.</p>

<p class="no_padding">First of all,</p>
<h2 class="no_padding" id="why-portfolio-auto-">Why Portfolio-Auto ?</h2> 
<p > even created &amp; you should use in first place.</p>

<blockquote>
  <p>Simply, any web-site creation is a time and money spending process, and when is comes to deploy that site you build, it gets even harder and non-trivial. All is all web site development is no easy task in contrast to is seems and your portfolio build is not far different from it. However, when it comes to personal or organizational portfolio website the essential information to need to display stay the same irrespective of industry or personal preferences. So, here <strong>Portfolio-Auto</strong> take care of all the redundant processes from website styling to deploying, and make you only to concentrate on adding you details to portfolio theme at preference. Although, this doesn’t mean you can customize have you own unique theme.</p>
</blockquote>

<p class="no_padding">So.. shall we</p>
<h2 id="build-your-portfolio">Build your portfolio</h2>

<p class="no_padding">So.. First,</p>
<h3 id="the-general-process">The general process</h3>
<p class="no_padding">of selection to deploying the portfolio</p>

<ol>
  <li>fork this github repo into your personal github account</li>
  <li>go to github action and check you new [but sample] portfolio</li>
  <li>select the theme at your preference</li>
  <li>add your details</li>
  <li>commit back</li>
</ol>

<p>Voilà, now your brand new portfolio it up on to the world</p>

<p class="no_padding">So.. are we finish?</p>
<h3 id="the-step-by-step-guide">the step by step guide</h3>
<p class="no_padding">if you needed, and of course you need.</p>

<h4 id="step-1-get-the-code">[step-1] get the code</h4>
<blockquote>
  <p>Unlike, usual <code class="language-plaintext highlighter-rouge">github</code> base development, here you don’t even need to clone the repo. But, that may I said, you can do the same thing with good old github clone and push process, and this shall be the only way when you customize the themes.</p>
</blockquote>


<p class="no_padding">anyway, let’s stop the high horse and go with the simplest path shall we</p>
<ol>
  <li>go the <a href="https://github.com/nipdep/Portfolio-Auto">portfolio-auto</a> original repo, hope you are already there 😉</li>
  <li>then <code class="language-plaintext highlighter-rouge">fork</code> the repo onto you personal github user account
    <blockquote>
      <p>here <code class="language-plaintext highlighter-rouge">fork</code> process guarantee timely updates when the original <strong>portfolio-auto</strong> repo get new features or themes</p>
    </blockquote>
  </li>
  <li>and, you are good to go to the next step
<img class="raw_img" src="docs\HowTo\fork.png" alt="how to step 2">
BTW, if you are <code class="language-plaintext highlighter-rouge">pro</code> or one looking to customize themes</li>
  <li>you can follow above <code class="language-plaintext highlighter-rouge">fork</code> based step as it said</li>
  <li>plus, clone the <strong>portfolio-auto</strong> repo in your personal github account, start work on local.
<img class="raw_img" src="docs\HowTo\localCode.png" alt="how to step 2"></li>
  <li>for the advance operation and local testing follow <em>github</em> <code class="language-plaintext highlighter-rouge">Wiki</code> on <a href="https://github.com/nipdep/Portfolio-Auto/wiki">portfolio-auto</a></li>
</ol>


<h4 id="step-3-select-your-portfolio-theme">[step-2] select your portfolio theme</h4>
<blockquote>
  <p>here theme are defined by branches of the github repo, specifically branches with name starting from <code class="language-plaintext highlighter-rouge">theme/&lt;theme-name&gt;</code></p>
</blockquote>

<p><strong>Preview</strong></p>
<blockquote>
  <p>can be simply done just by looking at screen-shots in theme <code class="language-plaintext highlighter-rouge">readme</code> page 
when you select the theme, then you open and <em>pull request</em> from you selected theme branch to <code class="language-plaintext highlighter-rouge">dev</code> branch.</p>
</blockquote>

<p><img class="raw_img" src="docs/HowTo/themeBranchSelect.png" alt=" theme selection"></p>

<blockquote>
  <p>or, you can deploy theme portfolio test it out. Go to settings&gt; github pages&gt; select the theme branch, hit save and go to actions tab.
<img class="raw_img" src="docs/HowTo/buildAndDeploy1.png" alt="github pages ">
<img class="raw_img" src="docs/HowTo/buildNDeploy2.png" alt="save theme branch ">
<img class="raw_img" src="docs/HowTo/githubActions.png" alt=" ">
<img class="raw_img" src="docs/HowTo/pages_buildNDeployment.png" alt=" ">
<!-- <img src="docs/HowTo/" alt=" "/> --></p>
</blockquote>

<h4 id="step-4-add-your-details">[step-3] add your details</h4>
<p>First, important file &amp; folders to learn</p>
<ol>
  <li><code class="language-plaintext highlighter-rouge">_config.yml</code></li>
</ol>

<p><img class="raw_img" src="docs/HowTo/config_file.png" alt=" "></p>
<blockquote>
  <p>define your website configuration</p>
  <ul>
    <li>website title</li>
    <li>portfolio description</li>
    <li>base-url, <code class="language-plaintext highlighter-rouge">"/Portfolio-Auto"</code> should be same as the your github repo name</li>
    <li>contact information; phone, address</li>
    <li>social media information; github, LinkedIn, Facebook, Slack, Instagram</li>
  </ul>
</blockquote>

<ol>
  <li><code class="language-plaintext highlighter-rouge">index.md</code></li>
</ol>

<p><img class="raw_img" src="docs/HowTo/index.md.png" alt=" "></p>
<blockquote>
  <p>root or the home page of your portfolio</p>
  <ul>
    <li>nothing important from <em>content</em> aspect</li>
    <li>but the page layout should be in <code class="language-plaintext highlighter-rouge">home</code>
      <ol>
        <li><code class="language-plaintext highlighter-rouge">Gemfile</code></li>
      </ol>
    </li>
  </ul>
</blockquote>

<p><img class="raw_img" src="docs/HowTo/gemfile.png" alt=" "></p>
<blockquote>
  <p>jekyll website build file</p>
  <ul>
    <li>again nothing much to change</li>
  </ul>
</blockquote>

<ol>
  <li><code class="language-plaintext highlighter-rouge">personal.md</code></li>
</ol>

<p><img class="raw_img" src="docs/HowTo/personal.md.png" alt=" "></p>
<blockquote>
  <p>your personal information summary</p>
  <ul>
    <li>all the information defined in the <code class="language-plaintext highlighter-rouge">_data/personal.yaml</code></li>
    <li>where you can add <strong>description</strong>, <strong>fields_of_interest</strong>, <strong>soft_skills</strong>, <strong>certificates</strong></li>
    <li>also, you can add key-value paired information in <strong>details</strong>
<img class="raw_img" src="docs/HowTo/personalYmLnMD.png" alt=" "></li>
  </ul>
</blockquote>

<ol>
  <li>routing pages, <code class="language-plaintext highlighter-rouge">projects.md</code>, <code class="language-plaintext highlighter-rouge">publications.md</code>, <code class="language-plaintext highlighter-rouge">experience.md</code>, <code class="language-plaintext highlighter-rouge">achievements.md</code>
    <blockquote>
      <p>these pages contains tag information, routings to all details posts</p>
    </blockquote>
    <ul>
      <li>nothing to change
<img class="raw_img" src="docs/HowTo/posts_folder_structure.png" alt=" "></li>
    </ul>
  </li>
  <li>
    <p>post pages, <code class="language-plaintext highlighter-rouge">_posts/*</code> all the <code class="language-plaintext highlighter-rouge">.md</code> files</p>

    <blockquote>
      <p>detail of the post</p>
      <ul>
        <li>all the posts should be in particular directory in <code class="language-plaintext highlighter-rouge">_posts</code> as  <code class="language-plaintext highlighter-rouge">post.type</code></li>
        <li>you just have only have to duplicate existing <code class="language-plaintext highlighter-rouge">.md</code> file under the same directory and change the <em>front-matter</em> accordingly. i.e. except <code class="language-plaintext highlighter-rouge">layout</code>, <code class="language-plaintext highlighter-rouge">categories</code>, <code class="language-plaintext highlighter-rouge">type</code> and <code class="language-plaintext highlighter-rouge">permalink</code></li>
        <li>and `` 
<!-- SS<- as this is shown --></li>
        <li>all the post name should be in <code class="language-plaintext highlighter-rouge">data-nametag.md</code>, example: <code class="language-plaintext highlighter-rouge">2023-10-23-project_1.md</code>
<img class="raw_img" src="docs/HowTo/postPages.png" alt=" "></li>
      </ul>
    </blockquote>
  </li>
  <li>post data pages, <code class="language-plaintext highlighter-rouge">_data/*</code> all the <code class="language-plaintext highlighter-rouge">.yml</code> files
<img class="raw_img" src="docs/HowTo/yamlFolderStructure.png" alt=" ">
    <blockquote>
      <p>files that contains all the details about you endeavors and only place you truly have to put effort into</p>
    </blockquote>
    <ul>
      <li>all the posts should be in particular directory in <code class="language-plaintext highlighter-rouge">_data</code> as  <code class="language-plaintext highlighter-rouge">post.type</code></li>
      <li>if you are going with current information point in <code class="language-plaintext highlighter-rouge">.yml</code> files, just duplicate and set file name in <code class="language-plaintext highlighter-rouge">&lt;project-name&gt;.yml</code>, assuming there will be not duplicate project names found</li>
      <li>then you just change the actual information under each key.</li>
      <li><strong>we strongly recommend you not to add or change keys in those <code class="language-plaintext highlighter-rouge">.yml</code> files</strong></li>
      <li>_for any conciliation you need to add information under new tag, you can do it but it has to taken care in related and all the other post files in <code class="language-plaintext highlighter-rouge">_posts</code> directory.</li>
      <li>checkout <em>github</em> <code class="language-plaintext highlighter-rouge">Wiki</code> on <a href="https://github.com/nipdep/Portfolio-Auto/wiki">portfolio-auto</a> example of advance operations</li>
      <li>__all the value names under <code class="language-plaintext highlighter-rouge">technologies</code> key in any <code class="language-plaintext highlighter-rouge">.yml</code> file should be in <code class="language-plaintext highlighter-rouge">assets/images/logos</code> in same name formatting
<img src="docs\HowTo\technologies_logos.png" alt="technologies logo"></li>
    </ul>
  </li>
</ol>

<h3 id="step-5-commit-and-deploy-you-portfolio-site">[step-4] commit and deploy you portfolio site</h3>
<blockquote>
  <p>if you following fully online way, you just have to push commit and check to deployment. 
<!-- SS to show commit in the github -->
as a next step you could create a <em>pull request</em> from <code class="language-plaintext highlighter-rouge">dev</code> to <code class="language-plaintext highlighter-rouge">main</code> branch.
when you working on local and then follow <a href="https://github.com/nipdep/Portfolio-Auto/wiki">the wiki</a>
<!-- <img src="docs/HowTo/linkToSite.png" alt=" "/> --></p>
</blockquote>

<h4 id="step-2-checkout-your-newly-deployed-portfolio">[step-5] Checkout your newly deployed portfolio</h4>
<p><strong>What ??</strong></p>
<blockquote>
  <p>Oh, yes. you have already deployed you portfolio. But, the little problem is there name is ‘John Deo’ and that guy is a figment of imagination.
<!-- SS- settings url of the page you -->
<img class="raw_img" src="docs/HowTo/fullpageview.png" alt="page view"></p>
</blockquote>

<blockquote>
  <blockquote>
    <p>but, Why?
<!-- SS - yaml of workflow/SS of action --></p>
  </blockquote>
</blockquote>

<p>glad, you asked. <strong>notice</strong> following section contains some serious CI/CD concepts. so let’s get to it
the website deployment happens as a <code class="language-plaintext highlighter-rouge">github-page</code> and that process is automated by <code class="language-plaintext highlighter-rouge">github-action</code> more specifically, that repo <code class="language-plaintext highlighter-rouge">.github/workflows</code> directory contained <code class="language-plaintext highlighter-rouge">jekyll.yml</code> file see every action happens to the repo (<strong>CI</strong>)  and run jekyll site building and deployment (<strong>CD</strong>) on  <code class="language-plaintext highlighter-rouge">git push to main</code>, <code class="language-plaintext highlighter-rouge">git pull-request main</code>
So.. that what it take to deploy at a your commit, and now magic is gone.
<!-- <img src="docs/HowTo/" alt=" "/> --></p>

</div>