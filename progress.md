# Progress

### 9/23/2017

**Initial Thoughts**: At this current moment, I don't view myself as a particularly *good* developer. I know it may be common for people to immediately jump in and exclaim, "*imposter syndrome*," but I'd like to think I'm self-aware enough to realize that:

1) I am not as good as I can be

and

2) I am not as good as I want to be

Actually, I take it all back. I am **NOT** a good developer. Not at all. I believe that acknowledging this lack of competence is the first step in my journey to getting better. I have so much more to learn. I want to improve my skillset to the point where I am comfortable with my abilities. I realize that day may never come, but that speaks more to my own mindset and mentality at this current moment. I am somewhat of a perfectionist at heart and that manner of thinking has definitely held me back in the past. I acknowledge that is an area I need to improve in as well. It's a work in progress.

It's not all bad! As someone who has been developing professionally for roughly one year, I have definitely noticed myself making progress. When I look at my work in my older repositories, I cringe at what I see. Hell, I even cringe at stuff I've written a couple of months ago. I enjoy seeing that my thinking has shifted and I have begun to think more programmatically. The manner in which I approach particular problems has evolved as well. All of that being said, I still recognize that I have *a lot* of room for improvement. I will use this document to track my progress so I can continually see both how I am growing and how I can continue to improve. There is *always* another level. I suppose that I hope my old repositories make me cringe in the future because that would mean that I learned how to do things in a better manner. <!-- ¯\_(ツ)_/¯ -->

In this field, one thing I have noticed is there is a lot of information, I mean, **a lot**. A shit-ton is probably the correct scientific term. It is easy to get overwhelmed. This often happens to me because I keep switching without completing. What I mean by this is that I never allow myself to acquire mastery in one specific domain. I keep jumping from course to course trying to glean as much information as possible. In these attempts, I pick up a very surface level understanding of many topics, but have no deep understanding in any one given technology. I openly acknowledge that this is a dumb approach. I understand this feeling of mastery will not occur in a year, hell, some people may never feel like a master, but at the very least I know that I can do better. I can become more efficient. One way I will combat this feeling is by working diligently on P1xt's guides until I complete them. I also believe that pushing this out publicly will give me a layer of accountability.

I will attain the level of knowledge that satisfies me. I will accomplish what I set out to do.

In general, if you have any advice or comments, I am all ears. I really enjoy learning and growing so please share any thoughts you may have. I'm sure this seems silly to most, but I genuinely appreciate and value feedback, even if it can be difficult to hear / take from time to time. I am well aware that I will feel discouraged and dumb at many points throughout this journey. Don't worry, you won't discourage me, I've already felt that way a number of times while learning how to program. It won't be the first time and it definitely won't be the last. There is something about programming that keeps me coming back for more. I love the challenge. There will be pain and frustration, but there is an equal, if not an even more rewarding euphoric feeling when it all clicks, when you fix a bug, or when you solve that problem that was stumping you.

Seriously though, I'd like to become a better developer and hopefully help some people along the way. I would love any feedback that could help me accomplish that. =]

**Plan**: Initially, I will work my way through P1xt's FAQ guide, move on to the front-end / job-ready curriculum, and finish off by completing the more broad web dev / cs guide. I realize that this will take a serious time commitment, but time is what I currently have. I am ready to invest it properly.

**Completed**:

[X] [Try Git](https://try.github.io/levels/1/challenges/1)
  * This tutorial was pretty simple. I rarely, if ever, use `git diff`. I usually use the built in tool in Atom that monitors changes to the local repository. Atom recently introduced a pretty nifty staging environment for git, but I still primarily enjoy using the terminal and `git status` for tracking files that have been changed and need to be committed. I don't ever use `git log` either. I typically look at a repository's / branch's history on Github. I will try both out a couple of times and try to incorporate them into my workflow if they prove useful.

[X] [Git Guide](http://rogerdudler.github.io/git-guide/)
  * I enjoyed this guide. I've never heard of tagging a particular commit through `git tag` for software releases, but then again, I don't primarily write *software*. It seems like cool little tool that could really help compare what the changes were between certain releases and to look at a previous version if a bug occurs down the road. I also want to learn and make use of the different commands in the **Useful Hints** section. I never heard of any of those and they seem pretty cool.

[X] [Git Foundations](https://www.youtube.com/playlist?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-)
  * I really enjoyed this playlist. First off, the intro of two octocats meowing was absolutely adorable. I enjoyed rewatching that 22 times. The videos were a great refresher of basic git commands, but they also explained a lot of the background information that I never really knew or learned. One thing I was somewhat surprised about was how often they mentioned a GUI. I personally enjoy working with git through the command line, but I can see the appeal of using a GUI to stay away from the *scary* terminal. I suppose I used to be somewhat scared / cautious when approaching the command line when I was first learning to program, but as I have become more comfortable interacting with terminal, I feel I have become a more competent programmer.
  <!-- ¯\_(ツ)_/¯ -->
  * A few cool things I picked up and want to try are:
    - `git diff --staged`
    - `git diff --color-words` and `git diff --word-diff` for working with staged commits.
     - Again, I pretty much rely on Atom to tell me these differences, but Atom marks changes even when you switch punctuation or changing the spacing style of a particular line. It may sometimes be useful to see what specifically changed in a particular line compared to the last commit.
    - `git log --stat` and `git log --patch`
      - I typically use GitHub to view the changes made to files in particular commits, but I can see where this could be beneficial.
    - `git log --graph --all --decorate --oneline`
      - Seems like a cool command. Don't know how practical it is for me in my current work environment.
    - `git add -u .` helpful for removing multiple files.
    - `git add -A .` for tracking many files that have been moved.
    - `git log --stat -M --follow -- filename`
      - Starting to see the power of `git log` in general, but seeing the history of a file, even when it is moved (didn't know that was possible), is pretty awesome. I know that GitHub holds a particular file's history, but I don't think I've used it before.
    - A cool concept was the similarity index that git uses. Never knew that was there working in the background.
    - `git ls-files --others --ignored --exclude-standard` tells you the files that .gitignore is telling git to not track
    - `git merge --squash`
      - I typically squash commits in a `git rebase`, but I may try this method out if I ever want to squash merged commits.
    - `git reflog`

[X] [Hello World](https://guides.github.com/activities/hello-world/)
  * Straightforward walkthrough of making a repository, creating a branch, and merging the branch back into the master branch. It was pretty cool that you could do all that from the GitHub online interface.

[X] [Git Immersion](http://gitimmersion.com/index.html)
  * This was a great tutorial. It was really in depth and allowed me to use a few of the topics covered in some of the previous tutorials that I've never used before. I am a person who learns by doing, and it was great to get my hands dirty and refresh my knowledge about git commands I *knew*, but never really used. It was also fun exploring a lot of the background information of git. Exploring the `.git` file was fun and eye opening for me. It's not something I've done in the past, and learning how git stores a repository's information was awesome to learn.
  * I learned some really cool things:
    - First off, I've never played with Ruby before, and while the Ruby programming was sparse, I really enjoyed working with a language that was outside of my domain. I love touching the stuff I don't know. Perhaps that's why I switch topics so often.
    - I never knew you could make aliases for git commands, so adding those to my `.gitconfig` in my $HOME directory was nifty. I especially liked `hist = log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short`. I started using `git hist` quite a bit during this tutorial and enjoyed it. I don't know how often I'd use it in a work environment, but I'm going to try to get into a habit of using it and see if it is beneficial.
	- I will research all the things mentioned in lab 52: "Reverting Committed Changes," "Cross OS Line Endings", "Remote Servers", "Protocols", "SSH Setup", "Remote Branch Management", "Finding Buggy Commits (git bisect)", "Workflows", "Non-command line tools (gitx, gitk, magit)", and "Working with GitHub" to learn about them.

**Thoughts**: I know that P1xt wrote to choose one git tutorial, but I rather enjoyed going through all the different ones she had listed. It was a nice refresher of all things git, and I even learned a few new tricks. I first learned how to program at Grand Circus, a coding bootcamp in Detroit, Michigan. While I learned a lot of practical information, I missed out on some of the theory and bigger picture concepts. That is a lot of the knowledge that I am trying to pick up in order to fill in the gaps. I have a couple more to get through, and I will continue to go through the guide to make as much progress as possible. I'd appreciate any feedback, and if you made it this far, a genuine and sincere thank you!

See y'all next time. =]
