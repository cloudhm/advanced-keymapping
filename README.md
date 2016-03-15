# advanced-keymapping

In order to get most of this post, please read [OSX-shortcuts-you-might-not-know](https://github.com/yifanchen/OSX-shortcuts-you-might-not-know) first. 

I am going to talk about how and why I map `hjkl` as `arrow` keys. For the mapping to work, you will need to use either of the following tools. 

[Karabiner](https://pqrs.org/osx/karabiner/): The most powerful key mapping tool. Capable of doing all sorts of crazy key mappings, they come in options,
just check the boxes of the ones you like. Still unsatisfied? Then make your own `private.xml` and import it in. Yes, it is just this amazing. On top of that, 
it comes with a great customer service.(I got responds within 8 hours when I sent emails to ask questions) Most importantly, it is free.

[BetterTouchTool](https://www.boastr.net/): BTT is well known, and very intuitively easy to use. It is no longer free, however spending few bucks to have it 24/7.
I am totally down. In this post, I am not going to show how BTT works, it's very easy to figure out.

Between these two tools, I would go with Karabiner over BTT for two reasons:

1. Unlike `arrow` keys, `letter` keys don't repeat themselves when holding down, which make navigating inconvenient, however Karabiner fixes this problem by enabling specific 
   terminal commands.

2. Free.

### About HJKL

I started to use Vim last year. I absolutely like model editing and the idea of mouse-less. `hjkl` is one of the most beautiful inventions in Vim. 
I wanted to apply the idea to the entire system. It turned out better than I thought. Now I use it for everything, checking out emails in Mail, browsing files in Finder,
going through lists in Slack, etc. 

The screen shot is my setting. You are welcome to play with it, map anyway you like. I am going to use my mapping as an example.

![Karabiner key mapping](https://github.com/yifanchen/advanced-keymapping/blob/master/imgs/karabiner1.jpg) 

After you map it the way like I do, the beautiful part happens:

`control` + `h` + `j` + `k` + `l`: `left` `down` `up` `right`.

`control` + `cmd` + `h` or `l`: navigating through beginning and end of a line.

`control` + `cmd` + `shift` + `h` or `l`: select entire line.

`control` + `cmd` + `k` or `j`: top or bottom of the file

`control` + `cmd` + `shift` + `k` or `j`: select entire file from either top or bottom.

`control` + `j` and `control` + `k`: going through intellisense or up and down when search in google.

`control` + `l`: very useful to attach parameters to the end of a url.

Now, you can navigate through lines of code without moving right hand to `arrow` keys.

# 中文

玩vim有感，觉得hjkl做为方向键再合适不过了。试想一下，打字的时候，光标可以左右切换并且手指不需要离开键盘的黄金位置。用多了发现就离不开了。不经意间，
找到一款神级快捷键编辑器，强大到不行。

如果你也是按我的设置来的话（如图），下面这些快捷会让你幸福很多。

`control` + `h` + `j` + `k` + `l`: 左，下，上，右。

`control` + `cmd` + `h` or `l`: 到整行的开始或者末尾。

`control` + `cmd` + `shift` + `h` or `l`: 选择整行。

`control` + `cmd` + `k` or `j`: 文件的最开始和结尾。

`control` + `cmd` + `shift` + `k` or `j`: 选择所有文件内容。

`control` + `j` and `control` + `k`: 这个在百度搜索东西的时候上下选择很有用。

`control` + `l`: 网络地址太长不想打的时候而又需要在末尾加的东西的时候很管用。
