# getting things not-so-done
Getting things done? Not with us!

Welcome to my [never-ending quest for](http://drawntogether.wikia.com/wiki/Xandir) the perfect software for... everything? So probably my major problem is that I'm looking for a unification of things like project management, issue tracking, tagging system, digital assets management system, (code) editor and let's throw in a cryptocoin miner while we're at it...

So, what are you, esteemed reader, up for? I'm not sure yet myself. I'm just dumping my thoughts here, and frankly at the moment I'm wondering how you even will have ended up here. But for the sake of practice, I'll use GitHub pages in a few commits to turn this into a website. And while we're at it, I'll try to figure out how to combine that with a commenting system (I find [this one](https://github.com/wireddown/ghpages-ghcomments/tree/master) rather interesting), or even with annotation via https://web.hypothes.is/ or the likes. Maybe a hybrid? And there you may already spot my problem, best summarized by whom else but XKCD:

![[](https://xkcd.com/761/)](https://imgs.xkcd.com/comics/dfs.png "A breadth-first search makes a lot of sense for dating in general, actually; it suggests dating a bunch of people casually before getting serious, rather than having a series of five-year relationships one after the other.")

You might also notice my spelling will contain errors. I'm too lazy to pull and locally edit this file, and GitHub's online editor assumes code. But ah, I just used Firefox's "inspect element" to change the `<div class="CodeMirror-code">`'s `spellcheck="true"`, so now my spelling will improve :+1: But of course I don't want to manually modify this all the time again, so now I'll either have to find an actually GitHub setting or learn enough Greasemonkey (or is Stylish enough?) to fix this... OK, so according to https://help.github.com/articles/editing-files-in-your-repository/ GitHub is using https://codemirror.net/ (the `class` above might have given that away, but it's been a while since I checked up on online code editors). And maybe [this StackOverflow post](https://stackoverflow.com/q/12343922/321973) is helpful here. Did I mention I :heart: the StackExchange network? Not yet, but I'll certainly mention and use it a lot! (Note to self: check the emoji chart, obviously a survival skill these days... And does Markdown still not support footnotes?)

## Single-focus? Not really.

Is my focus _slightly_ drifting while I'm trying to write & research this? Hell yes. I think it would be interesting to attach a list of open tabs to each commit here. Let's just have a rough overview: At the moment I have three windows of Firefox open, each filled with too many tabs, and oh boy [TreeStyleTab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/) is such an enabler for my behaviour. So one Window contains mostly tabs for job vacancies I'm considering to apply to (I'm basically unemployed at the moment, though technically it's paid ~vacation~ indemnity (is that the correct word?) until February 2018). One contains tutorials and the likes for Docker, Raspberry Pi, Ethereum, btrfs VS zfs VS ceph (is that a bit like comparing apples to oranges?), reviews or project / issue management etc. I'm certain I'll actually read and work with all of this. Just like I'm going to play [all the currently 2218 games I got on Steam](http://steamcommunity.com/id/zommuter). Thank you _so_ much, http://humblebundle.com. *Note to self: Find a sarcasm-emoji...*

The final Window contains, among other "Projects" I'm trying to work on (e.g. some mathematical problems, some Physics, some more. Maybe I'll reveal some about that later, but at the moment I'm secretly hoping one of those ideas turns out to be something no one else actually ever considered or at least managed to complete. Egoistic, and against the spirit of a platform like GitHub, and probably also futile. Speaking of which, a Borg-like hive mined would be the perfect remedy for this thinking. But anyway, one of my project ideas actually is _about_ project ideas, how to share parts of them without "loosing" your self-declared rule over them. Or at least, how to exchange ideas without the fear of someone "stealing" them. Have a look at [zomtems](https://github.com/zommuter/zomtems "Is there no easy way to link to a repo? I only found the PR/issue-linking"), though that's very much WIP), this text and the related tabs, such as:

* https://github.com/wireddown/ghpages-ghcomments/tree/master
  * http://ivanzuzak.info/2011/02/18/github-hosted-comments-for-github-hosted-blogs.html
  * https://mademistakes.com/articles/jekyll-static-comments/
    * https://staticman.net/
    * http://michelleful.github.io/code-blog/2014/03/16/adding-third-party-comments-to-a-jekyll-blog/
  * https://web.hypothes.is/
    * https://annotorious.github.io/#
    * https://github.com/ecds/digitaledition-jekylltheme
    * https://web.hypothes.is/for-publishers/#embedding
* https://github.com/kogmbh/WebODF/issues/170
  * https://github.com/GitbookIO/feedback/issues/255
* https://addons.mozilla.org/en-US/firefox/addon/stylish/
  * https://codemirror.net/
  * https://stackoverflow.com/questions/12343922/codemirror-with-spell-checker
  * https://discuss.codemirror.net/t/inputstyle-contenteditable-we-may-hope-for-browser-spell-checking/608/6
  * https://github.com/codemirror/CodeMirror/issues/1017#issuecomment-122308718

not all of them read yet, of course.

# Tasks

So, since I haven't found the perfect tool for what I'm doing, I have to write down my tasks in another way. Fortunately GitHub-flavored Markdown supports checkboxes, so

* [X] Use checkboxes for tasks

As [it turns out](https://help.github.com/articles/about-task-lists/), the boxes are only interactive when used in comments on issues and pull requests. Should I actually be using GitHub's issue system for this "project" somehow? I'm reluctant to do so, since I'm actually still trying to evaluate what kind of tool(s) I actually need. The checkboxes actually reminds me that I wanted to have a look at org-mode. But while we're at it, I also recently learned GitHub will also render AsciiDoc, which might be a viable alternative to ReStructuredText. Oh yes, welcome to my mind. [Jumping around](https://www.youtube.com/watch?v=KZaz7OqyTHQ).

I'm getting tired of unrendered Markdown. I think I'll try to integrate https://github.com/brrd/Abricotine into my workflow somehow.

OK, let's dump some tasks here for now:

* [ ] Getting things not-so-done
  * [ ] Have CodeMirror automatically use spell-checking when GitHub-editing Markdown
  * [ ] or change the work-flow, e.g. use Abricotine locally (with an on-save commit/pull?)
  * [ ] a TOC would be nice. But will this project remain monolithic?
  * [ ] Convert this into a github page
  * [ ] Add comment and/or annotation system (how will annotations work with content changing over time? Maybe this monolith should be shattered)
  * [ ] monolithic or not?
* [ ] Determine proper task tracking system
  * [ ] GitHub issues
  * [ ] or GitLab (I'm somehow hoping I'll find something OpenSource and self-hosted, yet usable without any further effort...)
  * [ ] Trello
  * [ ] http://taiga.io
  * [ ] Phabricator
  * [ ] ???
  * [ ] Profit <!-- also insert a Ferengi-joke here if you want -->
* [ ] Project management
* [ ] Understand Ethereum better
* [ ] Set up my Raspberry Pi 3 (with the self-hosted OpenSource super-tool I'm still trying to describe)
* [ ] Zomtems
* [ ] the other "Projects"
* [ ] Sift through my Steam games, maybe even _play_ some
* [ ] Gift away all those duplicate game keys...
