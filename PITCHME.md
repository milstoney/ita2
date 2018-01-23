
@title[Agenda]

## Nablarch

#### ・Web Application
#### ・Web Service(REST)
#### ・Batch
#### ・Workflow

---
@title[全体像]
#### Nablarchアプリケーションフレームワークの全体像

![ALT](https://nablarch.github.io/docs/5u9/doc/_images/framework.png)

---

@title[ウェブアプリケーションの構成]
#### ウェブアプリケーションの構成
![ALT](https://nablarch.github.io/docs/5u9/doc/_images/application_structure1.png)
#### ・Nablarchサーブレットコンテキスト初期化リスナ (NablarchServletContextListener)
  システムリポジトリやログの初期化処理を行うサーブレットコンテキストリスナ。

#### ・Webフロントコントローラ (WebFrontController)
  受け取ったリクエストに対する処理をハンドラキューに委譲するサーブレットフィルタ。
  


---

@title[Introduction]

# Git<span class="gold">Pitch</span>

#### Markdown Presentations For Everyone on Git.*
<br>
<br>
<span class="byline">[ GitHub, GitLab, Bitbucket, GitBucket, Gitea, Gogs ]</span>

---

@title[PITCHME.md]

#### GitPitch turns <span class="gold">PITCHME.md</span> into
#### interactive,
#### online and offline slideshows.
<br>
<span class="aside">Just like this one...</span>

---

#### No more <span class="gray">Keynote</span>.
#### No more <span class="gray">Powerpoint</span>.
<br>
#### Just <span class="gold">Markdown</span>.
#### Then <span class="gold">Git-Commit</span>.

---?code=assets/md/hello.md&title=Step 1. PITCHME.md

<br>
#### Create slideshow content using GitHub Flavored Markdown in your favorite editor.

<span class="aside">It's as easy as README.md with simple slide-delimeters (---)</span>

---

@title[Step 2. Git-Commit]

### <span class="gold">STEP 2. GIT-COMMIT</span>
<br>

```shell
$ git add PITCHME.md
$ git commit -m "New slideshow content."
$ git push

Done!
```

@[1](Add your PITCHME.md slideshow content file.)
@[2](Commit PITCHME.md to your local repo.)
@[3](Push PITCHME.md to your public repo and you're done!)
@[5](Supports GitHub, GitLab, Bitbucket, GitBucket, Gitea, and Gogs.)

---

@title[Step 3. Done!]

### <span class="gold">STEP 3. GET THE WORD OUT!</span>
<br>
![GitPitch Slideshow URLs](assets/images/gp-slideshow-urls.png)
<br>
<br>
#### Instantly use your GitPitch slideshow URL to promote, pitch or present absolutely anything.

---

@title[Slide Rich]

### <span class="gold">Slide Rich</span>

#### Code Presenting for Blocks, Files, and GISTs
#### Image, Video, Chart, and Math Slides
#### Multiple Themes with Easy Customization
<br>
#### <span class="gold">Plus collaboration is built-in...</span>
#### Your Slideshow is Part of Your Project
#### Under Git Version Control within Your Git Repo

---

@title[Feature Rich]

### <span class="gold">Feature Rich</span>

#### Present Online or Offline
#### With Speaker Notes Support
#### Print Presentation as PDF
#### Auto-Generated Table-of-Contents
#### Share Presentation on Twitter or LinkedIn

---

### Go for it.
### Just add <span class="gold">PITCHME.md</span> ;)
<br>
[Click here to learn more @fa[external-link fa-pad-left]](https://github.com/gitpitch/gitpitch/wiki)
