---
title: How to Post to this Blog
author: mds17 
---

Hopefully, by the time you read this post, you’ll already be familiar with
Markdown, [Atom](http://atom.io), Git, and [GitHub](http://github.com). You’ll
also have a GitHub account, you’ll be added to the [NewYorkScapes GitHub
group](http://github.com/nyscapes), and you’ll have posting privileges to this
blog.

As you know, Git works with *projects* or *repositories*, not with single
files. This blog, then, is such a project, made up of many smaller files that
get mixed together to make what you see in your browser. Your task, in order
to write a post, then, is simple:

1.  you will create a file
1.  you will fill the file with your thoughts
1.  you will add the file to the project by saving-staging-committing-pushing

I hope the middle step is the hardest. The rest of this post will detail the
other two steps…

![A helpful screenshot](https://i.imgur.com/RMxqrkJ.png)

All of the blog posts for this blog live as individual files inside the
`_posts` folder in this project. You should see it in Atom. The first step,
then, is to make sure that the file you will be creating is in that folder.
Next, the file’s name has to follow a very specific format:

`2018-nn-mm-some-title-here.md`

The `nn` is the month, with a zero, and the `mm` is the day, with a zero. The
rest is words separated by hyphens that identify the file. The last part, the
`.md`, lets the computer know that you’re typing a Markdown file. In order to
create this file, then, you click on the `_posts` folder like in the picture,
so that it’s highlighted, and then type the letter `a`. A little box should
show up that asks you to enter the name, so you type something like:

`_posts/2018-nn-mm-some-title-here.md`

If all went well, that `_posts/` is already in the text box.

Now you have a blank document in Atom. You *must* paste in the following for
the first four lines:

```
---
title: How to Post to this Blog
author: mds17 
---
```

Where it says `title:`, you can replace my title with your own. And you should
also change `author:` to your NYU netid. Remember that this is four lines,
meaning you need that `---` on the top and `---` on the bottom. Of course, you
can always look at other posts in the `_posts` folder—like this one—for tips.

Next is that tricky part of filling in the content with your thoughts.

When you’re done, you save-stage-commit-push. But, as always, you can save as
much as you want before you stage-commit, and commit as much as you want
before you push. But you should typically only push once—when you like what
you’ve got.

And that’s it!
