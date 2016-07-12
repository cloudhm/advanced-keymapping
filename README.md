# advanced-keymapping

In order to get most of this post, please read [OSX-shortcuts-you-might-not-know](https://github.com/yifanchen/OSX-shortcuts-you-might-not-know) first. I suggest karabiner to everyone no matter if you are a Emacs user or a Vim user,

### Chrome C-Vim

<a href="https://github.com/1995eaton/chromium-vim" target="_blank">C-Vim</a> is a must have if you use Vim, it comes with tons features to reinforce the golden keyboard rules.

[Karabiner](https://pqrs.org/osx/karabiner/): The most powerful key mapping tool. Capable of doing all sorts of crazy key mappings, they come in options,
just check the boxes of the ones you like. Honestly, I drop my jaw every time I browse through the option list, there are too much options even including Dota2, LOL, Starcraft, etc.
Still unsatisfied? Then make your own `private.xml` and import it in. Yes, it is just this amazing. On top of that,
it comes with a great customer service.(I got responds within 8 hours when I sent emails to ask questions) Most importantly, it is free.

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

`control` + `j` and `control` + `k`: going through intellisense in IDE or up and down when search in google.

`control` + `l`: very useful to attach parameters to the end of a url.

##### Example of adding a parameter to an url with both hands on row 2 of keyboard.

1. `cmd` + `l`
2. `control` + `l`
3. type the parameter.

Now, you can navigate through lines of code without moving right hand to `arrow` keys.


##### What if I already mapped `control` + `hjkl` in Vim?

1. I suggest to disable Karabiner when iTerm is running. Why? Becuase Vim comes with powerful shortcuts, we should learn them.
2. `fn` + `hjkl`


##### Map `caps lock` to `control` smartly

Instead of mapping `caps lock` to `control` permanently, why don't just map it only when `caps lock` is holding down with other keys.
Use [Seil](https://pqrs.org/osx/karabiner/seil.html.en) to do it.

##### C-Vim for Google Chrome


### Conclusion

This post is meant to share my key mappings, shortcuts and how I benefit from them, I am sure there are far more than I know.
With good softwares, be creative with your own mappings.
